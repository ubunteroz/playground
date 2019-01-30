# WordPress container

## Details
| Image                        | Ports | Volumes | Access                   |
|------------------------------|-------|---------|--------------------------|
| bitnami/wordpress:5          | 8084  | ./wp    | User: admin; Pass: admin |
| mariadb:latest               |       | ./db    | User: wp; Pass: test     |
| phpmyadmin/phpmyadmin:latest | 8085  |         | User: root; Pass: test   |

## Running
`$ docker-compose up -d`

## Stopping
`$ docker-compose down`
