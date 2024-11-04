## Course Information
- **Lectures**: TuTh 5:00 pm - 6:20 pm
- **Location**: ECEB 1013
- **Instructor**: Prof. [Yupeng Zhang](https://zhangyp.web.illinois.edu/) zhangyp@illinois.edu
- **Office Hour**: Wednesday 3:00 - 4:00pm, CSL 468
- **TA**: Mehul Oswal, mehuljo2@illinois.edu
- **TA Office Hour**:  Friday, 4:00 – 5:00pm, CS Tutoring Center (Siebel Center Basement Open Area)

## Course Description

Cryptography uses mathematical algorithms and protocols to ensure the confidentiality, integrity, and authenticity of information. Today, cryptographic principles and systems form an integral part of almost all online activity. This course is an introduction to the fundamentals of modern cryptography. You will learn about cryptograhy’s formal approach to security. You will learn about cryptographic primitives, and you will learn how those primitives can be used.

This webpage serves as the course syllabus, and it will be edited throughout the semester to release resources.


## Textbook

**Introduction to Modern Cryptography, 3rd edition, Jonathan Katz and and Yehuda Lindell.**

Additional references:
- Mike Rosulek’s [The Joy of Cryptography](https://joyofcryptography.com/) is an excellent, albeit unfinished, free resource.

- Dan Boneh’s and Victor Shoup’s [A Graduate Course in Applied Cryptography](https://toc.cryptobook.us/) is an additional resource.

## Prerequisites
The following courses are required:

- CS 225: Introduction to Data Structures and Algorithms

- CS/ECE 374: Introduction to Algorithms and Models of Computation

Prerequisite overrides will be considered on a case-by-case basis. We expect that you are familiar with basic probability, modular arithmetic, and logarithms. Take the time to read [chapter 0](https://joyofcryptography.com/pdf/chap0.pdf) of The Joy of Cryptography and make sure you understand the concepts within.

## Links

**Slides and files**: [https://canvas.illinois.edu/](https://canvas.illinois.edu/)

**Assignment submission and Grading:** [https://www.gradescope.com/](https://www.gradescope.com/)

**Annoucements and discussions: Piazza** [https://piazza.com/class/m0bh0wniqb54o3](https://piazza.com/class/m0bh0wniqb54o3)

## Grading
**Class Participation:** 10%.  Please show up to class, and participate in discussions in class and on Piazza. We will sometimes take formal attendance in class. You can miss up to 2 lectures without excuse; after that, each unexcused absence will deduct of your participation grade.

**Homework:** 50%. The course will include **five** homework assignments. Each homework will include careful instructions. Homework problems will include (1) long-form problem write-ups and proofs as well as (2) C++ programming assignments. For programming assignments, follow instructions carefully to receive full credit.

Homeworks are to be submitted via Gradescope. Late homework will not be accepted without valid excuses and approval of the instructor.

- **Collaboration.** Homeworks are to be submitted individually. However, you may collaborate with up to one other student on homework assignments. On each homework submission, declare your collaborator (if any). In your collaboration you are expected to discuss the homework, not merely copy answers. Plagiarism will not be tolerated (see Academic Integrity).

**Midterm Exam:** 20%. It will be a combination of multiple choice and free response problems. **5:00-6:20pm, Tuesday, October 15, in class**

**Final Exam:** 20%. The final exam will be a cumulative test on all course topics. It will be a combination of multiple choice and free response problems.


**(4 credit hours only) Project and presentation:** 20%. In teams of 2, you will read papers on advanced topics in the cryptography literature, and write a technical report. Come talk to me about potential topics. (If you are registered for four credit hours, your final grade will be out of 120, and it will be normalized to out of 100.)

**Grading:** [93-100] A, [90-92] A-, [87-89] B+, [83-86] B, [80-82] B-, [77-79] C+, [73-76] C, [70-72] C-, [67-69] D+, [63-66] D, [60-62] D-, [0-59] F.

## Schedule (tentative)

<table style="width: 100%;" border="1">
    <tr>
        <th style="width: 10%;">Week</th>
        <th style="width: 10%;">Date</th>
        <th style="width: 50%;">Topic</th>
        <th style="width: 30%;">Readings</th>
    </tr>
    <tr>
        <th rowspan="2">Week 1</th>
        <th>8/27</th>
        <th>Introduction and background on Cryptography</th>
        <th></th>
    </tr>
     <tr>
        <th>8/29</th>
        <th>Ancient ciphers</th>
        <th>Chapter 1.1-1.3, Introduction to Morden Cryptography</th>
    </tr>
    <tr>
        <th rowspan="2">Week 2</th>
        <th>9/3</th>
        <th>Perfect secrecy, one-time pad</th>
        <th>Chapter 1.4, 2</th>
    </tr>
    <tr>
        <th>9/5</th>
        <th>Computational Security, Pseudorandomness</th>
        <th>Chapter 3.1-3.3</th>
    </tr>
    <tr>
        <th rowspan="2">Week 3</th>
        <th>9/10</th>
        <th>Chosen plaintext attack, stream cipher</th>
        <th>Chapter 3.4, 3.6, 7.1</th>
    </tr>
    <tr>
        <th>9/12</th>
        <th>Pseudorandom Function and Block cipher</th>
        <th>Chapter 3.5</th>
    </tr>
    <tr>
        <th rowspan="2">Week 4</th>
        <th>9/17</th>
        <th>DES and AES</th>
        <th>Chapter 7.2</th>
    </tr>
    <tr>
        <th>9/19</th>
        <th>Modes of Operation</th>
        <th>Chapter 3.6</th>
    </tr>
    <tr>
        <th rowspan="2">Week 5</th>
        <th>9/24</th>
        <th>Padding oracle attacks</th>
        <th>Chapter 5.1</th>
    </tr>
    <tr>
        <th>9/26</th>
        <th>Message Authentication Codes</th>
        <th>Chapter 4</th>
    </tr>
    <tr>
        <th rowspan="2">Week 6</th>
        <th>10/1</th>
        <th>CCA security and Authenticated Encryption</th>
        <th>Chapter 5.1.2, 5.2-5.3</th>
    </tr>
    <tr>
        <th>10/3</th>
        <th>Cryptographic Hash functions and SHA</th>
        <th>Chapter 6.1, 6.4, 7.3</th>
    </tr>
    <tr>
        <th rowspan="2">Week 7</th>
        <th>10/8</th>
        <th>Merkle-Damgard Transformation, Merkle hash tree</th>
        <th>Chapter 6.2, 6.6.2</th>
    </tr>
    <tr>
        <th>10/10</th>
        <th>HMAC, Midterm review</th>
        <th>Chapter 6.3</th>
    </tr>
    <tr>
        <th rowspan="2">Week 8</th>
        <th> 10/15 </th>
        <th><b>Midterm Exam</b></th>
        <th></th>
    </tr>
    <tr>
        <th>10/17</th>
        <th>Number Theory</th>
        <th>Chapter 9.1, 9.3</th>
    </tr>
    <tr>
        <th rowspan="2">Week 9</th>
        <th> 10/22 </th>
        <th>Diffie-Hellman key exchange</th>
        <th>Chapter 11.3, 12.4</th>
    </tr>
    <tr>
        <th>10/24</th>
        <th>Public key encryption, ElGamal encryption</th>
        <th>Chapter 9.4, 12.3</th>
    </tr>
    <tr>
        <th rowspan="2">Week 10</th>
        <th> 10/29 </th>
        <th>Factoring assumptions and RSA encryption</th>
        <th>Chapter 9.2, Chapter 12.5</th>
    </tr>
    <tr>
        <th>10/31</th>
        <th>RSA with CCA security</th>
        <th>Chapter 12.5</th>
    </tr>
    <tr>
        <th rowspan="2">Week 11</th>
        <th>11/5</th>
        <th>Random Oracle, Digital Signature</th>
        <th>Chapter 6.5</th>
    </tr>
    <tr>
        <th>11/7</th>
        <th>RSA Signature</th>
        <th>Chapter 13.1-13.4</th>
    </tr>
    <tr>
        <th rowspan="2">Week 12</th>
        <th>11/12</th>
        <th>Schnorr Signature and PKI</th>
        <th>Chapter 13.5, 13.6</th>
    </tr>
    <tr>
        <th>11/14</th>
        <th>Elliptic curve</th>
        <th>Chapter 9.3.4</th>
    </tr>
    <tr>
        <th rowspan="2">Week 13</th>
        <th>11/19</th>
        <th>Bilinear pairing and BLS signature</th>
        <th>Chapter 15.4 and 15.5 in A Graduate Course in Applied Cryptography</th>
    </tr>   
    <tr>
        <th>11/21</th>
        <th>No class due to travelling</th>
        <th></th>
    </tr>
    <tr>
        <th>Week 14</th>
        <th></th>
        <th>Fall Break No Class</th>
        <th></th>
    </tr>
    <tr>
        <th rowspan="2">Week 15</th>
        <th>12/3</th>
        <th>Blockchain and Cryptocurrency</th>
        <th></th>
    </tr>
    <tr>
        <th>12/5</th>
        <th>Zero-knowledge proofs</th>
        <th></th>
    </tr>
    <tr>
        <th>Week 16</th>
        <th>12/10</th>
        <th>Final Exam Review session</th>
        <th></th>
    </tr>
</table>




## Academic Integrity

Academic dishonesty is a serious offense. The University of Illinois Urbana-Champaign Student Code [https://studentcode.illinois.edu](https://studentcode.illinois.edu) is considered a part of this syllabus. If you are ever in doubt of what constitutes plagiarism or cheating, do not hesitate to ask me.

## Disability Accommodations

To obtain disability-related academic adjustments and/or auxiliary aids, students with disabilities must contact the course instructor and the Disability Resources and Educational Services (DRES) as soon as possible. To contact DRES you may visit 1207 S. Oak St., Champaign, call 333-4603 (V/TTY), or e-mail a message to [disability@illinois.edu](disability@illinois.edu).
