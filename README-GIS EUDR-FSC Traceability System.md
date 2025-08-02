# GIS EUDR/FSC Traceability System  
**ระบบติดตามย้อนกลับผลิตภัณฑ์ป่าไม้ตามข้อกำหนด FSC และ EUDR**

This system is designed to help track and verify the traceability of forest products in compliance with the Forest Stewardship Council (FSC) and the European Union Deforestation Regulation (EUDR). It allows stakeholders to trace the origin and journey of products through their entire supply chain, ensuring sustainability and legal compliance.  
**ระบบนี้ถูกออกแบบมาเพื่อช่วยติดตามและตรวจสอบย้อนกลับผลิตภัณฑ์ป่าไม้ให้เป็นไปตามข้อกำหนดของ Forest Stewardship Council (FSC) และระเบียบควบคุมการตัดไม้ของสหภาพยุโรป (EUDR) โดยผู้มีส่วนเกี่ยวข้องสามารถตรวจสอบต้นทางและเส้นทางของผลิตภัณฑ์ตลอดทั้งห่วงโซ่อุปทาน เพื่อความยั่งยืนและการปฏิบัติตามกฎหมาย**

## 📑 Ex ภาพตัวอย่างระบบที่ใช้การจัดการ วิเคราะห์ และแสดงผลข้อมูลเชิงพื้นที่
<img width="1883" height="776" alt="baasemap_GIS" src="https://github.com/user-attachments/assets/383a462d-25b8-48cc-8203-fbe133235d2e" />
<img width="1577" height="781" alt="baasemap_GIS2" src="https://github.com/user-attachments/assets/84e6b4f6-b55e-4f74-8512-78408cda215c" />
<img width="1834" height="778" alt="baasemap_GIS5" src="https://github.com/user-attachments/assets/2d41c5a7-8c74-4e0d-a274-6c847f04ff14" />


---

