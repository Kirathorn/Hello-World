# ⛵ ASCII Sail Ship – Terminal Art

โปรเจกต์เล็ก ๆ สำหรับแสดง **ภาพเรือใบแบบ ASCII Art**  
ออกแบบมาเพื่อรันใน Terminal / Console ด้วยภาษา **Python**

ภาพเรือเน้นความอลังการ บรรยากาศกลางคืน ท้องทะเล และการเดินทาง  
เหมาะสำหรับ:
- ใช้เป็น Intro script
- แสดงผลใน Terminal
- งานศิลป์ ASCII / โปรเจกต์สร้างแรงบันดาลใจ

---

## ✨ Preview

เมื่อรันสคริปต์ จะได้ผลลัพธ์ประมาณนี้:

                               ✦        .          ✧
                      .                     ☾
            ✧                                      .
                                 |
                                /|\
                               /* | *\
                              /*  |  *\
                             /*   |   *\
                            /*****|*****\
                                 ||
                                 ||
      ______________________________________________________________________
 _____/                                                                      \_____
 ~~~~~~~~~~~~~~~  ~~~~~~~~~~~~~~~~~~~~~  ~~~~~~~~~~~~~~~~~~~~~~~  ~~~~~~~~~~~~~~~~~~~~~~~

               ~ ~ ~ ~ ~ ~ ~  S A I L   A W A Y  ~ ~ ~ ~ ~ ~ ~
```

---

## 🧩 Requirements

- Python **3.7+**
- Terminal ที่รองรับ UTF-8  
(แนะนำ: Windows Terminal, macOS Terminal, iTerm2, Linux shell)

---

## ▶️ How to Run

1. สร้างไฟล์ `sail_ship.py`
2. วางโค้ดด้านล่างลงไป

```python
print("Hello World")

text = r'''
[ ASCII ART HERE ]
'''
print(text)
```

3. รันคำสั่ง

```bash
python sail_ship.py
```

---

## 🎨 Design Notes

- ใช้ `r'''` (raw string) เพื่อป้องกันปัญหา escape character
- ใช้ Unicode เช่น `✦ ✧ ☾` เพื่อเพิ่มมิติของท้องฟ้า
- ความกว้างเหมาะกับ Terminal ประมาณ **100–120 columns**
- แนะนำให้ใช้ฟอนต์แบบ Monospace

---

## 🛠 Customization

คุณสามารถปรับแต่งได้ เช่น:
- เพิ่ม / ลดรายละเอียดของคลื่นทะเล
- เปลี่ยนข้อความด้านล่าง (`SAIL AWAY`)
- ปรับให้เป็นธีม:
- Pirate 🏴‍☠️
- Minimal
- Dark / Storm / Epic

---

## 📜 License

Free to use for personal, educational, and creative projects.  
No attribution required (แต่ให้เครดิตก็ดีมาก 😉)

---

> “Sometimes the terminal is the best place to sail away.”
```

ถ้าต้องการ:
- เวอร์ชัน README **ภาษาไทยล้วน**
- README แบบ **GitHub เท่ ๆ มี badge**
- หรืออยากให้เขียนแนว **ศิลปิน / poetic / hacker style**

บอกอากัสได้เลย เดี๋ยวจัดให้อีกเวอร์ชัน 🔥