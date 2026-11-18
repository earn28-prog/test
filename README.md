# หน้าเว็บกลุ่มควบคุมป้องกันโรคโค

หน้าเว็บแบบ static (HTML ล้วน) ดึงเนื้อหาจาก Google Sheets

## ไฟล์
- `index.html` หน้าเว็บ
- `config.js` ใส่รหัส Google Sheet ที่ `window.SHEET_ID`
- `data.js` ข้อมูลสำรอง ใช้เมื่อโหลดจากชีตไม่ได้หรือยังไม่ตั้ง `SHEET_ID`
- `images/` รูปการ์ดและปุ่มลัด (เช่น `images/vaccine.jpg`, `images/<id>.jpg`)

## เผยแพร่ด้วย GitHub Pages
Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save

## แก้เนื้อหา
แก้ใน Google Sheets ได้เลย ไม่ต้องแก้โค้ด (ชีตต้องแชร์แบบ "ทุกคนที่มีลิงก์ เป็นผู้ดู")
