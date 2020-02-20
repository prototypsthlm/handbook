# The tech lead role

This document aims to describe the tech-lead role in detail and consists of the following sections:    
1. [Why does Prototyp exist?](#why-does-prototyp-exist)
2. [In what ways do these goals inform the way we work?](#in-what-ways-do-these-goals-inform-the-way-we-work)
3. [What are the responsibilities of the roles at Prototyp?](#what-are-the-responsibilities-of-the-roles-at-prototyp)
4. [Responsiblity categories](#responsibility-categories)
    1. [Sales support](#sales-support)
    2. [Tech decisions](#tech-decisions)
    3. [Estimation](#estimation)
    4. [Writing tenders](#writing-tenders)
    5. [Contribute to pitches together with our partner agencies](#contribute-to-pitches-together-with-our-partner-agencies)
    6. [Continuously capture requirements (both high-level and detailed)](#continuously-capture-requirements-both-high-level-and-detailed)
    7. [Backlog grooming](#backlog-grooming)
    8. [Sprint planning](#sprint-planning)
    9. [Maintain and protect our agile work process (TDD, CRs, CI/CD etc.)](#maintain-and-protect-our-agile-work-process-tdd-crs-cicd-etc)
    10. [Manage customer expectations (and saying no to the client)](#manage-customer-expectations-and-saying-no-to-the-client)
    11. [Keep deadlines and continuously follow up on hours spent/budget remaining](#keep-deadlines-and-continuously-follow-up-on-hours-spentbudget-remaining)
    12. [Maintaining high project quality, delivering things we can be proud of](#maintaining-high-project-quality-delivering-things-we-can-be-proud-of)
5. [In closing](#in-closing)

## Why does Prototyp exist?
*... to be such a great company that we inspire others to do what we do*

* No overtime
* Profitability
* Strong company culture
* Work in teams, from our own office
* Allow part-time work
* Allow remote work when needed
* Technical curiosity and agnosticity
* Stay on the cutting edge of tech
* Allow our employees the opportunity to grow professionally in a variety of areas

## In what ways do these goals inform the way we work?

Several of the goals above is directly tied to the role we call “tech lead”. If we want to be profitable and not work
overtime, we need to provide sensible cost estimates to our clients, and to do that we need someone technical
understanding the business needs and requirements at an early stage. If we want to explore new tech and stay on the
cutting edge, we need to be the ones in a position to choose or recommend the technical solution. Here are some more
reasons why we have this really broad tech lead role:


* Align sales with delivery – no over promise and under deliver
* Tech present in early stages of customer relationship – build trust right away (= great for sales)
* Flexibility – the tech lead can focus on the area which needs the most attention for the moment, e.g. planning in the
early stages and coding in the later stages.
* Continuous technical validation – we can steer away from unnecessarily costly or bad solutions right from the early
stages of the project
* Developer empowerment – no one is thought of as being “just” a coder who needs to be told by someone else what to do
* Professional development – give all employees the opportunity to expand their competency within a wide range of skills
* Remove admin roles not adding (enough) value
* Shorten communication paths to minimize misunderstandings

## What are the responsibilities of the roles at Prototyp?

//TODO

Below follows detailing for most of the responsibilities from the table above, from a tech lead perspective.
Each heading could be used as a basis for discussion.

## Responsibility categories

### Sales support

A tech lead is present at an early meeting (often the first meeting) with prospective clients. The role of the tech lead
in this meeting is to build trust. To listen to their challenges and the business problem they’re trying to solve. Give
feedback from a tech perspective and preferably suggest a possible solution. Convey a sense of confidence and
competency: we’ve got this, we will solve this problem for you and you can spend this (considerable) amount of money
without worry. Building trust does not mean saying 'yes we can do everything' just because it is a sales meeting, 
sometimes quite the opposite.

### Tech decisions

The tech lead is often responsible for choosing what tech is best suited to a certain project. What exactly is chosen
varies widely and can include things like coding language, database, PAS provider and what libraries and frameworks to
use. There are always multiple aspects to take into consideration when making these choices, the most important being
(in order of importance):

1. Solving the problem in the best way, considering the budget and business requirements
2. Fitting the client’s pre-existing tech environment
3. Using a good mix between new and tried-and-true tech to keep things interesting for the dev team without risking the
project and sticking the client with niche and dead-end tech

The single most important thing when making a tech choice or recommendation is to be able to justify your decisions with
concrete reasons, e.g. “We’re targeting Google Assistant because it’s the most widely used voice assistant” or “We’re
using Elixir because we believe the high developer productivity coupled with the speed of the Erlang VM will provide
the best user experience for the least amount of money” or “Your DevOps team already use CircleCI and GCP so we’re
using them as well” or “We’re recommending React because it’s the most widely used frontend framework and we can share
part of the codebase when we build native apps in React Native down the line”.

### Estimation

When we have a project scope and a suggested solution, we almost always need to provide a high-level cost estimate. The
tech lead is responsible for creating an estimation document and leading the estimation together with the team.

### Writing tenders

Generally a tender is mostly written by a business lead or partner agency, but the tech lead is often responsible for
describing the proposed technical solution (with justifications, see above) and the cost estimate.

### Contribute to pitches together with our partner agencies

For a tech lead, a pitch meeting is a combination of being sales support and justifying a technical solution. The
primary goal in the pitch is the same as in any early sales meeting, to build trust (see “Sales support” above). But,
you’ll most likely also have to present and justify your tech decision suggestions and cost estimate
(see [“Tech decisions”](#tech-decisions) above.)

### Continuously capture requirements (both high-level and detailed)

The tech lead is responsible for setting up recurring meetings with the client. At a minimum, these meetings need to
accomplish the following:
1. Add any new requirements, bugs etc. to the project backlog
2. Prioritize the project backlog
3. Get feedback on what has been done so far

### Backlog grooming

Backlog grooming is the process of keeping the backlog up to date with the latest developments in the project. Ever
changing requirements and priorities from the client will make it necessary to continuously add, edit, remove and
reorganize stories in the backlog.
 
As part of the grooming, the tech lead takes features from the project backlog and does a preliminary breakdown into
stories in (usually) Pivotal Tracker. This is a concession to efficiency; in a perfect world the entire team would do
all of the feature breakdown together, but we have found that sprint planning is much less tedious if someone does some
of the breakdown-work ahead of time. But a lot of the technical design happens in the breakdown process, so It’s not
advisable for the tech lead to always do all of the breakdown alone. It’s a balancing act, but try to break down
uncomplicated things when grooming and leave the complicated features to the sprint planning meeting.

Backlog grooming (and the planning and estimation it enables) is absolutely instrumental to our work process and the
success of our projects, and is therefore perhaps the most important responsibility of the tech lead.

### Sprint planning

The tech lead is responsible for scheduling sprint planning meetings with the team to keep enough estimated stories in
the backlog so every team member is working on the most prioritized stories and can keep working without running out of
things to do. The rule-of-thumb is to always have about two sprints worth of stories estimated and ready in the backlog.
Generally, it’s really hard to achieve this but our experience is that when we manage to do it, we get a payoff in
increased velocity. So consider it a recommendation and something to strive for, but don’t lose any sleep when you
don’t quite get there.

### Maintain and protect our agile work process (TDD, CRs, CI/CD etc.)

The tech lead makes sure everyone on the team knows about and is working according to our agile work process. This
includes the team doing code reviews on all stories, making sure CI/CD is set up early in the project, deciding
(with the team) when and if TDD is appropriate in the current project, making sure the team has a common DoD and that
peer testing is done on all stories.

### Manage customer expectations (and saying no to the client)

We manage customer expectations primarily by having frequent planning and demo meetings, and by involving the client in
decisions along the way. Still, the client often want to add new requirements which will make the project cost more and
miss the deadline. This is fine, if the customer is ok with that. If the customer is not ok with that it’s the tech lead
who usually have to say no in a respectful way and explain why. If the customer is pushing hard for something and it’s
hard to say no, remember you can always get help from the business lead or a more experienced tech lead.

### Keep deadlines and continuously follow up on hours spent/budget remaining

As a tech lead, you should have a clear image of the status of your project. This is actually often not that easy to
have, so you need to sit down every week and build that image for yourself. Although you can never know for sure, you
need to have at least a pretty good answer to questions like “Are we going to finish on time?” and “What’s done and what
still remains to be done?”.

The tech lead is responsible for following up on hours spent in the project, and how that corresponds to any deadlines
and keeping the budget. The most important thing is to raise any issues as early as possible, while there’s still time
to make choices affecting how we spend the remainder of the budget. It’s much, much easier to tell a client “It’s going
slower than expected, so we need to find a way to decrease the scope or increase the budget or we’re not going to meet
the deadline. The choice is yours but I’m happy to help you find ways to simplify some features to get us there” than it
is to say “I know the deadline is tomorrow, but we’ve spent the budget and we’re not done”.

### Maintaining high project quality, delivering things we can be proud of

One of the hardest responsibilities of the tech lead (and of everyone at Prototyp) is to make sure we maintain a high
level of quality in everything we do. This requires experience – to know what is an acceptable level of polish and what
is not. It’s especially tricky when the budget is tight and you need to decide if we need to put some non-billable hours
into the project to be able to deliver something we are proud of. When this happens, remember to ask for help with the
decision from the business lead and more experienced tech leads.

## In closing

Being a tech lead is hard and alot of responsibility. It’s something that takes practice to get right, it’s something
you learn and get better at over time. No-one gets all of this right at the first try, it’s ok to fail.
