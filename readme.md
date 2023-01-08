This is my attempt at Exercise 2 of Gophercises by Jon Calhoun (https://gophercises.com/)

The aim was to create a URL shortener so eg going to /dogs would redirect to https://www.nonexistentcooldoggosite.com

Instructions
============

Assuming you have Go installed already, you can simply run:

```
go run .
```

Then navigate to http://localhost:8080

Afterthoughts
=============

I found this quite difficult, and I mostly followed along with the solution videos to get it working. To some extent it felt like the exercise was mostly about working with maps and manipulating YAML files and to that extent I was doing quite well. But the exercise gave the http server ready made with the idea of just inserting the URL shortener as a function. So, I found it a bit difficult to fully understand how the URL shortener was supposed to work around the existing code. Though I have some experience of http servers in Ruby and Python; I'm still getting to grips with how the different Types work within Go. I think a further exercise of building a http server from scratch would have been more benefit but that's an area I can focus on in future. I also struggled with importing packages, as that's something new to me. I worked it out in the end but had to re-arrange the files as they were at the beginning.

