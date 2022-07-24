# PLATYPUS -libraries management APP
## MIGRATIONS
1. init migration
    ```
    npx sequelize
    ```
2. create migrations
    ``` npx sequelize migration: generate --name create-roles
    (nanti bikin file baru di migration misal bikin roles)
    ```
3. running migration
    ```
    npx sequelize db:migrate
    ```

4. undo migration
     ```
     npx sequelize db:migrate:undo
     ```