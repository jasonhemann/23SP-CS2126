---
title: Syllabus
layout: single
toc: true
toc_label: "Syllabus Contents"
toc-depth: 2
to: pdf
standalone: true
documentclass: scrartcl
fontsize: 11pt
geometry:
  - margin=1in
linestretch: 1.15
mainfont: TeX Gyre Pagella
colorlinks: true
---

## Purpose and Objectives

This course teaches the design, implementation, analysis, and proper
application of abstract data types, data structures, and their
associated algorithms. We will explore a wide variety of data
structures both conceptually and concretely via implementation. The
class involves a significant hands-on programming component; you will
both implement and use several data structures yourself. To summarize,
in this course you will:

After this course you will know how to:

  1. Understand the basic data structures commonly used in computer
     science, such as arrays, linked lists, stacks, queues, trees, and
     graphs.
  1. Analyze the time and space complexity of different algorithms,
     and understand the trade-offs between different data structures
     and algorithms.
  1. Implement basic algorithms, such as sorting and searching. 
  1. Understand the principles of algorithm design, including
     divide-and-conquer, dynamic programming, and greedy algorithms.
  1. Use data structures and algorithms to solve real-world problems
     in an efficient and effective manner.

This syllabus contains policies and expectations I have established
for {{ site.title }}. Please read carefully the entire syllabus before
continuing in this course. I intend for these policies and
expectations to create a productive learning atmosphere for all
students. Unless you are prepared to abide by these policies and
expectations, you risk losing the opportunity to participate further
in the course. Policies and expectations as set forth in this syllabus
may be modified at any time by the course instructor. Notice of such
changes will be made by announcement in class, by written or email
notice, or by changes to this syllabus posted on the course website.

## Contact

The best way to get in contact for personal, private (FERPA, etc)
messages is via my email address [{{ site.author.emailaddr }}]({{
site.author.email }}). You should expect a response within 48 hours.
If I deem it even potentially useful to others, I will likely
anonymize your letter, answer it in an FAQ post to the class, and
forward you the link.

A great regular way to reach out for help is via my [office hours]({{
site.baseurl }}/office-hours/). Outside of my office hours, you should
not expect to reach me by MS Teams chat. I rarely check it outside of
those hours, and will likely not receive your message. 

## Additional Support

In addition to lecture, I provide the following additional resources
for students to avail themselves. Do consider taking regular advantage
of them.

### Scheduled Office Hours

Course personnel will make ourselves available for 4-6 hours of
[office hours]({{ site.baseurl}}/office-hours/) available weekly,
concentrated toward assignment due dates. If our office hours schedule
in particularly ill-suited to your class schedule, let me know and I
may be able to adjust them. 

### Textbooks

For the most part lectures are intended to be standalone, with the
textbook as a supplement for students who want to reinforce their
learning or go deeper into a topic. Some topics, however, will not be
covered directly in lecture; you will therefore need to read the
relevant textbook chapter to be able to understand what follows in
class. The Cormen text is @emph{very} comprehensive, but not always
easy to approach. Its emphasis is also more on the theoretical side of
things than this class's. Nonetheless, it is a useful book to have on
hand for computer scientists, and will supplement our in-class
activity. The "Grokking" text is intended to give you an easier segue
into some of those topics.

### Supplementary Videos

The great thing about learning elementary data structures and
algorithms is that so many of these topics are covered so well in
multiple mediums. I will link to a variety of supplementary videos
about various {{ site.title }}-related topics. I recommend watching
them early on; they offer valuable advice that can be quite helpful
in understanding assignments. 


## Assessment

This class uses a form of **Specifications Grading** (Nilson 2015). In
particular, it features mainly qualitative assessment, and does not
rely on points, percentages, and weighted averages to determine final
grades.

