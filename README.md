# Calculator-Android-Studio

A simple and beginner-friendly **Android CGPA Calculator App** built using **Kotlin** and **XML layouts**.  
This app allows users to input grade points for three subjects and calculates the **overall CGPA instantly**.

---

## 🚀 Features

- ✔ Enter grade points for 3 subjects  
- ✔ Validates empty inputs  
- ✔ Calculates CGPA using the formula:  
  **CGPA = (Sub1 + Sub2 + Sub3) / 3**
- ✔ Clean and minimal UI  
- ✔ Built using Kotlin + XML  

---

## 📸 Screenshots  
(Add your screenshots here after uploading images in `assets/` folder)

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

