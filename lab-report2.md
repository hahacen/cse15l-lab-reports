## change 1

![pic1](https://github.com/hahacen/cse15l-lab-reports/blob/main/731650840079_.pic.jpg)

- the failure inducing input: https://github.com/hahacen/markdown-parser/blob/main/test-file4.md

![pic2](https://github.com/hahacen/cse15l-lab-reports/blob/main/45001650847593_.pic.jpg)

- it is problematic because there's the closeBracket and closeParen missed or there're some random ones(they are not in pari), and therefore we need this statement to stop and exit the while loop. Therefore, in the code, as we find either openBracket or openParen or closeBracket or closeParen is not present in the code. 

## change 2

![pic3](https://github.com/hahacen/cse15l-lab-reports/blob/main/751650860220_.pic.jpg)

- the failure inducing input: https://github.com/hahacen/markdown-parser/blob/main/test-file5.md

![pic4](https://github.com/hahacen/cse15l-lab-reports/blob/main/761650860977_.pic.jpg)

- the output is probelmatic because the picture link should not be returned, therefore we should break the while loop using this if statement, there're two links, but this should only be one. Therefore, we should discard this picture link situation. 



## change 3

![pic5](https://github.com/hahacen/cse15l-lab-reports/blob/main/771650867065_.pic.jpg)



