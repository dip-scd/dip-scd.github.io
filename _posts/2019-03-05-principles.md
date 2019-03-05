---
layout: post
title: "Principles"
description: "List of personal working principles learned hard way"
category: articles
tags: [processes, documentation]
comments: false
---

### Calendar should be used instead of personal TODO list
Each time when a new task is received, don't put it into a TODO list. Create a calendar entry instead. Such practice allows to develop the estimation skill quickly - it will be immediately visible if the task took more time than was planned. In such a case, scheduled tasks are shifted. Also, it allows to see, how many hours (days, weeks) are already filled with tasks. Tasks can be re-estimated and shifted. However, if there is a planned task, it always must have a designated time slot for it.

### Periodical meetings must be replaced by continuous information flow
Any periodical meeting (such as sync-up, standup, demo, grooming) is a workaround that mitigates the lack of proper communication channels in the organization. It can and should be replaced by a continuous flow of information, automatic documentation and ad-hoc meetings with concrete agenda.
#### Problem description
Periodical meetings are one of the most favorite tools of the incompetent managers. They create an illusion of awareness and control, fill the working time and allow to avoid digging into the problems, replacing it by "status updates." They have a non-concrete agenda and quickly evolve into rituals. Symptoms of the problem include the following:
* Audience of the meeting grows with time.
* Fewer and fewer experts participate in the meeting while the percentage of line managers grows.
* Content of the meeting doesn't match its title. Even if meeting series initially has a specific topic, such series with time transforms into a generic sync-up for a given half-random group of people.
* "Let's discuss it's on tomorrow sync-up." People are holding important information and avoid the discussions until the next meeting occurrence, instead of just sharing the information or setting up the discussion as soon as possible.
* "No updates or questions from my side." 

### Documentation must be used as a primary source of knowledge
Knowledge must be shared via documentation. Emails, IM, comments, meetings are for active discussions at the stage when decision or expertise regarding the specific topic is still emerging (i.e., for expert-to-expert communication). Once knowledge is acquired, it must be communicated to consumers via persistent documentation. Documentation can be further commented, discussed and changed, but the main point is that it can be easily referenced and shared.
#### Problem description
While there are one-time decisions, a vast majority of information, that is generated in the organization, is used more than one time and by multiple people. If there is no established documentation culture, the following symptoms will be observed:
* There are "oracles" that need to be asked each time anyone needs to get the knowledge about the process or technical system.
* Same questions are asked multiple times and answered via emails, IM and meetings. People are copy-pasting the old messages and retelling the sacred knowledge to newcomers.
* "No, this is not what I said." Agreements and commitments are periodically broken, but no one is sure that such an agreement had the place.
* "I don't have time for documenting this." People keep repeating the same text or spoken messages instead of placing the same message into the persistent documentation system. Communicating the knowledge takes O(n) instead of O(1) for the source of knowledge, where n is a number of knowledge recipients.

### There should be continuous processes automation
Processes automation is an essential activity that must have dedicated resources. Every trivial, repetitive activity that is done by humans is a waste of organization resources. Such type of activity is especially ironical in software development companies.
#### Problem description
Often, while almost everyone in the organization agrees that "automation is good," there are no actual measures regarding this. Assigning developer or two to the process automation tasks seems to be a waste of resources, especially when deadlines are approaching (and they always are). In the case of outsourcing companies, the time of such developers can't be sold to a customer. Instead, the company hires more line managers or assistants to do a trivial job. Even if some automation attempts are made, they often quite clunky and demand the machine-like behavior from the humans ("this form must be filled exactly using this format for our script to work") instead of liberating them from the mechanical tasks and rigid interfaces by introducing some minimal machine learning. Symptoms:
* One of the responsibilities of line managers is to prepare reports by trivially recomposing summaries of the reports from their subordinates.
* Operations that are atomic from the organizational point of view are technically non-atomic and require the fixed set of actions to be performed by a human each time when such operation is made. For example, passing the ticket with requirements to the development teams requires filling the same three (or five, or fifteen) fields with the same values each time.
* People are obliged to submit periodical, formal reports. For example, time reporting, where each day (week, month) same form is submitted with the same values (just filling some table with a bunch of '8h').

### Meetings must either have a small audience or be moderated
Meetings with more than ten people must have a moderator. There is no formal theory behind this number. It is just an empirical observation.
#### Problem description
A large non-moderated meeting may indicate that problem was not decomposed enough, that organizer of the meeting is not aware of the roles and expertise distribution, or that architecture of organization is not effective, with a lot of entangled departments and authority-expertise disbalance. Symptoms:
* Some or even majority of people keep doing non-meeting activities (such as checking emails). This means that these people are not required on this meeting, no matter their titles or roles.
* Audience is split into two or more groups, trying to discuss different topics simultaneously.
* No concrete decision is made, except the one that one more meeting is required (or even series).
* As it turns afterward, some people had important pieces of information but didn't share them during the meeting because they didn't have a chance to speak.

### Non-working processes must be removed or updated, not ignored
If the process is unrealistic and clunky, it must be reviewed and changed asap, instead of ignoring the fact that everyone is working around this process. If the process in its current form is considered essential (for example, it’s related to security), then enforcing mechanisms should be introduced. One way or another, there must not be the case that process exists, but people are not working by it.
#### Problem description
If a company doesn't have functional feedback loops, it will tend to produce many processes that are not realistic or usable. This often happens when a company hires some consultant to "set up the process." Alternatively, when some framework is adopted by higher management without adapting it to this specific organization. Alternatively, one department is producing processes for other departments. This means that people, who create the process, are not the ones that would be affected by it. Symptoms:
* Nothing is done by the process and everyone knows it. 
* Process is documented but no one reads it. It is perceived as something either obsolete or from a parallel reality.
* Artifacts, that process supposed to produce, are created only before an audit or assessment.
* People are punished for criticizing the process. Process stays unchanged.

### Obsolete information must be removed
Often much more can be achieved by removing a process, implementation, specification, then by adding a new one. Therefore there should be a continuous (rather than stop-the-world) process of refactoring of the technical systems and organization itself.
#### Problem description
People tend to avoid removing things because they don’t feel they have an authority to do so. Also, removing something requires a detailed analysis of the context while adding something seems more comfortable and safer. Symptoms of the problem:
* There is redundancy in the documentation, with inevitable contradictions. Each time when the behavior of the documented system must be updated, a whole new set of artifacts (static documents, wiki pages) is created instead of editing existing ones.
* Source code contains multiple implementations of the same or very similar function. Developers don't feel the ownership of the whole code base and keep inventing the wheel in their small area instead. 
* Process is overloaded with multiple mandatory steps and artifacts because each time, when a gap was found, it was mitigated by an additional step instead of reviewing the process as a whole.

### Information must be referenced, not copy-pasted
In the case of documentation, this means that it should be created as hypertext, not text. In the case of communication, this means that proxy-mailing and similar practices must be avoided. 

### External knowledge must be reused
Establishing internal mentorship and knowledge sharing is a good thing, but it’s important not to forget that there is a whole world out there. There is no need to re-invent internal best coding practices or project management essentials course. There is enough high-quality public information on that topic. 
