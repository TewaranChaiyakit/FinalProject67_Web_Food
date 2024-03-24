EasyFood
- โปรแกรมดึงข้อมูลจากฐานข้อมูล API จาก  www.themealdb.com สามารถแสดงข้อมูลจากฐานข้อมูล 
- Search meal by name, Lookup full meal details by id , List all meal categories , Lookup a single random meal และ Filter by Category
- สามารถค้นหาชื่ออาหารได้
- สามารถกด Bookmark ในเมนูชอบได้ สามารถเพิ่ม ลบ Bookmark ได้


# เทคโนโลยี และ Libraries ที่ใช้
-Navigation component: หนึ่งกิจกรรมประกอบด้วยหลาย Fragment แทนที่จะสร้างกิจกรรมหลายๆ ตัว
-Retrofit: การเชื่อมต่อ HTTP กับ REST API และแปลงไฟล์ JSON เมลเป็นอ็อบเจ็กต์ Kotlin/Java
-Room: บันทึกอาหารในฐานข้อมูลภายในเครื่อง
-MVVM & LiveData: แยกโค้ดตรรกะออกจากมุมมองและบันทึกสถานะในกรณีที่มีการเปลี่ยนแปลงการกำหนดหน้าจอ
-Coroutines: ดำเนินการโค้ดบางส่วนในพื้นหลัง
-View Binding: แทนที่การสร้างมุมมองด้วยการบินของมุมมองในที่นั้น
-Glide: จับภาพและโหลดภาพใน ImageView

## ตอนนำเสนอพูดสลับกันนะครับอาจารย์ ขออภัยด้วยครับ Glide ดึงภาพ Retrofit เอาAPI มาใช้ ขออภัยครับบบ



