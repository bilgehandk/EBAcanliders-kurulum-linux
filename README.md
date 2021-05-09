# EBAcanliders-kurulum-linux
Wine ile .exe dosyasını linuxta çalıştırma.


## Linux'ta EBA Canlı Ders Kurulum 
İlk olarak linux terminali açmanız gerekiyor.<br/>
Sonrasında termianala şu kodu yazmanız gerekiyor.

```
sudo apt-get install wine-stable
```

Kodu yazdıktan sonra sizden şifre isteyecektir, şifrenizi girdikten sonra size [e/h] şeklinde bir komut satırısı gelirse e yazıp devam edebilirsiniz.
Yüklenme bittikten sonra yazarak versiyon sürümünüzü kontrol edebilirsiniz.

```
wine --version
```

Eğer versiyon numarası yazıyor ise ise işleme devam edebilirsiniz. Yazmıyorsa yönergeyi baştan tekrarlayın.
Sonrasında indirdiğiniz .exe dosyasının konumuna dosya nın bulunduğu konuma gelerek sağ tıklıyarak uç birimde aça tıklayın. ![Ekran Görüntüsü 2021-05-09 12-58-51](https://user-images.githubusercontent.com/64328743/117567790-7baed280-b0c6-11eb-8848-87152a964f17.png)

Sonrasında şu kodu yazın.

```
ls
```

Sonrasında .exe dosyasına sağ tıklayıp. Özellikleri seçin ve isimi kopyalayın yazacağımız koddan sonra dosya adını terminala yapıştırın ve enter'a tıklayın.

```
wine dosya_adı(sağ tık-yapıştır)
```

Sonrasında exe dosyası çalışacaktır. Yükleme işlemlerini yaptıktan sonra kullanabilirsiniz.
