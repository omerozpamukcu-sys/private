# AORKing2 Windows paketi

Windows x86 EXE ve gerekli .NET çalışma zamanı ZIP dosyasına dahildir.

Pointer / Offset giriş ekranının eksik olması düzeltildi; bu sekme hem önizlemede hem normal masaüstü açılışında bulunur.

1. `AORKing2-Windows.zip` dosyasını indirip bir klasöre çıkar.
2. Rota kayıt, Tedarik ve Pointer / Offset sekmelerini incelemek için `ArayuzuGor.cmd` dosyasını aç.
3. **Pointer / Offset** sekmesinde değerleri HEX biçiminde girip kaydet. İsteğe bağlı `0x` öneki kullanılabilir.
4. Kaydedilen `pointers.json` dosyasını EXE ile aynı klasörde tut. Uygulamayı kapatıp `BotuAc.cmd` ile yeniden açınca değerler yüklenir. Mevcut ayar dosyan varsa koru.

Tamir, ekipman dayanıklılığı 700 veya altına indiğinde tetiklenir. Slota dönüşte mevcut tedarik turu biter ve atak başlar; otomatik tedarik açıksa açık kalır.

Windows yayını, 46/46 tedarik ve 8/8 ayar testi Linux bulut ortamında tamamlandı. Windows'ta pencere ve canlı NPC işlemleri burada çalıştırılamadı. Paket güncel pointer/offset değerleri sağlamaz.
