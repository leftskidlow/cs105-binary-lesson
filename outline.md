# Binary Lesson Outline

## Resources
[Try Engineering: Binary](https://tryengineering.org/wp-content/uploads/binary_0.pdf)

[Khan Academy: Binary](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:digital-information/xcae6f4a7ff015e7d:binary-numbers/a/bits-and-binary)

[Australian Dept. of Ed](https://www.digitaltechnologieshub.edu.au/teachers/lesson-ideas/introduction-to-binary)

[Code.org: Binary Numbers](https://curriculum.code.org/csp-18/unit1/5/)

[CS: Binary](https://edu.gcfglobal.org/en/computer-science/binary/1/)

[Binary Odometer](https://studio.code.org/s/csp1-2018/lessons/5/levels/2)

[Codecademy Logic Gates Site](https://content.codecademy.com/courses/logic-gates/logic.html)

## Learning Standards

- Learning Standard 1
  - Demonstrate understanding of the decimal and binary numbering systems through number conversion
- Learning Standard 2
  - Discuss binary conversion methods in programming language in guided conversation
- Learning Standard 3
  - Understand the purpose of binary data in digital processing and the advantages/disadvantages of other systems
- Learning Standard 4
  - Evaluate binary data through a series of simple hardware components and logic processors

There are several "models" of learning, I am using an the models I was trained on [Instructor's Manual, Chpt 3, pg 15](https://www.faa.gov/regulations_policies/handbooks_manuals/aviation/aviation_instructors_handbook/media/05_aih_chapter_3.pdf), it is geared more toward the adult learner than most of the childhood models I have found, though really there aren't too many diffrences. Essentially there are four basic levels of learning, remembered with the mnemonic RUAC:

- Rote: Memorization of a subject
- Understanding: Comprehension of a subject
- Application: Using the understanding a subject in a meaningful way
- Correlation: Understanding and applying what has been learned into the larger topic of what has already or is yet to be learning

## Lesson Description

This lesson will introduce the student to a formal lesson on the binary number system. By now the user has come in contact with binary on a number of occassions although it may not have been thoroughly explained. The lesson will use everyone familiarity with the decimal system to create an understanding of how numbers and information are stored through 'bits' of information. The student will learn why computers and electrical devices use binary and the advantages and disadvantages that that creates. After a binary conversion exercise, this mini lesson will take students on a deep dive into the fundamental microchips that make up the modern computer. By looking at a variety of simple logic gates (AND/OR/NAND/NOT/XOR) the student will be able how binary information is processed and how these components build upon each other to create more robust computing systems.

>After the base of knowledge is build, the follow-on mini lesson will guide students through the processing of complex data transfer and storage, touching on graphics, generic files, network communications and compression.

>The rest of the "Logic Gates" lesson that was produced a few years ago would be an excellent off shoot if the user wanted to take a deep dive into those chips and how they can be built upon to create the more complex chips such as adders, multiplexers, and demultiplexers. I think since it is already created, it would be an easy add to the CS 105 course with hardly any touch up needed at all.

## Lesson Code Description

There will be hardly any coding in this lesson, the goal will be not to distract the user with trying to figure out the code, and rather focus on putting answers into responses so they can be checked against the testing software. It might prompt a user to "fill in the integer represented by: 27" or "Convert 0100101 to decimal and enter your answer in the code on the right."

## Exercise Overview

First Half:

- Introduction
- Decimal & Binary Numbering System
- Converting Decimal <-to-> Binary
- Computer Logic
- Phyiscal Logic Gates (AND / OR / NOT / NAND / XOR) -> Use [Logic Gates JS](https://content.codecademy.com/courses/logic-gates/logic.html)

Second Half:

- Binary Streams (Graphics)
- Binary Streams (Files)
- Binary Streams (Network / Internet)
- Compression (may combine with graphics)
- Summary

## Exercises In-Depth

### Introduction
- NARRATIVE
  - What is binary? (0/1, off/on, true/false)
  - Why it's used
  - The problem with more than two states
- Instructions:
  - Click next to proceed
- ARTWORK: Matrix like graphic

### Decimal & Binary Numbering System
- NARRATIVE
  - How we use numbers
  - Base 10 counting breakdown
  - Base 2 counting breakdown
  - Binary Numbers, multiple examples
  - Most languages have methods to do this
- Instructions:
  - Click next to proceed
ARTWORK / APPLET -> [This would be awesome](https://studio.code.org/s/csp1-2018/lessons/5/levels/2)

### Converting Decimal <-to-> Binary
- NARRATIVE
  - Decimal to binary conversion is a common job for computers
  - Tips / Techniques for converting back and forth
- Checkpoints
  - Convert three numbers to binary -> submit answers to python console
  - Convert three numbers to decimal -> submit answers to python console

### Computer Logic
- NARRATIVE
  - Intro to how computers use bits
  - Why bits make it easy to compute logic
  - Hardware advantages and disadvantages of binary
  - The future -> From Bit to Qubit
- Instructions
  - Research quantum computing [Bloomberg Article](https://www.bloomberg.com/news/articles/2019-10-26/why-quantum-computers-will-be-super-awesome-someday-quicktake#:~:text=But%20in%20a%20quantum%20computer,more%20information%20so%20much%20faster.)

### Physical Logic Gates
- NARRATIVE
  - Adapt current lesson to fit at end of this lesson
  - Explain the five fundamental gates and how they build on each other (AND / OR / NOT / NAND / XOR)
  - Focus on Computer Architecture related deep dive to components
- Instructions
  - Play around with the logic gates to understand how the work
