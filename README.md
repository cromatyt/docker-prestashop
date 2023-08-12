# Prestashop

:warning: **This project is an example, do not set insecure password in your docker compose !** :warning:

1. Create tree structure

```bash
mkdir -p mariadb/data mariadb/scripts prestashop/data prestashop/apache2
```

2. Before deploying docker-compose, you need to be sure that your data prestashop/mariadb forder are empty (mariadb need to be empty to run entrypoint and prestashop to run his installer)
