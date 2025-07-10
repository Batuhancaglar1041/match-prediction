Dosya yolları göreli değildir . Kendi bilgisayarınıza clone ettikten sonra ek bir ayar yapmanız gerekiyor.

proje/
│
├── data/
│   ├── soccer/
│   │   └── database.sqlite
│   └── basketball/
│       └── nba.sqlite
│
├── models/
│   ├── soccer_rf.pkl
│   ├── soccer_xgb.pkl
│   ├── soccer_mlp.pkl
│   ├── soccer_scaler.pkl
│   ├── basketball_rf.pkl
│   ├── basketball_xgb.pkl
│   ├── basketball_mlp.pkl
│   └── basketball_scaler.pkl
│
├── notebooks/
│   ├── soccer3.ipynb              # Soccer train notebook
│   ├── basketball.ipynb           # Basketball train notebook
│
├── test/
│   ├── test_soccer.ipynb          # Soccer test notebook
│   └── test_basketball.ipynb      # Basketball test notebook
│
├── README.md
└── (diğer dosya ve dökümanlar)

soccer3.ipynb: Soccer verisi için feature çıkarımı, eğitim ve model kaydetme.

basketball.ipynb: Basketbol verisi için aynı işlemler.

test_soccer.ipynb: Eğitilmiş soccer modelleriyle test işlemleri ve skorlar.

test_basketball.ipynb: Eğitilmiş basketbol modelleriyle test işlemleri ve skorlar.

models/: Eğitimden çıkan .pkl model ve scaler dosyaları.

data/: Orijinal veritabanları.





Kod ve fonksiyonların tamamı özgün olarak hazırlanmıştır. Kullanılan literatür ve kod kaynakları ilgili hücrelerin altında belirtilmiştir.

Model parametre seçimlerinde şu literatürler dikkate alınmıştır:

Stanford CS230 Proje Raporu

Mendel Makalesi