# dovecot [![Ansible Role](https://img.shields.io/ansible/role/d/cornfeedhobo/dovecot)](https://galaxy.ansible.com/cornfeedhobo/dovecot)

Install and configure dovecot

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [dovecot_bin_path](#dovecot_bin_path)
  - [dovecot_config](#dovecot_config)
  - [dovecot_config_dir](#dovecot_config_dir)
  - [dovecot_configure](#dovecot_configure)
  - [dovecot_group](#dovecot_group)
  - [dovecot_install](#dovecot_install)
  - [dovecot_owner](#dovecot_owner)
  - [dovecot_package_state](#dovecot_package_state)
  - [dovecot_packages](#dovecot_packages)
  - [dovecot_service](#dovecot_service)
  - [dovecot_service_enabled](#dovecot_service_enabled)
  - [dovecot_service_name](#dovecot_service_name)
  - [dovecot_service_state](#dovecot_service_state)
  - [dovecot_ssl](#dovecot_ssl)
  - [dovecot_ssl_dir](#dovecot_ssl_dir)
  - [dovecot_ssl_pair](#dovecot_ssl_pair)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.9`

## Default Variables

### dovecot_bin_path

#### Default value

```YAML
dovecot_bin_path: '{{ __dovecot_bin_path }}'
```

### dovecot_config

#### Default value

```YAML
dovecot_config: ''
```

### dovecot_config_dir

#### Default value

```YAML
dovecot_config_dir: '{{ __dovecot_config_dir }}'
```

### dovecot_configure

#### Default value

```YAML
dovecot_configure: false
```

### dovecot_group

#### Default value

```YAML
dovecot_group: '{{ __dovecot_group }}'
```

### dovecot_install

#### Default value

```YAML
dovecot_install: false
```

### dovecot_owner

#### Default value

```YAML
dovecot_owner: '{{ __dovecot_owner }}'
```

### dovecot_package_state

#### Default value

```YAML
dovecot_package_state: present
```

### dovecot_packages

#### Default value

```YAML
dovecot_packages: '{{ __dovecot_packages }}'
```

### dovecot_service

#### Default value

```YAML
dovecot_service: false
```

### dovecot_service_enabled

#### Default value

```YAML
dovecot_service_enabled: true
```

### dovecot_service_name

#### Default value

```YAML
dovecot_service_name: dovecot
```

### dovecot_service_state

#### Default value

```YAML
dovecot_service_state: started
```

### dovecot_ssl

#### Default value

```YAML
dovecot_ssl: false
```

### dovecot_ssl_dir

#### Default value

```YAML
dovecot_ssl_dir: '{{ __dovecot_ssl_dir }}'
```

### dovecot_ssl_pair

#### Default value

```YAML
dovecot_ssl_pair:
  name: ''
  key: ''
  crt: ''
```

## Discovered Tags

**_dovecot_**

**_dovecot-configure_**

**_dovecot-install_**

**_dovecot-service_**

**_dovecot-ssl_**


## Dependencies

None.

## License

MIT

## Author

cornfeedhobo
