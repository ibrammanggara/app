# install in amazon linux 2
`curl -fsSL https://rpm.nodesource.com/setup_16.x | sudo bash -`

`sudo yum install nodejs -y`
# update npm
`npm install -g npm@latest`


# db mysql
`create database school;`


`CREATE TABLE siswa (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nama VARCHAR(255),
    kelas VARCHAR(50)
);`
