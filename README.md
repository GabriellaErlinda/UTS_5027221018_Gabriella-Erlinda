Website ini berguna untuk mencatat kebiasaan sehari-hari agar kita menjadi lebih konsisten dalaml menjalankannya.

## Project Execution
Untuk menjalankan web ini, lakukan serangkaian langkah berikut:
1. Buka folder pada terminal, lalu jalankan `go mod tidy`
2. Buka 2 terminal terpisah, jalankan `make run-server` lalu `make run-client` pada terminal lainnya.
3. Website sudah bisa digunakan

## Project Description
- Project ini menggunakan gRPC dan protobuf sebagai api dan database nya terkoneksi menggunakan atlas mongodb
- Client dapat menambahkan, membaca, mengubah, dan menghapus habit yang diinginkan
- Setiap client menambahkan habit baru, habit tersebut akan ditampilkan dalam Habit List
- Ketika ada habit yang sudah terselesaikan, client bisa menandai habit tersebut sebagai `Done`. Ketika client mencentang checkbox, maka progress bar akan bertambah.
- Ketika pergantian hari dan client akan memulai melaksanakan habit nya dari awal, client bisa meng-klik button `Reset` untuk mereset checkbox dan progress bar

#### Create
![image](https://github.com/GabriellaErlinda/UTS_5027221018_Gabriella-Erlinda/assets/128443451/9c44687a-c640-42f1-8cbe-d15b1ce849db)
![image](https://github.com/GabriellaErlinda/UTS_5027221018_Gabriella-Erlinda/assets/128443451/f26c60e9-db32-4046-be4f-c766577edb44)

#### Read
![image](https://github.com/GabriellaErlinda/UTS_5027221018_Gabriella-Erlinda/assets/128443451/6dc8494a-a323-446e-816c-9573bf04a76a)

#### Update
![image](https://github.com/GabriellaErlinda/UTS_5027221018_Gabriella-Erlinda/assets/128443451/452c8943-838d-448e-af88-3a49302e13e3)

#### Delete
![image](https://github.com/GabriellaErlinda/UTS_5027221018_Gabriella-Erlinda/assets/128443451/005aba7a-35d9-4fb1-b07d-22c027395e25)
![image](https://github.com/GabriellaErlinda/UTS_5027221018_Gabriella-Erlinda/assets/128443451/22122a17-c847-46bf-9984-fd3e4c7f9eef)

#### Atlas MongoDB
![image](https://github.com/GabriellaErlinda/UTS_5027221018_Gabriella-Erlinda/assets/128443451/55a02423-86d2-4cbb-b4ff-3d6534996155)
