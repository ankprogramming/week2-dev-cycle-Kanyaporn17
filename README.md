# แบบรายงานการทดลองครั้งที่ 2

## ตัวอย่าง

**สถานการณ์ที่ 1** : นายไก่อยากกินไข่เจียว เขามีอุปกรณ์เตรียมพร้อมทำไข่เจียวครบทุกอย่าง

**จงเขียนอัลกอริทึมและผังงานการทำไข่เจียว**

**ข้อมูลเข้า** : _ไข่ไก่_

**ข้อมูลออก** : _ไข่เจียว_

**อัลกอริทึม ของการทอดไข่เจียว**

1.  หยิบไข่ไก่
2.  ตอกไข่ไก่ใส่ภาชนะ
3.  ปรุงรสด้วยเครื่องปรุง
4.  ตีไข่ด้วยช้อนส้อม
5.  ตั้งกระทะบนเตา
6.  เปิดแก๊ส และติดไฟ
7.  ใส่น้ำมันพืช
8.  นำไข่ที่ปรุงรสแล้วใส่ลงในกระทะร้อน
9.  ทอดจนสุก
10. ตักขึ้นใส่จานที่เตรียมไว้

----------

## ขั้นตอนการทดลอง

**สถานการณ์ที่ 2** : นักเรียนเดินทางมาวิทยาลัยโดยมีเงิน 100 บาท

**จงเขียนอัลกอริทึมเพื่อช่วยให้นักเรียนสามารถเดินทางมาวิทยาลัยได้ เริ่มตั้งแต่ตื่นนอนจนถึงวิทยาลัย**

**ข้อมูลเข้า** : $1 เงิน 100 บาท 1$

**ข้อมูลออก** : $2 วิทยาลัย  2$

**อัลกอริทึม ในการเดินทางมาวิทยาลัย**

$3

1.  ตื่นนอน
2.  เข้าห้องปัสสวะ
3.  อาบน้ำ
4.  แต่งตัว
5.  แต่งหน้า
6.  กินข้าว
7.  ไปรอรถสองแถว
8.  ขึ้นรถสองแถว
9.  ลงจากรถสองแถว
10. จ่ายค่ารถ
11. เดินเข้าวิทยาลัย

3$

----------

**สถานการณ์ที่ 3** : นักเรียนเกิดอยากไปซื้อของที่เซเว่นหน้าวิทยาลัย โดยหน้าวิทยาลัยจะมีทางม้าลาย และสัญญาณไฟจราจร บนถนนมีรถสัญจรไปมาเป็นระยะๆ

**จงเขียนอัลกอริทึมและผังงานเพื่อให้นักเรียนสามารถข้ามถนนไปซื้อของที่เซเว่นได้ โดยไม่ถูกรถชน**

**ข้อมูลเข้า** : $4   ซื้อของ    4$

**ข้อมูลออก** : $5    เซเว่น   5$

**อัลกอริทึม ในการเดินทางไปเซเว่นหน้าวิทยาลัย**

$6

1.  ขอยามออกไปเซเว่น
2.  รอฟังคำอนุญาตจากยาม
    - ถ้ายามไม่อนุญาต เดินกลับมา
    - ถ้าอนุญาติ ขอบคุณยาม
3.  เดินออกไปเซเว่น
4.  ข้ามถนนตรงทางม้าลาย
5.  มองซ้ายมองขวาก่อนข้ามถนน รอรถว่าง
6.  เดินข้ามถนน เข้าเซเว่น
7.  ซื้อของที่ต้องการ
8.  จ่ายเงิน
9.  เดินออกจากเซเว่น
10. รอข้ามถนน ตรงทางม้าลาย
11. มองซ้ายมองขวาก่อนข้ามถนน รอรถว่าง
12. เดินข้ามถนน
13. กลับเข้าวิทยาลัย

6$

----------

