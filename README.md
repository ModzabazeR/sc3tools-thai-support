# sc3tools

A CLI tool for extracting and modifying text in .scx and .msb scripts found in visual novels based on MAGES. engine. It's meant to be a replacement for the old, overly complicated tool which had the same name and was part of the now-abandoned [SciAdv.Net project](https://github.com/CommitteeOfZero/SciAdv.Net).

## เกมที่รองรับ
- Steins;Gate (Steam)
- Steins;Gate 0
- Robotics;Notes
- Robotics;Notes DaSH

## วิธีใช้
รันคำสั่ง ``./sc3tools`` โดยไม่ต้องมี argument เพื่อดูลิสต์คำสั่งทั้งหมด รวมถึงเกมที่รองรับและคำย่อต่างๆด้วย (เช่น ``sghd`` คือ Steins;Gate Steam)

รันคำสั่ง ``./sc3tools help <คำสั่งที่ต้องการ>`` เพื่อดูวิธีใช้งานคำสั่งนั้นๆ

ด้านล่างนี้จะเป็นตัวอย่างที่ใช้ในการแกะไฟล์จากสคริปต์ของ Steins;Gate นะครับ:

``./sc3tools extract-text C:/src/OB/sghd-scx/*.scx sghd``

ไฟล์ output จะอยู่ในโฟลเดอร์ที่ชื่อ ``txt`` (ในกรณีนี้ก็คือ ``C:/src/OB/sghd-scx/txt``).
