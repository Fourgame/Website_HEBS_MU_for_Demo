# 🏥 Health Education Mahidol University (Demo)

เว็บไซต์ Demo (**Refined UX/UI Concept**) สำหรับ ภาควิชาสุขศึกษาและพฤติกรรมศาสตร์ คณะสาธารณสุขศาสตร์ มหาวิทยาลัยมหิดล มุ่งเน้นการยกระดับการเข้าถึงข้อมูลหลักสูตรและงานวิจัยด้วยดีไซน์ที่ทันสมัย

---

## 🚀 Quick Access
* **🌍 Live Demo:** [View Website](https://fourgame.github.io/website_Health_Education_MU)
* **🏫 Official Site:** [Department of Health Education](https://phhe.ph.mahidol.ac.th)

---

## 🔥 Key Features
* **⚡ Modern Navigation:** ระบบเมนูที่ลื่นไหล เข้าถึงหน้าหลัก, บุคลากร และข่าวสารได้อย่างรวดเร็ว
* **📚 Academic Hub:** เจาะลึกข้อมูลหลักสูตรระดับบัณฑิตศึกษา (Master's & PhD) พร้อมลิงก์ตรงสู่ระบบรับสมัคร
* **📢 News Feed:** อัปเดตข่าวประชาสัมพันธ์ กิจกรรม และประกาศสำคัญแบบ Real-time (Static Demo)
* **📱 Ultra-Responsive:** ปรับแต่งการแสดงผลให้สมบูรณ์แบบทั้งบน PC, Tablet และ Smartphone
* **🤝 Ecosystem Partnering:** แสดงเครือข่ายความร่วมมือระดับประเทศ (สสส., กองสุขศึกษา, ASH)

---

## 📂 Project Architecture
```bash
WEBSITE_HEALTH_EDUCATION_MU/
├── 📁 .vscode/               # VS Code configuration files
├── 📁 assets/                 # ทรัพยากรหลักของเว็บไซต์
│   ├── 📁 CV/                # เอกสารประวัติบุคลากร
│   ├── 📁 images/            # รูปภาพประกอบทั่วไป
│   ├── 📁 news/              # รูปภาพสำหรับข่าวสาร
│   ├── 📁 stand_model/       # รูปภาพโมเดลกราฟิก/ตัวการ์ตูน
│   ├── 📄 banner1.jpg        # ภาพแบนเนอร์หลัก
│   ├── 📄 Mahidol_Logo.png   # โลโก้มหาวิทยาลัยมหิดล
│   └── 📄 video_web.mp4      # วิดีโอพื้นหลังหรือวิดีโอแนะนำ
├── 📁 tools/                  # เครื่องมืออัตโนมัติ (Python & Automation)
│   ├── 📄 news_editor_gui.py  # โปรแกรมจัดการข่าว (Python GUI)
│   ├── 📄 update_news.py      # สคริปต์สำหรับอัปเดตข้อมูลข่าว
│   └── 📄 *.exe               # ไฟล์โปรแกรมสำเร็จรูปสำหรับจัดการ Staff/News/Service
├── 📄 index.html              # หน้าแรก (Landing Page)
├── 📄 about.html              # ข้อมูลภาควิชาและประวัติ
├── 📄 staff.html              # รายชื่อและข้อมูลบุคลากร
├── 📄 news.html               # ศูนย์รวมข่าวประชาสัมพันธ์
├── 📄 Services.html           # ข่าวสารบริการวิชาการ
├── 📄 contact.html            # ข้อมูลการติดต่อและแผนที่
├── 📄 profile.html            # หน้าแสดงรายละเอียดโปรไฟล์รายบุคคล
├── 📁 *.json                  # ไฟล์ฐานข้อมูล (Data Storage) สำหรับ News, Staff, Services
└── 📄 README.md               # เอกสารแนะนำโปรเจกต์