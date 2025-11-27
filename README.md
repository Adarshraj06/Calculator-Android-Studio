# Calculator-Android-Studio

A simple and beginner-friendly **Android CGPA Calculator App** built using **Kotlin** and **XML layouts**.  
This app allows users to input grade points for three subjects and calculates the **overall CGPA instantly**.

---

## 🚀 Features

- ✔ Enter grade points for 3 subjects  
- ✔ Validates empty inputs  
- ✔ Calculates CGPA 
- ✔ Clean and minimal UI  
- ✔ Built using Kotlin + XML  

---

## 📸 Screenshots  
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/66fa3df1-0e5c-4052-a830-edff7a500dea" />

---

## 🛠 Tech Stack

- **Language:** Kotlin  
- **UI:** XML Layouts  
- **Minimum SDK:** Android API 21+  
- **IDE:** Android Studio  

---

---

## 📘 MainActivity.kt (Logic)

```kotlin
val sub1 = s1.toDouble()
val sub2 = s2.toDouble()
val sub3 = s3.toDouble()

val cgpa = (sub1 + sub2 + sub3) / 3.0

tvResult.text = "CGPA: %.2f".format(cgpa)
```
## 💡 Author

👤 **Adarsh Raj**  
🎓 B.Tech CSE  
📱 Android & Kotlin Developer

