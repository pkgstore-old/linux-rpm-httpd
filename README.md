# HTTPD

The **Apache HTTP Server** is a powerful, efficient, and extensible web server.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/httpd
$ dnf install -y httpd
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y httpd
```

## Remove

```
$ dnf erase -y httpd
$ dnf copr remove pkgstore/httpd
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/httpd).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/httpd) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
