# interviewQuestions
### Interviews questions for QA Engineering and related areas


```text
Introduction:
Interviewer introduction && vacant role that we are interviewing for
Candidate introduction && shorten history flashback

https://www.mytectra.com/interview-question/top-appium-interview-questions-2017/

https://www.testingexcellence.com/agile-testing-interview-questions/


Creativity & Innovations:
Developing solutions for potential problems OR new ideas (looking @ things from 2nd perspective).

Potentials questions:
1- What’s your best idea you came up in your current role. (this question leads to):
What was the outcome for your idea?
Did you face any issues during the implementation for this idea? (this question leads to):
             How did you overcome this problem/issue?
Tell me about your automation frameworks


=============================================
People & Management:
Ability to set clear achievable objectives for your team and how to motivate your members.

Potentials questions:
1- Please describe me how you set goals for your team members. (this question leads to):
Could you please help by giving an example for a real life scenario?
Did you ever get a negative feedback? And how you did overcome that?


=============================================
Customer/Client Focus:
Prepared to give 101% effort at some point to achieve company's goal. (extra mile)

Potentials questions:
1- At some critical point are you willing to that extra push to reach team goal?. (this question leads to):
So when you say yes? Then you have some points you can help with, could you please help by giving an example?
What factors you think will make a project passed to LIVE stage?



Have you been involved in test estimation and how do you do it?
What is your acceptance criteria
What tools and why








MAIN QUESTIONS (General testing):
=============================================
FIRST
What type of test you perform for a web based application
You came across TESTING_TYPE, can you help by giving an example for TESTING_TYPE scenario?
--------------------------
SECOND
Main software testing challenges
Lag on BR & TR knowledge
Unstable testing environments
Different developers for same fix
Delay in delivery for fix
Requirements changes (late stages).
--------------------------
THIRD
Tell me about your QA roles in SDLC (leads to question):
When QA will be involved?
--------------------------
FOURTH
Login is not working? What’s your troubleshooting will be 
My answer will be near by:
1- Try to reproduce the issue on required environment
2- Check console while testing for errors to stand if it’s a FE or BE issue
3- In case of FE, then compatibility testing for bug reporting accuracy 
4- Create a ticket and assign a priority and severity depending on the situation.
--------------------------
FIFTH
How to handle a situation in which you don’t have time for full regression testing?
My answer will be near by:
1- i will perform a quick ad-hoc test to stand for the actual implementation for the doc that i was reading
2- first test to perform is a sanity test in which is the test to cover product’s blocker and critical areas
3- UI checks while running the tests
--------------------------
SEXTH
Equivalence and boundaries testing for an input field 1-10 entries
My answer will be:
Eq analysis will generate 3 test cases(0-random-11)
Bo analysis will generate 3 set of test cases (1-10) (0-9) (2-11)









--------------------------
SEVENTH
Help me with some special test cases for mobile App product?

App behavior in background
App behavior with some heavy other Apps
Simulate end users update scenario
App behavior interrupted with a phone call
App integration test with related web platform
App performance such as speed...etc
App behavior while connection lost
App behavior using 3/4G connection
App behavior using low speed connection
--------------------------
EIGHTH
Tell me about verification and validation (leads to)
Can you help by giving some examples?
What impact did these knowledge make for QA officer?
--------------------------
NINTH
How do you overcome bad BUGs fixes (deploying fix many times with same results)
Will you help developer? Yes? How?
--------------------------
TEN
What is the most difficult change you made in your QA job
How did you overcome this?
--------------------------
ELEVEN
Scenario and please give me a test case for each testing type
How did you overcome this?

--------------------------
TWELVE
What benefits as QA engineers we can get from traceability matrix
Mainly we can reach higher test coverage as we are addressing a test cases for each BR and TR through this matrix.
--------------------------
THIRTEEN
ALPHA && BETA // What is compatibility testing??
Etc…
--------------------------
FOURTEEN
Give me your test cases for a basic login form
Negative testing
Positive testing
Fields edges testing
Invalid entries
Spacing trimming

MAIN QUESTIONS (Automation):
=============================================
FIRST
What tools are you using for automation testing and daily tech
-----------------------------------
SECOND
Main challenges in automation
Test scripts maintainability
Lag of qualified testers
Automation will find loads of issues and BUGs
-----------------------------------
THIRD
What kind of assertion lib you are using to assert your testing?
BDD?  chai
-----------------------------------
FOURTH
Are you familiar with selenium? What is it?
Selenium is a automation tool in which you can write your tests using different programming languages
-----------------------------------
FIFTH
How you can locate elements for writing test scripts
-----------------------------------
SIXTH
Can i read your test scripts easily
My answer will be near by:
Yes, my scripts following some standards such as comments/annotations for each code block or test scenario 
-----------------------------------
Seventh
What criteria do you consider for automation
1- How often does the test need to be executed? i.e. is that going to be a regression test? Sometimes the test will need to be executed once, but with a large set of data
2- How much time does automating this test will save me so that I can use my time in exploratory testing
3- How important is the test to the business; i.e. is the test scenario a typical user journey through the application
4- How complex is it to automate the test and how likely is it that the complexity doesn’t cause many false positives which increases results analysis time?
5- How likely is it that this test catches a defect?

-----------------------------------
Eight
What tests should not be automated
1- Usability Testing – at times this can be an impossible task to perform by automation as the computer cannot efficiently judge if the system is of any use to its users
2- Tests that only need to be executed once – unless the same test needs to be executed for a large dataset then it makes sense to automate
3- Tests without predictable results – test automation should give us confidence in the results of the tests. If there are intermittent failures then the tests cannot be reliable and cannot be dependent on
4- Tests that need to be verified visually
-----------------------------------
How you can resolve a conflict in git
How to create a .git directory in you local
What’s git diff function
Difference between git diff and git status

```