**สถานการณ์ที่ 4** : นักเรียนไปซื้อข้าวที่โรงอาหาร ซึ่งจะมีการจ่ายเงินซื้อคูปอง โดยคูปองมี 3 ราคา คือ 5, 10 และ 20 บาท ถ้านักเรียนเป็นคนจ่ายคูปอง นักเรียนจะมีวิธีการอย่างไร ที่จะใช้จำนวนใบคูปองให้น้อยที่สุด

**จงเขียนอัลกอริทึมเพื่อแสดงวิธีการแลกคูปองให้ได้จำนวนใบน้อยที่สุด**

**ข้อมูลเข้า** : $7   เงิน   7$

**ข้อมูลออก** : $8   คูปอง   8$

**อัลกอริทึม การแลกคูปองให้ได้จำนวนใบน้อยที่สุด**

$9

1. ดูจำนวนเงินที่ต้องการแลก 
2. ถ้ามากกว่า >=20 ให้จ่าย คูปอง 20 กลับไปทำข้อ 1
3. ถ้า <20 >10 ให้จ่าย คูปอง 10 กลับไปทำข้อ 1
4. ถ้า <10 ให้จ่าย คูปอง 5 กลับไปทำข้อ 1

9$

----------

## ภาระงาน

**วิเคราะห์และออกแบบการทำงานของตู้กดน้ำอัตโนมัติ พร้อมทั้งเขียนคู่มือและบอกแนวทางการบริการและบำรุงรักษา**

![File not found](img/drink1.jpg)

**วิเคราะห์และออกแบบ**

$10

เครื่องจ่ายน้ำในราคาประหยัด และมีคุณภาพได้ผ่านการตรวจสอบคุณภาพน้ำจากกรมวิทยาศาสตร์การแพทย์ มีสติกเกอร์การดูแลรักษาตู้น้ำทางด้านหน้าตู้ สคบ. และใบตรวจสอบคุณภาพน้ำจากบริษัทเอกชน โดยเครื่องจ่ายน้ำหยอดเหรียญมีขบวนการกรองน้ำให้บริสุทธิ์ ด้วยระบบ RO. REVERSE OSMOSIS น้ำที่ได้จากเครื่องกรองน้ำระบบ RO. เป็นน้ำที่ปราศจากแร่ธาตุ และเป็นน้ำที่ปราศจากสารปนเปื้อน ตู้น้ำหยอดเหรียญ คุณภาพได้มาตราฐาน ราคาประหยัด 

10$


**คู่มือสำหรับผู้ใช้**

$11

