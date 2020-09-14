---
title: "Server Architectures For Handling Concurrent Connections"
date: 2020-06-13T20:49:53-07:00
draft: false
author: "Neel Parikh"
---


A scalable web architecture is composed of many components, one of which is a web server responsible for serving client requests. A scalable system is essentially one that remains operational under increasing workloads. In the context of web servers, one parameter to describe workload is the number of concurrent connection requests per second handled by the server. This post explores two different web server architectures for handling several thousand concurrent requests and introduces the I/O models provided by the operating system that make this possible.

## I/O Models
A web server is characterized as primarily executing I/O-bound operations and so if 

## Thread-Based Connection Handling

## Event-Based Connection Handling