## 📑 Table of Contents  
- [Overview / ภาพรวม](#overview--ภาพรวม)  
- [Features / คุณสมบัติ](#features--คุณสมบัติ)  
- [Technologies / เทคโนโลยีที่ใช้](#technologies--เทคโนโลยีที่ใช้)

---

## Overview / **ภาพรวม**  
The **GIS EUDR/FSC Traceability System** is a geospatial platform that integrates data related to the FSC certification and EUDR requirements.  
**ระบบ GIS EUDR/FSC Traceability เป็นแพลตฟอร์มภูมิสารสนเทศที่รวบรวมข้อมูลที่เกี่ยวข้องกับการรับรอง FSC และข้อกำหนดของ EUDR**

This system facilitates the monitoring of deforestation-related activities by tracking forest product origins and their transportation paths from forests to end users.  
**ระบบนี้ช่วยในการติดตามกิจกรรมที่เกี่ยวข้องกับการตัดไม้ โดยตรวจสอบต้นทางของผลิตภัณฑ์จากป่าไม้ไปจนถึงผู้ใช้งานปลายทาง**

The system allows for:  
- Monitoring FSC-certified products  
  **ตรวจสอบผลิตภัณฑ์ที่ได้รับการรับรองจาก FSC**  
- Ensuring compliance with the EUDR  
  **รับรองความสอดคล้องกับข้อกำหนดของ EUDR**  
- Providing a transparent, traceable process for forest products  
  **สร้างกระบวนการที่โปร่งใสและสามารถตรวจสอบย้อนกลับได้ของผลิตภัณฑ์ป่าไม้**  
- **New Feature**: Checking and visualizing **Conservation Forests** and **National Parks**  
  **ฟีเจอร์ใหม่**: ตรวจสอบและแสดงผล **ป่าสงวน** และ **อุทยานแห่งชาติ**  
- **New Feature**: Generating **GEOJSON** files in compliance with **EUDR** format for tracking deforestation  
  **ฟีเจอร์ใหม่**: สร้างไฟล์ **GEOJSON** ตามรูปแบบของ EUDR เพื่อใช้ติดตามการตัดไม้ทำลายป่า  
- **New Feature**: **Managing Project Members** with a database for member tracking  
  **ฟีเจอร์ใหม่**: **จัดการสมาชิกในโครงการ** ด้วยระบบฐานข้อมูล  
- **New Feature**: **Generating Project Reports** including compliance status and audit trails  
  **ฟีเจอร์ใหม่**: **สร้างรายงานโครงการ** รวมถึงสถานะการปฏิบัติตามข้อกำหนดและประวัติการตรวจสอบ

  

<img width="333" height="997" alt="baasemap_GIS6" src="https://github.com/user-attachments/assets/a44d3738-a4c8-4791-a526-bea4c5e941c2" />
<img width="1917" height="787" alt="baasemap_GIS7" src="https://github.com/user-attachments/assets/f6947ecd-340b-4de3-8275-0ff10cfb809d" />
---

## Features / **คุณสมบัติ**

- **GIS Integration**  
  Visualize the supply chain in a geographic context using maps and spatial data.  
  **การเชื่อมต่อกับ GIS**: แสดงภาพห่วงโซ่อุปทานในบริบทเชิงพื้นที่ด้วยแผนที่และข้อมูลภูมิสารสนเทศ  

- **EUDR Compliance**  
  Ensure compliance with the European Union's deforestation regulation.  
  **สอดคล้องกับข้อกำหนด EUDR**: ตรวจสอบว่าการดำเนินงานเป็นไปตามข้อกำหนดของสหภาพยุโรปเกี่ยวกับการตัดไม้  

- **FSC Certification Tracking**  
  Verify that the products are certified by the Forest Stewardship Council.  
  **ติดตามการรับรอง FSC**: ตรวจสอบว่าผลิตภัณฑ์มีการรับรองจาก FSC  

- **Real-time Data**  
  Continuous tracking of forest products from origin to market.  
  **ข้อมูลแบบเรียลไทม์**: ติดตามผลิตภัณฑ์จากต้นทางจนถึงตลาดอย่างต่อเนื่อง  

- **Traceability Reports**  
  Generate detailed reports for auditing purposes.  
  **รายงานการติดตามย้อนกลับ**: สร้างรายงานละเอียดเพื่อใช้ในการตรวจสอบ  

- **Conservation and National Park Verification**  
  Check areas designated as **Conservation Forests** and **National Parks** to ensure compliance.  
  **การตรวจสอบพื้นที่อนุรักษ์และอุทยานแห่งชาติ**: ตรวจสอบว่าต้นทางอยู่ในพื้นที่อนุรักษ์หรือไม่  

- **GEOJSON Export**  
  Generate **GEOJSON** files based on EUDR for spatial tracking.  
  **ส่งออก GEOJSON**: สร้างไฟล์ GEOJSON ตามข้อกำหนดของ EUDR สำหรับติดตามทางภูมิศาสตร์  

- **Project Member Management**  
  Maintain a database of member information, roles, and history.  
  **การจัดการสมาชิกในโครงการ**: จัดเก็บข้อมูลสมาชิก บทบาท และประวัติการมีส่วนร่วม  

- **Project Report Generation**  
  Export reports summarizing compliance, project activities, and audit trails.  
  **การสร้างรายงานโครงการ**: สรุปกิจกรรมโครงการ ความสอดคล้อง และประวัติการตรวจสอบ
<img width="1859" height="783" alt="baasemap_GIS3" src="https://github.com/user-attachments/assets/59abab50-f478-445e-8bc4-99226ca4f55b" />
<img width="1870" height="783" alt="baasemap_GIS4" src="https://github.com/user-attachments/assets/038c8966-de4a-4d71-ae35-b4c0b80d60de" />
<img width="1917" height="787" alt="Image" src="https://github.com/user-attachments/assets/d71742b7-0f68-47db-a507-07459eca8d89" />
<img width="333" height="997" alt="Image" src="https://github.com/user-attachments/assets/8c6573bb-d5ac-4b93-88fb-5e6fe03528e9" />
---

## Technologies / **เทคโนโลยีที่ใช้**

### Frontend / **ส่วนแสดงผล**
- **Vue.js Framework**  
  A JavaScript framework for building reactive interfaces.  
  **เฟรมเวิร์ก Vue.js**: ใช้สร้างอินเทอร์เฟซผู้ใช้ที่ตอบสนองแบบเรียลไทม์  

- **Leaflet**  
  Library for interactive maps and geospatial visualization.  
  **Leaflet**: ไลบรารีสำหรับแผนที่โต้ตอบและการแสดงผลข้อมูลภูมิสารสนเทศ  

- **Proj4**  
  Used for transforming coordinate systems.  
  **Proj4**: ไลบรารีสำหรับแปลงระบบพิกัดและโปรเจกชันแผนที่  

### Backend / **ส่วนประมวลผล**
- **PHP**  
  Handles API requests and business logic.  
  **PHP**: จัดการคำร้อง API และตรรกะระบบ  

- **MSSQL Server**  
  Stores product, member, and spatial data securely.  
  **MSSQL Server**: ฐานข้อมูลสำหรับเก็บข้อมูลผลิตภัณฑ์ สมาชิก และข้อมูลแผนที่  

### Authentication / **การรับรองตัวตน**
- **JWT (JSON Web Token)**  
  Secures frontend-backend communication.  
  **JWT**: ระบบรับรองความปลอดภัยในการเข้าถึงข้อมูลระหว่างผู้ใช้และเซิร์ฟเวอร์  
