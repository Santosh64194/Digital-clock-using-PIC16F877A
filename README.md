# Digital-clock-using-PIC16F877A


This project implements a **24-hour digital clock** using the **DS1307 RTC** and a **PIC microcontroller**. It displays time and date on a **16x2 LCD** and allows time/date adjustments via buttons.

---

###  Features

* Time format: **HH\:MM\:SS** (24-hour)
* Date format: **DD-MM-YY**
* Adjustable time and date using 3 buttons
* Data stored in **DS1307 RTC** via I2C
* Display using **16x2 LCD**

---

###  Hardware

* PIC microcontroller (e.g., PIC16F877A)
* DS1307 RTC module with battery
* 16x2 LCD
* 3 push-buttons (Set, +, -)
* I2C pull-up resistors (4.7k)
* Crystal oscillator (1MHz for RTC)
* 5V regulated power supply

---

###  Button Functions

* **RA0** – Switch between hour, minute, date, month, year
* **RA1** – Increment selected field
* **RA2** – Decrement selected field

---

###  Tools Used

* MikroC PRO for PIC
* Proteus (for simulation)
* MPLAB / PICkit (for flashing)

---

###  Files

* `main.c` – Source code
* `README.md` – Project documentation

---
