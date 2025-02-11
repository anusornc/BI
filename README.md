# Tutorial
- https://help.tableau.com/current/pro/desktop/en-us/parameters_create.htm
- https://help.tableau.com/current/pro/desktop/en-us/calcs_add_calculated_column.htm
- https://help.tableau.com/current/pro/desktop/en-us/calculating_z_scores.htm
- https://help.tableau.com/current/pro/desktop/en-us/kpi.htm
- https://help.tableau.com/current/pro/desktop/en-us/pareto.htm
- https://help.tableau.com/current/pro/desktop/en-us/population_pyramid.htm
- https://help.tableau.com/current/pro/desktop/en-us/co_occurrence.htm



#เตรียมข้อมูล:

## ดึงข้อมูลจาก World Bank

- Pivot ข้อมูลจากรูปแบบ crosstab เป็นรูปแบบ columnar โดยใช้ฟีเจอร์ Pivot ของ Tableau

- สร้างฟิลด์คำนวณ Rank:

- สร้างฟิลด์คำนวณชื่อ "Rank" ซึ่งเท่ากับ RANK_UNIQUE(sum([GDP]))

- ลากฟิลด์คำนวณ Rank ไปที่ Rows

- วาง Country Name ลงใน Detail ใน Marks

- คลิกขวาที่ Rank ใน Rows และเปลี่ยนจาก continuous เป็น discrete

## การสร้างภาพ:

- ลาก GDP ไปที่ Columns

- คลิกขวาที่ Rank และเลือก Compute Using จากนั้นเลือก Country Name

- ลาก Year ไปที่ Pages

- ไปที่ Format -> Animations และตรวจสอบให้แน่ใจว่าเปิดใช้งาน

- วาง Country Name ลงใน Color และ Label และเปลี่ยนชื่อ Titile

## การเล่นหน้า:

ใช้ฟีเจอร์ Page Playback เพื่อแบ่งมุมมองออกเป็นชุดของหน้า แต่ละหน้าจะแสดงถึงปีหนึ่งๆ

