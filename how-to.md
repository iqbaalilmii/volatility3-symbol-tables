# How to pasang symbol table linux ke Volatility3

Download dulu symbol tablenya, bisa dari http://ddebs.ubuntu.com/pool/main/l/linux/ atau https://github.com/Abyss-W4tcher/volatility3-symbols

volatiltiy3 butuh format ISF (Intermediate Symbol Format) dalam bentuk file json.xz

saya saranin download dari githubnya Abbyss-W4tcher saja, biar ga perlu ngubah ddeb jadi ISF (json.xz), setelah download, pindahkan file tersebut ke volatility3/volatility3/symbols/<os>/ 

kalau path os contoh linux belum ada, bisa dibuat dulu, dan setelah itu, congrats, you now can analyze your linux memory dump!
