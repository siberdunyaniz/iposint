🌐 ARIVA IP OSİNT TOOLS v3.5 🌐
=============================

🕵️‍♂️ Eğitim Amaçlı OSINT (Açık Kaynak İstihbarat) Aracı 🕵️‍♂️
------------------------------------------------------------

ArivaIPOsint, IP adresleri hakkında detaylı bilgi toplayan, eğitim amaçlı bir OSINT aracıdır. Coğrafi konum, WHOIS bilgileri, veri ihlalleri ve sahte hizmet verileri gibi özellikleriyle siber güvenlik meraklıları için harika bir araçtır! 🚀

⚠️ ***Yasal ve etik kullanım dışı sorumluluk kabul edilmez.***

📲 İletişim:
- Telegram: t.me/AtahanArslan | t.me/siberdunyanizz
- E-posta: siberdunyaniz@gmail.com
- YouTube: SiberDunyaniz (https://www.youtube.com/@SiberDunyaniz)
- Web Sitesi: Yakında... 🌍

🔥 Özellikler
------------

- 🌍 **IP Bilgisi Toplama**: Şehir, ülke, zaman dilimi, internet sağlayıcı gibi detaylar.
- 🔍 **WHOIS Sorguları**: ASN, ağ adı, CIDR, kayıt tarihi gibi bilgiler.
- 🛡️ **Veri İhlali Kontrolü**: IP ile ilişkili alan adlarının bilinen veri ihlalleri.
- 🖥️ **Sahte Veri Simülasyonu**: Açık portlar, hizmetler, cihaz türü, tehdit skoru.
- 🗺️ **Google Haritalar Entegrasyonu**: IP'nin coğrafi konumunu haritada görselleştirme.
- 💾 **JSON Çıktısı**: Sorgu sonuçlarını JSON formatında kaydetme.
- 🎨 **Renkli ve Tablo Tabanlı Arayüz**: Kullanıcı dostu, görsel terminal çıktısı.
- 📊 **Platform İstatistikleri**: Toplam kullanıcı, çevrimiçi kullanıcı gibi sahte veriler.

🛠️ Kurulum
----------

### 📋 Gereksinimler
- Python 3.8+ 🐍
- Gerekli Python kütüphaneleri:
  - requests
  - tabulate
  - pystyle
  - colorama
  - ipwhois
  - tldextract

### 🐧 Kali Linux Kurulumu
1. Depoyu klonlayın veya dosyayı indirin:
   ```
   git clone https://github.com/SiberDunyaniz/iposint.git
   cd iposint
   ```

2. Python ve pip'in güncel olduğundan emin olun:
   ```
   sudo apt update
   sudo apt install python3 python3-pip
   ```

3. Gerekli kütüphaneleri yükleyin:
   ```
   pip3 install requests tabulate pystyle colorama ipwhois tldextract
   ```

4. Scripti çalıştırın:
   ```
   python3 arivaiposint.py
   ```

### 📱 Termux Kurulumu
1. Termux'u güncelleyin ve gerekli araçları yükleyin:
   ```
   pkg update && pkg upgrade
   pkg install python git
   ```

2. Depoyu klonlayın:
   ```
   git clone https://github.com/SiberDunyaniz/iposint.git
   cd iposint
   ```

3. Gerekli kütüphaneleri yükleyin:
   ```
   pip install requests tabulate pystyle colorama ipwhois tldextract
   ```

4. Scripti çalıştırın:
   ```
   python arivaiposint.py
   ```

💡 **Not**: Termux'ta `xdg-open` yerine Google Haritalar bağlantısını manuel olarak tarayıcıda açmanız gerekebilir.

🎮 Kullanım
----------

1. Programı çalıştırdığınızda şu menüyle karşılaşırsınız:
   ```
   [1] IP Adresi Sorgula 🕵️
   [2] Araç Hakkında ℹ️
   [3] Çıkış 🚪
   ```

2. IP adresi sorgulamak için:
   - Bir IP adresi girin (ör. 8.8.8.8) veya genel IP için boş bırakın.
   - Google Haritalar'da konumu görmek için "e" (evet) veya "h" (hayır) seçin.
   - Sonuçları JSON formatında kaydetmek için "e" veya "h" seçin.

### 📺 Örnek Çıktı
```
═══════════════════════════════════════════════════════════
           IPInfoOSINTFetcher (OSINT ile güçlendirildi)
═══════════════════════════════════════════════════════════
[1] IP Adresi Sorgula 🕵️
[2] Araç Hakkında ℹ️
[3] Çıkış 🚪
Seçiminizi yapın (1-3): 1
IP adresini girin (genel IP için boş bırakın): 8.8.8.8
Google Haritalar'da göster? (e/h): e
JSON formatında kaydet? (e/h): h

🌐 IP Info OSINT Raporu 🌐
📍 IP Bilgileri:
┌────────────────────────────┬────────────────────────────┐
│ Alan                       │ Değer                      │
├────────────────────────────┼────────────────────────────┤
│ IP Adresi                  │ 8.8.8.8                    │
│ Tarih ve Saat              │ 12:34:56 01-05-2025        │
│ Ana Bilgisayar             │ dns.google                 │
...
└────────────────────────────┴────────────────────────────┘
```

⚠️ Etik Kullanım Uyarısı
----------------------

ArivaIPOsint, yalnızca **eğitim ve araştırma** amaçlı geliştirilmiştir. Yasal olmayan veya etik dışı herhangi bir kullanım kesinlikle yasaktır. Araç, yalnızca izinli sistemler ve kendi IP adresleriniz üzerinde test edilmelidir. Kullanıcı, aracı kullanırken tüm yasal sorumluluğu üstlenir. Geliştiriciler, kötüye kullanımdan dolayı sorumluluk kabul etmez. 🚨

🤝 Katkıda Bulunma
------------------

Katkıda bulunmak isterseniz:
1. Depoyu forklayın.
2. Yeni bir dal oluşturun: `git checkout -b feature/yeni-ozellik`
3. Değişikliklerinizi yapın ve commit edin: `git commit -m 'Yeni özellik eklendi'`
4. Dalınızı itin: `git push origin feature/yeni-ozellik`
5. Bir Pull Request açın.

Hatalar veya öneriler için Issues sayfasını kullanabilirsiniz:
https://github.com/SiberDunyaniz/iposint

📜 Lisans
---------

Bu proje **MIT Lisansı** altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasını inceleyin.

📬 İletişim
----------

- GitHub: https://github.com/SiberDunyaniz
- Telegram: t.me/AtahanArslan | t.me/siberdunyanizz
- E-posta: siberdunyaniz@gmail.com

Siber güvenlik topluluğuna katkıda bulunmak için projeyi yıldızlamayı unutmayın! ⭐

🚀 SiberDünyanıza Hoş Geldiniz! 🚀