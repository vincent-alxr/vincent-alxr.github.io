+++ 
draft = false
date = 2024-06-20T06:58:47+02:00
title = "Development on Deployment Service"
description = "Summary on the past development done and on the actual day"
authors = []
tags = []
categories = []
externalLink = ""
series = []
+++

## Introduction

To summarize effectively, i'm Hermann Vincent, Application developer designer at Alixir, my mission is to think, create and test softwares and i'm actually working a on deployment service.

As Alixir is a development studio, we have to work on different projects and they all have one thing in common, they need to be deployed in order to be visible firstly by the entire team and secondly by the client so that he can produce his series of tests.

As you can imagine, if you are in the business, manually deploying application can be time-consuming and redundant so there is the first mission of the deployment service. ***Automatize processes***. Yesterday i finalized the first version, the **v0.1**.

Who embarks with it:
- An SSE api endpoint so that the team can call to deploy any docker compose project with just the need of providing the repository name and the branch name et get the logs in live
- An api endpoint to get the logs

## Today

This morning, i took a branch i have created named *refactorization*, i did it in the past as an R&D process with 0 priority and it is almost finished, it embark with it plugins arch / testing / github action for build and testing / docker container development environment.

I rebased my refactorization branch with the master branch which got some improvement

After that, i stopped on this branch and get back on current release sprint board. This board actually target the ***v0.2*** and it have seven issues. theses issues is here to improve the software by adding auto subdomain binding, creating a discord bot, creating a github app to get access to any github repository without the need of playing with an ssh key which have some limitations.

So this morning i have estimated charges of each issues, placed the right tag on theses issues and did a better description of each cards, so that i can go forward on this sprint effectively

After that i have focused on the first two tasks which is improving the security of the API