
class: dark, middle

# NoSQL

What's NoSQL & why should I care?

.intro-img[![intro](./img/nosql.png)]

<!-- a Swagger implementation of the REST API that will let the user interactively explore the API
and try it out, instead of just reading it from a PDF. I think Duncan has plans to make this really
effective, so that we can automatically both push out the Swagger API documentation and also client
libraries. That will not only contribute to the usability of the product, but also it’s quality,
since it forces synchronization of the product and the documentation. -->

---
class: toc, middle

# Scalable SQL and NoSQL Data stores

subtitle

---
class: toc

# A Database Model...

It tells you about the logical structure of a database and ways to store and manipulate the data.

---
# Importance of choosing the ‘right’ Data Model

<!-- Bullet points -->

* Picking up the right model helps everyone, the company(profits), the client(trust), and of course the developer(time)
* Studies have shown that about 70% of software development efforts fail in wake of premature development.
* Data Modeling, as it may seem, doesn’t add to the project budget. Rather, it reduces the overhead of solving errors down the line by accessing them beforehand.

---
class: toc

# A few Data Stores...
 
* Key-value Stores
* Document Stores
* Extensible Record Stores
* Scalable RDBMS


---
class: toc

# Key-Value Stores

* Simplest data stores
* Store pairs of key-values
* Support a single object per database
* Efficient
* Easily scalable(through key distribution over nodes)

--
class: toc

###When to use?
For persisting objects obtained by redundant and CPU and memory intensive computations. E.g. dictionary implementations

---
# Client Libraries

---
# Integrate Lindsay's Ditta docs with Spec

<!-- Like we did for the embedded help stuff -->

---

# How do we write & maintain this?

## 1.x

* By hand :(
* Hopefully the 1.x API isn't changing much :)

## 2.x

* Get it (mostly) for free from the framework (vert.x + jersey)

---

class: dark, middle, center

#fin

Questions?
