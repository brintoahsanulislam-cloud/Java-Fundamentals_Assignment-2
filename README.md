# Java Fundamentals – Assignment 2

## Project Overview

This repository contains three Java programming tasks completed as part of the **Programming Fundamentals and Database** course at **Vilnius College of Design (VCD)**.

The assignment focuses on fundamental Java programming concepts, including conditional statements, logical operators, arithmetic operations, user input, and decision-making.

Each task is implemented in a separate Java package.

## Assignment Tasks

### Task 1 – Summer Olympic Games

**Package:** `task1`  
**File:** `OlympicGames.java`

This program determines whether a given year is a Summer Olympic year and calculates the edition number of the Olympic Games.

The first Summer Olympic Games were held in Athens in 1896. According to the assignment, Olympic years occur every four years, including years when the Games were cancelled.

**Conditions:**
- The entered year must be 1896 or later.
- The difference between the entered year and 1896 must be divisible by 4.

**Formula:**

`Edition = ((Year - 1896) / 4) + 1`

**Example:**

Input: `2024`

Output:
```text
2024 is an Olympic year.
Olympic Games edition: 33
```

### Task 2 – Digital Clock

**Package:** `task2`  
**File:** `DigitalClock.java`

This program calculates the time displayed by a digital clock one second after the entered time.

The user enters hours, minutes, and seconds using the keyboard.

The program handles:
- Increasing seconds by one.
- Changing minutes when seconds reach 60.
- Changing hours when minutes reach 60.
- Resetting the clock to 00:00:00 after 23:59:59.
- Checking whether the entered time is valid.

**Example:**

Input:
```text
Hours: 23
Minutes: 59
Seconds: 59
```

Output:
```text
Time one second later: 00:00:00
```

### Task 3 – Leap Year

**Package:** `task3`  
**File:** `LeapYear.java`

This program determines whether an entered year is a leap year or a non-leap year.

A leap year has 366 days, while a non-leap year has 365 days.

**Conditions:**
- A year divisible by 400 is a leap year.
- A year divisible by 4 but not by 100 is a leap year.
- Otherwise, it is a non-leap year.

**Example:**

Input: `2024`

Output:
```text
2024 is a leap year.
Number of days: 366
```

## Technologies Used

- Java
- IntelliJ IDEA
- Apache Maven
- Git
- GitHub

## Project Structure

```text
Java-Fundamentals-Assignment-2/
├── src/
│   └── main/
│       └── java/
│           ├── task1/
│           │   └── OlympicGames.java
│           ├── task2/
│           │   └── DigitalClock.java
│           └── task3/
│               └── LeapYear.java
├── pom.xml
└── .gitignore
```

## How to Run the Programs

1. Clone or download the repository from GitHub.
2. Open the project in IntelliJ IDEA.
3. Make sure a compatible Java JDK is installed and configured.
4. Navigate to `src/main/java`.
5. Open the package containing the required task.
6. Run the Java class using its `main()` method.
7. Enter the requested values in the console.
8. View the calculated result.

## Learning Outcomes

Through this assignment, I practiced:

- Reading keyboard input using the `Scanner` class.
- Using integer variables and arithmetic operators.
- Implementing `if` and `else` statements.
- Applying logical operators (`&&`, `||`).
- Using the modulus operator (`%`).
- Working with time calculations and leap-year conditions.
- Organizing Java programs into separate packages.
- Managing and uploading a Java project using Git and GitHub.

## Author

**Ahsanul Islam**  
Vilnius College of Design (VCD)  
Program: Smart Automation Industries – Robotics Programming System

**Course:** Programming Fundamentals and Database  
**Assignment:** 2
