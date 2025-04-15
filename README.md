## 🎥 Cuplikan Fitur

- Tampilan animasi intro yang lucu dan geeky
- Pertanyaan interaktif: tombol untuk memilih "ya" atau "tidak"
- Animasi happy atau sedih tergantung jawaban
- Efek cinta-cintaan di akhir yang bikin senyum-senyum sendiri 😍

---

## 📦 Komponen yang Dibutuhkan

| Komponen         | Jumlah |
|------------------|--------|
| ESP32            | 1      |
| OLED SH1106 1.3" | 1      |
| Push Button      | 2      |
| Kabel Jumper     | Secukupnya |
| Breadboard       | 1      |

---

## 🔌 Wiring / Rangkaian

| OLED SH1106 Pin | ESP32 Pin |
|-----------------|------------|
| VCC             | 5V       |
| GND             | GND        |
| SCL             | GPIO 22    |
| SDA             | GPIO 21    |

| Push Button | ESP32 Pin |
|-------------|-----------|
| Button Hijau (YA) | GPIO 23 |
| Button Merah (TIDAK) | GPIO 19 |

> **Note:** Kedua tombol terhubung ke **GND**, dan pin ESP32 di-set sebagai `INPUT_PULLUP`.

---

## 🧠 Library yang Digunakan

Pastikan kamu install library berikut via Library Manager di Arduino IDE:

- `Adafruit GFX Library`
- `Adafruit SH110X`
