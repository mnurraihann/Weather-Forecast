# Weather-Forecast
Aplikasi untuk memenuhi Tugas 2 Seleksi Calon Asisten Lab Programming 2018

oleh

Muhammad Nurraihan Naufal / 13516017

-----
### 1. API dan OpenWeatherMap API

API atau *Application Programming Interface* adalah kumpulan perintah, fungsi, protokol, dan objek yang dapat digunakan oleh *programmer* untuk membuat perangkat lunak atau berinteraksi dengan sistem eksternal. (Sumber: https://techterms.com/definition/api)

OpenWeatherMap merupakan API yang dapat digunakan untuk mendapatkan data cuaca dari berbagai kota di dunia. Beberapa API yang tersedia dari OpenWeatherMap ini misalnya *Current Weather*, *5 day / 3 hour forecast*, dan *16 day / daily forecast*.

Pada API *Current Weather*, misalnya. API ini akan memberikan akses untuk mendapatkan data cuaca pada lebih dari 200.000 kota di seluruh dunia. Cuaca yang didapatkan pun selalu ter-*update* berdasarkan data yang diperoleh dari lebih dari 40.000 stasiun cuaca. Data yang didapatkan dapat diperoleh dalam bentuk JSON, XML, maupun HTML. (Sumber: https://openweathermap.org/api)

-----
### 2. Struktur *Package*

Karena saya masih belum terlalu mendalami *java packages*, jadi dalam aplikasi ini saya hanya akan membuat satu *package*, yaitu weatherforecast. *Package* ini akan terdiri dari empat kelas, yaitu:
1. *Class* Main

Kelas utama

2. *Class* Panel

Kelas untuk *User Interface*

3. *Class* CityController

Kelas untuk mengelola daftar kota yang tersedia dari data yang didapat dari OpenWeatherMap API

4. *Class* City

Kelas yang merepresentasikan sebuah kota beserta data cuacanya

5. *Class* WeatherGetter

Kelas untuk memperoleh data dari OpenWeatherMap API

-----
### 3. *Checklist*
| No  |Nama Kelas   |Sudah?   |
| ------------ | ------------ | ------------ |
|   1| Main  | Belum  |
|   2| Panel  | Belum  |
|   3| CityController  | Belum  |
|   4| City  | Belum  |
|   5| WeatherGetter  | Belum |