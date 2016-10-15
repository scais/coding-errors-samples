# Coding errors samples  

This repository contains samples of coding errors in open source projects.  

## Why repository with samples of coding errors?
This repository is part of bigger research project focused on [technical debt](https://en.wikipedia.org/wiki/Technical_debt) in software. The research is concentrating on techniques for improving the identification and evaluation of *technical debt* in source code.  The current goal is to investigate the time needed to fix a coding error (coding errors can be considered as technical debt [[1]](http://www.slideshare.net/castsoftware/estimating-the-principal-of-an-applications-technical-debt) ). 

## How can I help?
It is simple - clone the repository, fix the reported coding issues and share the time you needed to fix them.

##### What are the problems I need to fix?
Each sample contains one coding error to fix. The code of the samples starts with a short preamble identifying the error (project, line, error description) and ends with a row ```Time to Fix```:

```java
/*
 * Project: https://github.com/awesome/awesomefoo
 * File: Foo.java
 * Link: https://github.com/awesome/awesomefoo/564fa64sdfa/Foo.java
 * Line: 160 [147]
 * Error text: Foo is too awesome
 * Error description link: http://findbugs.sourceforge.net/bugDescriptions.html#TOO_AWESOME
 *
 * ==========================
 * Time to fix: %h %m %s
 * ==========================
 */
```

##### How can I share my results?
You have several options here. You can either create a pull request, i.e. fork the repository, commit your times and fixes, and create  [pull request](https://help.github.com/articles/about-pull-requests/) **OR** create an issue in this repository and paste here your changes and times **OR** send your results to ![alt text](http://home.zcu.cz/~scais/mail/mail.png "e-mail")

## I found a nice coding error, can I submit it?
Sure! Please create a *pull* request.


