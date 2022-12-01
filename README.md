# DELL Latitude 5491 14" | Intel i7 (8850H)

[![macOS](https://img.shields.io/badge/macOS-12.6-orange)](https://www.apple.com/ge/macos/monterey/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.8.6-9cf)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/indir-son%20sürüm-blue.svg)](https://github.com/sutsurup/DELL-Latitude-5491-Hackintosh/releases)

<img align="right" src="Images/latitude5490.png" alt="DELL" height="260" width="363">

Türkçe | [English](https://github.com/sutsurup/ASUS-K555UB-Hackintosh/blob/master/README_EN.md)

**macOS Versiyonu: 12.6**

**OpenCore Versiyonu: 0.8.6**

Yardımcı olabilecek kaynaklar: 

- [OpenCore Yükleme Rehberi](https://dortania.github.io/OpenCore-Install-Guide)


# Detaylar

    Tarih:        Aralık 1, 2022
    Durum:        Stabil
    Destek:       BIOS (1.23.0)
    Yapı:         OpenCore

## Donanım

| **DELL** | Detay                                                  |
| ------------------- | ------------------------------------------- |
| Model Ismi      | DELL Latitude 5491      |
| Anakart           | 	DELL 0VGJ22     |
| CPU              | Intel(R) Core(TM) i7-8850H CPU @ 2.60GHz Coffee Lake              |
| RAM           | 2666 MHz 8GB + 2666 MHz 8GB SODIMM (Total: 16GB)   |
| Dahili Grafik Kartı | Intel UHD Graphics 630                    |
| Wi-Fi | 	Intel(R) Wireless-AC 9560 160MHz (OpenIntelWireless Support)               |
| BIOS Versiyonu      | 1.23.0                   |

![](Screenshots/info.png)

## Uyumluluk
**macOS Big Sur 12.6** sürümünde çalışmaktadır. 12.6 sürümüne kadar güncelleme yapabilirsiniz.
Releases bölümünde EFI klasörü için zip dosyası paylaştım. macOS kurulum belleğinizdeki EFI için ayrılan disk bölümünde, EFI adında bir klasör oluşturun ve zip içerisindeki BOOT ve OC klasörlerini EFI klasörü içerisine kopyalayınız.
macOS High Sierra 10.13.6, Mojave 10.14.6, Catalina 10.15.7, macOS Big Sur 12.6 sürümlerinde çalıştırmayı deneyebilirsiniz.

### Çalışıyor

- [x] Uyku
- [x] Wi-Fi + Bluetooth (openIntelWireless, HeliPort'suz)
- [x] Ses ve Mikrofon
- [x] Batarya yüzde göstergesi
- [x] TouchPad ve macOS fonksiyonları (Full)
- [x] Fonksiyon tuşları (fn Keys)
- [x] Ekran parlaklığı

### Çalışmıyor
- [ ] SIM Kart (Cellular - Sierra Wireless AirPrime)
- [ ] Ethernet (BIOS'tan Ethernet'i açınca macOS açılmıyor)
- [ ] HDMI (tam anlamıyla çalışmıyor)

![](Screenshots/update.png)

## Kurulum sonrası yararlanabileğiniz rehber bağlantıları
* önerilir: iCloud'a giriş yapacaksanız veya iMessage, FaceTime kullanmak istiyorsanız, bu rehberi harfiyen uygulayın: [OpenCore ile iMessage ve Apple Servislerini Aktif Etmek](https://osxinfo.net/konu/opencore-ile-imessage-ve-apple-servislerini-aktif-etmek.16297/) (Bu rehberde Clover Configurator gösterilmiş, siz OpenCore Configurator kullanacaksınız, Clover Configurator üzerinden takip edin, verileri OpenCore Configurator aracılığıyla config.plist dosyanıza girin)
* [ProperTree](https://osxinfo.net/konu/propertree-opencore-bootloader-icin-config-duzenleyici.12919/) (config.plist düzenlemek için)
* Hackintool ([Forum thread](https://www.insanelymac.com/forum/topic/335018-hackintool-v286/) | [Direkt indirme linki](http://headsoft.com.au/download/mac/Hackintool.zip)) (Detaylı sistem bilgileri öğrenme ve düzenlemeleri için)

## İletişime geçin
Herhangi bir adımda sorun yaşıyorsanız, öncelikli olarak [issue](https://github.com/sutsurup/DELL-Latitude-5491/issues) bölümüne destek talebi açın! Diğer sorularınız için, Website: http://sutsurup.com // Mail: [veyselfurkan@icloud.com](mailto:veyselfurkan@icloud.com)

## Ekran Görüntüleri
![](Screenshots/Monterey.png)

</details>

## Destek olun.
Projeyi faydalı bulduysanız, kaynak bulma konusunda bana yardımcı olmak için bağış yapabilirsiniz:
```
₿ 1Q8CEMHTuecxPUJpEdpRiG6Bg2GVtzw4bN
``` 
<a href='https://github.com/sutsurup/sutsurup/blob/main/Donate.md'><img alt='Bağış' src='https://github.com/sutsurup/MSI-Hackintosh-Build/blob/main/Images/donate.png?raw=true' height='360px' width='375px'/></a>
```
QR koda tıklayarak alternatif seçeneklere ulaşabilirsiniz
``` 
