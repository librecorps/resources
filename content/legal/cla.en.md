---
title: "Contributors License Agreements"
date: 2018-12-29T11:02:05+06:00
type: "post"
weight : 2
---

**What are CLAs used for?**

So a Contributor License Agreement is often seen being used in open source projects to form a legal agreement between an individual or company and a project maintainer.
This agreement usually includes a waiver of copyright as well as the right to patent their contribution.

CLAs became popular during the early days of open source and Free software. 
Prior to the growth of platforms such as Github and GitLab patches were often emailed to mailing lists and accepted by maintainers as such. 
Unfortunately, this method of communication did not always make clear the waiver of rights to whichever license the codebase was licensed under. 
In order to minimize risk on the maintainer's part, CLAs were developed to make that waiver explicit.

CLAs are less popular, even on large projects, due to the popularity and use of platforms such as Github. 
The Github [terms of service explicitly state](https://help.github.com/en/articles/github-terms-of-service#6-contributions-under-repository-license) that a user waives their copyright to whichever license is included in the repository at that time of the contribution. 
This is considered by most to fulfill the need of a CLA.

**What alternatives exist for CLAs?**

Other than the terms of service provided by Github, the Linux Foundation introduced a Developer Certificate of Origin (DCO) as a more lightweight method to have developers waive their rights.
Instead of maintaining a database of signed contracts, users can simply sign [using specific formatting of commit messages](https://probot.github.io/apps/dco/) _provided a project publishes a CLA/DCO in its repository._

**What do I need to develop my own CLA?**

Unlike licenses, CLAs are not as standardized due to their lack of popularity.
Apache [has an individual CLA](https://www.apache.org/licenses/icla.pdf) which can be taken and modified. 
Fedora [also has an "open-source friendly" CLA](https://fedoraproject.org/wiki/Legal:Fedora_Project_Contributor_Agreement) which can serve as a reference for an easily understandable individual CLA.
I would recommend working with a lawyer to modify the document to ensure that there is clarity on which rights you expect contributors to waive.
