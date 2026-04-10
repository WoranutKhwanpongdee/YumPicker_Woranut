📱 แบบฟอร์มส่งงานสอบ Take-home | Take-home Assignment Template

ชื่อ - นามสกุล (Full Name): Woranut Khwanpongdee

รหัสนักศึกษา (Student ID): 6631503036

ชื่อแอป (App Name): YumPicker

Framework ที่ใช้ (Framework Used): React Native

ลิงก์ GitHub Repository: https://github.com/WoranutKhwanpongdee/YumPicker_Woranut

ลิงก์ไฟล์ติดตั้ง (APK/IPA): https://expo.dev/accounts/woranut/projects/MyFinal/builds/9f007c6b-3d33-417c-b8a3-0ce1a3445d4c?fbclid=IwY2xjawJ55Q9leHRuA2FlbQIxMABicmlkETFyam15bTF5MlJJQnQ2OVByAR7l_VXpQdkkFMOyFZ_3jaqDT9FZAHIadDI7pD21JKmmlgblRxHT9AH28LesYw_aem_g9QqwpEJ0NvyQx2z4OCGLQ/9f007c6b-3d33-417c-b8a3-0ce1a3445d4c

1. การออกแบบแอป | App Concept and Design (2 คะแนน / 2 pts)
1.1 ผู้ใช้งานเป้าหมาย | User Personas

Persona 1:  
- ชื่อ: นิว 
- อายุ: 20 ปี  
- อาชีพ: นักศึกษาปี 1  
- ความต้องการ: อยากได้แอปพลิเคชันช่วยสุ่มเมนูอาหาร

Persona 2:  
- ชื่อ: ขนุน  
- อายุ: 21 ปี  
- อาชีพ: นักศึกษาปี 3  
- ความต้องการ: มีความต้องการแอปพลิเคชันที่สามารถคิดเมนูอาหารจากวัตถุดิบที่มีในตู้เย็นได้
  
1.2 เป้าหมายของแอป | App Goals
- ช่วยให้ผู้ใช้เลือกวัตถุดิบที่มี แล้วหาเมนูอาหารที่ทำได้
- มีระบบสุ่มเมนูอาหารแนะนำ
- มีหน้าแดชบอร์ดแสดงเมนูแนะนำประจำวัน

1.3 โครงร่างหน้าจอ / Mockup
ใส่รูปภาพ หรือคำอธิบายแต่ละหน้าหลัก 3 หน้า | Attach image or describe 3 main pages
- หน้า Home Screen:
หน้าหลักแสดงโลโก้แอป, ปุ่ม "Find Recipes" และ "Random Menu" (ไปยังการเลือกวัตถุดิบ หรือสุ่มเมนูทันที)
- หน้า Ingredient Input Screen:
ผู้ใช้สามารถเลือกวัตถุดิบที่มี, ค้นหา, เลือกหมวดหมู่วัตถุดิบ และ Clear ได้
- หน้า Recipe Result Screen:
แสดงรายการเมนูอาหารที่ได้

1.4 การไหลของผู้ใช้งาน | User Flow
เปิดแอป → เข้าหน้า Home → กด "Find Recipes" → เลือกวัตถุดิบ → กด Find → ดูเมนูที่ตรงกับวัตถุดิบ
หรือ
เปิดแอป → เข้าหน้า Home → กด "Random Menu" → สุ่มเมนูจากระบบทันที

2. การพัฒนาแอป | App Implementation (4 คะแนน / 4 pts)
2.1 รายละเอียดการพัฒนา | Development Details
เครื่องมือที่ใช้ / Tools used:
- React Native (Expo)
- JavaScript (ES6)
- Package: @react-navigation/native, expo

2.2 ฟังก์ชันที่พัฒนา | Features Implemented
Checklist:
- [x] เลือกวัตถุดิบจากหมวดหมู่
- [x] ค้นหาวัตถุดิบด้วย Text Input
- [x] ล้างวัตถุดิบที่เลือก (Clear All)
- [x] แสดงเมนูตามวัตถุดิบ
- [x] สุ่มเมนูอาหาร

