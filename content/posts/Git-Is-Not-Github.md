---
title: "Git Is Not Github"
date: 2020-12-10T02:12:54-05:00
draft: true
---

[xkcdlink]: https://xkcd.com/1597/
[xkcdpng]: ../../img/git.png#center

## Finally Getting Git

As someone that has been mainly an infrastructure admin for their whole career, git and the whole concept of git was not something that has come naturally to me. I don't consider myself a coder/programmer but can slap together some basic shell scripts to help make my day to day a little easier. It wasn't until a couple years ago that I even thought about using git or starting to learn the basics of it.

When I switched my concentration from Unix Engineer to Cloud Engineer, it became apparent that I was going to have to get used to some form of version control. Infrastructure as Code is all the rage and for good reason. Almost anyone can just login to the console for AWS/Azure/GCP and click around and check boxes and make choices from dropdown menus to build out your infrastructure. That may be fine for small projects or your own personal use. I even still do it from time to time when I just need to test something real quick or learn how a service I've never used before works. But as the environment grows and becomes more complex, the need for repeatability, accountability, and collaboration makes anything but Infrastructure as Code a poor choice.

The focus of my day job is AWS. For better or for worse we have settled on using [AWS CloudFormation](https://aws.amazon.com/cloudformation/) for our Infrastructure as Code. Personally I think learning and using [Terraform by Hashicorp](https://www.terraform.io/) would be a better option and have gotten to play with it in other roles but it's not my decision and CloudFormation does what we need it to for how big our cloud presence is. We have hundreds of yaml files that have been used to create almost everything in our environment and working with these templates was my real first acquaintence with git.

[![xkcd 1597][xkcdpng]][xkcdlink]