ไส้กรอง PP หรือ Sediment filter 5 ไมครอนเป็น 20 นิ้ว มีหน้าที่กรองและกำจัดสิ่งสกปรก ที่เป็นสารแขวนลอยขนาดเล็ก ที่ปนเปื้อนมากับน้ำ ทุก 1-3 เดือน ถอดมาตรวจสอบ ถ้าสกปรก มีตะกอนมากให้เปลี่ยน (หรือขึ้นอยู่กับปริมาณการใช้น้ำ)
ไส้กรอง Carbon 20 นิ้ว มีหน้าที่กรอง โดยใช้หลักการแลกเปลี่ยนประจุ เพื่อขจัดคราบหินปูนแล้วปล่อยประจุที่เป็นโซเดียม เพื่อลดความกระด้างของน้ำอายุการใช้งาน 4-8 เดือน(หรือขึ้นอยู่กับปริมาณการใช้น้ำ) ไส้กรอง PP 20 นิ้ว มีหน้าที่กรอง คลอรีน กลิ่นสี กำมะถันและสารแปลกปลอมอื่นๆอายุการใช้งาน 6-12 เดือน (หรือขึ้นอยู่กับปริมาณการใช้น้ำ) ไส้กรอง เมมเบรน (Membrane) 150 GPD ความละเอียด 0.0001 ไมครอนอายุการใช้งาน ประมาณ 35 ยูนิคแล้วก็จะตัน หรือขึ้นอยู่กับสภาพน้ำ หรือเปลี่ยนเมื่ออัตราการไหลของน้ำเป็นหยดหรือไหลน้อย กรณีปล่อยให้ตันนาน ๆ จะทำให้ปั๊มที่อัดเมมเบรนเสียได้ ไส้กรอง PP หรือ Sediment filter 1 แคปซูล ไมครอนเป็น มีหน้าที่กรองและกำจัดสิ่งสกปรก ที่เป็นสารแขวนลอยขนาดเล็ก ที่ปนเปื้อนมากับน้ำก่อนเข้าระบบเมมเบรน 1-2 ปีไส้ Rasin แคปซูล in Line มีหน้าที่กรอง คลอรีน กลิ่นสี สารอินทรีย์ ก่อนลงถังพักอายุการใช้งาน 8-12 เดือน หรือเมื่อน้ำมีกลิ่น ไส้กรอง Carbon (คาร์บอน) 10 นิ้ว มีหน้าที่กรองน้ำจากถังก่อนจ่ายน้ำ ระยะเปลี่ยน 1 ปี ขั้นตอน UV (Ultraviolet) ฆ่าเชื้อโรคก่อนจ่ายน้ำลงภาชนะให้ลูกค้า สามารถใช้งาน ได้หลายปี จนกว่าหลอดจะขาด ไส้กรอง แร่ เพิ่มแร่ธาตุให้กับคุณภาพน้ำ ควรนำล้างหินแร่ทุกๆ 6-12 เดือน เพื่อชำระล้างให้สะอาด

11$

**แนวทางการบำรุงรักษา**

$12

ภาชนะบรรจุที่จะใช้ใส่น้ำดื่มควรเป็นภาชนะที่สะอาดและไม่เคยใช้บรรจุสิ่งอื่นมาก่อน ถ้าเป็นภาชนะบรรจุใหม่ที่ไม่เคยใช้บรรจุสิ่งอื่นใดนอกจากน้ำดื่ม เราควรล้างด้วยน้ำที่เราไปกดจากตู้หยอดเหรียญนั่นแหละ ยอมเสียน้ำไปหน่อยเพื่อความสะอาดและปลอดภัยของเราเอง โดยใช้น้ำในปริมาณเล็กน้อย แล้วเขย่าให้ทั่วภาชนะบรรจุ เททิ้ง ทำเช่นนี้ 1-2 ครั้ง แล้วจึงเติมน้ำต่อ นี่คือการล้างที่ได้ผลวิธีหนึ่ง แต่ถ้ามีเวลามากพอ ก็สามารถล้างภาชนะบรรจุด้วยน้ำยาล้างจานก็ได้ โดยใช้แปรงขนอ่อนขัดล้าง (ไม่ควรใช้แปรงแข็งเพราะจะทำให้เกิดรอยขีดข่วนและเป็นแหล่งสะสมเชื้อจุลินทรีย์) จากนั้นจึงล้างออกด้วยน้ำสะอาด และก่อนเติมน้ำก็ล้างด้วยน้ำดื่มอีกครั้ง แค่นี้ก็สะอาดเพียงพอแล้วล่ะค่ะ ในกรณีที่ภาชนะบรรจุสกปรกมาก ๆ เช่นมีตะไคร่น้ำ ก็สามารถล้างออกได้ด้วยการใช้คลอรีนเทลงไปแล้วตั้งทิ้งไว้ประมาณ 5 นาที หลังจากนั้นจึงล้างคลอรีนออกด้วยน้ำสะอาด ถ้ายังมีกลิ่นคลอรีนหลงเหลืออยู่ ก็ใช้ถ่าน(ใส่ในถุงผ้า) หย่อนลงไปในถังทิ้งไว้ข้ามคืน กลิ่นก็จะหายไปได้นะคะ

12$
