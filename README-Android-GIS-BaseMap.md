# Android-GIS-BaseMap

## A short description  
An Android application that lets you capture geographic coordinates as polygons, manage data in GeoJSON format, and display them seamlessly on maps, both online and offline.

## คำอธิบายสั้นๆ  
แอปพลิเคชัน Android ที่ช่วยให้คุณสามารถเก็บพิกัดทางภูมิศาสตร์ในรูปแบบ Polygon, จัดการข้อมูลในฟอร์แมต GeoJSON, และแสดงผลบนแผนที่ทั้งแบบออนไลน์และออฟไลน์ได้อย่างราบรื่น
<img width="720" height="1080" alt="Image" src="https://github.com/user-attachments/assets/7f48caaa-b42c-4e30-be8f-7d3ef147e2b8" />
<img width="720" height="1080" alt="Image" src="https://github.com/user-attachments/assets/d3126de1-4fa9-48dc-92f7-72211fe81319" />
<img width="720" height="1080" alt="Image" src="https://github.com/user-attachments/assets/7c35e2c3-2223-4c17-8042-b4f4da0ac7bf" />
---

## 📑 Table of Contents
- [About the Application / เกี่ยวกับแอปพลิเคชัน](#about-the-application--เกี่ยวกับแอปพลิเคชัน)
- [Key Features / คุณสมบัติหลัก](#key-features--คุณสมบัติหลัก)
- [Technologies Used / เทคโนโลยีที่ใช้](#technologies-used--เทคโนโลยีที่ใช้)
- [Installation / การติดตั้ง](#installation--การติดตั้ง)
- [How to Use / วิธีการใช้งาน](#how-to-use--วิธีการใช้งาน)
- [Offline Map Setup / การตั้งค่าแผนที่ออฟไลน์](#offline-map-setup--การตั้งค่าแผนที่ออฟไลน์)
- [Contact / ติดต่อ](#contact--ติดต่อ)

---

## 📌 About the Application / เกี่ยวกับแอปพลิเคชัน  
**Android-GIS-BaseMap** is designed to meet spatial data management needs, specifically for creating and saving Polygon (area) data into GeoJSON files and rendering that data flexibly on maps, whether or not an internet connection is available.  
It's ideal for field surveys, asset management, or any project requiring portable map data management.

**Android-GIS-BaseMap** ถูกออกแบบมาเพื่อตอบสนองความต้องการในการจัดการข้อมูลเชิงพื้นที่ โดยเฉพาะอย่างยิ่งการสร้างและบันทึกข้อมูล Polygon (พื้นที่) ลงในไฟล์ GeoJSON และนำเสนอข้อมูลเหล่านั้นบนแผนที่ได้อย่างยืดหยุ่น ไม่ว่าจะเป็นการเชื่อมต่ออินเทอร์เน็ตหรือไม่ก็ตาม เหมาะสำหรับงานสำรวจภาคสนาม การจัดการสินทรัพย์ หรือโครงการที่ต้องการการจัดการข้อมูลแผนที่แบบพกพา

---

## ✨ Key Features / คุณสมบัติหลัก
- **Polygon Coordinate Capture**  
  Users can easily tap on the map to add coordinate points and create polygon shapes. Existing polygon points can be edited, added, or deleted.  
  **การเก็บพิกัด Polygon**: แตะบนแผนที่เพื่อเพิ่มจุดพิกัดและสร้างรูปทรง Polygon แก้ไข เพิ่ม หรือลบจุดได้

- **GeoJSON Data Management**  
  Saves polygon data in GeoJSON format. Can load and display existing GeoJSON from internal/external storage.  
  **การจัดการข้อมูล GeoJSON**: บันทึกและโหลด GeoJSON ได้จากหน่วยความจำในเครื่องหรือภายนอก

- **Map Display (Online/Offline)**  
  Uses OSMBonusPack to support OpenStreetMap and offline map tiles (.mbtiles).  
  **การแสดงแผนที่ (ออนไลน์/ออฟไลน์)**: รองรับแผนที่ออนไลน์และออฟไลน์ผ่านไฟล์ .mbtiles

- **Map Zoom and Pan**  
  Pinch-to-zoom and drag-to-pan gestures are supported.  
  **ซูมและแพนแผนที่**: รองรับท่าทาง pinch และ drag เพื่อควบคุมแผนที่

- **Display Current Location**  
  Shows the user’s location with proper permission.  
  **แสดงตำแหน่งปัจจุบัน**: แสดงตำแหน่งผู้ใช้บนแผนที่ (เมื่อได้รับสิทธิ์)

---

## 🛠 Technologies Used / เทคโนโลยีที่ใช้
| Technology             | Description (EN/TH)                                                                 |
|------------------------|-------------------------------------------------------------------------------------|
| Java                   | Programming language / ภาษาโปรแกรม                                                 |
| Android SDK            | Android application development toolkit / เครื่องมือพัฒนาแอปบน Android            |
| OSMBonusPack           | Library for OpenStreetMap with extra features / ไลบรารีสำหรับการจัดการแผนที่     |
| GeoJSON                | Format for geographic data / ฟอร์แมตข้อมูลเชิงพื้นที่มาตรฐาน                    |
| AndroidX Libraries     | Modern Android libraries for compatibility / ไลบรารีสำหรับการใช้งานร่วมสมัย      |
