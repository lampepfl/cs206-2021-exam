# CS-206: Midterm Exam

Wednesday, 14 April 2021, 14:15 - 17:00

This exam is open book in the sense that you are allowed to consult the PDF slides for all lectures in this course and the Functional Programming course. The exam will cover all the material seen in the class up to week 6 (included).

The exam consists of four programming assignments that you should solve using the usual tools from the class (git, sbt, and your favorite text editor). In addition to problem statements, each problem comes with a set of automated tests, just like for the labs. Those tests will be used to compute your grade. Make sure to follow any additional requirements listed in the problem statement. Some of those requirements might not be covered by our automated tests and will be graded manually.

The TAs will be available on Discord during the exam. In case you have questions or need help, don’t hesitate to contact one of the TAs using Discord’s private messages or our public Discord channel. It is your responsibility to ensure that you have access to reliable internet connection, hardware, and software for the duration of the exam. Also make sure that you are comfortable using the usual tools from the class, so that you can focus on the exam.

Your answers are submitted by pushing your code on GitLab. At the end of the exam, you will be given an extra 15 minutes to make sure that your solutions are uploaded and to handle any potential technical difficulties. Commits pushed after 17:15 will not be graded.

*No cheating*: Each student must solve the exam individually. Consulting with anyone except the teaching staff of this course during the exam, copying solutions from the Internet, or making your solution available to anyone is considered cheating and a reason for disciplinary action. We will use plagiarism detection tools on your solutions. We reserve the right to follow up with some of you on Zoom after the scheduled slot and ask you about solutions to your or similar questions, whether or not we suspect you cheated; this possibility is a normal part of the examination this year.

## How to obtain questions

Assignments will be available online at the start of the exam. Please clone the following repository to have access to problem statements in case you lose your internet connection:

```
git clone https://github.com/lampepfl/cs206-2021-exam
```

Each assignment is published similarly to labs: the problem statements are given as markdown files in the following directory: https://github.com/lampepfl/cs206-2021-exam/tree/main/midterm; the code skeleton for each problem is available in a separate branch of your private GitLab repository. Each student will receive a list of links to their questions before the exam by email.

## How to submit questions

Your answers are submitted by pushing your code on GitLab, just like the labs. After you submit your solution, you will receive a preliminary grade for that question. This information will be available in the GitLab CI. The tests executed on the CI are identical to those you can run locally. For detailed information, refer to labs submission instructions: https://gitlab.epfl.ch/lamp/cs206/-/blob/master/labs/grading-and-submission.md#committing-and-pushing-your-code.

You are allowed to push multiple times for the same question (only the last commit will be considered).

## How to run tests

Refer to labs submission instructions for detailed information on how to run tests: https://gitlab.epfl.ch/lamp/cs206/-/blob/master/labs/grading-and-submission.md#local-tests-and-grading

## Recommended workflow summary

After you have obtained a question, do the following:

1. read the requirements carefully
2. write the solution taking the requirements into account
3. make sure your solution compiles
4. make sure your solution passes the local tests on your machine; if it does not, repeat previous steps
5. submit your solution using git
6. start working on the next question

If you feel you are spending more time on the question and will likely not solve it, then go to step 6 to get a chance at solving the subsequent question. This way you will still get some points for the partially solved question. If you have time, you can go back to it later.

## How we grade your exam

Each question is worth 10 points. If you do not manage to solve a particular question, you can skip to the next one. This way you will get some points for partially correct solutions, as indicated in the grader output (a grade of 9/10 gives you 9 points for that question). An entire question can never be assigned a negative number of points; the least amount of points is zero.

You need to push your code to GitLab to receive a grade. If you forget to submit your solution before 17:15, you will recieve zero points for that question.
