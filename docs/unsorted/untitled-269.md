# Snyk Code language and framework support

* [ Introduction to Snyk Code](https://github.com/snyk/user-docs/tree/58f91d848e16ddf2ffcca3711d6b8852412be402/hc/en-us/articles/360017059758-Introduction-to-Snyk-Code/README.md)
* [ Snyk Code language and framework support](https://github.com/snyk/user-docs/tree/58f91d848e16ddf2ffcca3711d6b8852412be402/hc/en-us/articles/360016973477-Snyk-Code-language-and-framework-support/README.md)
* [ Using Snyk Code \(web\)](https://github.com/snyk/user-docs/tree/58f91d848e16ddf2ffcca3711d6b8852412be402/hc/en-us/articles/360017147558-Using-Snyk-Code-web-/README.md)

## Snyk Code language and framework support

Snyk Code currently supports:

* [Java](untitled-269.md)
* [JavaScript and TypeScript](untitled-269.md)
* [Python](untitled-269.md)

### Language type and framework support

Snyk Code can work with a variety of relevant language types:

* Dynamically typed languages such as JavaScript or Python.
* Optionally strong typed languages such as TypeScript.
* Strong typed languages such as Java.

Contact Snyk for a full list of support for frameworks, libraries and vulnerability types

#### Framework support

To support a specific framework, Snyk Code needs to both support the relevant language, and to be trained on projects using the framework. The found patterns are then annotated by our security team and extended by curated content.

#### JavaScript frameworks

These are some of the supported frameworks for JavaScript; contact Snyk for a full list of supported frameworks.

* **React**: Open-source, front end, JavaScript library for building user interfaces or UI components for websites and mobile applications.
* **Vue.js**: Open-source model–view–viewmodel front end JavaScript framework for building user interfaces and single-page applications.
* **Express**: Back-end web application framework for Node.js, released as free and open-source software.It has been called the de facto standard server framework for Node.js.

These are some of the supported frameworks for Java; contact Snyk for a full list of supported frameworks.

* **Apache Camel**: Open source framework for message-oriented middleware with a rule-based routing and mediation engine.
* **Apache Struts**: Open-source, MVC framework for creating elegant, modern Java web applications.
* **Spring MVC**: The Spring Web model-view-controller \(MVC\) framework.
* **Spring JDBC**: The Spring JDBC data access layer, a simple ORM.
* **Jakarta XML Services**: Framework to implement XML-based Web Services.

These are some of the supported frameworks for Python; contact Snyk for a full list of supported frameworks

* [Django](https://www.djangoproject.com/): a framework for full-stack web application development and server development.
* [Flask](https://palletsprojects.com/p/flask/) a lightweight [WSGI](https://wsgi.readthedocs.io/) web application framework

### Language support with Snyk Code AI Engine

Snyk Code is based on a semantic AI using an analytics engine, the Snyk Code AI Engine.

When files are provided for analysis, the engine determines which file to feed into which parser, in a language-independent common intermediate format. This format preserves and exposes characteristics of the scanned source code.

This technology allows Snyk Code to:

* Support a variety of programming languages easily.
* Support multi-language projects, spanning security scans over the different languages.
* Unveil interfile issues, such as issue patterns spread over several source files, which are typically especially hard to track.
* Find issue patterns using the Snyk Code engine, compiling the found issues as a report.

#### AI engine capabilities

The AI engine can analyze the following in your code:

* **Hard coded secrets**: including use of account-names, passwords, or secrets in the code. 
* **Coding issues**: problems such as dead code, branches that are predefined, and branches having the same code on each side.
* **Type inference**: determining the initial type and its changes; this is of special interest for dynamically typed languages.
* **Value ranges**: infers possible values for variables used to call functions to track off-by-one errors in arrays, division-by-zero, and null dereferences.
* **Data flow**: follows the flow of data within the application, from the source to the sink. Combined with AI-based learning of external insecure data source, data sinks, and sanitation functions, this enables a strong taint analysis.
* **Use of APIs**: using open source or the documentation of frameworks to learn how functions need to be used, can identify API misuse such as using the wrong parameter type or calling with the wrong value range. This mechanism can also identify use of insecure functions.
* **Control Flow**: identifies null dereference or race conditions by modelling each possible control flow in the application.
* **Point-to Analysis**: identifies multiple possible issues including from buffer overruns, null dereferences, and type mismatches, by modelling the usage of memory in variables and references.
