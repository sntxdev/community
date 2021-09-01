
> วันนี้เราขอแนะนำ deployment slots ซึ่งเป็นคุณสมบัติใหม่ที่จะปรับปรุงประสบการณ์ของนักพัฒนาในบริการโฮสต์ของ SubQuery

[โปรเจกต์ SubQuery](https://project.subquery.network/) ถูกใช้เป็นบริการโฮสต์และการบริหารจัดการสำหรับโปรเจกต์ต่างๆ มากมาย ไม่ว่าจะเป็น chain explorer, wallet, NFT explorer หรืออื่นๆ ซึ่งเป็นบริการที่ลูกค้าของเราไว้วางใจ

![](https://miro.medium.com/max/1400/0*PugDgh6weZspRIO2)

ตอนนี้คุณสามารถปรับใช้กับ staging slot ที่แยกออกมาได้แล้ว

แม้ว่าคุณจะสามารถเรียกใช้โครงสร้างพื้นฐานของ SubQuery ได้เองเสมอ (ด้วยโหนดและบริการ query ข้อมูลของคุณเอง) เราก็ยังมุ่งหวังที่จะทำให้บริการโฮสต์ของเราเป็นผู้ให้บริการข้อมูลที่เชื่อถือได้, ยืดหยุ่น, และมีประสิทธิภาพมากที่สุดในระบบนิเวศ Polkadot/Substrate

ผู้สร้าง [SubQuery Projects](https://project.subquery.network/) กำลังปรับปรุงและอัปเดตโปรเจกต์รวมถึงข้อมูลภายในโปรเจกต์เหล่านั้นอย่างต่อเนื่อง แต่ก็น่าเสียดายที่ต้องใช้เวลาหลายชั่วโมง (หรืออาจหลายวัน) เพื่อจะสร้างดัชนีข้อมูลของเชนขึ้นใหม่ในกรณีที่มีการเปลี่ยนแปลงครั้งใหญ่ ซึ่งท้ายที่สุดแล้วเป้าหมายของเราคือการช่วยให้คุณสามารถอัปเดตโปรเจกต์, จัดทำดัชนีข้อมูลของคุณใหม่, และอัปเกรดโปรเจกต์ SubQuery ที่โฮสต์อยู่โดย**ที่ระบบไม่หยุดทำงาน

**ซึ่งนั่นคือสิ่งที่ deployment slots จะมาช่วยแก้ปัญหา**

![](https://miro.medium.com/max/1400/0*vQ33aqhn1eVllo5t)

โดย staging slot ของคุณจะรันโดยไม่ขึ้นกับ production slot หลัก

เมื่อสร้างการ deploy ใหม่ให้กับ [SubQuery Project ในบริการโฮสต์ของเรา](https://project.subquery.network/) คุณสามารถเลือกที่จะ deploy กับ production slot หรือ staging slot ซึ่ง slot ทั้งสองนี้มีสภาพแวดล้อมที่แยกจากกัน และต่างมีฐานข้อมูลของตัวเองรวมถึงซิงค์ (sync) อย่างอิสระจากกัน เมื่อ staging slot ของคุณเริ่มต้นและเสร็จสิ้นการจัดทำดัชนีแล้ว คุณสามารถเลื่อนระดับมันเป็น production ได้โดยที่ระบบไม่หยุดทำงาน

Staging slot นั้นเหมาะสำหรับ:

-   การตรวจสอบการเปลี่ยนแปลงโปรเจกต์ SubQuery ในสภาพแวดล้อมที่แยกจากกัน staging slot นั้นมี URL ที่แตกต่างไปจากแบบ production ซึ่งคุณสามารถใช้ได้ใน dApps ของคุณ
-   การวอร์มอัพและจัดทำดัชนีข้อมูลสำหรับโปรเจกต์ SubQuery ที่อัปเดตแล้วเพื่อที่จะกำจัดการหยุดทำงานใน dApp ของคุณ
-   การเตรียมปล่อยเวอร์ชันใหม่สำหรับโปรเจกต์ SubQuery ของคุณโดยไม่เปิดเผยต่อสาธารณะ ซึ่ง staging slot นั้นจะไม่ปรากฏต่อสาธารณะบน explorer และมี URL เฉพาะที่มองเห็นได้เพียงคุณเท่านั้น

คุณสามารถทดลองใช้งานได้ทันทีใน [SubQuery Projects](https://project.subquery.network/)