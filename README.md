# 🧠 SmartNotes – Akıllı Not Sistemi

SmartNotes, notlarınızı kolayca oluşturabileceğiniz, düzenleyebileceğiniz ve yönetebileceğiniz bir Django tabanlı web uygulamasıdır.  

Ek olarak chatbot modülü ile interaktif not sorgulama/önerme özellikleri mevcuttur.

## ✨ Özellikler
- Not oluşturma/güncelleme/silme
- Kullanıcı girişi (isteğe bağlı)
- Chatbot (OpenAI tabanlı)
- Basit ve sezgisel arayüz

## 🔧 Teknolojiler
- Django 4.x
- Python 3
- SQLite
- HTML / CSS / Bootstrap

## ⚙️ Kurulum

```bash
git clone https://github.com/Kinlesh/smartnotes.git
cd smartnotes
pip install -r requirements.txt  # varsa
python manage.py migrate
python manage.py runserver
