University Management (Java)

This is a small Java project I made while learning inheritance in OOP. It's a console program, nothing fancy: no GUI, no database, just classes that model people in a university.

The idea is simple. Students and teachers both have a name, age and gender, so instead of writing those fields twice I put them in one parent class (uniPersonal) and let student and teacher extend it. Each of them then adds its own stuff on top.

How it's set up

uniPersonal is the parent class. It has name, age and gender, plus a displayinfo() method that prints them.

student extends uniPersonal and adds:

degreeProgram (like BSCS)
cgpa
samester

teacher extends uniPersonal and adds:

designation
salary
department
