---
layout: post
title: Is Python an Interpreted Language?
tags: [python, interpreted languages, programming, data scientist]
---
<p align="justify">
When I started learning Python, I always came across this statement – “Python is an interpreted language”, which meant that it executes a code line by line. To understand what “interpreted” really means, I tried to deep dive a little on this concept and realized that a more correct way of making that statement  would be - it has an **“interpreted implementation”.
</p>

Confused? Let’s try to break this down in a simpler language. 

<p align="justify">
Programming languages can either be interpreted or compiled or both. During my C programming lab in under-graduation, I remember using the compiler every time to run the C program. Now when I started learning python, I came across the concept of interpreters. I am no major in computer science but I tried to understand the basic difference between the two concepts that I would like to share.
</p>

<p align="justify">
The categorization of programming languages into compilers and interpreters does not make any sense. Just like humans need a language to converse and understand each other, a computer understands only machine code in binary which is not human readable. A programming language is first written in a human-readable language and then translated to machine code. The process in which a code is translated is what makes it interpreted or compiled.
</p>



<img src="img/compiler.png" width="500" height="500">


<p align="justify">
Interpreting means that the code is translated simultaneously or compiled and executed directly (not to be confused with just-in-time compilation) as it is written, because of which it is considered slower. Whereas, compiling means that the source code is converted into machine code for once and for all and can be executed any time after that. It is therefore considered faster and more efficient compared to an interpreter. However, interpreters provide more flexibility, dynamic typing and are easier to learn.
</p>



<p align="center">
<img src="img/compilepic.jpg"  width="300" height="300">
</p>

<p align="center">
Source: (https://www.explainxkcd.com)
</p>

<p align="justify">
Every programming language can be implemented by an interpreter or compiler. An ambitious programmer can write both, a compiler and interpreter for a language.Some of the commonly compiled languages are C, C++, FORTRAN, Go (a compiled programming language designed by Google!), etc, whereas some commonly interpreted languages are Python, JavaScript, Perl, etc.
</p>
<p align="justify">
There’s a lot more to learn about the difference between interpreters and compilers, which you can easily find on the internet (check out StackOverflow for any confusion). I mentioned about just-in-time compilation above, which is one of the ways how a compiler runs and is often confused with an interpreter. I would not be talking about it here as it would be a lot to handle for a beginner and at this point it would be enough to understand the basic difference.
</p>

<p align="justify">
I hope I was able to provide a simple but clear understanding of these concepts. Do share your feedback if you find something explained incorrectly and let me know ways in which I can further improve my blogs (I’m not a good writer so your feedback would really help!). Also, I am posting few links below which helped me to get a more detailed understanding.
</p>

Thanks for reading!

Refrerence Links:

[https://nedbatchelder.com/blog/201803/is_python_interpreted_or_compiled_yes.html](https://nedbatchelder.com/blog/201803/is_python_interpreted_or_compiled_yes.html) 

[https://softwareengineering.stackexchange.com/questions/399335/can-every-language-be-categorized-as-either-compiled-or-interpreted](https://softwareengineering.stackexchange.com/questions/399335/can-every-language-be-categorized-as-either-compiled-or-interpreted) 

[https://stackoverflow.com/questions/2426091/what-are-the-differences-between-a-just-in-time-compiler-and-an-interpreter](https://stackoverflow.com/questions/2426091/what-are-the-differences-between-a-just-in-time-compiler-and-an-interpreter) 

[https://en.wikipedia.org/wiki/Interpreted_language](https://en.wikipedia.org/wiki/Interpreted_language) 
