# PCD_Assignment02 – Peningkatan Kualitas Citra (Image Enhancement)
## Nama : Chelsea Christofera Antonioli Purnomo 
## NIM : 25/558145/PA/23462

## Gambaran Umum

Tugas ini berfokus pada peningkatan kualitas citra menggunakan OpenCV dan Python.

1. Citra *underexposed* (kurang pencahayaan)
2. Citra kontras rendah
3. Citra kabur (*blurred*)
4. Citra *overexposed* (kelebihan pencahayaan)

## Metode

| Citra | Masalah | Metode |
|---|---|---|
| Citra 1 | *Underexposure* | Koreksi Gamma |
| Citra 2 | Kontras Rendah | *Contrast Stretching* + CLAHE |
| Citra 3 | Kabur (*Blur*) | *Unsharp Masking* |
| Citra 4 | *Overexposure* | Koreksi Gamma |

## Struktur Repositori
```text
PCD_Assignment02/
│
├── PCD_Assignment02.ipynb
│
├── dataset/
│   ├── image1_underexposed.jpeg
│   ├── image2_low_contrast.jpeg
│   ├── image3_blurred.jpeg
│   └── image4_overexposed.jpeg
│
├── results/
│   ├── image1_underexposed_enhanced.png
│   ├── image2_low_contrast_enhanced.png
│   ├── image3_blurred_enhanced.png
│   └── image4_overexposed_enhanced.png
│
├── report/
│   └── PCD Assignment02 Report Analysis.pdf
│
└── README.md
