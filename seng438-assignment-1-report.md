>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group \#:   10    |   |
|-----------------|---|
| Student Names:  | Mohammad Mahtab Khan [ 30102408 ] |
|                 |  Redwanul Islam [ 30103527 ] |
|                 |  Rahat Islam [ 30095015 ] |
|                 |  Zeeshan Chougle [ 30094417 ] |

**Table of Contents**

[1 Introduction](#Introduction)

[2 High-level description of the exploratory testing plan](#High-level-description-of-the-exploratory-testing-plan)

[3 Comparison of exploratory and manual functional testing](#Comparison-of-exploratory-and-manual-functional-testing)

[4 Notes and discussion of the peer reviews of defect reports](#Notes-and-discussion-of-the-peer-reviews-of-defect-reports)

[5 How the pair testing was managed and team work/effort was
divided](#how-the-pair-testing-was-managed-and-team-workeffort-was-divided)

[6 Difficulties encountered, challenges overcome, and lessons
learned](#difficulties-encountered-challenges-overcome-and-lessons-learned)

[7 Comments/feedback on the lab and lab document itself](#commentsfeedback-on-the-lab-and-lab-document-itself)

# Introduction

<p>The main purposes of this assignment were to familiarise with the system under test (SUT) and the defect tracking system, and the 3 different types of testing methods (Exploratory, Manual Scripted, and Regression Testing). 
The SUT is an ATM simulation system with two versions, 1.0 and 1.1. We used backlog (a defect tracking system) to report issues concerning the system under test (SUT).
    </p>
<p>

During the exploratory testing phase, we worked in pair testing to plan our manual testing strategies and execute it on the SUT. Upon reaching the manual scripted testing phase, we used a predefined test suit containing 40 test cases to test the SUT and recorded defects in backlog. Finally, we performed regression testing on the updated version of the SUT (1.1) using the same 40 test cases and reported differing system behaviour in backlog.

</p>


# High-level description of the exploratory testing plan

<p>
    Exploratory testing is a form of software testing in which the actual test cases the tester will perform aren’t defined beforehand. Testers create a test idea to have a sense of what they are looking for and start exploring the software. Testers make spontaneous decisions of what features and actions to test, thus reflecting the individual interests of end-users.
</p>

<p>
We began our exploratory testing by familiarising ourselves with the SUT requirements. Then we created multiple plans to test the SUT. Our strategy was to first identify the functions to be tested. Then our approach was to test most functions to check if their basic functionality is working. Moreover, our plan was to test the most common paths that users of the system will take. We reported every defect on backlog by creating an issue and adding the defect description.

</p>

# Comparison of exploratory and manual functional testing

<p>
    Exploratory testing comes as a natural approach to test a program. Essentially, you are not behaving like a programmer, but a consumer of a product. When looking at the program from the eyes of a consumer, we were able to find bugs that would inhibit us from accomplishing our tasks. The bugs were much faster to find, and often times they were the major bugs that were detrimental to the product.
    </p>
<p>

Manual testing on the other hand helped us find both major and minor bugs through a more meticulous approach. In the end of the assignment, most of our bugs found in exploratory testing also came up in the manual functional tests. That goes to show that when manual scripted tests are very extensive, they can find all the bugs from an exploratory test. The caveat is that is just takes so much time. Further, despite the 40 tests, the test suite was unable to detect errors in the money market balance inquiry, where where this was found quickly in exploratory tests. This goes to show that to fully cover a program with manual tests can be very exhaustive, which is why exploratory testing is still important to detect major bugs across the entire system.


</p>

# Notes and discussion of the peer reviews of defect reports

<p>
While peer reviewing the defect reports created, we realised that everyone created the defect reports without using a standardised template. This meant that the defect reports looked a little different. In hindsight, it would probably be a good idea to come up with a standardised template for future defect reports. Moreover, we also noticed that we used different naming schemes for the “Subject” field. Regardless, the content is understandable even though we used our own templates and naming schemes.
</p>

# How the pair testing was managed and team work/effort was divided 

<p>
Initially, we decided to split the testing process amongst the 4 members to speed up the testing process, each testing different features of the ATM Software individually as a part of exploratory testing. However, when we moved on to manual testing we noticed that there were some key issues which we had overlooked over our initial testing phase which helped us realise the importance of “Pair Testing” as testing with the supervision of another member greatly reduced the chances of missing or overlooking fundamental flaws.So, we performed the MST and Regression testing in groups of 2 wherein the first group tested cases from 1-20 and second group tested cases from 21-40 in Appendix C. Finally, each group reviewed the other groups work eliminating any chances of missing a fundamental flaw with the ATM software. We used the first assignment as an opportunity to learn about each person’s strengths and weaknesses, and in future assignments we hope to utilise this knowledge in order to further streamline our group work.

</p>

# Difficulties encountered, challenges overcome, and lessons learned


1. Initially, we decided to split the testing process amongst the 4 members to speed up the testing process, each testing different features of the ATM Software individually as a part of exploratory testing. However, when we moved on to manual testing we noticed that there were some key issues which we had overlooked over our initial testing phase which helped us realise the importance of “Pair Testing” as testing with the supervision of another member greatly reduced the chances of missing or overlooking fundamental flaws.
 
2. Secondly, we learnt the importance of not only testing each different feature of the software but also trying these features with different inputs (edge cases) which can potentially lead to bug detection in certain cases. For instance, Card #2 did not have a Savings account so trying any transaction for this specific card type could have a lead to a potential bug when performing a transaction although the feature worked successfully for Card#1 (has a savings account) which is something we overlooked during exploratory testing.
 
 3. We also realised the importance of having descriptive and well-worded bug reports. We planned to work in pair testing, wherein group 1 tested MST cases from 1-20 and group 2 tested cases from 21-40. However, our initial bug reports had very brief and unclear descriptions which made it hard for the other group to review each other's reports as they did not provide a clear idea of the defect detected. We fixed this by providing detailed and clear description for each bug which helped us realise the importance of well-structured bug reports when testing in teams.


# Comments/feedback on the lab and lab document itself

This assignment has greatly helped us familiarise with the fundamentals of exploratory, manual and regression testing and has also helped provide hands-on experience on the usage of Backlog software for maintaining bug reports and various aspects associated with logging and documenting software tests. Moreover, It has also provided us with an opportunity to learn about each person’s strengths and weaknesses, and in future assignments we hope to utilise this knowledge in order to further streamline our group work. Finally, the lab document was a great way to summarize and document our work throughout the lab which could serve as a great reference tool for future assignments.
