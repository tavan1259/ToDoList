# ขั้นตอนการใช้งาน
แตกไฟล์ front-end-test.zip 

ตั้งโฟลเดอร์ front-end-test เป็นโฟล์เดอร์หลัก และทำการ Run frontend และ backend

## ขั้นตอนการ Run frontend เพื่อแสดงหน้าเว็บไซต์
เปิด terminal แล้วไปยังpath "\front-end-test" 

พิมพ์คำสั่งดังนี้

npm install

npm run dev

เมื่อเสร็จสิ้น เปิดเว็บไซต์แล้วไปที่ http://localhost:5173/ หากถูกต้องหน้าเว็บจะแสดง TodoList ที่ไม่มีข้อมูล task

## ขั้นตอนการ Run backend เพื่อเชือมฐานข้อมูล
เปิด terminal แล้วไปยัง path "\front-end-test\backend" 

พิมพ์คำสั่งดังนี้

npm install

node index.js

หากสำเร็จจะแสดงข้อความ Server is running on port 5000

(หน้าเว็บที่ควรจะแสดงเมือ Run frontend และ backend)
![image](https://github.com/user-attachments/assets/61a8820a-f061-4d1b-a9ed-5b0ae78567c7)

# การใช้งาน
สร้าง task โดยกดไปที่ปุ่ม Add Task

![image](https://github.com/user-attachments/assets/36033416-ef60-4502-8f33-6dff22c805b4)

กรอกข้อมูลให้ครบ ทั้ง Title Description Due เมื่อกรอกเสร็จสิ้นกดปุ่ม AddTask เพื่อเพิ่มข้อมูล

![image](https://github.com/user-attachments/assets/34ab8531-62f3-4ab4-ba6a-934d518921e2)

เมื่อเสร็จสิ้นข้อมูลจะนำแสดงด้านล่างสุดของข้อมูล

![image](https://github.com/user-attachments/assets/4fc91158-f87f-4cac-a50e-0061120d469b)

หากต้องการแก้ไข้ข้อมูลที่สร้างไปแล้ว สามารถกดดินสอสีเขียวเพื่อเข้าไปแก้ไขได้

![image](https://github.com/user-attachments/assets/c25aca12-2b85-43c3-ab65-55c16dbad699)

กรอกข้อมูลแก้ไขเสร็จ กดปุ่ม Edit task เพื่อแก้ไขได้เลย

![image](https://github.com/user-attachments/assets/b2a74de5-cb54-438f-8a5c-9bf5f920c52a)

(ข้อมูลหลังถูกแก้ไข)

![image](https://github.com/user-attachments/assets/4febd1b9-f846-4319-8849-eae77b4af843)
