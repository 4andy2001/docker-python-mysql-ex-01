# docker-python-mysql

Demonstrates dockerizing a python app, MySQL server and phpMyAdmin to show how to use MySQL from a python app.

- Uses mysql-connector-python driver for communicating with MySQL servers: https://pypi.org/project/mysql-connector-python/

- Uses phpMyAdmin for administering the MySQL server: https://www.phpmyadmin.net/

See the following links for sources of this example.

https://www.youtube.com/watch?v=WBqHr2kPc_A&t=55s

https://vaishnavipkand.medium.com/python-app-mysql-containerization-using-docker-508e5f47f771

https://blog.miguelgrinberg.com/post/create-a-mysql-database-using-docker

## Setup git for the project
Create repository in github 4andy2001 called docker-python-mysql
Get the URL of the repository, i.e., git@github.com:4andy2001/docker-python-mysql.git

Create a .gitignore file

In the directory containing the project files, i.e., docker-python-mysql execute the following to initialize the git project do the initial commit and push: 
```
git init
git add .
git commit   
git remote add origin git@github.com:4andy2001/docker-python-mysql.git
git branch -M main
git push -u origin main
```


## Execute
```
docker compose up
```