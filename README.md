Project Overview & How to Run-
The Campus Course & Records Manager (CCRM) is an end-to-end turnkey system implemented using Java SE. It is intended to be a powerful platform for managing an educational institution’s core information — student and course records, financial informations, and the like.

Requirements: Java Development Kit (JDK): Version 17 and Above
IDE: Eclipse, IntelliJ IDEA, or VS Code with Java extensions

How to Run-
    1. Clone the Repository:
       git clone <your-repository-link>
       cd <repository-folder>
 
    2. Open in IDE:

 	(a). Open your IDE (e.g., Eclipse).

 	(b). Select File > Open Projects from File System... or Import... > Existing Maven/Gradle Project.

 	(c). Navigate to and select the cloned repository folder.

    3. Run the Application:

 	(a). Locate the main class, which should be in a file like edu/ccrm/cli/Main.java.

 	(b). Right-click on the Main.java file and select Run As > Java Application.

    4. Run from Command Line (Optional):

 	(a). Navigate to the project's source directory.

 	(b). Compile the code:
 		javac -d out edu/ccrm/cli/Main.java
 
 	(c). Run the compiled code:
 		java -cp out edu.ccrm.cli.Main


Evolution of Java:


    1. JDK 1.0 (1996): The initial release of Java, codenamed "Oak."

    2. J2SE 1.2 (1998): Introduced the Swing GUI toolkit, the Collections Framework, and the JIT (Just-In-Time) compiler.

    3. J2SE 5.0 (2004): A major update that added Generics, Enums, Autoboxing, and Annotations.

    4. Java SE 8 (2014): A landmark release introducing Lambda Expressions, the Stream API, a new Date and Time API, and default methods in interfaces.

    5. Java SE 11 (2018): The first Long-Term Support (LTS) release after the new six-month release cadence. Added the var keyword for local variables.

    6. Java SE 17 (2021): The next LTS release, which brought Sealed Classes and refined Pattern Matching.

    7. Java SE 21 (2023): The latest LTS release, introducing major features like Virtual Threads (Project Loom), Record Patterns, and Sequenced Collections.


Java ME vs SE vs EE Comparison-

Java SE-

 	Primary Use- Core Java platform for desktop and server applications.

 	Core API- The foundation of the Java language (java.lang, java.util, etc.).
 
 	Example APIs- Swing, Collections, Stream API, NIO.2

 	Target Audience	General- purpose developers.

 
Java EE-

**Primary Use-** For large-scale, web-based, enterprise applications.




 	Core API- Built on top of Java SE, adds APIs for web services, servlets, etc.

 	Example APIs- Servlets, JSP, EJB, JPA, RESTful web services (JAX-RS)

 	Target Audience General- Enterprise application developers.

  Java ME-

**Primary Use-** For resource-constrained and embedded devices (IoT, older phones).




 	Core API- A strict subset of the Java SE API, optimized for small memory.

 	Example APIs- CLDC (Connected Limited Device Configuration), MIDP (Mobile Information Device Profile

 	Target Audience General- Embedded systems developers.



JDK / JRE / JVM Explanation

The Java platform consists of three core components that work together to enable Java's "write once, run anywhere" philosophy.

JVM (Java Virtual Machine): The JVM is an abstract machine that provides the runtime environment in which Java bytecode can be executed. It interprets the compiled .class files into native machine code for the underlying operating system. The JVM is platform-dependent, and it is the component that makes Java code platform-independent.

JRE (Java Runtime Environment): The JRE is the software package required to run a Java application. It includes the JVM, along with the core Java class libraries and supporting files. If you are an end-user and only want to run Java programs, the JRE is all you need.

JDK (Java Development Kit): The JDK is the full-featured software development kit for creating Java applications. It contains everything in the JRE, plus essential development tools like the Java compiler (javac), a debugger (jdb), and Wan archiver (jar). Developers need the JDK to write, compile, and debug Java code.

In simple terms: JDK = JRE + Development Tools, and JRE = JVM + Core Libraries.



JDK installation:


1) Search oracle java on google.
   
   <img width="602" height="306" alt="image" src="https://github.com/user-attachments/assets/dd7f467c-8869-447b-9391-ff873c189a11" />

3) Got to the official site and click on download java.
   <img width="940" height="470" alt="image" src="https://github.com/user-attachments/assets/14bdbf78-74a0-4350-bd09-0ed1ea89346a" />

4) Select JDK 24 from top left and choose windows, Press on any download link..
   <img width="940" height="481" alt="image" src="https://github.com/user-attachments/assets/4b0fa393-55ed-4b51-9d80-5eebf3fa4b3b" />

