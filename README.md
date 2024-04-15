# go-bookstore-mysql
## Bookstore API management using GoLang and MySQL database
### This project uses `GORM` to conect with `MYSQL` database

### Dependencies
```
github.com/go-sql-driver/mysql (mysql driver)
github.com/gorilla/mux (getting router params)
github.com/jinzhu/gorm (ORM for connecting to sql dbs)
```

### File Structure
- cmd
    - main
        - main.go
- pkg
    - config
        - app.go
    - controllers
        - book-controllers.go
    - models
        - book.go
    - routes
        - bookstore-routes.go
    - routes
        - util.go

### Connection URI
```
<USERNAME>:<PASSWORD>/<DATABASE>?charset=utf8&parseTime=True&loc=Local
```