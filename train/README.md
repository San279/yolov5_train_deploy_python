# ฝึก YOLOV11 AI ตราจจับวัตุ บน Google Colab
ในขั้นตอนนี้ เราจะทำการฝึก AI จากรูปที่เราได้รวบรวมจากขั้นตอนที่แล้ว

## วิธีใช้งาน
1. เปิดเว็ปไซค์ [Roboflow](https://app.roboflow.com/) และสร้างโปรเจ็คใหม่โดยกดไปที่ +New Project
2. ตั้งชื่อโปรเจ็ค และชื่อวุตถุต่างๆ ที่เราจะใช้ในการฝึก และเลือกชนิดของโปรเจ็คเป็น object detection
3. อัพโหลด รูปภาพเข้าไปใน Project
4. วาดกรอบของวัตถุที่จะให้ AI ตรวจจับในรูปภาพของเราทั้งหมด
5. เมื่อ annotate รูปภาพเสร็จเรียบร้อย เราก้พร้อมแล้วที่จะเรื่มการฝึก AI เปิด [Google Colab](https://colab.research.google.com/) และให้อัพโหลดไฟล์ Train_yolov11.ipynb ขึ้นไป
6. เมื่ออัพโหลดเสร็จแล้ว ระบบจะทำการเปิดไฟล์ และให้ทำตามขั้นตอนต่อไปบน google Colab

