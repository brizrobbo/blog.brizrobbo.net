---
title: "The Agile NOC'er (Part 1)"
date: 2017-11-29T13:21:59+10:00
---

## The experience of introducing agile practices into a reactive Operations team.

*Why "NOC’er"? In our Ops team, we term ourselves as in the “NOC” or “Network Operations Center”. We “belong to the NOC”, we are “on the NOC”, we are “NOC’ing” or we are “NOC’ers”. I just want to point out that the term NOC can sometimes be mistakenly limited to those working on networky-type issues only. Our team is much broader than that, encompassing all the tasks that a mature SaaS Operations team does. However, we do still refer to the NOC with much affection. :-)*

I've been working in software development and operations teams for quite a few years. In some of those teams, they even propounded that they "do" Agile. While I believe that using the Agile method is a journey, it wasn't until I started with Red Hat in 2016 that I began to learn what Agile really is. The team I joined (Red Hat Mobile) have been integrating the Agile method into their processes for a few years now, and they have benefited from a couple of leaders who really know what they are talking about in this regard.

In the Operations team at Red Hat Mobile, we've been watching all this "agile stuff" going on around us. We're already well-entrenched into the DevOps paradigm, and many of us are seasoned software developers - why can't we use Agile in the NOC?

This is a two-part post that attempts to document this journey. The first part outlines the problem we’re trying to solve, and the strategy we have chosen to solve it. The second part concerns the actual implementation, and how close our aspirations were to reality.

### The challenges

The traditional sprint/scrum approach does not suit the dynamic, reactive and unplanned milieu that a NOC operates within. For example, it 's hard to plan a sprint if you are always being side-tracked by critical production issues affecting customers. Priorities are often reset, and rightly so. The Kanban framework is better suited to these circumstances. However, many Operations-type teams complain that there is no real way to manage backlogs which explode for many of the same reasons as above.

The broad geographic distribution of the NOC team members further complicates the agile process. One of the critical features of the Agile methodology is the attention it pays to the communication of information. Organising a standup with all team members present is difficult when widely different time zones are involved.

### Our strategy

#### Kanplan

In the name of "Agile", proponents often gravitate towards a particular "style" (e.g. Scrum, Kanban, Lean, etc. ) and stick rigidly to it. However, for many teams and circumstances, rigidity does not work. There are too many nuances and ways of working. This classic infographic by [Lynne Cazaly](https://twitter.com/lynnecazaly) and [Craig Smith](https://twitter.com/smithcdau) shows an ever-growing number of methods as people try to define an approach which suits their own particular needs.

![image](/images/the-agile-nocer-pt1-1.jpg#c)

*Credit: [Lynne Cazaly](https://twitter.com/lynnecazaly/status/524373520550072321) and [Craig Smith](https://twitter.com/smithcdau)*

When commencing this project, I was encouraged to take a more holistic view of Agile in general. That is, "cherry pick what works, and come up with a hybrid approach which tries to solve your challenges as best you can". Personally, I think this is sage advice for those early in their Agile careers. I think the industry is also beginning to recognise this reality. For example, Atlassian's [Jira](https://www.atlassian.com/software/jira) product has recently introduced scrum-like backlog refinement into it's traditional Kanban offering, in an attempt to mitigate some of Kanban's natural limitations. They are calling this feature: "[Kanplan](https://www.atlassian.com/agile/kanplan)".

Here in the Red Hat Mobile NOC team, we have decided to adopt this Kanplan approach as the best-fit for our unique situation.

David Anderson has [written](http://www.djaa.com/kanban-cadences) about seven Kanban cadences (further summarised in this article by Paul Klipp):

1. Standup meeting

2. Replenishment meeting

3. Operations review

4. Delivery Planning meeting

5. Service Delivery review

6. Risk review

7. Strategy review

Notably missing is the **Backlog refinement activity**, which is the "plan" part in “Kanplan”. Also, we felt that we can't be truly Agile unless we add a **Retrospective** of some form. Adding these bring the number of ceremonies to 9:

1. Backlog refinement meeting (added)

2. Retrospective meeting (added)

#### The "boundary spanner"

Concerning the "geographically-challenged" agile team: my research revealed many stories of successful agile teams operating across spatial, temporal and cultural "boundaries". Across the board, the single biggest success factor was the implementation of a specific "boundary spanner" role. [Boundary spanning](https://en.wikipedia.org/wiki/Boundary_spanning) (link:https://en.wikipedia.org/wiki/Boundary_spanning) is a well-known concept of having a specific role that links internal teams (or sub-groups within a team) together to communicate information across "boundaries".

Therefore, to solve this problem we have specially commissioned a scrum-master role in each geographic region. In addition to the usual scrum-master functions, this role is asked to be this "boundary spanner" and liaise with other scrum-masters in other locations.

### Next - How did it all go?

In this post, I outlined what our basic challenges were in getting Agile processes into the NOC. I also described some of the broad strategies we thought would attempt to solve some of these problems. Stand by for Part 2, when the "rubber hits the road" and we honestly assess the effectiveness of these strategies.  
