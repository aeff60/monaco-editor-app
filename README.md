## monaco-editor-app

**โปรเจคต์นี้สร้างเว็บแอปพลิเคชั่นง่ายๆ โดยใช้ Monaco Editor ([https://github.com/microsoft/monaco-editor](https://github.com/microsoft/monaco-editor)) ที่ทรงพลังสำหรับการเขียนและรันโค้ด**

**เริ่มต้นใช้งาน**

1. **สิ่งที่ต้องมี:**
   - ติดตั้ง Node.js และ npm (หรือ yarn) บนระบบของคุณ ตรวจสอบได้โดยรัน `node -v` และ `npm -v` (หรือ `yarn -v`) ในเทอร์มินัลของคุณ หากยังไม่ได้ติดตั้ง ดาวน์โหลดจากเว็บไซต์ Node.js อย่างเป็นทางการ ([https://nodejs.org/en/download/package-manager](https://nodejs.org/en/download/package-manager))
2. **โคลนโค้ด:**
   ```bash
   git clone https://github.com/your-username/monaco-editor-app.git
   cd monaco-editor-app
   ```
3. **ติดตั้ง Dependencies:**
   ````bash
   npm install
   ``` (หรือ `yarn install`)
   ````
4. **รันแอปพลิเคชั่น:**
   ````bash
   npm start
   ``` (หรือ `yarn start`)
   ````

แอปพลิเคชั่นจะรันบนเซิร์ฟเวอร์พัฒนาและเปิดในเว็บเบราว์เซอร์ของคุณที่ `http://localhost:3000`

**ฟีเจอร์**

- เขียนโค้ดพร้อมไฮไลท์ไวยากรณ์และฟีเจอร์อื่นๆ จาก Monaco editor สำหรับภาษาโปรแกรมต่างๆ
- ปุ่ม "Run" เพื่อรันโค้ดที่เขียนใน editor
- พื้นที่แสดงผลลัพธ์เพื่อแสดงผลลัพธ์ของการรันโค้ด รวมถึง `console.log` ที่ดักจับไว้

**โครงสร้างโปรเจคต์**

```
monaco-editor-app/
├── package.json  # Dependencies และสคริปต์ของโปรเจคต์
├── public/
│   ├── index.html # ไฟล์ HTML หลักสำหรับแอปพลิเคชั่น
│   └── ...         # ไฟล์สแตติกอื่นๆ (ไม่จำเป็น)
└── server.js      # โค้ดเซิร์ฟเวอร์ Node.js
```
