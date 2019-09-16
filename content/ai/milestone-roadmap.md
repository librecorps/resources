---
title: "AI Ethics & Transparency Roadmap Template"
date: 2019-09-03T11:02:05+06:00
type: "post"
weight : 2
---
## **Team Name** AI Transparency Roadmap

**Executive Summary**

This is your at a glance version of the document. Details and resources attached

* Milestone 1 - **Understanding the Data Flow**
  * Data Ecosystem Map - Open Ticket
  * Information Sharing Protocol - Open Ticket
* Milestone 2 - **Understanding the Algorithm**
  * Dataset Structure - Open Ticket
  * Common Traps Mitigations - Open Ticket
* Milestone 3 - **Sharing the Model**
  * Model Card Created - Open Ticket

Understanding Data Flow

 * Primary Goal: Create documentation that ensures you know what data you&#39;re using and how you plan on sharing it.

This first milestone is about initially understanding the underlying data powering your model. This is generally important for understanding the plumbing and getting an idea about privacy and implications that may arise from sharing data.

**Outcomes:**

*  [**Data Ecosystem Map**](https://docs.google.com/document/d/18Zg2JwUDJajVDX5VU0vMijL-c9yfumeAUYDc7rgC4iQ/edit#) **:** This is to document where their data is coming from, what&#39;s using it, stakeholders, etc. The benefit here is not just helping organize how data collection will work in production but also projecting partnerships which may need to be formed in the future.
*  [**Information Sharing Protocol**](https://docs.google.com/document/d/1MISHbWU7KGo4Z4AR-b222f6uXrtpQ-GJiJemGYoL--E/edit#) **:** This document is all about conducting an initial assessment of the sensitivity of information you are collecting, who you want to share it with, and how. It&#39;s fairly well thought out but is worth a review and potentially some edits. If you are in the EU, it might just be better to do a[Data Protection Impact Assessment](https://ico.org.uk/for-organisations/guide-to-data-protection/guide-to-the-general-data-protection-regulation-gdpr/data-protection-impact-assessments-dpias/what-is-a-dpia/)

Understanding the Algorithm

 * Primary Goal: Create documentation to ensure your whole team understand exactly how your model will be working. A large part of this will be determining the method of managing your datasets as they evolve over the development of the program.

**Outcomes:**

* [**Determine Dataset Structure**](https://humanitarian.atlassian.net/wiki/spaces/imtoolbox/pages/61734950/File+and+Dataset+Management): As you create new data sets, update them, and remove old datasets, you should follow an easy to follow protocol for keeping track of your various data sets as they&#39;re updated and deprecated.
* [**Common Traps When Building Models**](https://drive.google.com/open?id=10Bun6ucDUbTu7ALvoL_Ul0VhTSwJqkaq1zSJ7dvGRls): Review the following traps and document potential risks of your application falling into any of these traps.

Documenting the Algorithm

 * Primary Goal: Produce documentation that should be shared with the model.

**Outcomes:**

*  [**Document Machine Learning Model Card**](https://drive.google.com/open?id=1n9GhLGqhNCKuQei2RJfgTcUJroZVW8A3eYsS4eY_xFw) **:** Before you release or begin production use of your machine learning model, you can use the linked template to comprehensively document the effects, background, and purpose of your model. This will serve as a core document showing how the model makes the decision it does.
