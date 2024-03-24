EasyFood
- โปรแกรมดึงข้อมูลจากฐานข้อมูล API จาก  www.themealdb.com สามารถแสดงข้อมูลจากฐานข้อมูล 
- Search meal by name, Lookup full meal details by id , List all meal categories , Lookup a single random meal และ Filter by Category
- สามารถค้นหาชื่ออาหารได้
- สามารถกด Bookmark ในเมนูชอบได้ สามารถเพิ่ม ลบ Bookmark ได้


# เทคโนโลยี และ Libraries ที่ใช้
(1.)Navigation component: หนึ่งกิจกรรมประกอบด้วยหลาย Fragment แทนที่จะสร้างกิจกรรมหลายๆ ตัว
(2.)Retrofit: การเชื่อมต่อ HTTP กับ REST API และแปลงไฟล์ JSON เมลเป็นอ็อบเจ็กต์ Kotlin/Java
(3.)Room: บันทึกอาหารในฐานข้อมูลภายในเครื่อง
(4.)MVVM & LiveData: แยกโค้ดตรรกะออกจากมุมมองและบันทึกสถานะในกรณีที่มีการเปลี่ยนแปลงการกำหนดหน้าจอ
(5.)Coroutines: ดำเนินการโค้ดบางส่วนในพื้นหลัง
(6.)View Binding: แทนที่การสร้างมุมมองด้วยการบินของมุมมองในที่นั้น
(7.)Glide: จับภาพและโหลดภาพใน ImageView

## ตอนนำเสนอพูดสลับกันนะครับอาจารย์ ขออภัยด้วยครับ Glide ดึงภาพ Retrofit เอาAPI มาใช้ ขออภัยครับบบ
