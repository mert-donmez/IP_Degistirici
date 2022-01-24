# IP_Degistirici
TOR ağı kullanılarak istenilen süre aralığında ip değiştirme programı

### kullanımı:
- tor ağını başlat
`service tor start`

- tor'dan şifre al
`tor --hash-password "şifre"`
- tor tarafından verilien hash tokenini `/etc/tor/torrc` dosyasındaki 'HashedControlPassword' kısmını yorum satırından kaldır ve tokeni yapıştır.
- Control Port 9051 kısmını yorum satırından kaldır

- toriptables kısmından ip adresi al
`python3 toriptables3.py -l` 

- IP degistiriciyi baslat
`python ip_degistirici.py`
