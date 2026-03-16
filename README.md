# 🧊 Refrigeration Master

เกมเรียนรู้ระบบทำความเย็นแบบมืออาชีพ สำหรับนักเรียน/นักศึกษาสาขาช่างแอร์และระบบทำความเย็น

## ✨ Features

- 🔐 ระบบลงทะเบียน/เข้าสู่ระบบด้วยเบอร์โทรศัพท์
- 🎮 เกมถาม-ตอบแบบมีจับเวลา
- 🏆 Leaderboard คะแนนสูงสุด 50 อันดับ
- 🔥 ระบบ Streak Combo เพิ่มคะแนน
- 👑 ยศ/ตำแหน่ง ตามคะแนนสะสม
- 📊 ติดตามความคืบหน้าแต่ละด่าน
- 👨‍💼 Admin Panel จัดการด่านและคำถาม

## 🛠️ Tech Stack

- HTML / CSS (Tailwind CDN)
- JavaScript (Vanilla)
- Firebase Firestore (Database)
- Firebase Auth (Anonymous)
- Font Awesome Icons
- Canvas Confetti

## 🚀 Deploy

เว็บไซต์นี้ Deploy บน [Vercel](https://vercel.com)

## 📋 การใช้งาน Admin

1. กดปุ่ม "ผู้ดูแลระบบ" ที่หน้า Login
2. ใส่รหัส Admin passcode
3. สร้างด่านและนำเข้าคำถามผ่าน CSV

## 📄 รูปแบบ CSV สำหรับนำเข้าคำถาม

```
คำถาม, คำตอบถูก, ตัวหลอก1, ตัวหลอก2, ตัวหลอก3
สารทำความเย็น R22 เป็นประเภทใด?, HCFC, HFC, CFC, HC
```
