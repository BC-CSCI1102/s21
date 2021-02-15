# CSCI 1102 Computer Science 2

### Spring 2021

---

## Grading

Like most CS courses, CSCI 1102 is very much a "learn by doing" course. Reflecting this, grades will emphasize the problem sets. Grades will be computed on a 200 point scale. The points are distributed as follows:

+ 140 points over 10 problem sets;

+ 30 points over 3 quizzes;

+ 30 points for class and piazza participation;

Grades will be recorded on the Canvas website.

#### Notes:

+ Unless specified otherwise, problem sets must be submitted by pushing your repository to GitHub by midnight on the due date. NB: under no circumstances at all can code be submitted for grading by attaching it to an email message. An attempt to submit code via email probably won't receive a reply notifying the sender that the attempted submission failed.


+ Late problem sets will be penalized 20% each day.
+ Students missing an exam without prior permission of the instructor will receive a zero for that exam unless they provide a note from their doctor.
+ Any violation of the [university's policy on academic integrity](http://www.bc.edu/offices/stserv/academic/integrity.html) will result in a failing grade for the course.

#### Notes for problem set grading

Some general criteria for grading of problem sets in CSCI 1102. The percentages are rough guidelines for the TA staff. A percentage should be interpreted as being *additive*. For example, the score for a program that compiles correctly will receive between 40% and 50% credit for that. If it furthermore runs correctly, producing the correct output, it will receive an additional amount between 20% and 30% more credit. If it is also written well, it will receive another 20% to 30% credit.  A program that doesn't compile will perhaps receive 30% to 40% plus whatever might be gained in the "written well" category, it would receive no credit for running correctly.

The total score will be the sum of these 3 properties.

1. Does the program compile? If not, is it a syntax error? A type error? An undefined symbol? Would a small change make it compile? (40 - 50%)

2. Does the program run correctly? (20% - 30%)

3. Is the program well written? (20 - 30%)

   1. Is the code reasonably efficient? Time? Space?

   2. Are subtasks appropriately delegated to helper functions?

   3. Are the identifier names well chosen? They should be informative but not too long.

   4. Are reasonable symbolic names introduced for constants appearing in the program? Literals 0, 1, 0.0 and 1.1 are OK but otherwise symbols should be used. E.g., 

      ```java
      static final int MAXHEIGHT = 100;
      ```

   5. Are literals occuring in the program of the correct types for the operations applied to them? (Want to avoid depending on implicit compiler type conversions.) E.g., `double x = 2;` should be written as `double x = 2.0;`

   6. Is there a brief but informative header comment for the file?

   7. Are the appropriate declarations private and public?

   8. If files were opened, were they closed appropriately?

   9. If exceptions are raised, are they caught?

   10. If input is solicited from the user, is the user told what to provide?