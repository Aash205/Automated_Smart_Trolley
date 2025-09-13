# 🛒 RFID-Based Smart Shopping & Billing System

An **innovative smart shopping cart** that uses **RFID technology** to automate product scanning and billing.
This system reduces checkout queues, improves shopping efficiency, and offers a **low-cost, scalable, and durable solution** for retail stores.

---

## 📷 System Preview

![Image](https://github.com/user-attachments/assets/f694308b-521b-49f5-bcee-34a7b4814046)

---

## ⚡ Components Used

* **Arduino Nano 33 BLE Sense**
* **RC522 RFID Reader + RFID Tags**
* **LCD 20×4 Display (I2C module)**
* **Buzzer**
* **Resistors & Jumper wires**

---

## 🔌 Pin Connections

### RC522 RFID Reader → Arduino Nano 33 BLE

| RC522 Pin | Arduino Pin |
| --------- | ----------- |
| VCC       | 3.3V        |
| RST       | 9           |
| GND       | GND         |
| MISO      | 12          |
| MOSI      | 11          |
| SCK       | 13          |
| SS        | 10          |

### LCD (I2C) → Arduino Nano 33 BLE

| LCD Pin | Arduino Pin |
| ------- | ----------- |
| VCC     | 5V          |
| GND     | GND         |
| SDA     | A4          |
| SCL     | A5          |

---

## 🛠️ Workflow

1️⃣ **Start system** → Initialize RFID, LCD, LEDs & Buzzer
2️⃣ **Scan item** → Display name & price on LCD, add to bill ✅
3️⃣ **Rescan same item** → Remove item, update bill ❌
4️⃣ **Unknown tag** → Show "Unknown Item" ⚠️
5️⃣ **Repeat process** until checkout

---

## 🚀 Features

* 📡 **RFID-based scanning** for contactless shopping
* 🧾 **Automated billing** with LCD feedback
* 🔊 **Buzzer + LED alerts** for actions & errors
* ⏱️ Real-time cart updates

---
