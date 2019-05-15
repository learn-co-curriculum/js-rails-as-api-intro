# Using Rails as an API

## Introduction

Now that you have gotten familiar with asynchronous requests in JavaScript,
we're going to take a brief step back and revisit Rails for a few lessons. Rails
itself can serve as both the frontend and backend of a website, but it can also
be configured specifically to work as an API.

An API, short for Application Programming Interface, put broadly, is a way for one 
system to communicate with other _external_ systems. An API abstracts away any
of the complicated logic of a system and presents something that is easier to interact with or build
upon, whether the API is serving up useful functions, services or data. In relation 
to web development, APIs are often sources of data that we can use in our own 
applications, like weather info or the number of people currently in space.

APIs that render JSON are particularly useful in combination with JavaScript, since 
we can use them with `fetch()` requests to asynchronously update a webpage using 
DOM events, rather then having to reload, and have already in previous sections.

Understanding how Rails can work as an API also means that you can design your
own APIs and begin to think about how to shape data to best serve your needs.

With some practice building APIs in Rails, combined with your skills with fetch
in JavaScript, you will be able to build full stack applications by the end of
this section.
