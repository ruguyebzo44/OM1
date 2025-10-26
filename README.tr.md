# OM1 — AçıkKaynak MODÜLER Yapay Zeka Runtime (Türkçe özet)

OM1, robotlar ve simülasyonlar için modüler bir yapay zeka çalışma zamanı sağlar. Humanoidler, mobil uygulamalar, web uygulamaları ve eğitim robotları (TurtleBot 4 vb.) için kullanılabilir.

## Özellikler
- Modüler mimari, Python tabanlı.
- Kamera, LIDAR gibi çoklu sensör girdilerini işler.
- ROS2, Zenoh ve CycloneDDS için eklenti desteği.
- WebSim üzerinden görsel hata ayıklama arayüzü.

## Başlarken — Hello World
1. Depoyu klonlayın:
2. Sanal ortam oluşturun (uv kullanılır):
3. Gerekli paketleri yükleyin.
- macOS:
- Linux:
4. OpenMind API anahtarınızı alın ve `config/spot.json5` veya `.env` içine ekleyin. (Portal: https://portal.openmind.org)
5. Örnek Spot ajanını başlatın:
WebSim varsayılan olarak `http://localhost:8000/` üzerinde çalışır.

## Katkıda bulunmak istersen
- Yeni girdiler veya aksiyonlar ekleyin.
- Konfigürasyon dosyalarını (`/config/`) özelleştirin.
- Dökümantasyon çevirileri ve iyileştirmeleri için PR açın.
