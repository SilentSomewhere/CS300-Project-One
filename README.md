# CS 300 Data Structures and Algorithms – Project One

## Project Overview

This project was completed as part of CS 300: Data Structures and Algorithms. Project One focused on analyzing different data structures for an advising assistance program for ABC University (ABCU). The purpose of the program is to help academic advisors access and organize course information, including course numbers, titles, and prerequisites.

Throughout the project, I evaluated vectors, hash tables, and binary search trees to determine which data structure would be the most appropriate for the final course planner application. This project helped strengthen my understanding of data structures, algorithm efficiency, runtime analysis, and how choosing the right data structure can affect the overall performance of a program.

## Project One

Project One focused on designing pseudocode and performing a runtime analysis for three different data structures: a vector, hash table, and binary search tree. Each data structure was evaluated based on how effectively it could load course information from a file, search for an individual course, and display all courses in alphanumeric order.

After comparing the advantages and disadvantages of each structure, I determined that a binary search tree would be an effective choice for the course planner. A vector provides simple storage but may require additional sorting and searching operations. A hash table offers efficient average lookup times but does not naturally maintain the courses in sorted order. A binary search tree provides efficient searching while also allowing the courses to be displayed in alphanumeric order using an in-order traversal.

## Reflection

### What was the problem you were solving in the projects for this course?

The main problem was determining the best way to organize and access course information for ABCU's academic advisors. The proposed program needed to load course data, display the entire Computer Science course list in alphanumeric order, and allow an advisor to search for a specific course to view its title and prerequisites. Project One required me to determine how vectors, hash tables, and binary search trees could each be used to accomplish these requirements.

### How did you approach the problem? Consider why data structures are important to understand.

I approached the problem by creating pseudocode for each data structure and examining how each one would handle the required operations. I compared how courses would be inserted, searched, sorted, and displayed using a vector, hash table, and binary search tree. I also analyzed the expected runtime of these operations to understand the performance differences between the structures.

This process showed me why understanding data structures is important when designing software. Different structures may store the same information, but the efficiency of operations can vary significantly. Selecting an appropriate data structure can make a program more efficient, organized, and scalable.

### How did you overcome any roadblocks you encountered while going through the activities or project?

One challenge I encountered was understanding how the same course information could be managed differently depending on the data structure being used. Creating pseudocode for all three structures helped me break each process into smaller steps and better understand how operations such as insertion, searching, and traversal work.

Runtime analysis was another important part of the project because I needed to consider more than whether an approach would simply work. I also had to think about how efficiently it would perform as the amount of course data increased. Reviewing the operations individually and comparing their runtime complexities helped me better understand the strengths and weaknesses of each structure.

### How has your work on this project expanded your approach to designing software and developing programs?

Project One taught me the importance of planning and analyzing a solution before beginning the coding process. Instead of immediately writing C++ code, I first developed pseudocode and compared several possible approaches. This allowed me to think more carefully about how the application should function and how different design decisions could affect its performance.

I now have a better understanding of how algorithms and data structures work together when designing software. Considering factors such as runtime, searching efficiency, sorting requirements, and scalability before implementation can lead to a stronger and more organized final program.

### How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?

This project helped me recognize the importance of creating clear and organized designs before implementing a program. Writing detailed pseudocode made it easier to separate the application into logical operations, such as loading course data, searching for courses, and displaying course information.

I also learned that maintainability involves more than writing readable code. Choosing an appropriate data structure can make future changes easier to implement and reduce unnecessary complexity. Moving forward, I will continue using pseudocode, runtime analysis, descriptive naming, comments, and modular design to create programs that are easier to understand, debug, and improve.

## Skills Demonstrated

* Data structure analysis
* Vector operations
* Hash table operations
* Binary search tree operations
* Pseudocode development
* Algorithm design
* Runtime complexity analysis
* Searching and sorting concepts
* Software design and planning
* Evaluation of performance and scalability
