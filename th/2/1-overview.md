---
title: ภาพรวมของบทที่ 2
actions: ['checkAnswer', 'hints']
material:
  saveZombie: false
  zombieBattle:
    zombie:
      lesson: 1
    humanBattle: true
    ignoreZombieCache: true
    answer: 1
---

ในบทที่ 1 เราได้สร้างฟังก์ชันที่สามารถรับข้อมูลในส่วนของชื่อ ซึ่งจะถูกนำไปใช้ในการสร้างซอมบี้ขึ้นมาในรูปแบบของการสุ่ม และเพิ่มซอมบี้ตัวนั้นเข้าไปใน database ที่อยู่ภายในแอพพลิเคชั่นซอมบี้ของเราบน blockchain

ในบทที่ 2 เราจะทำให้แอพพลิเคชั่นนี้มีความเสมือนเกมมากขึ้น: เราจะทำให้เกมนี้สามารถเล่นได้โดยหลายผู้เล่น (multi-player) และเรายังจะเพิ่มลูกเล่นในการสร้างซอมบี้ให้มากขึ้นไปอีก ไม่สร้างจากเพียงแค่การสุ่มเท่านั้น 

สงสัยใช่ไหมว่าจะสร้างซอมบี้ตัวใหม่ขึ้นมาอย่างไร ? โดยการให้มัน "กิน" สิ่งมีชีวิตอื่นยังไงล่ะ !

## ให้อาหารซอมบี้

เมื่อซอมบี้กัดกินเหยื่อจะทำให้เจ้าเหยื่อตัวนั้นติดเชื้อไวรัสเข้าไป ไวรัสก็จะเปลี่ยนให้เหยื่อกลายเป็นซอมบี้พวกเดียวกันและมาเข้าร่วมกองทัพซอมบี้ในที่สุด โดย DNA ของซอมบี้ตัวใหม่นั้นก็เกิดจากการผสมกันระหว่าง DNA ของซอมบี้ตัวเก่าและของเหยื่อนั่นเอง

ซอมบี้ของเรานั้นชอบกินอะไรที่สุดกันนะ ?

เพื่อที่จะหาคำตอบ... คุณจะต้องสำเร็จบทเรียนที่ 2 เสียก่อน!

# มาทดสอบกัน

เรามีตัวอย่างง่าย ๆ ของการให้อาหารอยู่ทางด้านขวา ลองคลิกบนตัวคนเพื่อดูว่าจะเกิดอะไรขึ้นเมื่อซอมบี้กินอาหารดูสิ !

เห็นได้ชัดว่า DNA ของซอมบี้ตัวใหม่จะถูกทำการวิเคราะห์จาก DNA ของซอมบี้ตัวเริ่มต้น เช่นเดียวกันกับ DNA ของเหยื่อ

เมื่อพร้อมแล้วให้คลิก "บทต่อไป" เพื่อที่จะเข้าสู่การสร้าง multi-player เกม ในบทต่อไป