5) Run the installer, press next.
   <img width="940" height="479" alt="image" src="https://github.com/user-attachments/assets/aa79fb40-c852-4284-ba55-7eac2e8b4607" />

6) Set the installation directory, then press next, let it install.
   <img width="940" height="470" alt="image" src="https://github.com/user-attachments/assets/1dbdb5a2-dd5d-4ace-8d09-101a277b64fa" />

7) Copy the directory c:/program files/java/jdk-24/bin and paste to environment variables.
   <img width="940" height="474" alt="image" src="https://github.com/user-attachments/assets/21196e62-198a-4a4a-8502-d0825fc2b128" />



Eclipse Installation:

•	Search eclipse on google and go to the official site
<img width="940" height="467" alt="image" src="https://github.com/user-attachments/assets/1e589bfa-4d36-411f-9b50-97e609b78145" />


 

•	Go to official site then press on download.
<img width="940" height="471" alt="image" src="https://github.com/user-attachments/assets/44ac565f-e6ff-47f8-8efa-884bd4f5b56d" />

 


•	Press on download button
<img width="940" height="473" alt="image" src="https://github.com/user-attachments/assets/bd1c3da6-5286-4c31-8461-f11281d9bd12" />


 

•	Again press download and your download should begin.
<img width="940" height="473" alt="image" src="https://github.com/user-attachments/assets/6e344fd6-3833-4f99-b269-09a0b7e17545" />

 





•	Run the installer file
<img width="940" height="467" alt="image" src="https://github.com/user-attachments/assets/3f8071cd-ed1c-47ae-be45-1aa495642496" />

 


•	Select eclipse IDE for java developer
<img width="940" height="469" alt="image" src="https://github.com/user-attachments/assets/ea223164-a669-4938-87ea-cdb6f51d5ef1" />

 




•	Press on install
<img width="940" height="475" alt="image" src="https://github.com/user-attachments/assets/22f5318c-112a-4b02-9bf7-a8907a34998b" />


 


•	Press accept now.
<img width="940" height="474" alt="image" src="https://github.com/user-attachments/assets/5f7af1ea-42ad-46be-ab05-66359b75f467" />

 




•	Add your workspace directory where all your java projects will be saved and press launch.
<img width="940" height="472" alt="image" src="https://github.com/user-attachments/assets/5e6e7265-e15c-47ae-b18c-3080eec01fb4" />

 


•	Eclipse is installed.
<img width="940" height="466" alt="image" src="https://github.com/user-attachments/assets/75ed47a3-585f-41da-9f50-d8aa2f28a8fd" />


Syllabus wise topic mappings: 
<img width="1100" height="385" alt="image" src="https://github.com/user-attachments/assets/4994e135-74d9-4a75-a163-1d27b7e28b8e" />




USAGE
This will be the first thing on console when you run the program: 
<img width="1773" height="508" alt="image" src="https://github.com/user-attachments/assets/01ed37c4-7493-457f-adf0-0b0976bb807a" />


First, import sample data by inputing 5 followed by 1:
<img width="1384" height="757" alt="image" src="https://github.com/user-attachments/assets/6fa5926e-71ea-4163-8734-4e0393c7c8c6" />

now, export this data to students_export.csv by pressing 5 followed by 2:
<img width="1403" height="746" alt="image" src="https://github.com/user-attachments/assets/fadcda86-d85d-49d6-9bae-2ba0e5a1f3b3" />

after Import/Export is completed, you can proceed by 
pressing 1 to manage students:
<img width="628" height="445" alt="image" src="https://github.com/user-attachments/assets/afb66ec1-cc0c-489f-a094-1e5aa86dbb4c" />

pressing 2 to manage courses: 
<img width="631" height="529" alt="image" src="https://github.com/user-attachments/assets/b710914b-1ccd-49aa-98fd-7b356992c0c4" />

pressing 3 to enroll a student in a course:
<img width="828" height="426" alt="image" src="https://github.com/user-attachments/assets/5040ea22-d68b-42e3-8571-388762676e22" />

pressing 4 to add an instructor to a course
<img width="1298" height="473" alt="image" src="https://github.com/user-attachments/assets/99610e4b-3240-4002-9233-179d69a189ce" />

pressing 6 to create a backup of data: 
<img width="1022" height="518" alt="image" src="https://github.com/user-attachments/assets/c192df43-2910-4acf-9fe1-0d849b04e6c4" />












 
