# Web Trafik Loglarına Dayalı Yapay Zeka Destekli Soru-Cevap Sistemi Geliştirme

Bu projede, bir web sitesi için oluşturulan trafik loglarını (IP Address, Timestamp, URL, vb.) kullanarak bir soru-cevap sistemi geliştireceğiz.

Log verilerini Kaggle gibi platformlardan almak yerine, aktif olarak kullanımda olan ve yönetimini de benim yaptığım bir WordPress haber sitesinden aldım. Aşağıda, adım adım log verilerinin nasıl alındığını, log verilerinin temizlenmesini, kullanıma hazır hale getirilmesini, verilerin vektöre dönüştürülüp uygun bir vektör veritabanına yüklenmesini, kullanıcı sorularını ve modelden çıkan cevapları vektörden doğal bir dile çevirmeyi ve RAG modelini kullanarak bir Q&A (soru-cevap) sistemi geliştirmeyi kodlarla beraber göstereceğim.

## Adım 1 – Log Verilerinin Çekilmesi
https://github.com/AhmetGmss/Web-Trafik-Loglarina-Dayali-Yapay-Zeka-Destekli-Soru-Cevap-Sistemi-Gelistirme/blob/main/1.adim.md
## Adım 2 – Çekilen Log Verilerinin Temizlenmesi ve CSV Dosyasına Çevirilmesi
https://github.com/AhmetGmss/Web-Trafik-Loglarina-Dayali-Yapay-Zeka-Destekli-Soru-Cevap-Sistemi-Gelistirme/blob/main/2.adim.py
## Adım 3 – Verilerin Vektörlere Dönüştürülmesi ve FAISS Vektör Tabanına Eklenmesi
https://github.com/AhmetGmss/Web-Trafik-Loglarina-Dayali-Yapay-Zeka-Destekli-Soru-Cevap-Sistemi-Gelistirme/blob/main/3.adim.py
## Adım 4 – Fine-Tuning ile RAG Modelinin Eğitilmesi
https://github.com/AhmetGmss/Web-Trafik-Loglarina-Dayali-Yapay-Zeka-Destekli-Soru-Cevap-Sistemi-Gelistirme/blob/main/4.adim.py
## Adım 5 – Kullanıcıya Cevap Verebilecek RAG Modelinin Kurulması
https://github.com/AhmetGmss/Web-Trafik-Loglarina-Dayali-Yapay-Zeka-Destekli-Soru-Cevap-Sistemi-Gelistirme/blob/main/5.adim.py
## Adım 6 – Sistemin Entegrasyonu
https://github.com/AhmetGmss/Web-Trafik-Loglarina-Dayali-Yapay-Zeka-Destekli-Soru-Cevap-Sistemi-Gelistirme/blob/main/6.adim.py
