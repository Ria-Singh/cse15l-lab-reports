
I found both bugs by manually searching through the results after running the time bash script.sh.

[This](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/510.md) is the link to the testfile 510.md and [this](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/511.md)
is the link to the testfile 511.md.

the below screenshot shows the outputs for both my own repository and the given repository to both these files
![](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-06-06%20at%2012.29.07%20AM.png)



# File 1 - 510.md
My markdownparser gets the output wrong while the given markdown parser gets it right.
My markdown parser fails to recognize the url as correct and gives an empty output while the given markdown parser is able to recognize the url correctly

The conditional statments as highlighted might need some refining
![](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-06-06%20at%2012.51.59%20AM.png)

# File 2 - 511.md
My markdown parser gets this right while the given one gets its wrong.
My markdown parser recognizes that the given output should not contain anything as the text within the square brackets contains more square brackets and hence messes up the syntax. The given markdown parser is unable to do so and hence gives the url as the output.

The bug may lie here
![](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-06-06%20at%2012.54.51%20AM.png)


