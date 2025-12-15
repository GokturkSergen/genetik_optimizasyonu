# Genetik Algoritma ile Üretim Planlama (Senaryo 5)

Bu proje, bir kimya tesisindeki **Reaksiyon Süresi** ve **Sıcaklık** değerlerini optimize ederek maksimum verimi bulmayı amaçlayan bir Genetik Algoritma çalışmasıdır.

## Proje Özeti
* **Senaryo:** 5 (Kimya Tesisi)
* **Amaç:** Verim fonksiyonunu ($y = 8x_1 + 3x_2 - x_1x_2 + x_1^2$) maksimize etmek.
* **Yöntem:** Python kullanılarak, hazır kütüphane olmaksızın Genetik Algoritma kodlanmıştır.

## Kullanılan Yöntemler
Bu projede literatürdeki temel genetik operatörler tercih edilmiştir:
1.  **Seçim:** Rulet Tekerleği yöntemi.
2.  **Çaprazlama:** Tek Noktalı çaprazlama.
3.  **Mutasyon:** Uniform Mutasyonu.
4.  **Kısıt Yönetimi:** Sınırları aşan veya kapasiteyi geçen bireylere **Ceza Puanı** uygulanması.

## Parametreler
Simülasyonda kullanılan hiper-parametreler şöyledir:

**Popülasyon Boyutu:** 100 
**Nesil Sayısı:** 100 
**Mutasyon Oranı:**  0.2 
**Çaprazlama Oranı:** 0.7 

##  Sonuçlar
Algoritma 100 nesil sonunda **660.00** verim değerine ulaşmış ve teorik maksimumu yakalamıştır.

* **Optimal Süre ($x_1$):** 60 dk
* **Optimal Sıcaklık ($x_2$):** 60 °C
* **Maksimum Verim:** 660.00
