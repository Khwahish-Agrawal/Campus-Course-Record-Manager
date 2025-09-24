#  Campus Course Registration and Management System (CCRM)

---

##  Project Overview
The *Campus Course Registration and Management System (CCRM)* is a *Java SE application* built to demonstrate university-style course registration.  

It covers:
- Student enrollment & profile management  
- Instructor assignments  
- Course catalog & registration with capacity checks  
- Transcript and grade management  
- File storage with NIO.2  
- OOP concepts, Exception Handling, Design Patterns, Collections, Recursion, Enums, Assertions
  
---

##  How to Run

### Requirements
- *JDK Version:* JDK 17 or higher  
- *IDE:* IntelliJ IDEA (preferred) / Eclipse  
 

### Command Line
```bash
cd src
javac edu/ccrm/cli/MainCLI.java
java edu.ccrm.cli.MainCLI
```

---

* #Evolution of Java

1995 – Java 1.0 released.

1998 – Java 2 introduced: J2SE, J2EE, J2ME.

2004 – Java 5: Generics, Annotations, Enhanced loops.

2011 – Java 7: NIO.2, try-with-resources.

2014 – Java 8: Lambdas, Streams, Date-Time API.

2017–2021 – Java 9 to 17: Modules, var, records, switch expressions.

Today – Used for web, cloud, mobile (Android), and enterprise apps.



---

* #Java ME vs SE vs EE

Java ME	Micro Edition	Embedded & Mobile	IoT apps, old mobile phones

Java SE	Standard Edition	Core + Desktop	Standalone apps, CLI tools

Java EE	Enterprise Edition	Web & Enterprise	Banking, e-commerce



---

* #JDK vs JRE vs JVM

JDK: Development Kit with compiler (javac), JRE, debugger.

JRE: Runtime environment to run Java programs (includes JVM).

JVM: Virtual machine executing bytecode → ensures portability.

---

* #Installation Steps (Windows)

1. Download JDK 17 from Oracle.


2. Install JDK → set JAVA_HOME in system environment variables.


3. Add %JAVA_HOME%\bin to PATH.


4. Verify:

java -version
javac -version

---

* #Eclipse Setup

1. Download Eclipse IDE.


2. Configure JDK 17 in Preferences.


3. Import project: File → Import → Existing Java Project.


4. Run MainCLI.java.



---

* #Mapping Table (Syllabus → Code)

Topic	File/Class/Method

Abstraction	Person.java (abstract)

Inheritance	Student extends Person

Polymorphism	StudentService.listStudents()

Encapsulation	Private fields in Student.java with getters/setters

Singleton	AppConfig.java

Builder Pattern	Course.java (static Builder)

Enums	Semester.java, Grade.java

File Handling	FileUtil.java

Exception Handling	InvalidInputException.java, CourseFullException.java

Recursion	BackupUtil.java

Collections	StudentService.java (HashMap, ArrayList)

CLI Application	MainCLI.java



---

* #Assertions in Java

How to Enable

Run with -ea:

java -ea edu.ccrm.cli.MainCLI

Example Usage

int credits = course.getCredits();
assert credits > 0 : "Course credits must be positive!";


---

* #Conclusion

This project demonstrates all Java SE syllabus topics in a working application.

It includes OOP, file I/O, collections, recursion, enums, exceptions, assertions, and patterns.

README covers installation, execution, mapping, and file structure.

Project is ready to upload on GitHub and submit for evaluation.

---
