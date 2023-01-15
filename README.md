# ansible-role-frp

Role to install frp, a fast reverse proxy to help you expose a local server behind a NAT or firewall to the Internet.

## Table of content

- [Default Variables](#default-variables)
  - [frp_download_url](#frp_download_url)
  - [frp_install_dir](#frp_install_dir)
  - [frp_install_file_tar](#frp_install_file_tar)
  - [frp_version](#frp_version)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### frp_download_url

frp download url

#### Default value

```YAML
frp_download_url: https://github.com/fatedier/frp/releases/download/v{{ frp_version
  }}/frp_{{ frp_version }}_linux_amd64.tar.gz
```

### frp_install_dir

frp install directory

#### Default value

```YAML
frp_install_dir: /usr/local/bin
```

### frp_install_file_tar

frp install filename

#### Default value

```YAML
frp_install_file_tar: frp_{{ frp_version }}_linux_amd64.tar.gz
```

### frp_version

frp version

#### Default value

```YAML
frp_version: 0.46.1
```



## Dependencies

None.

## License

license (GPL-2.0-or-later, MIT, etc)

## Author

andif888
