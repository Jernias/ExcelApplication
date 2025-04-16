# 🛠 macOS Kullanıcıları için Uygulama Açma Talimatı

macOS, Apple tarafından imzalanmamış uygulamaları güvenlik nedeniyle doğrudan çalıştırmanıza izin vermez. Aşağıdaki yöntemle uygulamayı kolayca çalıştırabilirsiniz:

---

### Adım adım aşağıdaki yazılanları uygulayın.

İlk olarak indirdiğiniz .dmg uzantılı dosyayı "Applications" klasörüne sürükleyip bırakın.

* Uygulama yüklendikten sonra "F4" tuşuna basarak "Terminal"'i açınız.
* Açılan terminal ekranında aşağıdaki komut satırını yapıştırıp enter'a basınız.
```bash
xattr -cr /Applications/Flyport\ Scraper.app 
```

* Terminal'i artık kapatabilirsiniz, uygulama sorunsuz çalışacaktır.




## NOT: Windows tarafında indirdiğiniz .exe uzantılı dosyayı direkt açabilirsiniz, bir sorunla karşılaşmayacaksınızdır.
