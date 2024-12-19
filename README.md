# Header-Pin-Connectors-for-PCB

![1X9_F_90](https://github.com/user-attachments/assets/cf564546-072b-4bcb-8c36-fcc3f8532498) ![1x2_F_180](https://github.com/user-attachments/assets/47a8e7aa-0233-4d1f-bb94-13102dbc4ddd)

**Proje Adı:** Header Kütüphanesi ve 3D Modelleri Oluşturma
**Kullanılan Yazılım:** Altium Designer
**Proje Amacı:** Elektronik devre tasarımlarında kullanılacak 1, 2 ve 3 rows header’ların şematik ve PCB kütüphanelerini oluşturmak ve her bir header tipi için 3D modelleri entegre ederek tasarım sürecinde verimliliği artırmak.

## Header Türleri ve Özellikleri

- 1 Row Header:
Dişi (Female) 90° ve 180°
Erkek (Male) 90° ve 180°

- 2 Row Header:
Dişi (Female) 90° ve 180°
Erkek (Male) 90° ve 180°

- 3 Row Header:
Dişi (Female) 90° ve 180°
Erkek (Male) 90° ve 180°

Her header tipi, devredeki sinyalleri ve güç bağlantılarını iletmek için kullanılır ve elektronik devrelerin birbirine bağlanmasını sağlar. 1, 2 ve 3 rows header'lar, her bir pin sayısına göre farklı işlevler ve bağlantılar sağlar.

## Şematik ve PCB Kütüphanelerinin Oluşturulması

- **2.54mm’lik header pinlerinin datasheet’leri incelendi ve gerekli parametreler alındı.**
- **Altium Designer’da her bir header tipi için şematik semboller ve footprint’ler oluşturuldu.**
- **Pin atamaları, her bir header için gerçek hayattaki karşılıkları ile uyumlu olacak şekilde düzenlendi.**
- **Her bir bileşen için 3D Step dosyaları indirildi ve Altium Designer’a import edilerek bileşenlere atandı.**
- **Oluşturulan header kütüphanesi, ilerideki projelerde tekrar kullanılabilecek şekilde düzenlendi.**
   
## Kütüphane İçeriği

- **1 Row Header Kütüphanesi:**
Dişi (Female) 90° – 10 Adet
Dişi (Female) 180° – 10 Adet
Erkek (Male) 90° – 40 Adet
Erkek (Male) 180° – 40 Adet

- **2 Row Header Kütüphanesi:**
Dişi (Female) 90° – 10 Adet
Dişi (Female) 180° – 20 Adet
Erkek (Male) 90° – 12 Adet
Erkek (Male) 180° – 40 Adet

- **3 Row Header Kütüphanesi:**
Dişi (Female) 90° – 16 Adet
Dişi (Female) 180° – 16 Adet
Erkek (Male) 90° – 12 Adet
Erkek (Male) 180° – 12 Adet

## Kütüphane Oluşturma Süreci

- **Şematik ve PCB Kütüphanelerinin Yapılandırılması:** Altium Designer ortamında, her bir header tipi için şematik semboller ve fiziksel footprint’ler tasarlandı. Pin atamaları, PCB üzerindeki pin atamalarıyla uyumlu olacak şekilde düzenlendi.

- **3D Model Entegrasyonu:** 3D step dosyaları indirildi ve Altium Designer’a import edilerek, header'lar için 3D görselleştirme sağlandı. Bu, PCB üzerindeki bağlantıların daha gerçekçi bir şekilde görülmesini sağladı.

- **Standardizasyon ve Verimlilik:** Her bir header tipi için oluşturulan bileşenler, tasarım sürecinde tekrar kullanılabilirliği sağlamak amacıyla entegre kütüphaneye eklendi. Bu, ilerideki projelerde standardizasyonu ve verimliliği artırdı.

## Sonuçlar ve Katkılar

Zaman Tasarrufu: Kütüphaneler sayesinde tasarımcılar, her seferinde aynı bileşeni manuel olarak çizmeye gerek kalmadan, entegre kütüphaneden bileşenleri seçip tasarımlarına ekleyebilecek.
Tasarımda Tutarlılık: Kütüphane, tüm projelerde tutarlılığı sağlayarak, her bileşenin doğru şekilde kullanılması sağlandı.
Verimlilik: Tasarım sürecinde tekrar eden görevlerden kaçınılarak, proje süresi kısaltıldı ve daha verimli bir çalışma sağlandı.


## Sonuç

1, 2 ve 3 rows header kütüphanelerinin oluşturulması, gelecekteki projelerde kullanılabilir ve tekrar kullanılabilir bileşenler sağladı. Ayrıca, her bir header tipi için detaylı şematik semboller, footprint’ler ve 3D modeller entegre edilerek, tasarım sürecinde verimlilik, doğruluk ve hız artırıldı.


## İletişim

**Not**: Şu an için yalnızca **1 Sıra Header'lar** kütüphaneye eklenmiştir. Tüm kütüphane hakkında daha fazla bilgi ve kullanım için iletişime geçmeniz gerekmektedir.

## Katkıda Bulunma

Bu projeye katkıda bulunmak isterseniz, yeni header türleri ekleyerek veya mevcut bileşenleri iyileştirerek bir pull request (çekme isteği) gönderebilirsiniz. Lütfen bileşenlerin adlandırma ve standartlara uygun olmasına dikkat edin.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır - detaylar için [LICENSE.md](LICENSE.md) dosyasını inceleyebilirsiniz.