This is likely quite different from what you have seen in your other
classes, and will take some getting used to on your part. This system,
however, has a number of benefits for students---see [Why
Spec](why-specs**.

### Programming Assignments

This class features five programming homeworks and a final project
that has a programming component, which chiefly contribute to our
*functional correctness* learning objective. All programming
assignments and related sub-assignments (see below) must be done
individually; see our [Academic Integrity](#academic-integrity) policy
later.

When evaluating your programming submissions, I will give you feedback
regarding where they fell short as well as assign the following possible
outcomes:

- *Got it*: your submission implements the specification correctly and
  in full.
- *Almost there*: your submission implements the specification with minor mistakes or omissions.
- *On the way*: your submission has elements of a correct solution, but requires non-trivial further work to be correct and/or complete.
- *Not yet*: your submission requires significant further work.
- *Cannot assess*: I could not evaluate your submission as is; repairs are required before I can do so.

Specifics of what is required to achieve each outcome are included in the
handout for each assignment; our expectations are stated up front, no surprises.

### Resubmissions

Making mistakes and correcting them is a natural part of the learning process.
An outcome of *On the way* or *Not yet* is **NOT** a failure: it
just means you still have things to learn from this assignment. Our assignments
are *intentionally* challenging and our grading is *intentionally*
strict in order to maximize your learning; it's perfectly normal to not get
them entirely correct on the first try.

To give you the opportunity to incorporate our feedback and get credit
for your improved learning, I will allow you to resubmit the code
portion of each homework one week after the initial deadline. See
schedule at the end for exact dates. To determine final grades, I
will use the best of the two outcomes your submissions have achieved.

### Self-Evaluations

Each of the five programming homeworks will be followed by a
self-evaluation, due one week after the initial deadline.
Self-evaluations will consist of a few questions about the code you
turned in. Specifically, the code you turned in for the *first*
submission, *not* the resubmission, and *not* work in
progress towards the resubmission. You can download your original
submission from Blackboard if you overwrote/misplaced it.

The purpose of these self-evaluations is to evaluate your submissions
on *non-functional correctness*: desirable aspects of programs that go
beyond strictly producing correct answers. Aspects like efficiency,
testing, robustness, or factoring. In actual programming (i.e., not in
classes), these are *just as important* (if not *more so*) than raw
functional correctness. This class will give you opportunities to
cultivate these skills and habits as you work on assignments.


### Project Report

Instead of a self-evaluation, the final project will include a written report
where you will explain your design and provide rationales for your decisions.
More details are included in the final project handout.

The final project and its associated report contribute to our
*evaluation* and *integration* learning objectives.


### Worksheets

To evaluate specific aspects of our *theory* learning objective, we
will have two worksheet-style assignments.

To ensure everyone has a solid theoretical foundation, these
worksheets will be done as Blackboard quizzes with unlimited retries;
I encourage you to re-do them until you fully understand.


### Exams

We will have two in-person, on-paper midterm exams which will chiefly
assess our *theory* learning objective. No notes or electronics
(laptops, calculators, tablets, phones, smart watches, etc.) will be
allowed during exams. Specifics and logistical details will be
announced leading to each exam.


## Final Grades

Final letter grades will be determined as follows.

To help you keep track of your progress, please see the self-serve final grade
worksheet on Blackboard.

### Base Grade

Your *base grade* will be determined based on your performance on
homeworks and the final project:

|               |                 | A-        | B            | C+           | D          |
|               |                 | Excellent | Good         | Satisfactory | Poor       |
|---------------|-----------------|-----------|--------------|--------------|------------|
| Homeworks     | Got it          | all 5     | 3            | 2            | 1          |
|               | Almost there    | --        | 1            | 1            | 1          |
|               | On the way      | --        | 1            | 1            | 1          |
|               | Not Counted     | --        | --           | 1            | 2          |
|---------------|-----------------|-----------|--------------|--------------|------------|
| Final Project | Minimum outcome | Got it    | Almost there | On the way   | On the way |

For example, a student whose homework submissions earned 4 "Got it"
but one "On the way" and whose project submissions earned an "Almost
there" would earn a base grade of **B**.

Failing to meet the criteria for a D will result in a base grade of **F**.

**Warning** These criteria put a lot of importance on the final
project, which is intentional. I find that the learning experiences
from the project are especially valuable. This course therefore
considers it very important, and I want you to do so as well.

### Modifiers

This base grade will then get adjusted with *modifiers* based on your
performance in other aspects of the class. Each of these can either
increase your grade by a partial letter grade, leave your grade
unchanged, or decrease your grade by a partial letter grade. There are
a total of six possible modifiers:

|                  |           | Increase           | Unchanged                | Decrease                 |
| Worksheets       |           | Both 100%          | Both >= 80%              | Either < 80%             |
| Self evaluations | # 5/5s    | 4                  | --                       | --                       |
|                  | # >= 3/5s | --                 | >= 3                     | <= 2                     |
|                  | # <= 2/5s | <= 1               | <= 2                     | >= 3                     |
| Exam #1          |           | >= 80              | 70 <= score < 80         | < 70                     |
| Exam #2          |           | >= 50              | 40 <= score < 50         | < 40                     |
| Project program  |           | Above expectations | Meets expectations       | N/A                      |
| Project report   |           | Outstanding        | Minor errors / omissions | Major errors / omissions |

Here "Above expectations" means "a higher outcome than required for
your base grade."

Both worksheets are considered together to determine a single modifier; both
must meet the expected level. Similarly, all five self-evaluations are
considered together to determine the self-evaluation modifier. Each exam,
however, has its own modifier.

For example, suppose our hypothetical student who earned a base grade
of **B** got everything right on both worksheets (**Increase**),
submitted self-evaluations that earned three 5/5s and two 2/5s
(**Unchanged**), did poorly on Exam 1 (**Decrease**) but well on exam
2 (**Unchanged**), and wrote an excellent project report
(**Increase**). This would work out to an increase of one partial
letter grade, for a final grade of **B+**. Good job, hypothetical
student!

Going up one partial letter grade means going forward one step in this
sequence, and going down one letter grade means going backwards one
step.

The letter grade sequence "saturates" on either end: applying four +
modifiers to a base of **B** results in an **A**, and applying two -
modifiers to a base of **D** results in an **F**.


## Late Policy

Unless otherwise indicated assignments are due by **09:59 p.m.** on
their due date. Dropboxes will close automatically, and late is late.

To accommodate everyday slippage and minor life hiccups, each student
starts the class with three *late tokens*. To use it you will need to
email me your late submission. Each of these late tokens can be
exchanged for a two-day *no questions asked* extension to any
(non-exam) assignment, including resubmissions. Only one token can be
used per submission; i.e., two days is the maximum extension possible.
Late tokens will be used automatically when you submit late; you don't
need to reach out and ask for permission. This two-day extension will
begin from the moment you turn something in late; that is to say, your
extended due date will be 09:59 pm two calendar days after the
original due date. I will be tracking these late tokens for the class.

In a student runs out of tokens, I'll be in touch. Being occasionally
late is perfectly fine. Being consistently late, on the other hand,
may be a sign of deeper underlying issues: let's talk so we can figure
out the best way to help you.

Barring extreme circumstances, we will not grant further ad-hoc
extensions or accommodations. If you do end up in a situation that
would warrant additional flexibility, you must contact your dean of
students and have them contact me. They will help you coordinate
extensions and accomodations across all your classes, which will
ensure you get the support you need across the board, not just in this
class.


### Caveats

Even this amount of flexibility and self-control over your grades has
some limitations in penalties from small mistakes. It is your
responsibility to make sure the work you submit is as close a
reflection of your actual learning as possible, so I can get the best
picture I can of where you're at as a student. And in turn, so you can
get as much recognition as possible for your learning. Concretely,
this means:

- For programming assignments, being thorough in your testing to avoid
  silly mistakes, and taking full advantage of our feedback when
  working on resubmissions.

- For "one-shot" assessments like exams or self-evaluations, be very
  careful to read instructions completely and thoroughly, and ask for
  clarifications if need be. I can't assess your learning if you
  answer the wrong question.


## Academic Integrity

It's OK to meet with colleagues, form study groups, discuss
assignments with them, compare alternative approaches, go over
examples from textbooks or other sources. But it is never OK to share
code or homework solutions, or even to see each other's code or
solutions. What you turn in must be your own work. Copying (or even
studying) code, solution sets, test cases, materials from other
previous terms, etc., from anywhere (e.g., other people, web, GitHub)
is strictly prohibited. In this context, cheating refers to copying or
submitting as your own, with or without consent, someone else’s work
as your own. Misrepresentation of someone else’s work as one’s own is
a grave violation of academic ethics. This includes copying from
someone else answers to questions during an examination as well as
copying programs from internet sources. Plagiarism refers to using
someone else’s work in your own and not properly crediting the authors
of that work. This includes adapting someone else’s code to solve a
problem or write a program. The only exception to this rule applies to
course resources from the current semester such as starter code, code
from lectures, resource videos, or test cases you received in grading
feedback; you may use those as you see fit. Tools which automatically
generate code for you (e.g., GitHub copilot) are also strictly
prohibited. If you discuss your work with other people, please
acknowledge them by listing their names in your submission.

There will be no tolerance for cheating and plagiarism in
this course. Any material that is not entirely your own work needs to
be properly indicated and cited. This includes any work produced
together with fellow students. You MUST indicate any sources of help
outside of the course text(s) and your own work, including the names
of students with whom you worked, internet resources or other sources
of help. Failure to do so constitutes a violation of academic
integrity. When in doubt, ask your instructor. Violations of academic
integrity will lead to a score of zero on the offending assignment and
likely an immediately failing grade for the course.

It is also forbidden to share, post, or otherwise publicize course
materials. This includes (but is not limited to) homeworks, exams,
solutions, test cases, or your own submissions (in whole or in part).
This extends even after the semester ends; course material remains
private information which you may not share or reproduce.

## Academic Accommodations

It is the policy and practice of Seton Hall University to promote
inclusive learning environments. If you have a documented disability
you may be eligible for reasonable accommodations in compliance with
University policy, the Americans with Disabilities Act, Section 504 of
the Rehabilitation Act, and/or the New Jersey Law against
Discrimination. Please note, students are not permitted to negotiate
accommodations directly with professors. To request accommodations or
assistance, please self-identify with the Office for Disability
Support Services (DSS), Duffy Hall, Room 67 at the beginning of the
semester. For more information or to register for services, contact
DSS at (973) 313-6003 or by [e-mail](mailto:DSS@shu.edu), or visit
their [webpage](https://www.shu.edu/disability-support-services/index.cfm).

## Equity and Compliance

One of our responsibilities in supporting student learning 360° is to
help create a safe learning environment both in person and virtually.
You should carefully consult the university's [relevant information
and policies](https://www.shu.edu/title-ix/index.cfm), and if you have
or experience any violations of the above I encourage you to take full
advantage of the university resources.

It is also important that you know that federal regulations and
University policy require me to promptly convey any information about
certain kinds of misconduct known to me to our Title IX Coordinator.
In that event, they will work with a small number of others on campus
to ensure that appropriate measures are taken and resources are made
available to the student who may have been harmed. Protecting a
student’s privacy is of utmost concern, and all involved will only
share information with those that need to know to ensure the
University can respond and assist.

## Technology and Platforms

We will use a variety of tools and platforms to facilitate teaching
and learning over the semester. Please see the [technology page]({{
site.baseurl }}/tech/) for more details.

## Acknowledgments

Thanks over the years for inspiration and content from at least the
following: Dan Friedman, Shriram Krishnamurthi, Lindsey Kuper, Vincent
St-Amour, and Marco Morazán.

![In the syllabus]({{ site.baseurl }}/assets/images/syllabus.gif "Might just be worth checking.")
