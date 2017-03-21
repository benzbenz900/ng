---

- Preview ไม่ได้เพิ่มลงไป เนื่องจากต้องแก้ระบบใหม่ค่อนข้างเยอะ และต้องเพิ่ม DB เพื่อเก็บ ข้อมูล Preview แยก หรือคือ ทำหน้าแบบเดี่ยวกันกับหน้าแสดงผล แต่งเก็บเป็นอีกไฟล์ไว้

---
#### ค้างทำ หลักๆ
	- เอาข้อมูลในหน้าตั้งค่า  title,title_en,description,description_en,keyword,keyword_en มาใส่หน้าเว็บ
	- ใน PPT สไลต์ 11-13 CMS ส่วนของ คณะผู้บริหาร

---

#### √ แก้เพิ่มแล้ว
#### ∆ ยังไม่ได้เพิ่ม
#### >> อัพเดจใหม่

---
- Home Banner àแยกอัพรูปกับข้อความต้องพิมพ์ข้อความและแก้ไข font size ได้ + มี Preview เพื่อดูว่าจะแสดงผลบหน้าเวบแบบไหนก่อนยืนยัน
- Banner หน้ารวมโครงการ àแยกอัพรูปกับข้อความต้องพิมพ์ข้อความและแก้ไข font size ได้ + มี Preview เพื่อดูว่าจะแสดงผลบหน้าเวบแบบไหนก่อนยืนยัน
- Banner โครงการàแยกอัพรูปกับข้อความต้องพิมพ์ข้อความและแก้ไข font size ได้ + มี Preview เพื่อดูว่าจะแสดงผลบนหน้าเวบแบบไหนก่อนยืนยัน

^ ตัวนี่เพิ่มจากหน้าเดี่ยวกัน "ภาพสไลต์"

	- ลบ รูปภาษาอังกฤษ ออก √
	- เพิ่ม ขนาดตัวอักษร √
	- css ข้อความบนรูป √
	- ตัวแยกแสดงในหน้าต่างๆ √ ดังนี้
		1. หน้า home √
		2. หน้ารวมโครงการ √
		3. หน้าโครงการ แยกโดย หมวดหมู่ √

---

- Home Banner àวน Loop 5 วิ และหากต้องการปรับspeed สามารถ set หลังบ้านได้เอง

^ เพิ่มตัวตั้งค่าในหน้า ตั้งค่าเว็บ √

	- ถูกเพิ่มในหน้าตั้งค่าเว็บ √ >>

---

- เพิ่ม DB ตั้งค่าเว็บ ในส่วนของ CMS เพื่อให้ลูกค้าแก้ไขข้อมูลได้เอง √
 
 		- title ชื่อเว็บไทย √
		- title_en ชื่อเว็บ ENG √
		- loop_banner ปรับ Speed Banner √
		- logo √
		- logo_en √
		- description รายละเอียดเว็บ √
		- description_en รายละเอียดเว็บ ENG √
		- keyword คำค้นหา √
		- keyword_en คำค้นหา ENG √
		- address ที่อยู่ √
		- address_en ที่ยู่ ENG √
		- map แผนที่ √
		- donated ข้อความบริจาคหน้าแรก √ >>
		- donated_en ข้อความบริจาคหน้าแรก ENG √ >>
		- tel_number เบอร์ติดต่อ √ >>
		- fax_number โทรสาร √ >>
		- about เกี่ยวกับ NG √ >>
		- about_en เกี่ยวกับ NG ENG √ >>

---

- แก้ Format  วันที่ TH เป็น เดือนย่อ พ.ศ. (ตัวอย่าง เช่น ก.ค. 2554)
- แก้ Format  EN เป็น เดือนย่อ ค.ศ. (ตัวอย่าง เช่น Jun 2015)

^ แก้ไขแล้ว √

	- เพิ่มเป็น function _date_(); และแยก เดือนแบบ ย่อเป็น ไทย อังกฤษ √

	- พ.ศ. เขียน +543 ไว้ใน function √

---
- ข่าวสารและกิจกรรมที่ผ่านมา ไม่แน่ใจว่ามีหลักในการดึงข้อมูลมาแสดงผลอย่างไรบ้างคะ? ตอนนี้ข้อมูลทั้งหมดซ้ำกับข่าวสารและกิจกรรมปัจจุบัน เท่ากับมีข้อมูลซ้ำสองที่ในหน้าเดียวค่ะ
- โครงการที่ผ่านมา ไม่แน่ใจว่ามีหลักในการดึงข้อมูลมาแสดงผลอย่างไรบ้างคะ? ตอนนี้ข้อมูลทั้งหมดซ้ำกับโครงการปัจจุบัน เท่ากับมีข้อมูลซ้ำสองที่ในหน้าเดียวค่ะ

^ แก้ไขแล้ว √ เปลี่ยนไปใช่ Ramdom แทน

	- หากต้องการให้แก้เงื่อนไขแสดงแบบอื่นสามารถอธิบายเพิ่มเติมเข้ามาได้ครับ √

---
- CMS คณะกรรมการมูลนิธิ à สามารถแก้ไขชื่อและตำแหน่งของคณะกรรมการ รวมถึงรูปประธานจากหลังบ้านได้

^ ต้องเพิ่ม DB ในหน้าตั้งค่า ∆

- แก้ไข CSS HTML คำต่างๆ ใน ppt เรียบร้อยแล้ว √ >>
	- คำภาษา ต่างๆ รวมถึง css ที่เพี้ยน √ >>

---

- ใน ppt ยังไม่ได้ทำ CMS สไลต์ 11-13 ∆

	- Foundation Board ∆
	- ยังไม่ได้เพิ่มในส่วนของ สไลต์ 11-13 ∆
---
- ส่วนของแกลเลอรี่จริงๆแล้วจะต้องมี template ให้เลือกได้จากหลังบ้าน กรณีจำนวนรูปของแต่ละโครงการมีมากน้อยไม่เท่ากัน โดยจะมีทั้ง 4 templates ด้วยกันตามด้านล่างค่ะ

^ แก้ไขแล้ว √

	- เพิ่มเท็มเพจ และ DB 2 ตัว สำหรับเช็คค่า เท็มเพจ √
	- เพิ่มตัวเลือก ว่าจะแสดงวิดีโอหรือแสดงรูปหรือแสดงทั้งคู่ √

---
