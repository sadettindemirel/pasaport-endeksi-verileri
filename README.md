Pasaport Endeksi Verileri
================

### Veri Seti Hakkında

Pasaport Endeks verisi 2015 - 2019 yıllarını kapsamaktadır. Veriler [pasaportindex.org'dan kazınmıştır](https://www.passportindex.org/byHistoric.php). Verisetinde
iki temel gösterge vardır:

**hareketlilik skoru** : Pasaportun diğer ülkelere seyahatteki esnekliği
(yüksek puan = daha iyi skor)

**sıralama** : Sıralama ise alınan hareketlilik skoruna göre
değişmektedir.

Aşağıdaki tabloda *year* sütunu *yil*’ın sadeleştirilmiş halidir.

``` r
head(pp_tidy2,10)
```

    ##                   ülke          gosterge        yil deger year
    ## 1          Afghanistan hareketlilik_skor 2019-01-01    30 2019
    ## 2              Albania hareketlilik_skor 2019-01-01   114 2019
    ## 3              Algeria hareketlilik_skor 2019-01-01    60 2019
    ## 4              Andorra hareketlilik_skor 2019-01-01   151 2019
    ## 5               Angola hareketlilik_skor 2019-01-01    59 2019
    ## 6  Antigua and Barbuda hareketlilik_skor 2019-01-01   135 2019
    ## 7            Argentina hareketlilik_skor 2019-01-01   158 2019
    ## 8              Armenia hareketlilik_skor 2019-01-01    72 2019
    ## 9            Australia hareketlilik_skor 2019-01-01   164 2019
    ## 10             Austria hareketlilik_skor 2019-01-01   167 2019

**Pasaportların Hareketlilik Skorlarının Görselleştirilmiş Hali**

![](https://github.com/sadettindemirel/pasaport-endeksi-verileri/blob/master/pasaport_viz2.png?raw=true)
