java c
Algorithms  Data Structures (IT+) 
Assessed Exercise (2024–2025) 
This exercise is assessed. Its weighting is 0.2 in the ADSIT course assessment. There are 2 parts of the assessment worth a total of 20 marks. Read all three pages of this document thoroughly.
The deadline is Friday 14 March 2025 at 16:30.
1. [5 marks] 
This part of the exercise is to show that you understand the Java interface Set and its implementation, TreeSet. See Lecture 1 for an example of these classes in use.
You have been provided with three files: a text file birds.txt, an outline of a class, AssEx1_outline.java, and a pdf file exampleOutput.pdf. You should make a copy of AssEx1_outline.java and rename it AssEx1.java.
Complete the AssEx1.java class as instructed in the comments within the file. Do not change the main method in any way or include any package declaration. You should include any import statements necessary for me to run the program from the command line thus:
> javac AssEx1.java
> java AssEx1 "birds.txt"
You may add helper methods if you need to, but any unnecessary complexity (of code) will be penalised.
When you are happy with your class, run it and store the output in a pdf document called AssEx1_output.pdf (remove any additional print statements you may have added to your methods for testing purposes first). You should include your name and matriculation number at the top of this document.
The file exampleOutput.pdf which I generated using a different input text file (one related to dogs rather than birds) will illustrate the exact form. of the output required. You can use whichever font you like.
Full submission instructions will be included at the end of this document, but for this part of the exercise you will submit your two files: AssEx1.java and AssEx1_output.pdf.
2. [15 marks] 
This part of the exercise is to show that you understand:
 the difference between an algorithm and its Java implementation, and
 how to manipulate Doubly Linked Lists
2.1 [10 marks] Devise algorithms to do the following:
o Insert a new node into the middle (i.e. if there are n nodes in total, the new one should be inserted in such a way that there are ⌊n/2⌋ nodes in front of it) of a linked list L with first node first and last node last. Note that the notation ⌊n⌋ is used to represent the floor function, i.e. the integer part of a real number.
For example, if L consists of 10 nodes, the new one would be inserted such that there are 5 nodes before and 5 nodes after it. On the other hand, if L consists of 11 nodes, the new one would be inserted such that there are代 写Algorithms & Data Structures (IT+) Assessed Exercise (2024–2025)Java
代做程序编程语言 5 nodes in front of it and 6 nodes after it.
o Delete every alternate node from a linked list L with first node first. For example, if L consists of nodes containing the following strings:
ant, bat, cat, dog, elephant, flamingo, giraffe
your algorithm should change the list so that it now consists only of the nodes containing the strings:
ant, cat, elephant, giraffe
Use a suitable text processing package to create a document:
AssEx2Algorithms.pdf containing, for each algorithm:
o a picture illustrating your algorithm (this may be a photograph/scan of a pen and paper drawing),
o a formal step-by-step algorithm written in English,
o an analysis of the complexity of your algorithm, in terms of the lengths of any linked lists involved.
2.2 [5 marks] Implement your algorithms as Java methods by following the instructions below. You have been provided with an outline Java class for this part of the exercise:
AssessmentDLL_outline.java.
You should:
o make a copy of this file and rename it:
AssessmentDLL.java.
o complete the AssessmentDLL.java class as instructed in the comments within the file. You must:
o not change the provided methods in any way
o not include any package declaration
o not change the names of any methods in the class.
But you may include additional helper methods if necessary.
o Create your own test program, AssExTest.java, say, which uses your class (but you will not submit this class). I should be able to run my own test program, which will use your AssessmentDLL.java class, from the command line thus:
> javac AssessmentDLL.java
> javac AssExTest.java
> java AssExTest
For this part of the exercise, you will submit your two files:
AssessmentDLL.java and AssEx2Algorithms.pdf.
Submission 
By the deadline stated above, you must submit your deliverables through the ADS (IT+) Moodle page. (Click “Assessed exercise submission”.) The deliverables are all the files requested in parts 1 and 2, namely:
 Part 1: AssEx1.java and AssEx1_output.pdf
 Part 2: AssessmentDLL.java and
AssEx2Algorithms.pdf
Do not submit any additional files.
Your files should be contained in a single (zipped) folder. Penalties will be applied for failure to comply with submission instructions (e.g. including additional files, package statements, changing provided methods, naming files not according to instructions, etc.). These include the instructions contained withing the comments of the outline Java files AssEx1_outline.java and AssessmentDLL_outline.java.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
