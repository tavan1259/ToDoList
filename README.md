# ขั้นตอนการใช้งาน
แตกไฟล์ front-end-test.zip 

ตั้งโฟลเดอร์ front-end-test เป็นโฟล์เดอร์หลัก และทำการ Run frontend และ backend

## ขั้นตอนการ Run frontend เพื่อแสดงหน้าเว็บไซต์
เปิด terminal แล้วไปยังpath "\front-end-test" 

พิมพ์คำสั่งดังนี้

npm install

npm run dev

เมื่อเสร็จสิ้น เปิดเว็บไซต์แล้วไปที่ http://localhost:5173/ หากถูกต้องหน้าเว็บจะแสดง TodoList ที่ไม่มีข้อมูล task

## ขั้นตอนการ Run backend เพื่อเชือมกับฐานข้อมูล
เปิด terminal แล้วไปยัง path "\front-end-test\backend" 

พิมพ์คำสั่งดังนี้

npm install

node index.js

หากสำเร็จจะแสดงข้อความ Server is running on port 5000
