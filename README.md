# ⚡ Zarvox Email-Osint v1.0

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9%2B-red?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Platform-Termux%20%7C%20Linux%20%7C%20Windows-blue?style=for-the-badge&logo=linux&logoColor=white">
  <img src="https://img.shields.io/badge/License-MIT-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-brightgreen?style=for-the-badge">
  <img src="https://github.com/user-attachments/assets/797db9f0-6cf1-4419-a2d4-3718f66e28c5">

</p>

**Zarvox Ghost-OSINT**, e-posta adresleri üzerinden dijital ayak izi takibi yapmak için geliştirilmiş, yüksek performanslı bir istihbarat çerçevesidir. 120'den fazla platformda saniyeler içinde derin tarama yaparak hedefin dijital DNA'sını ortaya çıkarır.

---

## 🚀 Özellikler

* **🔍 Derin Analiz:** E-posta adresinin bağlı olduğu Google ID ve dijital parmak izlerini anlık tespit eder.
* **🌐 Platform Doğrulama:** Holehe motoru entegrasyonu ile 120+ servis üzerinde (Instagram, Twitter, Netflix vb.) kayıt kontrolü yapar.
* **📡 Sunucu İstihbaratı:** Hedef domainin MX kayıtlarını ve mail sunucu aktifliğini profesyonelce sorgular.
* **⚠️ İhlal Taraması:** Veri sızıntılarında (Data Breaches) e-posta adresine ait metadata izlerini raporlar.
* **📊 Profesyonel Raporlama:** Tüm verileri şık ve scannable terminal tabloları içinde sunar.

---

## 📱 Termux Kurulumu

Termux kullanıcıları için optimize edilmiş hızlı kurulum komutları:

```bash
pkg update && pkg upgrade -y
pkg install python git -y
pip install holehe colorama terminaltables requests
git clone https://github.com/zarvoxx/Email-Osint.git
cd emailosint
python emailosint.py
