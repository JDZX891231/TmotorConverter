# 🛠️ TMotor Command and Status Converter

---

## 📄 Description
To control a motor that has been set up for **Servo Mode** over the CAN bus.<br>
Through these two executable files, **HEX code** can be quickly converted.

---

## 🔧 Command Converter
| Command Code | Mode                         |
|--------------|------------------------------|
| **0**        | Duty Cycle Mode              |
| **1**        | Current Loop Mode            |
| **2**        | Current Brake Mode           |
| **3**        | Speed Mode                   |
| **4**        | Position Mode                |
| **5**        | Set Origin Mode              |
| **6**        | Position-Speed Loop Mode     |
| **7**        | Exit                         |

---

## 🖥️ Status Converter
Enter CAN Data (8-Byte HEX data), separated by spaces.

---

## 🛡️ Additional Information
**R-LINK Config Tool** is provided by **Cubemars Motor**.<br>
The folder contains `R-LINK Config Tool.exe`, which also includes the `Sent Data Conversion Tool`, seemingly used for **MIT Mode**.

---

## 📝 Other
This work was created by myself in ***C#*** based on the ***AK Series Module Driver User Manual***.<br>
> ⚠️ There may be errors or other unknown issues. The conversion is for **reference only**, and if the conversion is incorrect, it may also be due to data type issues.

---

## 📌 Usage Restrictions:
> **For non-commercial use only.**
