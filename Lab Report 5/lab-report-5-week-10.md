# Lab Report 5
## Finding different implementations

### Finding difference between results

- Due to UI bug on my computer, I cannot use vim editor to search for differences over a certain amount of lines in command window. So I printed out the results of test in command terminal and serached for difference manually.

![image](ui.png)

- So I uploaded my `MarkdownParse.java` to the same directory and changed the file name to `MyMarkdownParse.java`, and edited the `script.sh` file to make it print out the results at the same time in the command window. 
![image](script.png)

- output in command line
![image](test194.png)

### [The link to test file](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/201.md)
- the expected output shown by VSC preview window
![image](test201.png)
 - exptected: `my_(url)`. 
- actual:
![image](actual.png)

So my implementation is correct. 

-  Possible solution:


![image](code.png)

For the highlighted part, there should be another condition to determine whether the brackets are closely followed by parenthesis. For exmaple, determine if the first string comes up after the close bracket is the open parenthesis.  






