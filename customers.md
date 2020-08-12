```
CREATE TABLE customers
(id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
fullname varchar(255),
username varchar(255),
email varchar(255),
phone_number varchar(13),
address varchar(255));
```

```
INSERT INTO customers (fullname, username, email, phoneNumber, address)
VALUES
('Angga Prasetya W', 'anggapw', 'agpw@gmail.com', '080989999', 'Jl. Soekarno Hatta No.99'),
('David Winalda', 'davidw', 'david@gmail.com', '0808123123', 'Jl. Gatot Subroto No.123'),
('Chris Yeo', 'chrisyeo', 'yeochris@gmail.com', '0899456789', 'Jl. Gajah Mada No.10'),
('Muhammad Ridho', 'ridhoaja', 'mridho@gmail.com', '0811506070', 'Jl. Soetoyo S No.22'),
('Mondang', 'monmon', 'mondang@gmail.com', '0889987654', 'Jl. Fatmawati No.46');

```
