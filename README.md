# Taekwondo Lesson Tracker

A Java command line tool for tracking private taekwondo students, their lesson packages, payments, and remaining lessons.

## Project Goal

I teach Taekwondo private lessons, and I struggle to keep track of each student's lesson package, whether they've paid, and how many lessons they have left. Right now I have no system for this, so it's easy to lose count or forgot who has paid. This is important to me because it's that I work with every week, and affects me and my students.

## MVP Scope (Version 1.0)

- Add a new student (name, contact info)
- Create a lesson package for a student (size, price)
- Log a completed lesson, which decrements the remaining count
- Record a payment and mark a package paid or unpaid
- View a student's status (lessons left, payment status)
- Save and load data between runs using a CSV file

## Future Plans (Version 2.0+)

- Low-lesson warning for students with 2 or fewer lessons left
- Weekly or monthly income summary
- Lesson history log with dates
- Edit or delete students, packages, and lessons
- Partial payments and payment plans

## Tech Stack

- Language: Java.
- Libraries: No external. Only use Java's standard library.
- Build/Tools: Plain javac and java from the terminal, Git and GitHub for version control, and IntelliJ as the editor.
- Data Storgage: CSV file

## Design Documents

- [Eisenhower Matrix](docs/taekwondo-matrix.pdf)
- [System Diagram](docs/system-diagram.png)

## How to Run

```bash
javac src/*.java -d out
java -cp out Main
```
## Roadmap

## Author

- Elizabeth Morsch
- https://github.com/ekmorsch32/taekwondo-lesson-tracker
