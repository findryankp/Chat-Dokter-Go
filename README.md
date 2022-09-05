# E-Satpam (Backend) - Golang
Aplikasi konsultasi dokter PT. Kimia Farma Tbk.

**Development by:** 
- Findryankp

## Init Project
- go mod init chatdok

## Install Packages
* go get github.com/gin-gonic/gin
  - Gin adalah kerangka kerja web yang ditulis dalam Go (Golang). Ini fitur API mirip martini dengan kinerja yang hingga 40 kali lebih cepat berkat httprouter.
* go get github.com/go-sql-driver/mysql
  - Untuk pengaturan koneksi ke mysql
* go get github.com/jinzhu/gorm
  - GORM adalah library ORM (Object Relational Mapping) untuk Golang. Mari kita mulai menulis CRUD API sekarang. Buat project GO baru dan install dependensi terkait. Kita menginstal GORM, Gin dan Mysql dengan menjalankan perintah berikut, pada cmd atau terminal yang sudah berjalan pada directory/folder project kita
* go get github.com/dgrijalva/jwt-go
  - Library json web token
* go get github.com/joho/godotenv
  - mengatur environment golang

**Swaggo documentation API:** 
* go get -u github.com/swaggo/swag/cmd/swag
* go get -u github.com/swaggo/files
* go get -u github.com/swaggo/gin-swagger

## Step By step (MAC OS)
- export PATH=$(go env GOPATH)/bin:$PATH
- swag init

## Fitur
* Auth
   - Register
   - Login
   - Logout
* On Develop

## License
[MIT](https://choosealicense.com/licenses/mit/)