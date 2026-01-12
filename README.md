# 🗺️ Kadastro OOP Lab: Master Seviye Görsel Eğitim Platformu

C# Nesne Yönelimli Programlama (OOP) kavramlarını, **Kadastro Mühendisliği** (Taşınmaz, Parsel, Ada, Tapu Sicili) terminolojisiyle harmanlayarak öğreten interaktif bir eğitim platformudur.

## 🔗 Canlı Demo
👉 [Projeyi Canlı İncele](https://erdemalpar.github.io/C-NesneYonelimliProgramlama_OOP/)

---

## 🏛️ Kadastro OOP Mimarisi

Uygulama, karmaşık yazılım mimarisini mesleki terimlerle somutlaştırır:

### 1. Temel Yapı Taşları
*   **Sınıf (Class):** Tapudaki boş bir tescil şablonu veya pafta örneğidir.
*   **Nesne (Object):** O şablona göre tescil edilmiş, alanı ve konumu belli GERÇEK bir parseldir.
*   **Kapsülleme (Encapsulation):** Taşınmazın yüzölçümünün (`private`) doğrudan değiştirilememesi, sadece yasal yollarla (ifraz, cins değişikliği) güncellenmesi.

### 2. Dört Ana Prensip
*   **Kalıtım (Inheritance):** Parsel ve Bina sınıflarının ortak 'Tasinmaz' özelliklerini miras alması.
*   **Çok Biçimlilik (Polymorphism):** Her taşınmazın tipine göre farklı tescil veya detay gösterme davranışı sergilemesi.
*   **Soyutlama (Abstraction):** `IKaydedilebilir` arayüzü ile sisteme eklenen her birimin tescil edilme zorunluluğunun getirilmesi.

### 3. SOLID Prensipleri (Kadastro Fokus)
*   **SRP:** Parsel sınıfının sadece mülkiyet verisinden sorumlu olması.
*   **OCP:** Sisteme 'Sit Alanı' gibi yeni türlerin ana kodu bozmadan eklenmesi.
*   **LSP:** Bir binanın, taşınmaz listesinde hatasız temsil edilebilmesi.
*   **ISP:** Sınıflara sadece ihtiyacı olan yeteneklerin (Örn: `IKoordinatli`) verilmesi.
*   **DIP:** Sistem mimarisinin somut parsellere değil, soyut taşınmaz modellerine bağlı olması.

---

## ✨ Öne Çıkan Özellikler

*   **Tescil Simülasyonu:** Yeni ada/parsel tescil ederek bellekteki (Stack/Heap) yansımasını görün.
*   **Akıllı Müfredat Turu:** 12 adımlık, işlem odaklı rehberli eğitim.
*   **Master Mimari:** `static`, `this`, `base`, `sealed` gibi ileri seviye anahtar kelimelerin kadastro bağlamında kullanımı.
*   **Premium UI:** Dark mode, glassmorphism ve akıllı konumlandırmalı eğitim kartları.

---

## 🛠️ Teknolojiler

*   **Tailwind CSS** | **Vanilla JavaScript** | **Font Awesome** | **Fira Code**

---

**Hazırlayan:** [Erdem Alpar](https://github.com/erdemalpar)
