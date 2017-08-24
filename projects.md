---
layout: default
title: Projects
---

***Vroom: Accelerating the Mobile Web with Server-Aided Dependency Resolution***

[Slides](https://docs.google.com/presentation/d/1AKqUnORLFiN3zoKrSxb2jSRHs-qVJiJG7YMuZw6rfFk/edit?usp=sharing)

Accessing web pages from mobile devices over a mobile connection is slow.
Prior studies attributed high page load times to dependencies within the 
page load process: network latency in fetching a resource delays its processing,
which in turn delays when other resources can be discovered and fetched.
Vroom is a rethink of the process of loading a web page that securely address the
inefficiency of the page load while preserving the end-to-end nature of the web.
Vroom does this by decoupling resource discovery from parsing and executing.
This allows the CPU and the network to be used independently. As a result, 
VROOM reduces the median page load time by more than 5 seconds 
across popular News and Sports sites.
