
class: dark, middle

# Swagger

What's Swagger & why should I care?

.intro-img[![intro](./img/swagger.png)]

<!-- a Swagger implementation of the REST API that will let the user interactively explore the API
and try it out, instead of just reading it from a PDF. I think Duncan has plans to make this really
effective, so that we can automatically both push out the Swagger API documentation and also client
libraries. That will not only contribute to the usability of the product, but also it’s quality,
since it forces synchronization of the product and the documentation. -->

---
class: toc

# What is Swagger?

* Spec document for our REST API
* Written in JSON

---

# What does it look like?

Replace with a real example:

```json
{
  "paths": {
    "/pet": {
      "post": {
        "tags": [
          "pet"
        ],
        "summary": "Add a new pet to the store",
        "description": "",
        "operationId": "addPet",
        "consumes": [
          "application/json",
          "application/xml"
        ]
      }
    }
  }
}
```

---
class: toc

# Why should I care?

<!-- Benefits -->

* Swagger UI
* Client Libraries
* REST API Mock Instances
* Integrate Lindsay's Ditta docs with Spec

---

# Swagger UI

---
# REST API Mock Instances

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
