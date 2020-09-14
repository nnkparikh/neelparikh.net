---
title: "Server Architectures For Handling Concurrent Connections"
date: 2020-06-13T20:49:53-07:00
draft: false
author: "Neel Parikh"
---


A scalable web architecture is composed of many components, one of which is a web server responsible for serving client requests. A scalable system is essentially one that remains operational under increasing workloads. In the context of web servers, one parameter to describe workload is the number of concurrent connection requests per second handled by the server. This post explores two different web server architectures for handling several thousand concurrent requests and introduces the I/O models provided by the operating system that make this possible.

## I/O Models
The workload of a a web server is characterized as primarily being I/O-bound. Since the web server application is a user-level process, the only mechanisms available to it for performing I/O operations are the ones that are provided by the operating system. In this discussion, we consider the I/O model provided under Linux as shown by the matrix in Figure 1.

## Thread-Based Connection Handling

## Event-Based Connection Handling

