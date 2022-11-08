# ansible-phpmyadmin

Setups phpMyAdmin.

### Example playbook
```yaml
---
- hosts: myserver
  roles:
    - role: sunfoxcz.phpmyadmin
        phpmyadmin_destination: /home/web/website.tld
        phpmyadmin_folder: /home/web/website.tld/myadmin
        phpmyadmin_domain: myadmin.website.tld
```

## License

Licensed under MIT license. See [LICENSE](LICENSE.md) for details.
