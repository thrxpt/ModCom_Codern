# ฐานข้อมูลดูยากจังเลย

CEO พึงพอใจเป็นอย่างมากกับระบบต้อนรับลูกค้าครั้งก่อน แต่เมื่อบริษัทใหญ่ขึ้น ระบบก็ต้องใหญ่ขึ้นตามทำให้การตอนรับลูกค้ามากขึ้น CEO ของ CPE Express จึงอยากให้ระบบตอนรับลูกค้าที่มาพร้อม ๆ กันทีละหลาย ๆ คน

## ข้อมูลนำเข้า (Input)
**บรรทัดที่ 1 :**  n จำนวนของผู้เข้าใช้ระบบ (1 ≤ n ≤ 99)

**บรรทัดที่ 2 :**  ชื่อของผู้ใช้ตามจำนวน n (ไม่เกิน 99 ตัวอักษร และไม่มีช่องว่าง)

## ข้อมูลส่งออก (Output)
ข้อความชื่อลูกค้าที่เรียงแล้วในรูปแบบ: 

 ```
1. ชื่อ_1
2. ชื่อ_2
...
n. ชื่อ_n
 ```

## ตัวอย่าง

| **ข้อมูลขาเข้า** | **ข้อมูลขาออก** |
|------------------|------------------|
| 3<br>James<br>Olivia<br>Emma | 1.Emma<br>2.James<br>3.Olivia<br> |
| 4<br>Alice<br>Ben<br>Charlie<br>David | 1.Alice<br>2.Ben<br>3.Charlie<br>4.David<br> |
| 5<br>Jane<br>Ben<br>Jane<br>Alice<br>Ben | 1.Alice<br>2.Ben<br>3.Ben<br>4.Jane<br>5.Jane<br> |


## หมายเหตุ

- การเรียงลำดับเป็นแบบ **พิมพ์ใหญ่เล็กตาม ASCII** (`A` มาก่อน `Z`, `a` มากกว่า `Z`)
- ต้องใช้ *string.h*
