# lab report 3

## task1

![pic1](871652059218_.pic.jpg)
 
we use this to  edit the file ```(base) Macintosh-4:.ssh a$ vi ~/.ssh/config ```

![pic2](881652059443_.pic.jpg)

we copy and paste the following to from lab 5 write up
```
    HostName ieng6.ucsd.edu
    User cs15lsp22zzz (use your username)
```

we type ``` ssh liu``` replacing the old ```cs15lsp22amu@ieng6.ucsd.edu```
![pic3](891652060096_.pic.jpg)

then I use scp to move the new file created to the remote server: 

![pic4](901652060238_.pic.jpg)

## task 2
![pic5](911652060336_.pic.jpg)
![pic6](921652060424_.pic.jpg)

here we create the public ssh key on github
![pic7](931652060529_.pic.jpg)

this is the public and private key
![pic77](59841652063902_.pic.jpg)

run and commit on ieng6 server:

![pic9](1101652747808_.pic.jpg)
![pic8](1111652747822_.pic.jpg)

[commit link](https://github.com/hahacen/markdown-parser/commit/ea28110d7d0c3e7722d58d233d753e1ef45553de)
## task 3
this is how we copy the whole resiptory step by step
![pic9](951652061603_.pic.jpg)
![pic10](961652061726_.pic.jpg)
![pic11](971652061741_.pic.jpg)
![pic12](981652061782_.pic.jpg)
![pic13](991652061794_.pic.jpg)
![pic14](1001652061819_.pic.jpg)

I can also use the combined code as the following:
```
scp -r . liu:markdown-parser; ssh liu "cd markdown-parser; javac -cp .:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar MarkdownParseTest.java; java -cp .:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar org.junit.runner.JUnitCore MarkdownParseTest"
```

![pic15](1141652751637_.pic.jpg)
![pic16](1151652751654_.pic.jpg)


These are the files in the markdown-parser resiptory in the local computer, which will be all copied to the remote server using scp
![pic18](1161652751800_.pic.jpg)

they are all copied to the remote server
![pic19](1171652751824_.pic.jpg)
![pic20](1181652751836_.pic.jpg)


