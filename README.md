# Kütüphane Otomasyonu

Bu yazılım, bir kütüphanedeki tüm işlemleri takip etmek ve yönetmek için geliştirilmiş bir otomasyon sistemidir. Program, personel tarafından yönetilir ve kullanıcılar internet üzerinden hazır bir şekilde kaydolmuş gibi işlem yapar.

## Özellikler

### 1. **Personel Kayıt İşlemi**
- **Personel Kayıt:** Personel, program üzerinden kayıt olur. Kayıt işlemi, kişisel bilgiler (ad, soyad vb.) ve çalışma bilgilerini içerir.
- **Kayıt Olma Butonu:** Personel, programda bulunan "Kayıt Ol" butonuyla kaydını yapar. Kullanıcılar ise internet üzerinden zaten hazır kayıtlı olarak görünürler.

### 2. **Kullanıcı Emanet İşlemleri**
- **Emanet Verme:** Personel, kitapların barkodlarını okutarak kullanıcılara emanet verir. Emanet verme işlemi sırasında kitap adı, kullanıcı adı, TC kimlik numarası, emanet verme tarihi ve emanet alınacak kitap sayısı gibi bilgiler kaydedilir.
- **Stoktan Düşürme:** Emanet verilen kitap, sistemdeki stoktan düşer ve güncel stok durumu takip edilir.

### 3. **Emanet Alma**
- **Emanet Geri Alınması:** Kullanıcılar, kütüphaneye geldiklerinde emanet aldıkları kitapları geri teslim ederler. Bu işlemde kitap, stokta geri eklenir ve kullanıcıların emanet geçmişi güncellenir.
- **Emanet Durumu Güncelleme:** Kitap teslim alındığında, teslim tarihi kaydedilir ve geçikmiş kitaplar için gerekli işlemler yapılır.

### 4. **Geçikmiş Kitaplar**
- **Geçikme Takibi:** Geçikmiş kitaplar otomatik olarak takip edilir. Geçikme durumu, teslim tarihi ve geçikmiş kitaplar ayrı bir listede görüntülenebilir.
- **Ödeme Bilgisi:** Eğer kütüphanede geçikme için ödeme yapılması gereken bir sistem varsa, bu da sistemde tutulabilir.

### 5. **Kitap Stok Takibi**
- **Stok Yönetimi:** Kitapların durumu ve mevcut stoklar sürekli güncellenir. Emanet verilen kitaplar stoktan düşerken, geri alınan kitaplar tekrar stokta görünür.
- **Kitap Bilgisi:** Kitaplar, ISBN, yazar, yayın evi gibi bilgileriyle birlikte kaydedilebilir.

### 6. **Kullanıcı Bilgileri**
- **Kullanıcı Görüntüleme:** Sistemdeki tüm kullanıcılar ve yaptıkları işlemler görüntülenebilir. Kullanıcı bilgileri, emanet aldıkları kitaplar ve geçmiş işlemler detaylı bir şekilde görüntülenir.
- **Kullanıcı Yönetimi:** Personel, kullanıcı bilgilerini güncelleyebilir, silebilir veya yeni kullanıcı ekleyebilir.

---

## Kullanıcılar İçin

Kullanıcılar, **internet üzerinden** zaten hazır bir şekilde kayıt olmuş gibi görüneceklerdir. Personel, sistem üzerinden kullanıcıların kitaplarını emanet verir ve alır.

## Personel İçin

Personel, kayıt olma işlemini sistem üzerinden gerçekleştirir ve ardından kitapları barkodlarıyla kaydeder. Personel, kullanıcıların emanet işlemlerini yönetebilir ve sistemdeki kitapları kontrol edebilir.

---

## Kurulum

1. Git deposunu klonlayın veya dosyaları indirin.
2. `KutuphaneOtomasyonu.rar` projesini Visual Studio'da açın.
3. Projeyi derleyin ve çalıştırın.

### Gereksinimler
- **.NET Framework 4.7.2 ve üzeri**
- **Microsoft Access**

---

## Kullanıcı Arayüzü

### 1. Kayıt Ekranı
Personel, kullanıcıları sistem üzerinden kaydeder ve bu işlem, kullanıcıların internetteki gibi hazır kaydolmuş gibi görünmesini sağlar.

### 2. Emanet Verme
Kitaplar, personel tarafından barkod okuyucusu ile okutularak kullanıcılara emanet verilir. Kitapların emanet verildiği tarih kaydedilir ve stoktan düşer.

### 3. Geçikmiş Kitaplar
Geçikmiş kitaplar, sisteme kayıtlı tüm kitaplar arasında görüntülenebilir ve detaylı bilgilerine ulaşılabilir.

### 4. Giriş Ekranı
Kullanıcı adı: Hamza, Şifre: admin

---

## Lisans

Bu yazılım, **MIT Lisansı** ile lisanslanmıştır.

---

## Yazar

Hamza GÜLEŞCİ

---
