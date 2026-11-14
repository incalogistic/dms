# DMS — เว็บหลังบ้าน

เปิดใช้งาน: **https://incalogistic.github.io/dms/**

หน้านี้คือหน้าจอของระบบ DMS ที่วางบน GitHub Pages (ไม่มีแถบเตือนของ Google)
ข้อมูลทั้งหมดยังอยู่ใน Google Sheets ของบริษัท — หน้าเว็บส่งคำสั่งไปที่ Web App ของ DMS (`/exec`)
และทุกคำสั่งตรวจ User + PIN และสิทธิ์ตามปกติ

- สร้างไฟล์ `index.html` ใหม่ทุกครั้งที่อัปเดต DMS: `python3 build_static.py <ลิงก์ /exec> index.html`
- ลิงก์เดิมของ Apps Script ยังใช้ได้เหมือนเดิม (สำรอง)
- แอปพนักงานขาย: https://incalogistic.github.io/sales-app/
