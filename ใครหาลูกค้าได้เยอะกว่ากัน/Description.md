# คำนวณค่าคอมมิชชันพนักงานจัดส่ง

หลังจากธุรกิจเติบโตขึ้น CEO Atip เริ่มแบ่งเขตการจัดส่งให้กับพนักงานในพื้นที่ต่างๆ พร้อมตั้งค่าคอมมิชชันตามจำนวนพัสดุที่ส่งได้ต่อวัน เพื่อจูงใจให้ส่งได้เยอะขึ้น พนักงานแต่ละคนจะได้ค่าคอมตามจำนวนพัสดุที่จัดส่ง ดังนี้:

### เงื่อนไขค่าคอมมิชชัน:
- ถ้าส่งได้ **ตั้งแต่ 1 ถึง 20 กล่อง** → ค่าคอม **5 บาทต่อกล่อง**
- ถ้าส่งได้ **21 ถึง 50 กล่อง** → ค่าคอม **7 บาทต่อกล่อง**
- ถ้าส่งได้ **มากกว่า 50 กล่อง** → ค่าคอม **10 บาทต่อกล่อง**

## ข้อมูลนำเข้า (Input)
- **บรรทัดที่ 1:** จำนวนกล่องที่พนักงานส่งได้ในวันนั้น (จำนวนเต็มบวก)

## ข้อมูลส่งออก (Output)
- ค่าคอมมิชชันที่ได้รับทั้งหมดในวันนั้น (จำนวนเต็ม)

## ตัวอย่าง

| **Input** | **Output** |
|----------|------------|
| 10       | 50         |
| 25       | 175        |
| 51       | 510        |
| 0        | 0          |
| 20       | 100        |
