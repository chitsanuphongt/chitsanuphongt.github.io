## Pulse Secure
Pulse Secure มาจากกลุ่มผลิตภัณฑ์ SSL VPN/NAC ของ Juniper ซึ่งในส่วนที่นำมาเสนอคือโปรแกรม Pulse Secure Client
![Mypic](PulseSecure/PulseSecure.jpg)

## Pulse Secure Client
เป็นโปรแกรมที่ใช้สำหรับการรีโมทไปที่ใดที่หนึงซึ่งได้ตั้งค่า VPN ให้สามารถใช้งานได้ โดย Authentication มีทั้ง
 * Username & Password
 * Multi-factor Authentication (MFA)
![Mypic](PulseSecure/PS0.jpg)
 
## Multi-factor Authentication (MFA)
มีขั้นตอนการใช้งานดังนี้
 * เปิดโปรแกรม Pulse secure client และ เพิ่มข้อมูลการเชื่อมต่อ เช่น Name, Server URL
![Mypic](PulseSecure/PS1.jpg) ![Mypic](PulseSecure/PS2.jpg)

 * กด Connect และใส่ข้อมูล Username & Password และ กด Connect อีกครั้ง
![Mypic](PulseSecure/PS3.jpg)![Mypic](PulseSecure/PS4.jpg)

 * กรอก Secondary Password ที่ได้จาก Token 
 
![Mypic](PulseSecure/PS5.jpg)

 * จะปรากฏข้อมูลการเชื่อมต่อสำเร็จดังรูป
 
![Mypic](PulseSecure/PS6.png)
