# Reflection Questions

Answer these questions thoroughly, using examples from your code. Good answers will be 1-2 paragraphs that cite specific code examples and show a meaningful reflection on how your development went, and how it could be improved in the future.

## Question 1

In part 2, you now have to support two different inputs, CSV and XLSX. Imagine we asked you to also support reading in another file format, such as JSON. How much code would you need to add/change to enable this? Cite specific existing functions/classes that would need to change.

## Answer

According to our code, we would have to write a very significant amount of code. The way our program currently runs, we check whether the file is a XLSX or CSV file, and then read the file and execute the appropriate method. For example, if the file is a CSV, our code reads that and then executes hamilton's method within one block of code. We would have to rearrange the structre of our code so that I would read each file separately, according to the format of each specific file, and then choose whether to execute hamilton's method or huntington hill's method. Our code would then be structured as a series of if statements checking if the file is an XLSX, CSV, JSON, etc. which then read those files. Then there would be a separate block of code after that that executes the appropriate method. 

## Question 2

Looking back, which part was more difficult? Part 1, where you had to start from scratch, or Part 2, where you had to change existing code. Explain your answer, citing any specific challenges. In hindsight, would you do anything differently?

## Answer

We found Part A/B to be the most difficult becuase we had to get accustomed to file reading. Once we conceptually understood how to read CSV files, the algorithm writing itself was not particularly difficult for us. As for Part C, going back through our code and making it applicable for a XLSX file included many of the procedures we used in Part A/B. While reading an XLSX file is somewhat different from reading a CSV file, we still found that the process of reading these files was similar, and thus easier the second time around. 

