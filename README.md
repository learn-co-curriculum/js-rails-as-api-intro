# Using Rails as an API

## Introduction

Now that you've become familiar with asynchronous requests in JavaScript,
we are going to take a brief step back and revisit Rails for a few lessons. Rails
itself can serve as both the frontend and backend of a website, but it can also
be configured specifically to work as an API.

An API, short for Application Programming Interface, put broadly, is a way for one 
system to communicate with other _external_ systems. An API abstracts away any
of the complicated logic of a system and presents something that is easier to interact with or build
upon, whether the API is serving up useful functions, services, or data. In relation 
to web development, APIs are often sources of data that we can use in our own 
applications, like weather info or the number of people currently in space.

Using Rails, _we can create our own APIs from scratch_ - if you've got hold of some data to you'd 
love to share with the others - for instance statistics about your local sports 
team or maybe the biographical information of all the characters in your 
favorite fantasy novel - you could build an API and share that information on the web.

In addition, Rails APIs render JSON strings, which is particularly useful, since 
we can use them when building frontends using JavaScript, DOM manipulation and 
asynchronous requests.

As we go through the process of setting up and configuring APIs, we will also 
look at different ways in which we can organize the data the API is providing. As
the creator of an API, you have full control over how information is structured,
and must always consider how that structure affects your code.

With some practice building APIs in Rails, combined with your skills with fetch
in JavaScript, you will be able to build full stack applications by the end of
this section.
