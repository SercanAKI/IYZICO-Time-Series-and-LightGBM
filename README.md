###############################################################
# İş Problemi
###############################################################

# Iyzico internetten alışveriş deneyimini hem alıcılar hem de satıcılar için kolaylaştıran bir finansal teknolojiler şirketidir.
# E-ticaret firmaları, pazaryerleri ve bireysel kullanıcılar için ödeme altyapısı sağlamaktadır.
# 2020 yılının son 3 ayı için merchant_id ve gün bazında toplam işlem hacmi tahmini yapılması beklenmekte.


###############################################################
# Veri Seti Hikayesi
###############################################################
#  7 üye iş yerinin 2018’den 2020’e kadar olan verileri yer almaktadır.

# Transaction : İşlem sayısı
# MerchantID : Üye iş yerlerinin id'leri
# Paid Price : Ödeme miktarı

###############################################################
# GÖREVLER
###############################################################

# Görev 1 : Veri Setinin Keşfi
            # 1. iyzico_data.csv dosyasını okutunuz. transaction_date değişkeninin tipini date'e çeviriniz.
            # 2.Veri setinin başlangıc ve bitiş tarihleri nedir?
            # 3.Her üye iş yerindeki toplam işlem sayısı kaçtır?
            # 4.Her üye iş yerindeki toplam ödeme miktarı kaçtır?
            # 5.Her üye iş yerinin her bir yıl içerisindeki transaction count grafiklerini gözlemleyiniz.

# Görev 2 : Feature Engineering tekniklerini uygulayanız. Yeni feature'lar türetiniz.
            # Date Features
            # Lag/Shifted Features
            # Rolling Mean Features
            # Exponentially Weighted Mean Features

# Görev 3 : Modellemeye Hazırlık
            # 1.One-hot encoding yapınız.
            # 2.Custom Cost Function'ları tanımlayınız.
            # 3.Veri setini train ve validation olarak ayırınız.

# Görec 4 : LightGBM Modelini oluşturunuz ve SMAPE ile hata değerini gözlemleyiniz.