2.3 ภาพหน้าจอแอป | App Screenshots
แนบภาพหรือ URL (Attach images or image links):
![image](https://github.com/user-attachments/assets/e514e281-6afa-4666-841f-65258db1655b)
![image](https://github.com/user-attachments/assets/b9527b09-c8e3-4ca6-8e7a-0ec0fdf9186c)
![image](https://github.com/user-attachments/assets/8ba7ba95-ae04-4975-8099-f2f7db578059)
![image](https://github.com/user-attachments/assets/aad87375-21ec-407a-bfd7-062ff6b2c737)

3. การ Build และติดตั้งแอป | Deployment (2 คะแนน / 2 pts)

3.1 ประเภท Build | Build Type
[x] Debug
[ ] Release

3.2 แพลตฟอร์มที่ทดสอบ | Platform Tested
[x] Android
[ ] iOS

3.3 ไฟล์ README และวิธีติดตั้ง | README & Install Guide
แนบไฟล์หรือคำอธิบายการติดตั้งแอป | Insert steps
1. ดาวน์โหลดไฟล์ .apk จากลิงก์ที่แนบไว้
2. เปิดในอุปกรณ์ Android
3. ติดตั้งผ่าน File Manager

4. การสะท้อนผลลัพธ์ | Reflection (2 คะแนน / 2 pts)
- ติดปัญหา build apk แล้วเจอ white screen → แก้ไขโดยตรวจสอบการ import assets และ build ใหม่ด้วย eas-cli
- ต้องเรียนรู้การแก้ปัญหาเรื่อง url source ตอน build APK
- ได้ลองใช้ Expo CLI และ EAS Build ในการสร้างไฟล์ .apk แบบไม่ต้องพึ่ง Android Studio
- อยากเชื่อมต่อกับฐานข้อมูลจริง (Firebase หรือ Supabase) เพื่อดึงเมนูออนไลน์
- ได้ประสบการณ์จริงในการ build app แบบมีไฟล์ .apk ใช้งานจริง

5. การใช้ AI ช่วยพัฒนา | AI Assisted Development (Bonus / ใช้ประกอบการพิจารณา)
5.1 ใช้ AI ช่วยคิดไอเดีย | Idea Generation
Prompt ที่ใช้:  
"Suggest mobile app ideas related to food ingredients and recipes."
ผลลัพธ์:  
ได้ไอเดียแอปเลือกวัตถุดิบแล้วหาสูตรอาหาร YumPicker

5.2 ใช้ AI ช่วยออกแบบ UI | UI Layout Prompt
Prompt ที่ใช้:  
"Design a simple minimal UI for food recipe ingredient selection app."
ผลลัพธ์:  
ได้ layout แบ่งเป็น Home → Ingredient → Result

5.3 ใช้ AI ช่วยเขียนโค้ด | Code Writing Prompt
Prompt ที่ใช้:  
"React Native code to build selectable ingredient chips with categories."
ผลลัพธ์:  
ได้โครงสร้าง Ingredient Chips ที่ responsive

5.4 ใช้ AI ช่วย debug | Debug Prompt
Prompt ที่ใช้:  
"My React Native app crashes when selecting ingredient. Show possible reasons."
ผลลัพธ์:  
AI ช่วยหา error เรื่อง undefined ของ data และการ fix mapping error

5.5 ใช้ AI ช่วย Deploy | Deployment Prompt
Prompt ที่ใช้:  
"How to deploy a React Native Expo app to Expo Hosting (publish to expo.dev)?"
ผลลัพธ์:  
AI แนะนำการใช้ expo publish เพื่อนำแอปขึ้น Expo Hosting ได้สำเร็จ พร้อมได้ URL สำหรับแชร์ให้ผู้อื่นทดสอบแอปผ่าน Expo Go หรือเว็บเบราว์เซอร์
