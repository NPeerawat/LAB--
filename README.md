# แบบรายงานผลการทดลอง 
# เรื่อง Transmission Line Filter Design 
sec 11 <br/>
กลุ่ม กลุ่มสาม
### จัดทำโดย
ธนดล    เนตรรัตนา    6410500751 <br/>
พีรวัส    แฉ่งชัยศรี     6410502231 <br/>
โยษิตา   ถิ่นจันทร์ฉาย  6410502273 <br/>
นพรุจ    พีรเพ็ญโภคัย  6410552076 <br/>

### เสนอ 
ผศ.ดร.เด่นชัย วรเศวต <br/>
รายงานนี้เป็นส่วนหนึ่งของรายวิชา ปฏิบัติการสถาปัตยกรรมและอุปกรณ์สื่อสาร <br/>
รหัสวิชา 01205381 ภาควิชาวิศวกรรมไฟฟ้า คณะวิศวกรรมศาสตร์ มหาวิทยาลัยเกษตรศาสตร์ ปีการศึกษา 2566 <br/>

## การทดลอง
นำค่า Electrical Length, Impedance และ Frequency ที่ได้จากการคำนวณบน excel ไปสร้างเป็นชิ้นงานในโปรแกรม sonnet โดยการหาขนาดจาก TXLine <br/>
![image](https://github.com/hidekkk/LabArchitect/assets/165928440/d3a191b2-45c8-44f2-89a0-ee8508a2b1a4)
![image](https://github.com/hidekkk/LabArchitect/assets/165928440/a9bb249e-91e8-42b2-ac97-4ad0d2420b30)

### ทำให้ได้กราฟออกมาดังนี้ 
- กราฟ port1 to port1

![s11](https://github.com/NPeerawat/LAB--/assets/164756138/88210bdf-fa7d-4c3b-94ad-51e9b8514cdb)

- กราฟ port1 to port2

![s12](https://github.com/NPeerawat/LAB--/assets/164756138/3d28b2a6-34db-4238-bfa6-4c9b6c69d4fb)


เมื่อได้รูปกราฟออกมาตามที่ต้องการ จึงนำชิ้นงานที่วาดได้ผ่านsonnet ไปวาดลงEasyEDA เพื่อนำไปสั่งทำเป็นผลงานจริง 

![image]


ภาพการสั่งทำชิ้นงาน

<img width="1440" alt="ภาพถ่ายหน้าจอ 2567-03-01 เวลา 19 43 21" src="https://github.com/NPeerawat/LAB--/assets/164756138/131609b3-c525-4779-922b-4b65ee591bf0">



นำชิ้นงานของจริงที่ได้ไปวัดค่าจริง โดยอ่านค่าผ่านโปรแกรม Putty แล้วนำไปพล้อตกราฟ<br/>

ค่าจริงที่ได้มีดังนี้

port1 to port1 <br/>

![image](https://github.com/hidekkk/LabArchitect/assets/165928440/166e1928-127d-4f79-a2c2-46d43fe01e5b) <br/>
![image](https://github.com/hidekkk/LabArchitect/assets/165928440/6c6af385-52c2-413a-a272-0816e53b70bd) <br/>

เปรียบเทียบกราฟที่ได้จากชิ้นงานจริง และ sonnet

![image](https://github.com/hidekkk/LabArchitect/assets/165928440/1f7d323d-a05d-409d-a7c7-057d15a9ec4f)

port1 to port2 <br/>

![image](https://github.com/hidekkk/LabArchitect/assets/165928440/92233a5b-b110-4438-a5b6-7989a2610fe9) <br/>
![image](https://github.com/hidekkk/LabArchitect/assets/165928440/0b44d87d-277b-4f42-8c98-305e5aa411e2) <br/>

เปรียบเทียบกราฟที่ได้จากชิ้นงานจริง และ sonnet

![image](https://github.com/hidekkk/LabArchitect/assets/165928440/e2134823-e66f-4b4f-af20-d0ab911cf340)


## สรุปผลการทดลอง
