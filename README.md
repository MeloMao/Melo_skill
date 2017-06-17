# Preface #
What's Melo_skill? You guys can comprehend it to my skills in my career, the skills I wanna have, or essential skills I should grasp. Now, whatever I've already konw it, I think I should learn or make it professional, all of them. So this list I will talk about the essential skills I chosen.
# List #
  * [Android](#android)
  * [Apache](#apache)
  * [Assembly](#assembly)
  * [C★](#c)
  * [CSS](#css)
  * [English★](#english)
  * [Github](#github)
  * [Hack★](#hack)
  * [HTML](#html)
  * [Java](#java)
  * [JavaScript](#javascript)
  * [JSP](#jsp)
  * [Linux★](#linux)
  * [Mysql★](#mysql)
  * [Oracle](#oracle)
  * [Perl](#perl)
  * [PHP](#php)
  * [Python★](#python)
  * [Reverse](#reverse)
  * [Ruby](#ruby)
  * [Scraping★](#scraping)  
  * [Shell★](#shell)
### Android #
* introduction  
Android is a free and open source operating system based on Linux, mainly used in mobile devices, such as smart phones and tablet PCs, led by Google and the Open Handset Alliance. Now Android Application demand is very large, so many developer chose to develop Android Application, it's a potential market.
* target  
Will, I admit that I have only a basic course in College, and after that, I can build a sample application like a 'helllo world', a simple button or a picture display device. So now maybe I don't have target.
* hello world  
Android's hello world program is rely on Java and XML, so it's unnecessary to display it.
### Apache #
* introduction  
Apache is the world's number one Web server software. It can run on almost all of the computer system, because of its cross platform and security is widely used, is one of the most popular Web server software. It's fast, reliable, and can be extended through a simple API to use Perl/Python and other interpreters compiled into the server. Besides, Apache is a tribe's name, a foundation or a type of helicopter's name. 
* target  
Use Apache to be the general server for web configure, just like PHP,JSP or ASP. If I wanna do this, I should learn the graphical UI and conf UI.
### Assembly #
* introduction  
Assembly language is a low-level language used in electronic computers, microprocessors, microcontrollers, or other programmable devices, also known as symbolic languages. In assembly language, instead of machine instructions with mnemonic operation code, with the address sign or label instead of instruction or operand address. In different devices, assembly languages correspond to different machine language instruction sets, which are converted into machine instructions by assembly. Generally speaking, specific assembly language and specific machine language instruction set are one-to-one, and different platforms can not be transplanted directly.
* target  
It's important for Hack skill, I was learned it a term, I was just 'in door' step. But in the future, I must improve it.
* hello world
```assembly
data segment  
    output db 'Hello World! $'  
data ends  
code segment  
      
start:   
    assume ds:data,cs:code  
    mov ax,data  
    mov ds,ax  
      
    mov dx,offset output  
    mov ah,09h  
    int 21h  
      
    mov ah,4ch  
    int 21h  
  
code ends  
    end start
```
### C #
* introduction  
C language is a general-purpose computer programming language, widely used. The goal of C is to provide a programming language that can be compiled and processed in a simple way, producing a small amount of machine code and running without any running environment support. Although the C language provides many low-level processing functions, but still maintain a good characteristic of cross platform, with a standard to write the C language program can be compiled in many computer platforms, and even contains some embedded processors (MCU) and super computer operation platform. In 1980s, in order to avoid the development of manufacturers using the C language grammar differences, by the National Bureau of standards for the C language has developed a complete set of international standard grammar, known as ANSI C, C language as the original standard.
* target  
Although the C language I just had a systematic study in the classroom, but C is already the door to learning other languages for me. Before, the teacher said "C is the best first language you learn", I was lucky enough to do it. For example, I used to write an encryption program with Python, but did I write it directly? No, I just used C to convert it, so C is too important for me.
* hello world
```c
	#include <stdio.h>
	main()
	{
		printf("Hello World!\n");
	}
```
### CSS #
* introduction  
CSS(Cascading Style Sheets) is a computer language that is used to represent HTML (an application of the Standard Generalized Markup Language) or XML (a subset of the standard generalized markup language). CSS not only can modify web pages statically, but also can be used to format the elements of the web page dynamically. CSS is able to accurately control the layout of the elements in the web page at the pixel level, support almost all font style, with the ability to edit web objects and model styles.
* target  
This skill just for Html or web front-side, and it likes markdown(but more complex).
### English #
* introduction  
English is Indo European Germanic West Germanic languages of the language, is the most frequently used official languages (as a native language, first language) is the world's most widely, and is also the official language of many international organizations and the European Union and the Commonwealth countries, with the number of native speakers in the world after third. The number of native speakers of Chinese and spanish.
The evolution of English language from ancient Denmark and Scandinavia peninsula from Germany, Holland and the surrounding white immigrants to the British Isles, Anglo Saxon and Jutes said to come, and to the rest of the world through the spread of British colonial activities. Since it has been in touch with many ethnic languages in history, its vocabulary has changed from one type to many, and the grammar has changed from "multi Inflection" to "less inflectional", and the phonetic has also undergone regular changes.
Between 19 and twentieth Century, Britain and the United States took the lead in culture, economy, military, politics and Science in the world, making English an international language. Nowadays, English is used as a medium of communication on many international occasions. English is also the most closely related language, and most programming languages are related to English, and with the use of the Internet, English is more widely used. English is one of the working languages of the United nations. Some people think that the lower Scotland dialect is the closest language to English, while others think it is a dialect of english. Scotland, lowland Saxon, Danish, German, Dutch, Afrikaans and English are also very close. With the descent Norman of France in Eleventh Century to conquer the kingdom of England, bringing tens of thousands of French vocabulary and Latin words, greatly enriched English vocabulary, vocabulary is also driven by many native.
* target
### Github #
* introduction  
GitHub is a managed platform for open source and private software projects, because it supports Git only as a unique version library format for hosting, so it was named GitHub.
* target
### Hack #
* introduction
* target
## Html #
* introduction
* target
* hello world
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title> First html program</title>
</head>
<body>
<p>Hello World!</p>
</body>
</html>
```
### Java #
* introduction
* target
* hello world
```java
public class HelloWorld {
    public static void main(String[] args){
        System.out.println("Hello World!");
    }
}
```
### JavaScript #
* introduction
* target
* hello world
```js
<html>
<body>
<script type="text/javascript">
document.write("Hello World!");
</script>
</body>
</html>
```
### JSP #
* introduction
* target
* hello world  
JSP can use two ways to build hello world program: Html and Java.
### Linux #
* introduction  
Linux is a free and freely distributed Unix operating system, a multi user, multi tasking, multi thread and multi CPU operating system based on POSIX and UNIX. It can running major UNIX tools, software, applications, and network protocols. It supports 32 bit and 64 bit hardware. Linux inherits the design philosophy of Unix as the core of the network, and is a stable multi-user network operating system.
The Linux operating system was born in October 5, 1991 (the first time officially announced). Linux has many different versions, but they all use the Linux kernel. Linux can be installed in a variety of computer hardware devices, such as mobile phones, tablet PCs, routers, video game consoles, desktop computers, mainframes and supercomputers.
Strictly speaking, the word 'Linux', itself represents only the Linux kernel, but in fact, people have become accustomed to using Linux to describe the entire Linux based kernel, and the use of GNU engineering various tools and database operating system.
* target
### Mysql #
* introduction
* target
### Oracle #
* introduction
* target
### Perl #
* introduction
* target
* hello world
```perl
print "Hello World!"
```
### PHP #
* introduction
* target
* hello world
```php
<html>
<head>
<title>First PHP program</title>
</head>
<body>
<?php echo '<p>Hello World</p>'; ?>
</body>
</html>
```
### Python #
* introduction
* target
* hello world
```python
print('Hello World!')
```
### Reverse #
* introduction
* target
### Ruby #
* introduction
* target
* hello world
```ruby
puts "Hello World!"
```
### Scraping #
* introduction
* target  
### Shell #
* introduction
* target
* hello world
```shell
#!/bin/bash  
echo "Hello World!" 
```
