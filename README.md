# Discord Bot Panel (balikesirlicalintipanel.py)

Bu proje, **Nextcord** tabanlı bir Discord botunu yönetmek için **PyQt5** ile hazırlanmış görsel bir panel sunar.  
Bot; sunucu ve DM mesajlarını görüntüleyebilir, mesaj gönderebilir, hata loglarını takip edebilir ve entegre edilmiş **Google Gemini** yapay zekası ile yanıt verebilir.

---

## ✨ Özellikler

- 🎛️ **GUI Panel** → PyQt5 ile şık bir Discord bot kontrol paneli  
- 📡 **Sunucu mesajlarını takip etme** ve panelden direkt mesaj gönderme  
- ✉️ **DM gönderme** ve DM loglarını izleme  
- ⚠️ **Hata loglarını görüntüleme**  
- 🤖 **Yapay Zeka entegrasyonu (Google Gemini API ile)**  
  - Normal, Alaycı, Delirme modları  
  - Ayarlanabilir "hayal gücü" (temperature) değeri  
- ⌨️ **Kısayol tuşları**  
  - F1 → Ana Menü  
  - F2 → Sunucu Mesajları  
  - F3 → DM Mesajları  
  - F4 → Hata Logları  
  - F5 → Botu Başlat  
  - F6 → Botu Durdur  
  - F7 → Yapay Zeka  

---

## 🔧 Kurulum

### Gereksinimler
- Python **3.9+**
- Aşağıdaki kütüphaneler:

```bash
pip install nextcord PyQt5 python-dotenv google-generativeai
```
Yapa bilir ve ya requirements.txt kullana bilirsiniz:
```bash
pip install -r requirements.txt
```

---

## ⚙️ .env Dosyası

Proje ilk çalıştırıldığında otomatik olarak `.env` dosyası oluşturur. İçine kendi bilgilerinizi ekleyin:

```
DISCORD_TOKEN=discord_bot_tokeniniz
GEMINI_API_KEY=gemini_api_keyiniz
```

---

## 🚀 Çalıştırma

```bash
python balikesirlicalintipanel.py
```

Başarılı çalıştırıldığında **karanlık temalı** bir kontrol paneli açılır.  

- **Botu Başlat** butonu ile bot devreye girer.  
- **Sunucu mesajları, DM’ler ve hata logları** panelde anlık gösterilir.  
- **Yapay zeka panelinden** AI durumunu açıp kapatabilir, modunu değiştirebilirsiniz.  

---

---

## ⚠️ Uyarılar

- Yasaklı içerik filtreleri (**çocuk istismarı, zoofili, vb.**) otomatik engellenir.  
- Yapay zeka **“Delirme” modu** NSFW içerik üretebilir. Kullanım tamamen **kendi sorumluluğunuzdadır**.  
- Discord bot tokeninizi **asla kimseyle paylaşmayın!**

---

## 📜 Lisans

# MIT License
# Copyright (c) 2025 Aetherlog
