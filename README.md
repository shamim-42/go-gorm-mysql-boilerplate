# Go GORM (object relational mapper for Golang) and Mysql boilerplate

## How to start
1. Clone the repository in your local pc
2. create a mysql database named `go_gorm_mysql`
3. Run `go run main.go` in the project root
4. Now test the apis by Postman or anyother API testing tool.
### Demo `.env`
```
# # Postgres Live
# API_SECRET=98hbun98h #Used when creating a JWT. It can be anything
# DB_HOST=127.0.0.1
# DB_DRIVER=postgres
# DB_USER=username
# DB_PASSWORD=password
# DB_NAME=fullstack_api
# DB_PORT=5432 #Default postgres port

# # Postgres Test
# TestApiSecret=98hbun98h
# TestDbHost=127.0.0.1
# TestDbDriver=postgres
# TestDbUser=username
# TestDbPassword=password
# TestDbName=fullstack_api_test
# TestDbPort=5432

# Mysql Live
API_SECRET=98hbun98h #Used when creating a JWT. It can be anything
DB_HOST=127.0.0.1
DB_DRIVER=mysql 
DB_USER=my_user_name
DB_PASSWORD=my_db_password
DB_NAME=go_gorm_mysql
DB_PORT=3306 #Default mysql port

# Mysql Test
TestApiSecret=98hbun98h
TestDbHost=127.0.0.1
TestDbDriver=mysql
TestDbUser=my_user_name
TestDbPassword=my_db_password
TestDbName=go_gorm_mysql
TestDbPort=3306
```

