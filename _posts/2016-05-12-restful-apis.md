---
layout: post
title:  "Restful APIs"
date:   2016-05-12
categories: jekyll update
---

An `API` is an abbreviation referring to: application program interface (API) that uses `HTTP requests` to `GET`, `PUT`, `POST` and `DELETE` data. These are also referred in general as `CRUD-operations`. Representational state transfer (REST), which is used by browsers, can be thought of as the language of the Internet. Now that cloud usage is on the rise, various application programming interfaces (APIs) are emerging to expose Web services and REST is a logical choice for building APIs that allow end users to connect and interact with cloud services. RESTful APIs are a cup of tea for many leading web platforms including Google.

A `RESTful API` breaks down a transaction to create a series of small modules, each of which addresses a particular underlying part of the transaction. This modularity provides developers with a lot of flexibility but can also be challenging for developers to design from scratch.

A RESTful API simply uses "PUT" to change the state of or update a resource, which can be an object, file or block; ``"GET"`` to retrieve a resource; POST" to create that resource; and "DELETE" to remove it.

Here is a code snippet showing a simple GET request using Python to retrieve a value from a saved location.

{% highlight ruby %}
>>> import requests
>>> ret = requests.get(url)
>>> ret.staus_code
200
#=> will retrieve the value stored in that location.
{% endhighlight %}

My next post shall feature exclusively on how to implement the RESTful api with a special emphasis on CRUD-operations.
