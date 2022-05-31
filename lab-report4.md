
- the [link](https://github.com/hahacen/markdown-parser) to MarkdownParse repository
- the [link](https://github.com/MichaelYe48/markdown-parser) to my peer's 

## Snippet1:

this is the expected:

```[`google.com, google.com, ucsd.edu]```


this is the test code
```
 @Test
    public void testSnippet1() throws IOException{
        Path fileName=Path.of("/Users/a/Documents/GitHub/markdown-parser/Snippet1.md");
        String content = Files.readString(fileName);
        List<String> expected= List.of("google.com","google.com", "ucsd.edu");
        assertEquals(expected,mark.getLinks(content));
    }
```
this is my output
![new s1.jpg](new%20s1.jpg)

this is my peer's :
![p1](s1.jpg)

## Snippet2:
 this is the expected:
 ```[a.com, a.com(()), example.com]```

this is my test code:
```
    @Test
    public void testSnippet2() throws IOException{
        Path fileName=Path.of("/Users/a/Documents/GitHub/markdown-parser/Snippet2.md");
        String content = Files.readString(fileName);
        List<String> expected= List.of("a.com","a.com(())", "example.com");
        assertEquals(expected,mark.getLinks(content));

}
```
my output:
![pic2](new%20s2.jpg)

this is my peer's
![peer2](peer2.jpg)
## Snippet 3:

this is the expected output:
```[https://www.twitter.com, https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule, https://cse.ucsd.edu/]```

```
@Test
    public void testSnippet3() throws IOException{
        Path fileName=Path.of("/Users/a/Documents/GitHub/markdown-parser/Snippet3.md");
        String content = Files.readString(fileName);
        List<String> expected= List.of("https://www.twitter.com"," https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule"," https://cse.ucsd.edu/");
        assertEquals(expected,mark.getLinks(content));

}
```
my output:
![pic3](new%20s3.jpg)

my peer's:
![peer3](peer3.jpg)
