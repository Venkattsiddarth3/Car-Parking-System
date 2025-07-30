# 🚗 Car Parking System Management

A simple console-based parking system developed in Java that allows users to park and remove cars, view currently parked cars, and track available slots. The system is interactive and uses a menu-driven approach.

---
## 💡Features

 **Initialize parking lot** with a specified number of **total slots**.
- Park cars by entering their **license plate number**.
- **Remove parked cars** using their **license plate number**.
- **Display a list** of all currently **parked cars**.
- **Real-time tracking** of available parking **slots**.

---

## 🛠️ Technologies Used

- Java Programming Language
- Java Collections (`ArrayList`)
- Standard Input/Output (`Scanner`, `System.in/out`)

---

## 🏁 Getting Started

### ✅ Prerequisites

- Java JDK installed (version 8 or above)
- IDE or terminal with Java support (e.g., IntelliJ, Eclipse, VSCode, or command-line)

### 🚀 Running the Program

1. Clone the repository or download the `.java` file.
2. Compile the Java file:\

# Running in Notepad ? 

## Open Command Prompt and run 
```bash
cd/

cd Foldername

javac ParkingSystem.java

java ParkingSystem
```
---

# Output Format 

```bash

Enter the total number of parking slots:
3

What would you like to do?
1. Park a car
2. Remove a car
3. View parked cars
4. Exit
Enter Choice : 1

Enter the license plate number of the car:
KA01AB1234
Car parked successfully. Available slots: 2

What would you like to do?
1. Park a car
2. Remove a car
3. View parked cars
4. Exit
Enter Choice : 1

Enter the license plate number of the car:
AP09CD5678
Car parked successfully. Available slots: 1

What would you like to do?
1. Park a car
2. Remove a car
3. View parked cars
4. Exit
Enter Choice : 3

Parked cars:
KA01AB1234
AP09CD5678

What would you like to do?
1. Park a car
2. Remove a car
3. View parked cars
4. Exit
Enter Choice : 2

Enter the license plate number of the car to be removed:
KA01AB1234
Car removed successfully. Available slots: 2

What would you like to do?
1. Park a car
2. Remove a car
3. View parked cars
4. Exit
Enter Choice :4

#Exit

