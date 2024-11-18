# LDAP Setup with Docker Compose

## Getting Started

```bash
git clone <repository-url>
cd <repository-folder>
docker-compose up -d
```

## Access phpLDAPadmin

- HTTP: [http://localhost:8080](http://localhost:8080)
- HTTPS: [https://localhost:6443](https://localhost:6443)

## Default LDAP Credentials

- **Organisation**: `my_org`
- **Domain**: `example.com`
- **Admin DN**: `cn=admin,dc=example,dc=com`
- **Admin Password**: `admin_password`

## Managing Containers

- **Stop containers**: `docker-compose down`
- **Remove volumes**: `docker-compose down --volumes`
