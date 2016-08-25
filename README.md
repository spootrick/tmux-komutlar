#TMUX Komutları

###Session komutları
Yeni isimsiz session oluşturma
```
tmux
```

İsim vererek yeni session oluşturma
```
tmux new -s <session-adı>
```

Session'ları listeleme
```
tmux list-sessions
tmux ls
```

Session'a bağlanma
```
tmux attach-session -t <session-adı>
tmux a -t <session-adı>
```

Session'dan ayrılma
```
ctrl + b + d
```

Session ad değiştirme
```
tmux rename-session -t <session-adı>
```

choose (ne işe yaradığını tam anlamadım)
```
tmux choose-session -t <session-adı>
```

Session bitirme
```
tmux kill-session -t <session-adı>
```

Önceki session'a geçme
```
ctrl + b + (
```

Sonraki session'a geçme
```
ctrl + b + )
```

Listeden session seçme
```
ctrl + b + s
```

###Ekranı bölümleme
Yatay olarak bölmek için
```
ctrl + b + "
```

Dikey olarak bölmek için
```
ctrl + b + %
```

Bölmeler arasında geçiş yapmak için
```
ctrl + b + <ok-tuşları>
```

Bulunduğun bölümü kapatmak için
```
ctrl + b + x
```

Bölüm numaralarını gösterir
```
ctrl + b + q
```

Bölümleme layout'ları arasında geçiş yapmak için
```
ctrl + b + <boşluk-tuşu>
```

Bulunduğun bölmeye zoom yapmak için
```
ctrl + b + z
```

Bulunduğun bölmeyi sağa taşımak için
```
ctrl + b + }
```

Bulunduğun bölmeyi sola taşımak için
```
ctrl + b + {
```

###Window komutları
Yeni window oluşturma
```
ctrl + b + c
```

Window'lar arasında geçiş
```
ctrl + b + p          # önceki
ctrl + b + n          # sonraki
```

Bütün komutları görüntüleme
```
ctrl + b + ?
```

