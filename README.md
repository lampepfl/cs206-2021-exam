# CS-206: Final Exam

Saturday, 10 July 2021, 8:15 - 11:00

Rooms: SG1, AAC137, CO1 and CE6

*Exam rooms are equipped with computer plugs. Students must bring their own laptops that are capable of developing and locally testing assignments such as labs done during the semester. As a student, it is your responsibility to ensure that you have access to reliable hardware and software for the duration of the exam. Please make sure that you are comfortable using the usual tools from the class, so that you can focus on the exam. If you have trouble assuring access to a laptop and are willing to work with a rented one, please contact us ASAP and we will explore if we can get you one to use during the exam.*

This is an open-book exam. For example, you are allowed to consult the PDF slides for all lectures in this course and the Functional Programming course and do Google search. The final exam will cover all the material seen during the semester.

*No cheating*: Each student must solve the exam individually. Consulting with anyone except the teaching staff of this course during the exam, copying solutions from the Internet, or making your solution available to anyone is considered cheating and a reason for disciplinary action.

The exam consists of four programming assignments that you should solve using the usual tools from the class (git, sbt, and your favorite text editor). In addition to problem statements, each problem comes with a set of automated tests, just like for the labs. Those tests will be one component used to compute your grade. Make sure to follow any additional requirements listed in the problem statement. Some of those requirements might not be covered by our automated tests; the teaching staff will check and grade such requirements manually.

You should submit your answers by pushing your code to GitLab. At the end of the exam, you will have an additional 15 minutes to make sure that your solutions are uploaded and to handle any potential technical difficulties. Commits pushed after 11:15 will not count for the exam.

## How to obtain questions

Assignments will be available online at the start of the exam. Please clone the following repository to have access to problem statements in case you lose your internet connection:

```
git clone https://github.com/lampepfl/cs206-2021-exam
```

We have prepared each assignment similarly to labs: the problem statements are markdown files in the following directory: https://github.com/lampepfl/cs206-2021-exam/tree/main/final; the code skeleton for each problem is in a separate branch of your private GitLab repository.

## How to submit your solutions

You should submit your solutions by pushing your code to GitLab, just like for the labs. After you submit your solution, you will receive a preliminary grade for that question based on automated tests only. This information will be available in the GitLab CI. The tests executed on the CI are identical to those you can run locally. For detailed information, refer to lab submission instructions: https://gitlab.epfl.ch/lamp/cs206/-/blob/master/labs/grading-and-submission.md#committing-and-pushing-your-code.

You are allowed to push multiple times the solution of a question. Only the last commit within the deadline will be considered for your grade.

## How to run tests on your laptop

Refer to labs submission instructions for detailed information on how to run tests on your laptop: https://gitlab.epfl.ch/lamp/cs206/-/blob/master/labs/grading-and-submission.md#local-tests-and-grading

## Recommended workflow summary

After you obtained a question, do the following:

1. read the requirements carefully
2. write the solution taking the requirements into account
3. make sure that your solution compiles
4. make sure that your solution passes the local tests on your machine; if it does not, repeat previous steps
5. submit your solution using git
6. start working on another question

You can solve questions in any order. If you conclude that you have spent some time on the question and you estimate that you will likely not solve it, then go to step 6 to get a chance at solving other questions.

## How we grade your exam

Each question is worth 10 points. If you do not manage to solve a particular question, you can skip to another one. You will get some points for partially correct solutions, as indicated in the grader output (a grade of 9/10 gives you 9 points for that question). An entire question can never receive a negative number of points; the least amount of points is zero.

You need to push your code to GitLab to receive a grade. If you forget to submit a solution before 11:15, you will receive zero points for that question.

## Hardware setup

We expect that the exam can be done reasonably on a laptop with a laptop around 14" screen, FullHD resolution, and a reasonable CPU and RAM such that the price range with Windows or Linux OS remains under 1000 CHF. You are allowed to bring external keyboard and a mouse. If you feel that you need to bring a monitor, you can do that, but we do not allow you to run multiple screens: you can keep on at most one screen on during the exam (this includes laptop screens, external monitors, tablets such as ipads and others, or phones, to give a few examples). If you plan to attach an external monitor, you need to keep your laptop lid closed during the exam. If you need multiple power sockets during the exam, please bring a socket strip with a straight plug (not a 90 degree one), as we are only guaranteeing to provide one plug per student.  Whereas you could, in principle, use a (mini) desktop instead of a laptop, we do not recommend this.

 We do not provide wired ethernet and expect you to use EPFL or Eduroam WiFi network, which will be available. We do not provide any guarantees on the quality of mobile phone data connection in the exam rooms. Please test your setup at EPFL, including the WiFi connection, before the exam. Do not change your hardware setup during the exam, unless it becomes absolutely necessary for you to continue the work. We advise you to keep your setup as robust and simple as possible and focus on solving the questions.

If you anticipate difficultues in arranging your computer setup for the exam according to the above instructions, please contact us immediately to discuss possible solutions.
