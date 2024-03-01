# install in amazon linux 2
`curl -fsSL https://rpm.nodesource.com/setup_16.x | sudo bash -`

`sudo yum install nodejs -y`

`sudo yum install mysql`

# update npm
`npm install -g npm@latest`


# db mysql
`create database school;`


`CREATE TABLE siswa (
    id integer PRIMARY KEY,
    nama VARCHAR(255),
    kelas VARCHAR(50)
);`
