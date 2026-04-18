ID_2.1 My Scheduled Reports: Export
 
 Icon Button: 
- Tıklanabiliyor mu? → Functional
- Yetkili kullanıcılar tarafından kolayca görülebiliyor mu? → Functional (UI) + Usability
- Yetkili kullanıcılar tarafından tıklanabiliyor mu? → Functional
- Tıklandıktan sonra hızlı açılıyor mu? → Performance
- Farklı browser ve sistemlerde çalışıyor mu? → Compatibility
- Yetkisi olmayan kullanıcılar için gizli mi / tıklanamaz mı? → Functional + Security (Authorization)
- Yetkisiz kullanıcı sayfaya girince hata mesajı alıyor mu? → Functional + Security
- Mesaj anlaşılabilir mi? → Usability
- Mesaj gösterilmezse sistem nasıl davranır? → Functional (Negative Testing)
- Tıklayınca pop-up açılıyor mu? → Functional

Pop-up:
- Ne kadar hızlı açılıyor? → Performance
- Gerekli 3 seçenek mevcut mu? → Functional
- Seçenekler çalışıyor mu? → Functional
- Seçenekler kullanıcılar tarafından anlaşılabilir mi? → Usability
- Seçenek isimleri doğru mu? → Functional (UI)
- Her belge formatı düzgün çalışıyor mu? → Functional
- Farklı browserlarda tutarlı çalışıyor mu? → Compatibility
- Unicode seçeneği doğru şekilde uygulanıyor mu? → Functional

ID_2.2. Report Export: File Format Availability

File Format Availability:
- Raporların boyutu doğru hesaplanıyor mı? → Functional
- Raporların boyutları hedeflenen süreler içerisinde hesaplanıyor mu? → Performance 
- Raporların boyutları kullanıcı Export kısmını açmadan hesaplanmış oluyor mu? → Functional
- Raporların boyutları kullanıcı Export kısmını açtığında henüz hesaplanmamış olursa sistem ne yapıyor? → Functional (Negative Testing)
- Desteklenmeyen dosya formatları kullanıcıya açıklayıcı bir şekilde iletiliyor mu? → Functional + Usability
- Raporların boyutu hesaplanırken loading spinner görünüyor mu? → Functional (UI)
- Belge boyutuna göre kullanılabilecek olan dosya formatları doğru ayrılıyor mu? → Functional (BVA) + (EP) 
- Dosya boyutu limitsiz olan formatlarda export yapılırken çok yüksek boyutlu dosyaların işlenmesi problem yaratıyor mu? → Performance (Stress Testing)
- Yükseltilmiş PDF dosyası payroll register PST reports haricinde export yapmaya izin veriyor mu? → Functional + Security (Allowed options)
- Export edilen dosyalar çalışıyor mu? → Functional + Structural
- Yoğun trafik altındayken dosya boyutları beklenen sürelerde hesaplanıyor mu? → Performance (Load Testing)



