---
layout: post
title:  "Feedback on Agile Software Development"
date:   2022-01-20
---

Inside the tech scene, using an agile methodology has established itself as the primary mode of organization. This takeover 
was not made without resistance, a good illustration is the conference by Erik Meijer *One Hacker Way* which begins with 
the punchline agile is a cancer that we have to eliminate from our industry. Another example is the talk  *Agile is dead* 
by Dave Thomas or *The death of Agile* by Allen Holub.

According to them the business made around this method, the use of many buzzwords and a certain heaviness in the setting 
up are the principal concerns. Even if this judgment can sound pretty hard, these concerns are mostly true, however the 
benefit you get makes those minor discomforts less important.

Agility emerged as a series of best practices and can be found in the 
[Manifesto for Agile Software Development](https://agilemanifesto.org/) published 
in 2001 by a group of programmers. This manifesto consists of 4 values and 12 principles. In order to apply these values 
and principles, different frameworks are available. It can be extreme programming, kanban, scrum or others. Scrum was 
originally a wrapper around extreme programming. But over time it has become the most popular, which is why we will 
focus on this framework.

In this article, we will see how to operate on a daily basis, with this agile method, now well implanted in 
modern businesses.


![Logo](/images/thesocialnetwork.png)

_The Social Network (2010) by David Fincher_

### The life under agile scrum as a software developer

The scrum method allows more structure in the development cycle : when it used to be a continuous linear process, 
it now has short iterations for a period of 2 weeks. An iteration is called a sprint, the sprint is punctuated by 
a set of recurring meetings. Here you can find what a sprint schedule look like with the meetings :

![Logo](/images/genericplanning.png)

First, the most common is the **Daily Standup Meeting or DSM** which is the shortest meeting, on average it’s 10 minutes 
(all other meetings are one hour or more) and takes place every day. Everyone explains what they are working on and 
if they are having difficulties. Then, on a weekly basis, there is the **refinement of the Backlog**, where future work 
that will be integrated into the next sprint is estimated. We estimate the difficulty of every future task with a vote 
system and eventually a discussion if there is no consensus on the vote.

At the end of each sprint we have 3 meetings : the **Demo**, when several teams of a similar functional scope regroup 
themselves to present key functionalities they developed during the sprint. Then the **SPM** for Sprint Planning Meeting 
takes place in two parts, a first where the product owner presents the different tickets that will be integrated into 
the next sprint and a second in which the developers divide the tickets into technical sub-tasks if necessary. And 
finally we have the **Retro**, which is very important, its objective is to determine what’s worked well or not during 
the iteration and to find future obstacles, all in the form of workshops.

Now that we saw what the schedule looks like, we can focus on five key points, to avoid an inconfort feeling from 
the project’s stakeholders.

### Technical subjects should not be on the side

It’s not uncommon to face a tension between product and technology, by pushing too much on the product side there is a 
serious risk of accumulation of technical debt. On the other hand, by making technology for the sake of technology, 
the result will be a delay in product advances. Unfortunately in most cases the importance is put on the product to 
the point of neglecting the technical side. But it’s possible to leverage the agile scrum method to avoid this and 
find an appropriate balance between both. To do this, I recommend always including technical development in the sprint, 
ideally up to 20%, which will allow short-term needs to be met. The second point is to include technical projects in 
the roadmap which will allow a reflection on the long term needs of the software. And the last point is to organize in 
the team a time dedicated to sharing knowledge / technical workshops. This moment allows learning from others, it helps 
progress toward pure technical knowledge.

### Task Estimation using points

Let’s take the following assignment "creation of a new endpoint of an already existing API", an estimation using time 
would be for instance two days and therefore the person who will take this will have two days to complete the new 
functionality. This mode can be reassuring for the management but will create unnecessary pressure on the development 
team, forcing them to make shortcuts such as not writing tests or worse to go faster. The quality of deliverables will 
decline as well as the motivation of developers who will not have the chance to produce quality code.

The alternative is to estimate by points. For instance we can have 
from 1 to 13 points. Above that limit it will be necessary to split the task into smaller ones. For the assignment 
above the estimation could be two points, and so the developer who takes this, knows that there is a little complexity 
and therefore is assumed to be finished relatively quickly. Indeed even with points we still have time management in 
our mind. So it’s a win-win situation where there is still estimation but without psychological pressure during the 
process of development.

### A set of rules around ticket management

In most cases in software development, tickets are used to complete a task. A ticket is most often written by the 
product owner but also by the developers themselves or the other stakeholders on the project. As this is an essential 
working tool, it is important that they are well written to avoid unnecessary waste of time. To illustrate this, if a 
bug is reported, the ticket must contain at least a clear title, the steps to reproduce the bug, the actual result 
(preferably with a screenshot) and the expected result. In addition to avoiding wasted time, it also provides clear 
documentation on the why and how of the changes that have been made. This is particularly useful for new members who 
join the project.

### The importance of the scrum master

The role is to guarantee the proper functioning of the sprints. This can be a full time job and in this case, 
the person will take care of several teams. Or it can be an additional mission of a team member. The scrum master, 
for instance, ensures that the daily standup meeting does not exceed the timebox. Is also organizes the sprint 
retrospective which is the most important meeting in the routine, and is indeed going to prepare workshops in 
advance for this. Another assignment is to make sure that no additional tickets are integrated into the sprint 
and the initial contract is respected. And finally there is also a privileged link with the product owner in order 
to transmit any problem related to the sprint.

### An approach to deal with emergency

Tasks based on points, presence of technical development, well-written tickets with a clear definition of ready/done, 
the presence of a scrum master, all of this allow quality work to be accomplished. But despite all this, there will 
unfortunately always be bugs in production or system failure which can disrupt the proper functioning of the sprint. 
To prevent this from happening it is interesting to assign a person in the team who will deal with all these urgents 
moments. If there are too many flaws, it means they are design implementation issues that need to be resolved as soon as 
possible. A week per person for this role is a good period of time.

Since agility is a synonym of flexibility, it’s always interesting to try new practices or remove elements if they do 
not work. In any case I hope this gave you some inspiration to enhance your own work methodology.

{% if site.disqus.shortname %}
    {% include disqus-comments.html %}
{% endif %}