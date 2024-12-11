# Ryan Hubbuck's ePortfolio

## Professional Self-Assessment
Hi, my name is Ryan Hubbuck and I am in my final term at Southern New Hampshire University.
I will be graduating with a Bachelor of Science (BS) in Computer Science, with a concentration
in Software Development. While this has been a lengthy process, my coding journey actually began
6+ years ago. I am a self-taught programmer who began by learning HTML, CSS, JavaScript, and Python, 
and utilized these skills to begin as a Junior Software Engineer in 2021.

Throughout this program I have gained valuable skills and exposure to technologies that are not
within my day-to-day tech stack. While I have learned a great deal in my time in the program, 
the three most important concepts or skills include an understanding of data structures and algorithms, 
the importance of and how to better implement unit testing, and the importance of developing a 
well-designed development plan and considering security or possible vulnerabilities throughout the 
entire software development lifecycle. In addition to these skills, I have also gained valuable experience 
writing programs in Java and C++, which are widely-used, and more strictly structured languages.

My career plans involve the progression from an entry/mid-level software engineer to eventually work as a 
senior software engineer. While this will be a lengthy process, each one of these skills will be necessary 
to reach my ultimate career goal. Understanding data structures and algorithms, best-coding practices, and 
security practices are essential for any software engineer, and will help me be a better programmer in my 
current and future roles. In addition, the communication skills developed during this process will be 
invaluable, because software engineers at higher levels need to be effective communicators with both 
technically savvy and non-technical individuals. 

## Original Artifact
The original artifact was a C++ program designed in CS-300. The goal was to allow users to 
read in a file of courses along with associated prerequisite courses, print a list of courses 
to the console after sorting the elements in alphanumeric order by course title, and look-up a 
course to print the associated prerequisite course numbers to the console. I specifically chose 
this artifact because it was limited in scope, and I saw many areas that could be improved upon to 
increase the amount of value delivered to users. Furthermore, since this was created in a lower level 
course, I identified many areas lacking in security or not following coding best practices.

