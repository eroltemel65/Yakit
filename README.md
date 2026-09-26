# Yakıt Kayıt Defteri

Şantiye makinelerine verilen motorin, AdBlue ve gresi; depoya gelen yakıtı ve depo durumunu takip eden web uygulaması.

- Sayfa: GitHub Pages (`index.html`)
- Veritabanı, giriş ve dosyalar: Supabase (`config.js` içindeki adres ve publishable anahtar)
- `.github/workflows/uyanik-tut.yml`: Supabase ücretsiz projesinin uykuya geçmemesi için 3 günde bir dürter.

Kullanıcı eklemek: Supabase → Authentication → Users → Add user → `girisadi@yakit.app` + şifre, "Auto Confirm User" işaretli.
Yetki değiştirmek: uygulamada Makineler → Hesap ve kullanıcılar (yalnızca yönetici).
