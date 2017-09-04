---
layout: post
title: "Document your RESTful API with Swagger"
excerpt: "As a recent task it was necessary to create a RESTful webservice based on parts of an existing web application."
tags: [netzkaempfer, socialwar]
comments: false
image:
  feature: netzkaempfer/netzkaempfer_header.jpg
---

{% include _netzkaempfer-archive.html %}
<br/><br/>
As a recent task it was necessary to create a RESTful webservice based on parts of an existing web application. The search for a tool to documentate the design and discuss it resulted in [Swagger](https://developers.helloreverb.com/swagger/). We gave it a try and the first results are promising.
<br/><br/>
You can create and manipulate your API configuration in a JSON format manually or generate it automatically from your implementation. There exists modules for various RESTful frameworks like node.js, Java JAX-RS, etc. The generated documentation needs to be hosted on a web server. Each method can be tested by filling the specfied parameters in proper input forms.
<br/><br/>
Altogether Swagger seems to be a nice tool to generate API documentation with a nice layout fast, keep it up to date on code changes and quickly test any given method.