[Original Codebase](https://github.com/rhubbuck-snhu/cs300final)

## Code Review
A code review is a process in which a software developer examines code written by another developer 
or dated code by the same individual in the case of this project, to improve the code quality by 
identifying bugs or potential security vulnerabilities and adherence to general coding or language-specific 
best practices. This is an important step in the growth process of software developers because knowledge can 
be shared, and this communication allows team members to ensure every individual understands the standard in 
the same fashion. Additionally, this process can prevent future bugs or vulnerabilities by making past errors 
obvious and then by recommending possible solutions. Best practices of code reviews include only reviewing 
200 to 400 lines of code at a time to ensure the code is being properly analyzed, taking your time when analyzing 
code to reduce the likelihood of missing errors, using a checklist, establishing a process for fixing defects, 
and maintaining a positive attitude. Code reviews should occur during the ‘development’ phase of the software 
development lifecycle, and more specifically after the coding and testing are complete and have been passed, but 
before the code is integrated or pushed to a main repository. This ensures that the code is complete and free 
from surface-level or simple errors, but it also ensures that the unit is properly reviewed before being merged 
into the existing code and potentially negatively impacting other units or the project.

[Code Review Video - Part 1](https://youtu.be/A8blCNwTyog)

[Code Review Video - Part 2](https://youtu.be/3K5BHJlHuyI)

## Enhancement One: Software Design and Engineering
The artifact was improved upon in several ways. First, functionality was added to allow users to 
dynamically add courses once the program is running, delete courses, and manage an individual course’s 
prerequisites through addition or deletion. Next, best practices were addressed by the removal of unnecessary 
comments and leftover testing lines of code, the inclusion of more descriptive and higher-quality comments 
at the top of the file and beginning of large functions, memory management through data structure and pointer 
deletion proper range checking when adding prerequisites, and input validation and length limiting. 
Finally, what was once a single .cpp file is now segmented into a main.cpp, functions.cpp/.h, Course.cpp/.h, 
and CourseLoader.cpp/.h. This separation of classes follows object-oriented programming principles and will make 
the codebase easier to manage in the future and provide the opportunity to reuse certain elements within other 
components.

This milestone primary addresses course outcomes 2, 4, and 5. The additional features created to address the 
‘Software Engineering and Design’ enhancements required the inclusion of high-quality documentation to explain 
code functionality, which aligns with delivering professional-quality written communication. Additionally, these 
additional features were designed, developed, and then integrated into the existing codebase by aligning with 
industry-specific goals and by following best practices related to C++. These added features allow users to dynamically 
create, update, and delete data also deliver value to users. Finally, many layers of security were added to the project 
including input validation and data cleaning, error handling, pointer cleanup, and general memory management, and all 
these features align with the outcome related to developing a security mindset to anticipate exploits, mitigate design 
flaws, and enhance the security of data and resources.  

This planned enhancement demonstrated many specific skills cultivated throughout the course of this program that align 
with course outcomes. First, problem solving and thorough analytic skills was required to identify shortcomings of the 
original program and plan how new features can be integrated most effectively. I also demonstrated my understanding of 
object-oriented programming and coding best practices by writing concise code and creating documentation for review. 
Next, my understanding of security vulnerabilities, adherence to security best practices, and understanding of how 
to catch and handle errors or exceptions were required to create a robust system that is fortified. Finally, the inclusion 
of memory management demonstrated my general computer science knowledge including how programs execute, pointers, and 
how the call stack operates within the operating system. 

[Original Codebase](https://github.com/rhubbuck-snhu/cs300final)

[Enhanced Artifact](https://github.com/rhubbuck-snhu/artifact1)

## Enhancement Two: Algorithms and Data Structures
The data structure included in the original codebase was a vector, which is simple to understand and code, 
but this enhancement required me to design and implement an AVL tree, which is a form of a balanced binary tree. 
This enhancement was warranted because inserting and sorting a new course into a vector resulted in O (n log n) 
time complexity, while switching to an AVL tree resulted in O (log n) time complexity. Designing the AVL tree 
class was by far the most challenging aspect of this milestone, and in particular, the functions required to 
balance the tree via left or right rotations were the most novel concepts to me. Throughout this process, I gained 
a greater understanding of balanced trees in general, and more specifically I learned the process of checking the 
height of a node’s children and then rotating that node in various ways to produce a balanced tree.

This planned enhancement of the underlying data structures and algorithms of the program demonstrated many 
fundamental skills expected of all software engineers. To ensure optimal program efficiency and a smooth user 
experience, I demonstrated my understanding of programming data structures, my knowledge of binary trees and 
how they compare to vectors, my understanding of sorting algorithms, and my ability to debug processes. This category 
also allowed me to demonstrate my understanding of general coding best practices and my proficiency using the C++ 
language, which is one of the most common programming languages. 

I was able to meet all the course outcomes that I planned on meeting, and the work produced during this module 
most closely relates to course outcome 3. I successfully analyzed the original software and data structure to identify 
areas of improvement, designed a new data structure, programmed the data structure, and then integrated the structure 
into the program to ensure proper functionality with the preexisting Course class objects. This core design choice uses 
computer science knowledge and algorithmic principles gained throughout this course to accomplish the goal in the 
most efficient way possible.

[Original Codebase](https://github.com/rhubbuck-snhu/cs300final)

[Enhanced Artifact](https://github.com/rhubbuck-snhu/artifact2)

## Enhancement Three: Databases
The original codebase included no database integration whatsoever, so I was able to design and develop the database from 
scratch. I chose to utilize SQLite due to its easy integration into Visual Studio C++ projects. Not only did I create a 
new database and table, but I also prevented SQL injection through secure coding best practices and prepared statements. 
Furthermore, this was my first time creating an SQL trigger. The trigger functions by updating a timestamp column any 
time a row is created or updated. This is particularly useful in real-world applications for keeping track of data changes. 
This trigger creation was the toughest part of this module because I was unsure of the proper syntax to use within SQLite.

The database enhancement demonstrated specific skills related to SQL, general database use and integration, and security. 
I was also able to show my ability to write SQL queries and to use more advanced techniques like SQL triggers. Additionally, 
I showed my ability to thoughtfully plan out and design a database to ensure optimal functionality with a program. Furthermore, 
I demonstrated my understanding of various security vulnerabilities related to database integration including SQL injection and 
buffer overflow, and I planned how to protect the program and implement those changes. 

The work completed within the ‘Database’ category most closely aligned with course outcomes 4 and 5. In the original program there 
was no database present whatsoever, so the entire database needed to be designed, developed, and integrated from scratch. The 
inclusion of a database delivered value to future users because this allows far more robust features to exist when compared to the 
original program. This required a demonstration of well-founded and innovative skills to create the database properly, and I needed 
to include tools not present in the original program such as SQLite. Furthermore, a security mindset was required to be developed to 
anticipate attacks like SQL injections, and to properly reduce security vulnerabilities by properly protecting data input and database connections. 

[Original Codebase](https://github.com/rhubbuck-snhu/cs300final)

[Enhanced Artifact](https://github.com/rhubbuck-snhu/artifact3)
