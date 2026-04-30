# adc-kart-16bit-1msps
16-bit 1MSPS Fully-Differential ADC Card - KiCad Design

Endüstriyel sensör sinyalleri için yüksek hassasiyetli 
veri toplama kartı.

## Özellikler
- ADS8861 — 16-bit, 1 MSPS, true-differential SAR ADC
- THS4551 — Fully-differential ADC sürücü
- LTC6655 — 2ppm/°C ultra düşük gürültülü voltaj referansı
- LM7705 — True-zero ölçüm için negatif voltaj pompası
- SPI haberleşme arayüzü

## Tasarım Kararları
- CMRR optimizasyonu için %0.1 toleranslı Thin Film direnç
- Sinyal yolunda C0G/NP0 dielektrik kapasitör
- Ferrit bead ile dijital/analog izolasyonu

## Durum
Tasarım tamamlandı. Üretim aşamasında.

## Araçlar
KiCad 7.x
