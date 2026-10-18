# NE1 อีสานทีม — Team Portal

เว็บไซต์รวมลิงก์ทำงานของทีม NE1 อีสานทีม ออกแบบให้รองรับมือถือและคอมพิวเตอร์

## ไฟล์ในโปรเจกต์
- `index.html` — เว็บไซต์ทั้งหมด (HTML, CSS และ JavaScript อยู่ในไฟล์เดียว)
- `.nojekyll` — ป้องกัน GitHub Pages ประมวลผลไฟล์ผ่าน Jekyll
- `README.md` — คู่มือการเผยแพร่เว็บไซต์

## วิธีเผยแพร่ด้วย GitHub Pages
1. สร้าง repository ใหม่บน https://github.com/new
2. ตั้งชื่อ repository เช่น `ne1-isan-team`
3. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ไปที่ root ของ repository
4. เปิด **Settings → Pages**
5. ใน **Build and deployment** เลือก **Deploy from a branch**
6. เลือก branch `main` และ folder `/(root)` แล้วกด **Save**
7. รอ GitHub Pages เผยแพร่ แล้วเปิด URL ที่ GitHub แสดงในหน้า Pages

## หมายเหตุ
- เว็บไซต์นี้เป็นแบบ static ไม่มีระบบ backend หรือหน้า Admin
- ลิงก์ภายนอกจะเปิดแท็บใหม่ และผู้ใช้ต้องมีสิทธิ์เข้าถึงไฟล์/บริการปลายทาง
- รายการเช็กลิสต์เป็นช่องติ๊กบนหน้าเว็บ ไม่ได้บันทึกสถานะถาวรเมื่อปิดหรือรีเฟรชหน้า
- ก่อนแชร์ให้ทีม โปรดทดสอบลิงก์และตรวจสอบสิทธิ์ของ Google Drive/Sheets ตามนโยบายองค์กร
