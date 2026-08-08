## 📝Mining Cart & Wage Calculator

    หลังจากขุดแร่มาได้ทั้งวัน พี่ต้องนำแร่ (กิโลกรัม) มาแบ่งใส่รถรางขนาดต่างๆ (1000, 500, 100 และ 50 กิโลกรัม) และคำนวณค่าจ้างให้คนงาน โดยปกติจะได้ค่าจ้าง 5 บาทต่อแร่ 1 กิโลกรัม แต่ถ้าคนงานทำยอดขุดทะลุ เป้าหมายรายวัน ที่กำหนดไว้ จะได้ค่าจ้างส่วนที่เกินเป้าหมายในราคา 10 บาทต่อกิโลกรัม และถ้าทำได้เป็น2เท่าของเป้าหมายหรือมากกว่าจะได้โบนัส 1000บาท 
 * แต่บริษัทไม่ได้ให้รถรางฟรี คนงานต้องจ่ายค่าเช่ารถรางจากค่าจ้างที่ได้
   * รถ 1,000 kg : หัก 50 บาท/คัน

   * รถ 500 kg : หัก 30 บาท/คัน

   * รถ 100 kg : หัก 10 บาท/คัน

   * รถ 50 kg : หัก 5 บาท/คัน 
* พี่อยากให้น้องช่วยหาว่าคนงานได้ค่าจ้างเท่าไหร่

## 📥Input(s)

  * `ore` น้ำหนักแร่ที่ขุดได้ทั้งหมด 
  * `quota` เป้าหมายรายวันที่ต้องขุดให้ถึง
  ### ยกเว้น 
  * oreเป็น 0 ให้คืนค่า out
  * quotaเป็น 0 ให้คืนค่า error


## 📤Output(s)
* `cost` ค่าจ้างคนงาน


## ⚙️Function

The function is defined in the file `Question.py` as the following:
>This is your default function for this Quiz

```python
def Mining(ore,quota):
    return 1
```

## 💡 Example  

**Input**  
```python
Mining(32050,32000)
#แร่ในเป้าหมาย: 32,000 kg × 5 บาท = 160,000
#แร่ส่วนเกิน: 50 kg × 10 บาท = 500
#รถ 1,000 kg: 32 คัน × 50 บาท = 1,600
#รถ 50 kg: 1 คัน × 5 บาท = 5
#60,500  1,605 = 158,895
```

**Output**
```python
158895 
```

## ▶️ To Run a Test Case  

Edit your answer in `Question.py`, then press **Run** in Moodle (VPL).
The server runs the test cases and shows the results.

## 🚨 Importance  

⚠️ **Always save/submit your latest code in Moodle before leaving the exam room!**  
🚀 This ensures your latest work is saved and reviewed correctly.
