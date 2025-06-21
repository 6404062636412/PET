# 🐾 PET-Detect-SeniorProject – Git Workflow Guide

---

## 🔄 Clone โปรเจกต์จาก GitHub

```bash
git clone https://github.com/opal-Pachara/PET-Detect-SeniorProject
```

คำอธิบาย:  
ใช้เพื่อคัดลอก (clone) โปรเจกต์จาก GitHub มายังเครื่องของเรา เป็นขั้นตอนแรกสุดในการเริ่มใช้งานโปรเจกต์นี้

---

## 🔀 เปลี่ยน Branch

```bash
git checkout [ชื่อ branch]
```

คำอธิบาย:  
ใช้เพื่อย้ายไปยัง branch ที่ต้องการ เช่น `git checkout dev` เพื่อทำงานใน dev

---

## 🌱 สร้าง Branch ใหม่และสลับไปใช้งานทันที

```bash
git checkout -b [ชื่อ branch ใหม่]
```

คำอธิบาย:  
ใช้เพื่อสร้าง branch ใหม่ เช่น `git checkout -b feature-detect-model` จะสร้าง branch ชื่อ `feature-detect-model` และย้ายไปยัง branch นั้นทันที

---

## ✏️ เพิ่มไฟล์ที่มีการเปลี่ยนแปลง

### เพิ่มไฟล์ทั้งหมด

```bash
git add .
```

### เพิ่มเฉพาะไฟล์

```bash
git add [ชื่อไฟล์ เช่น main.py]
```

คำอธิบาย:  
ใช้เพื่อเพิ่มไฟล์หรือโค้ดที่มีการเปลี่ยนแปลงเข้าสู่ staging area ก่อนที่จะทำการ commit

---

## 🗒️ Commit โค้ดพร้อมคำอธิบาย

```bash
git commit -m "เขียนสิ่งที่แก้ไขหรือเพิ่มเข้าไป"
```

ตัวอย่าง:
```bash
git commit -m "เพิ่มฟีเจอร์ตรวจจับสุนัขและแมวจากภาพ"
```

คำอธิบาย:  
ใช้สำหรับอธิบายว่าเราได้ทำการเปลี่ยนแปลงอะไรในโค้ด เช่น เพิ่มฟีเจอร์, แก้บั๊ก, ปรับปรุง UI ฯลฯ

---

## 🚀 ส่งโค้ดขึ้น GitHub ไปยัง Branch ที่กำลังทำงานอยู่

```bash
git push origin [ชื่อ branch]
```

ตัวอย่าง:
```bash
git push origin feature-detect-model
```

คำอธิบาย:  
ใช้สำหรับส่งโค้ดจากเครื่องเราขึ้น GitHub ใน branch ที่เรากำลังทำงานอยู่

---

## ✅ สรุปลำดับขั้นตอนที่ใช้บ่อย

```bash
# 1. Clone โปรเจกต์ (ทำครั้งแรกเท่านั้น)
git clone https://github.com/opal-Pachara/PET-Detect-SeniorProject
cd PET-Detect-SeniorProject

# 2. สร้าง branch ใหม่เพื่อทำงาน
git checkout -b feature-name

# 3. ทำการแก้ไขไฟล์ในโปรเจกต์

# 4. Add และ Commit
git add .
git commit -m "รายละเอียดการแก้ไข"

# 5. Push ขึ้น GitHub
git push origin feature-name
```

---

## 💡 หมายเหตุเพิ่มเติม

- อย่าลืม `pull` หรือ `merge` กับ branch หลักก่อนที่จะ `push` หรือ `merge` เพื่อป้องกัน conflict
- ตั้งชื่อ branch ให้สื่อความหมาย เช่น `fix-login-bug`, `feature-detect-model`

---

จัดทำโดย: ทีม PET-Detect  
โครงการปี: 2024 ~ 2025