```text
1) How well do you handle ambiguity?

Test cases are not always straight-forward and QA Engineers will need to act on their personal judgement. They need to feel comfortable with ambiguity.
```

```textmate
2) What is your mentality toward automating tests that are currently being done manually?

Automating test cases brings numerous benefits. Automation saves time and reduces human error. QA engineers should recognize the value in automation.
```

```youtrack
3) Explain how you distinguish a symptom vs. a cause when testing.

Often times within the QA process, test cases fail. But why are they failing? This can be tricky. A great QA engineer is able to provide exact reasons to the developer, rather than simply saying a test case “failed”.
```

```text
4) Do you feel comfortable standing up to developers who disagree with your results?

In some situations, reporting failures can be a delicate process. Perhaps a developer spent a lot of time on some code which does not exactly meet specifications. QA engineers need to be able to stand up for what they know is right.
```

```text
5) Are you willing to cut corners to save time?

The correct answer is NO. All test cases need to be run, and making assumptions frequently leads to issues down the road.
```

```text
6) Can you explain the SDLC and Agile methodology?

QA engineers must understand their role and where it fits into the ecosystem.
```

```text
7) Explain your attitude toward documentation. Do you believe more is better? Why or why not?

This is a trick question because more documentation is not always better. In fact, it can be detrimental. Documentation needs to be thorough, but still efficient as possible. If there is too much documentation, important details can be missed.
```

```text
8) How do you go about learning a new product?

This is perhaps the biggest challenge of being a QA engineer. They need to be comfortable and patient with learning complex software. They should be prepared to ask a lot of questions.
```

```text
9) How well do you work with others?

Many QA teams have team members who are from all corners of the world. QA engineers must be comfortable communicating with people of all backgrounds and all levels of language proficiency.
```

```text
10) Do you see yourself as a perfectionist?

Great QA engineers are perfectionists. Their job is to ensure that all of the software they test meets or exceeds quality standards, and sloppy work is only going to lead to trouble further down the line.

Download our free guide to understanding agile testing methodologies.
```

```text
11) How well do you work under pressure and with deadlines?

Testing usually comes at the end of the SDLC and testing can be viewed as a bottleneck, so being able to perform under tight deadlines and pressure is important.
```

```text
12) What experience do you have with developing corner cases?

This question will help you to figure out if your tester is willing to dig for different test case scenarios that might not be as intuitive or clear up front
```

```text
13) How do you keep up with current technology trends

Staying up to date on industry news and trends is important in order for you team to keep up with evolving technology and best practices changes.  It also shows how much they like their job!
```

```text
14) What motivates you?

There are several potential answers to this question. Company culture will play a large part in differentiating a good from bad answer.   For instance, if teamwork is important within the product team, a candidate who is driven by internal competition might not be the best fit.
```

```text
15) What are your ultimate career aspirations?

It is important to learn what your candidate hopes to be in the next year, or 3 years.   If the candidate desires a career path you can’t provide, you might be interviewing again sooner than you’d like.
```

```text
16) How would a friend describe you in one sentence?

Sometimes this question pulls out unique personality qualities that you might not discover from traditional work focused questions.  
```

```text
17) What made you want to get into testing?

Figuring out how your job candidate achieved their current career status can uncover a lot around their ambitions and aspirations.
```

```text
18) What do you think our company could do better?

This interview question helps you to uncover how much research the candidate did before meeting with you, and it demonstrates their ability to think on the spot.
```

```text
19) Why do you want to work for us?

The best way to learn if your candidate is excited and passionate about this job opportunity.  
```

```text
20) What testing methods are you familiar with?  Do you have a favorite?

It is important to hire a well rounded Test Engineer who is familiar with several different types of testing or find one who is willing to learn.
```


# Job Description:

```text
QA Engineer Responsibilities Includes:
Participate and review requirements, specifications during sprint planning and provide any extra information or details in which will ensure test coverage.
Creating detailed, comprehensive and well-structured test plans and test cases.
Estimating, prioritizing, planning and coordinating testing activities during SDLC.
Identify, troubleshoot, and document issues thoroughly during bugs tracking.
Perform Regression, Functional, Usability, Compatibility testing to support development team.
Provide full support for development team whenever needed for reproducing purposes.
Provide Automation scripts for assigned tickets/tasks.
Manage the respective team and act as a problem solver for.
Ability to distribute tasks as per defined priority and severity metrics and follow up

Desired skills:

4+ Year of solid experience in QA
Strong knowledge of Software QA methodologies, testing types, tools and processes.
Hands-on experience with both gray box and black box testing.
Experience in writing clear, concise and comprehensive test plans and test cases.
Appium knowledge and hands-on experience.
codeception PHP framework is a huge plus.
Element locating methodologies.
GitHub knowledge and hands-on experience.
Analytical thinking.
Attention to details.
Problem analysis and problem solving.
Teamwork.
Project tracking tools
Manual and automated experience.
CI and CD tools and hands-on
Travel and Tourism experience is a plus


Education/University degree:
Degree in Computer Science, Engineering or a related subject.

```