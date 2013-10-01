eds_project_2
=============

I'm working on using regular expressions to search and replace text. For example, the comments I'm searching follow the following pattern:

body: I always took it as those who are. edited:

I'm interested in the text that follows "body:" (i.e., the text of the comment) and that precedes " edited:". Setting a variable "names" equal to the text above, the following regular expression produces an output of just the comment body:

console.log(names.replace(/(body:) (I always took it as those who are.) (edited:)/, "$2"));

I'm hoping I can use a similar technique when searching large chunks of text to get the text I want.
