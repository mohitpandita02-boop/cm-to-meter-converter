# cm-to-meter-converter
A simple C program that converts centimeters into meters.

# CM to Meter Converter (C Program)

This is a simple and beginner-friendly C program that converts a length value from **centimeters (cm)** to **meters (m)** using basic arithmetic.  
This project is ideal for students who are learning C programming and want to practice input/output and simple calculations.

---

## 🚀 Features
- Converts centimeters into meters
- Uses only basic C concepts (int/float, input, output)
- Beginner-friendly code
- Runs on Code::Blocks, VS Code, or any C compiler

---


---

## 🛠 How to Run
1. Open the project in **Code::Blocks** or any C IDE  
2. Build & Run the program  
3. Enter value in centimeters  
4. Get result in meters  

---

## 📘 Sample C Code
```c
#include <stdio.h>
int main()
{
  printf("Centimeter to Meter Conversion\n");
  float Centimeter;
  printf("Centimeter : "); // Give centimeter value
  scanf("%f",&Centimeter);
  float Meter = Centimeter / 100; // Centimeter to Meter Conversion formula
  printf("Meter : %f",Meter); // Now you get the answer in meter
    return 0;
}
Mohit Pandita
Learning C Programming & Building Beginner Projects

⭐ Support

If you like this project, give it a star ⭐ on GitHub!
