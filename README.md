# IP_Degistirici
TOR ağı kullanılarak istenilen süre aralığında ip değiştirme programı

### kullanımı:
- tor ağını başlat:
`service tor start`

- tor'dan şifre al:
`tor --hash-password "şifre"`
- `/etc/tor/torrc` dosyasındaki 'HashedControlPassword' kısmını yorum satırından kaldır ve tor tarafından verilen tokeni yapıştır.
- Control Port 9051 kısmını yorum satırından kaldır

- 'toriptables' dosyasına gelip komutu çalıştır:
`python3 toriptables3.py -l` 

- 'ip_degistirici' dosyasına gelip IP degistiriciyi baslat:
`python ip_degistirici.py`

- Belirlenen şifreyi ve istenilen IP değiştirme süresini girip 'Baslat' butonuna tıklayın.
![Screenshot from 2022-01-24 21-05-25](https://user-images.githubusercontent.com/83416622/150839365-84f62d63-b725-4295-9d69-352beafd32d7.png)
