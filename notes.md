# CS 260 Notes

This file represents what I have learned about web programming.

- [My startup](https://startup.cs260.click)
- [My simon](https://simon.cs260.click)

## Helpful links

- [Course instruction](https://github.com/webprogramming260)
- [Canvas](https://byu.instructure.com)
- [MDN](https://developer.mozilla.org)

## AWS

Interesting things I have learned about AWS

## HTML

Interesting things I have learned about HTML

## React

Interesting things I have learned about React

## I love web programming!


9/15 Lecture Notes:

Index HTML: This is like the main file HTML name.

Assets folder is good for images, music, etc.

Making Notes in HTML: Command + / 

Learning HTML:
<head></head>

<body></body> ( alternatively sorta <main></main> )

<footer></footer>

<div></div>
<section></section>

<title></title>
<h1></h1>
<h2></h2>
<h3></h3>
<p></p>

<nav></nav>
<href></href>
<a></a>

<img></img>

<button></button>
<input></input>

src= 
id=

<table></table>
<tr></tr>
<th></th>
<td></td>


9/11 Pre Lecture Notes:
Technology Stack: Basically a stack of technology that work together to make something you designed / deliver
Web Framework: At the top of the stack, works with web services, and web services work with the backend
9/10 Lecture Notes:
8-10 commits minimum per assignment
Keep ReadMe up to date

AWS: Amazon Web Services (Google Cloud is also one)

Route 53 Connects Front End to Back End

Technology Stack
Caddy 2 (Bouncer)
Node JS (Cooks)
mongoDB (Fridge)

Layers:
Application (HTTPS)
Functionality like website
Transport (TCP / UDP)
Packet Delivery
Internet (IP)
Establishing connections, routing
Link (Fiber, Hardware)
Physical connections

dig / nslookup / whois
Get IP addresses for stuff

[subdomain.]*secondary.top
secondary.top: This is a root
secondary: This is a sld
top: This is a tld

localhost
Local host is specifically for my computer

DNS record types (Configuring how things connect)
A / AAAA
CNAME
NS
TEXT
SOA

IP addresses change, so we need to use elastic IP addresses, which cost $3 a month
Done in AWS

9/8 Lecture Notes:
React (HTML, CSS, Java): Front End
VS Code, Github, AWS: Back End

DNS “rents” you an IP Address to host a website that won’t change locations. Go-Daddy rents you the IP Address. 

HTML is the bones
CSS is the graphics
JavaScript (Closest Part to the Server) is the heavy logic

HTML can call functions in JavaScript

In HTML, “.” means class.

px in CSS means the exact pixel amount of something
vh in CSS means the visual height of something
vw in CSS means the visual width of something

<script> : in VS Code, this will do JavaScript
<style> : in VS Code, this will do CSS

<script scr”FILENAME.js”> : In VS Code in HTML files, this will import information from a java script file.
<style scr”FILENAME.css”> : In VS Code in HTML files, this will import information from a CSS file.

FUN FACT: You can write javascript and CSS in HTML files using those methods, but you CANNOT write HTML in .js or .css files, or .js in .css files, or vise versa. HTML is the only one where a person could do all 3.
9/8 Pre Lecture Notes:
Forks:
Create a copy of a thing in github, NOT in your IDE. So if you want to copy a code, and use it in your own personal github, you’d fork it!
Question for Class:
It is a prerequisite for all deliverables that you have at least 10 commits evenly spread across the assignment period for the deliverable?

This is the pattern that you want to make a reflexive part of your development process.

Pull the repository's latest changes from GitHub (git pull)
Make changes to the code
Commit the changes (git commit)
Push the changes to GitHub (git push)


SHA:
​​SHA's use a combination of trees, parent SHAs, Timestamps, and Authors / Committers to determine it's ID. This means that the chances of two things sharing the same ID are almost impossible. This leads to ID's being long, sure, but it you don't need the entire ID to identify the ID you're looking for. It also acts as a digital footprint, recording all these things in it's ID itself. This makes version histories also distinct from past version IDs. It also makes them secure because untampered ID's will have digital footprints, so if files have been tampered with, it's more noticeable. This isn't just for security reasons, but it is also useful for a debugging trail as well.

9/5 Post Lecture Notes:
My Web Application
A visual story book, which needs a login, password, and a username. The story book would use the user's name as the main character's name in the story. A few interactive elements, but mostly just places the user would click to progress to the next page / part of the story. You can see useful hints that other players have left behind as well, and maybe a prompt saying what other players are at that current point in the story. The backend would handle the story elements and also prompts given by other users.
9/3 Lecture Notes:
Will not submit assignments in Canvas
I will get $50 for AWS as a student.
Go to AWS, sign up with student email, choose “Paid” Plan, get Route53 Access to all Keep Credits
