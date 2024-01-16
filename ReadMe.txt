1. ganti nama database sesuai kebutuhan pada config/database.go
   pada baris 13  db, err := sql.Open("mysql", "user:password@/dbname?parseTime=true")
   sesuaikan username dan password dan nama database.
2. jalankan dengan go run .


credit https://www.youtube.com/watch?v=YYjb_RszQYY&t=2s&pp=ygULY3J1ZCBnb2xhbmc%3D 