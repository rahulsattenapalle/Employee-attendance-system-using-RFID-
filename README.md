# RFID Based Employee Attendance System using LPC2129

## Project Overview:
This project records employee attendance using RFID technology. Each employee carries a unique RFID tag. When the RFID reader scans a tag, the system marks the attendance and provides confirmation via buzzer or LED. It eliminates manual registers and improves accuracy.

## Working Principle:
- Each employee is assigned an RFID tag.
- The RFID reader scans the tag and verifies identity.
- A valid tag triggers buzzer and logs attendance.
- An invalid or repeated scan is ignored or flagged.

## Components Used:
- LPC2129 ARM7 Microcontroller
- RFID Reader (RC522)
- RFID Tags
- LCD Display (16x2)
- Buzzer
- LEDs
- MAX232 (for serial debugging)
- Power Supply, Breadboard, Jumper Wires

## Technologies Used:
- Embedded C Programming
- Keil µVision IDE
- Flash Magic (to flash the code)
- Serial communication (for debugging)

## Features:
- Automatic attendance logging
- Fast and contactless scanning
- Reduces manual error
- Easy to extend to database storage

## Future Scope:
- Integration with real-time database (MySQL)
- Admin-controlled web dashboard
- Biometric-RFID hybrid system

---

**Project Developed By:**  
**Rahul Sattenapalle**
