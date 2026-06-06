Harika bir proje! İstediğin yapıya uygun olarak, sağladığın teknik dokümandaki bilgilerle hazırladığım **ProEvent** README dosyasını aşağıda bulabilirsin.

---

# 🎓 ProEvent — Etkinlik Kayıt Sistemi

Modern etkinlik yönetim süreçlerini dijital ortama taşıyan, güvenli ve ölçeklenebilir etkinlik kayıt yönetim sistemi.

---

## 📌 Proje Tanıtımı

ProEvent, etkinlik planlama, katılımcı kayıt işlemleri, biletleme süreçleri ve raporlama ihtiyaçlarını merkezi bir yapı altında toplamak amacıyla geliştirilmiş masaüstü tabanlı bir yönetim platformudur.

**Sistem sayesinde:**

* Etkinlik oluşturma işlemleri kolaylaşır
* Katılımcı kayıt süreçleri hızlanır
* Biletleme işlemleri otomatikleştirilir
* Kontenjan takibi hatasız sağlanır
* Detaylı etkinlik raporları görüntülenebilir

---

## 🚀 Projenin Amacı

Bu platformun temel amacı:

* ✅ Etkinlik süreçlerini dijitalleştirmek
* ✅ Kayıt yönetimini merkezi hale getirmek
* ✅ Hızlı ve güvenli bilet oluşturmak
* ✅ Doluluk oranlarını anlık izlemek
* ✅ Kullanıcı dostu bir yönetim deneyimi sunmak

---

## 🛠️ Kullanılan Teknolojiler

| Teknoloji | Açıklama |
| --- | --- |
| **Python** | Ana programlama dili 

 |
| **PyQt5** | Grafik kullanıcı arayüzü 

 |
| **OOP** | Nesne yönelimli programlama 

 |
| **UUID** | Benzersiz bilet numarası üretimi 

 |

---

## 🧠 Yazılım Mimarisi

Sistem, veri güvenliğini sağlamak amacıyla **kapsülleme (encapsulation)** prensipleri uygulanarak geliştirilmiştir. Özellikler gizli (private) tanımlanmış ve modüler bir mimari benimsenmiştir.

### 👤 Katılımcı Sınıfı

Sisteme kayıt olan kişilerin temel bilgilerini yönetir.

* **Tutulan Bilgiler:** ID, Ad Soyad, E-posta
* **Metotlar:** `get_ad()`, `get_email()`, `bilgileri_guncelle()`

### 📅 Etkinlik Sınıfı

Etkinlik detaylarını ve kayıtlı katılımcıları yönetir; kapasite doluluk kontrolü yapar.

* **Tutulan Bilgiler:** Etkinlik adı, tarih, kapasite, katılımcı listesi
* **Metotlar:** `katilimci_ekle()`, `katilimci_cikar()`, `katilimci_raporu()`

### 🎟️ Bilet Sınıfı

Katılımcı ile etkinliği birbirine bağlayan yapıdır.

* 
**Özellik:** UUID tabanlı benzersiz bilet numarası üretir.


* **Metotlar:** `bilet_olustur()`, `bilet_iptal()`

---

## 🖥️ Grafik Kullanıcı Arayüzü (GUI)

Arayüz, PyQt5 kullanılarak kullanıcı dostu ve işlevsel modüllerle tasarlanmıştır.

### 📊 Dashboard

Sistemin genel özetini KPI kartlarıyla sunar. Aktif etkinliklerin doluluk durumlarını tablolar halinde görüntüler.

### ➕ Etkinlik Ekle

Tarih, kontenjan ve isim belirterek hızlıca yeni etkinlik tanımlanmasını sağlar.

### 📝 Kayıt Yönetimi

Katılımcı bilgilerinin girildiği ekrandır. E-posta doğrulaması ve kapasite kontrolü yaparak veri bütünlüğünü korur.

### 🎫 Biletler

Tüm biletlerin listelendiği modüldür. Detay butonuna tıklandığında görsel olarak zenginleştirilmiş bilet detay penceresini açar.

### 📈 Rapor

Seçilen etkinliğin doluluk oranını **yüzde bazında ilerleme çubuğu** ile görselleştirir ve kayıtlı kişilerin listesini sunar.

### 🔐 Admin Paneli

Giriş şifresi (123) gerektiren güvenli alandır.

* 
**Yetkiler:** Etkinlik silme, katılımcı kaydı iptali ve sistem işlem geçmişi (log) takibi.



---

## 🌟 Platform Avantajları

* ✅ Kapsülleme ile yüksek veri güvenliği 


* ✅ Görsel raporlama sistemi (İlerleme çubukları) 


* ✅ Hızlı etkinlik ve bilet yönetimi 


* ✅ Güvenli yönetici paneli 


* ✅ Modern PyQt5 arayüzü 



---

### 🏁 Sonuç

ProEvent, etkinlik yönetim süreçlerini verimli hale getirmek için geliştirilmiş modern, güvenli ve nesne yönelimli bir masaüstü uygulamasıdır. Hem teknik altyapısı hem de kullanıcı odaklı arayüzü ile etkinlik süreçlerinizde tam kontrol sağlar.

---

Bu proje teknik dokümantasyon esaslarına göre hazırlanmıştır.

---

ProEvent sisteminin mimarisini ve arayüz modüllerini daha iyi kavramak ister misin? Eğer istersen,  gibi sistem yapısını gösteren bir şema üzerinde çalışabiliriz.
