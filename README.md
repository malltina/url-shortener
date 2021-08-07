## Introduction

Due to following Malltina’s technical interview, we’d like to estimate the candidate’s coding skills. The purpose of the task is not to deliver a deploy-ready application, It is designed to evaluate the variant types of coding skills like your software development mindset, Object-Oriented Programming & Design, Coding style, software testing, and so on.

## The use case a candidate should implement
The URL shortener app takes a valid URL and generates a short version of it. Let’s check an example out. Imagine our domain address is https://shortener.app, If we give a URL like https://example.com/foo/bar?qs=baz, the app returns something like dRxi. So that, the https://shortener.app/dRxi returns https://example.com/foo/bar?qs=baz in an HTTP response format
Every shortened URL must have a unique URI and it could expire if the user wants.
That was all.

## Terms
- Use PHP (latest version preferred) to implement the above scenario
- You’re free to use any framework/tools, but, implement it either through pure PHP or micro frameworks like slim has a plus score
- Provide a clean, tested code
- You’re free to persist data anywhere, A RDBMS like MySQL or even a file-based persistence
- Neither authentication nor UI is needed
- Don’t forget to write a Readme
