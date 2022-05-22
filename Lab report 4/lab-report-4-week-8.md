# Lab Report 4

## Repositories

[My repository](https://github.com/vanvansan/markdown-parser)

[Reviewed repository](https://github.com/calistajlee/lab6-markdown-parser)

___

## Expected results

- Snippet 1:

    1. Expected results: ```[`google.com,google.com,ucsd.edu]```
    2. test code screenshot ![image](snippet1.png)
    3. My test output screenshot ![image](my1.png)
    4. Reviewed project output screentshot  ![image](r1.png)

- Snippet 2:

    1. Expected results: ```[a.com,`a.com(()),example.com]```
    2. test code screenshot ![image](snippet2.png)
    3. My test output screenshot ![image](my2.png)
    4. Reviewed project output screentshot  ![image](r2.png)

- Snippet 3:

    1. Expected results: ```[https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule]```
    2. test code screenshot ![image](snippet3.png)
    3. My test output screenshot ![image](my3.png)
    4. Reviewed project output screentshot  ![image](r3.png)


___

## Q&A

- Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.

    Answer:
    Yes, I can add more allowed punctuation in my code. In this way the links with strange names in the brackets will be counted.


- Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.

    Answer: 
    No, this case of markdown file is much more complicated and requries a lot of redos in my logic to make my code work. Because there are parenthesis and brackets in the names and links, which confuses the judgement.


- Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.

    Answer:
    Yes, the output is almost right. Only some reformat of the output is needed.