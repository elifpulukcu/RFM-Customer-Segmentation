# RFM Analizi & Müşteri Segmentasyonu

<a href="https://www.github.com/elifpulukcu">
    <img src="https://miro.medium.com/max/1190/1*SMx8ZNSq5ZLZSPh2u_peSw.png" width="800" align="center"></a>

## **İş Problemi** 
> **Problem:** Bir e-ticaret şirketi müşterilerini segmentlere ayırıp bu segmentlere göre pazarlama stratejileri belirlemek istiyor.

- Şirket, ortak davranışlar sergileyen müşteri segmentleri özelinde pazarlama çalışmaları yapmanın gelir artışı sağlayacağını düşünmektedir.
- Şirket için çok kazançlı olan müşterileri elde tutmak için farklı kampanyalar, yeni müşteriler için farklı kampanyalar düzenlenmek istenmektedir.

## **Veri Seti Hikayesi**

> **Veri Seti:** https://archive.ics.uci.edu/ml/datasets/Online+Retail+II

- Online Retail II isimli veri seti İngiltere merkezli online bir satış mağazasının 01/12/2009 - 09/12/2011 tarihleri arasındaki satışlarını içeriyor.
- Bu şirketin ürün kataloğunda hediyelik eşyalar yer almaktadır.
- Şirketin müşterilerinin büyük çoğunluğu kurumsal müşterilerdir.


## **Değişkenler**

- InvoiceNo: Fatura numarası. Her işleme (faturaya) ait eşsiz numara. Eğer bu kod C ile başlıyorsa işlemin iptal edildiğini ifade eder.
- StockCode: Ürün kodu. Her bir ürün için eşsiz numara.
- Description: Ürün ismi
- Quantity: Ürün adedi. Faturalardaki ürünlerden kaçar tane satıldığını ifade etmektedir.
- InvoiceDate: Fatura tarihi ve zamanı.
- UnitPrice: Ürün fiyatı (Sterlin cinsinden)
- CustomerID: Eşsiz müşteri numarası
- Country: Ülke ismi. Müşterinin yaşadığı ülke.

## **Dosyalar**

*data/online_retail_II.xlsx* - [Veri Seti](https://github.com/elifpulukcu/RFM-Customer-Segmentation/tree/master/data)

*RFM.ipynb* - [Proje Dosyası](https://github.com/elifpulukcu/RFM-Customer-Segmentation/blob/master/RFM.ipynb)

## **Kullanılan Kütüphaneler**

```
pandas
numpy
seaborn
matplotlib
datetime
```

## **Yazar**

- Elif Pulukçu - [elifpulukcu](https://github.com/elifpulukcu)
