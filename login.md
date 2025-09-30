# Problem Statement
Dibutuhkan mekanisme untuk memvalidasi kredensial dari orang yang mengakses website/aplikasi dan membedakan peran pengguna 

# Solution

## Functional Requirements
- User bisa memasukkan username dan password untuk mengakses akunnya
- Jika user salah mengetik username atau password, sistem memberitahu dengan jelas bahwa username dan password yang dimasukkan tidak cocok.
- Jika username dan password yang dimasukkan benar, langsung diarahkan ke halaman inventory

## UX/UI
- UI Login 
![login](https://github.com/adhikanugraha/E-commerce-Documentation/blob/main/assets/login.png)
- UI Login failed
![alttext](https://github.com/adhikanugraha/E-commerce-Documentation/blob/main/assets/login_wrong.png)

## Business Logic
- Core Rule:
  - User harus mengisikan username dan password untuk login
  - User hanya boleh login jika akun sudah terdaftar

- FLowchart :
  
![login diagram](https://github.com/adhikanugraha/E-commerce-Documentation/blob/main/diagrams/login.png)
