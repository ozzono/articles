# Critique and comment on technical validation during the recruitment

In this article, I will address the leading practices for validating the skills and technical knowledge of programmers and software developers during the recruitment process.

##### Leia em português [aqui](./skill-assesment_pt.md)

## Table of contents

- Technical Validation tools:

- [Technical validation tool](#technical-validation-tool)

- [An entire project shared through a Git repository](#an-entire-project-shared-through-a-git-repository)

- [Live coding interview](#live-coding-interview)

- [Technical Interview](#technical-interview)

- [Edit code in an existing project](#edit-code-in-an-existing-project)

- [Assessment of public repositories](#assessment-of-public-repositories)
- [Opinion](#opinion)
- [To recruiters](#to-recruiters)
- [Technical validation tool](#technical-validation-tool)

[back to the top](#table-of-contents)

## Technical validation tool

### HackerRank and similar tools

Help evaluate the technical knowledge of programmers and software developers. However, the strict time restriction present in most tests can be a problem, as it prevents the candidate from delivering the work and, consequently, does not allow for evaluating their performance. At least some platforms enable one to complete the tests within 24 hours, with a specific duration for each test. This approach provides greater flexibility and avoids continuous tests of 120 minutes, for example. Although most tests are exciting and challenging, both the type of problem and the time constraint do not match the daily reality of those working with programming and therefore do not adequately assess the candidate's skills.

|Pros|Cons|
|-|-|
|Tests are usualy quick.|There is strict time limit and some test can add up to 180m.|
|It may include database tests in addition to code and logic tests.|The test is limited, making it superficial and insufficient.|
||The test is conducted online, which could be better.|
||**Does not** assess skills used in the daily routine of most programmers or companies|

[back to the top](#table-of-contents)

## An entire project shared through a Git repository

Also known only as a code challenge, it's a flexible way to evaluate candidates' technical knowledge. The technical team provides a description of what should be developed and the candidate shares the result using code versioning tools like Github. However, this comprehensive evaluation can be slow and take around a week. This approach can discourage candidates and generate workload, especially if they are in simultaneous recruitment processes. Additionally, the candidate may have developed something similar in a previous challenge, which can make the evaluation less effective. Therefore, it's recommended to check the candidate's GitHub history before starting the process, as described here. Analyzing the repositories shared by the candidate can make the recruitment process much faster without giving up technical requirements.

|Pros|Cons|
|-|-|
|Huge flexibility.|Slow assessment.|
|Ability to assess in-depth knowledge of only the topics of interest.|Possible demotivation due to delay.|
||A possible feeling of wasted time at the end of the evaluation.|
||Possible overload on the candidate.|
||The candidate may have already done something similar before and repeat and adapt.|

[back to the top](#table-of-contents)

## Live coding interview

A method of challenge in which the candidate is invited to write code along with their evaluators and as the test is done, the evaluator asks key questions to assess the candidate's level of knowledge and fluency in the technology in question. Interviews like this are quick and would be similar to a mix between a [Technical Interview](#technical-interview) and a [Full Project](#an-entire-project-shared-through-a-git-repository), given the complexity and time of the challenge. The live assessment can also help assess the candidate's ability to communicate and work in a team and their ability to handle pressure and adaptability. However, the evaluator must have effective communication and feedback skills to avoid making the candidate feel uncomfortable or too pressured. Additionally, it is recommended that the challenge is designed to be realistic and consistent with the daily work of a programmer to provide an accurate and fair assessment.
Because it is a limited time option, it can also become inconsistent with workday.

|Pros|Cons|
|-|-|
|Relatively short interview|Due to the time constraint, it becomes difficult to address advanced technical aspects|
|Assesses the ability to handle pressure and adaptability|Requires caution from the evaluator to avoid excessive pressure on the candidate.|
||It may not make sense if pair programming is not part of the company's developers' daily routine.|
||Generally, real tasks do not have a deadline in minutes or hours, making them more flexible than what is addressed in the test.|

[back to the top](#table-of-contents)

## Technical Interview

A direct interview with a person recognized by the company for having more experience and knowledge of technology and development. As a rule, it addresses the technologies and challenges that are part of the company's daily routine.

The technical interview is usually conducted by the so-called tech lead, a professional with more career time and experience in the technologies and problems that are part of the company's business. Unfortunately, this interview needs to be more objective and reflect the accurate level of knowledge and experience of the candidate, which can lead to hiring doomed to failure and frustration for all parties, as well as the early dismissal of a good candidate.

In turn, the interviewer has the opportunity to address challenges that are impossible to contemplate in a code challenge, such as concurrency, optimized use of resources, specific challenges of the company, and security under various aspects among many others.

|Pros|Cons|
|-|-|
|Typically short, lasting at most 1 hour.|Depends on the subjective interpretation of the interviewer.|
|Allows the interviewer to ask questions that are typically not covered in code challenges.||

[back to the top](#table-of-contents)

## Edit code in an existing project

Editing code that has already been started and is functional, implementing new business rules or features according to the description of the challenge.

In this format, the candidate receives a ready and active repository, and it is up to them to implement something new as requested. This challenge is the closest to the day-to-day development where it is necessary to navigate through legacy code and, more importantly, understand what is written and find a way to implement what is asked. If well-designed, there will be a need to understand various technologies and concepts such as git, databases, automated tests, or REST, as well as development paradigms such as MVC or maybe some design pattern.

This format would also be a hybrid between online [technical assessment tools](#technical-validation-tool) since it does not require to build a project from scratch and [shared code challenge](#an-entire-project-shared-through-a-git-repository) since it is close to the day-to-day of the company. It, therefore, encompasses the advantages of both approaches.

Because it is the most directed type of validation, it requires care to prevent it from becoming a superficial test.

|Pros|Cons|
|-|-|
|The challenge is usually quick, lasting on average 1 hour.|Too directed tests may be superficial|
|Opportunity to evaluate important related knowledge such as git, databases, REST, MVC, design patterns, automated tests.||
|Assesses the ability to understand legacy code and implement new features.||

[back to the top](#table-of-contents)

## Assessment of public repositories

Access and evaluate public repositories written and maintained by the candidate to gauge their knowledge depth. In this format, the candidate does not do anything, as supposedly everything is already done in projects they have worked on and made public on their profile on platforms such as GitHub. It is, therefore, up to a tech lead to read the code and validate that the candidate has the necessary knowledge. The result is similar to the [code challenge](#an-entire-project-shared-through-a-git-repository), as it can be precisely a project derived from a previous challenge.
If it is needed to gauge any additional skills or knowledge, a targeted test can be done on the specific topic.

|Pros|Cons|
|-|-|
|Assessment without candidate effort required.||
|If necessary, allows for the assessment of specific skill or knowledge only.||
|Quick assessment.||

[back to the top](#table-of-contents)

## To recruiters

A poor performance in a validation test, especially the more superficial ones, does not mean that the candidate lacks sufficient skills or knowledge. Moreover, it is important to know what requirements are truly necessary for the job and which are secondary. Today, there are many ways to solve complex problems thanks to the abundance of available sources of consolidated and shared knowledge. Therefore, it is an important skill for a software developer to know how to ask the right question in order to find the answer they need, making it unnecessary to have everything at their fingertips.

Moreover, to recruiters and tech leads who participate in selection processes, an invitation is extended for them to include, in addition to applying any of the technical validation formats, also a feedback, the famous feedback, in this case technical feedback, in order for the candidate to be able to, if applicable, know their own mistakes and also better prepare for the next opportunities that arise. This feedback does not need to be detailed and complete; it can be just a summary or even the notes made by the interviewer that led them to conclude negatively about the candidate.

[back to the top](#table-of-contents)

## Opinion

As I have already been submitted to all these types of assessment, I believe that the best way to assess the knowledge of a software developer consists the sum of a technical test followed by a technical interview so that it is possible to determine both fluency in the language in which intends to work on understanding the most common challenges when maintaining a code with high complexity and demand, as well as allowing the review of the submitted code to know how the candidate reasons and solves problems.

I would choose repository [editing with legacy code](#edit-code-in-an-existing-project) or [assessment of public shared repositories](#an-entire-project-shared-through-a-git-repository) maintained by the candidate followed by a technical interview with one or more tech leads. Submitting to a code challenge with a project combined with a [technical interview](#technical-interview) focused on commenting on the shared code also allows you to understand how much the candidate understands about the code he wrote and alternatives to what was presented.

[back to the top](#table-of-contents)
