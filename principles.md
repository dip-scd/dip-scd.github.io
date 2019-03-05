### Periodical meetings must be replaced by continuous information flow
Any periodical meeting (such as sync-up, standup, demo, grooming) is a workaround that mitigates the lack of proper communication channels in the organization. It can and should be replaced by a continuous flow of information, automatic documentation and ad-hoc meetings with concrete agenda.
#### Problem description
Periodical meetings is one of the most favorite tools of the incompetent managers. They create an illusion of awareness and control, fill the working time and allow to avoid digging into the problems, replacing it by "status updates". They have non-concrete agenda and quickly evolve into rituals. Symptoms of the problem include the following:
* Audience of the meeting grows with time.
* Less and less experts participate in the meeting while percentage of line managers grows.
* Content of the meeting doesn't match it's title. Even if meeting series initially has a specific topic, such series with time transforms into a generic sync-up for a given half-random group of people.
* "Let's discuss it's on tommorrow sync-up". People are holding important information and avoid the discussions until the next meeting occurence, instead of just sharing the information or setting up the discussion as soon as possible.
* "No updates or questions from my side". 

### Documentation must be used as a primary source of knowledge
Knowledge must be shared via documentation. Emails, IM, comments, meetings are for active discussions at the stage when decision or expertise regarding the specific topic is still emerging (i.e., for expert-to-expert communication). Once knowledge is acquired, it must be communicated to consumers via persistent documentation. Documentation can be further commented, discussed and changed, but the main point is that it can be easily referenced and shared.
#### Problem description
While there are one-time decisions, vast majority of information, that is generated in the organisation, is used more than one time and by multiple people. If there is no established documentation culture, following symptoms will be observed:
* There are "oracles" that need to asked each time anyone needs to get the knowledge about the process or technical system.
* Same questions are asked multiple times and answered via emails, IM and meetings. People copy-pasting the old messages and retelling the sacred knowledge to a newcomers.
* "No, this is not what I said". Agreements and commitments are periodically broken but no one is really sure that such agreement had place.
* "I don't have time for documenting this". People keep repeating the same text or spoken messages istead of placing exactly the same message into the persistent documentation system. Communicating the knowledge takes O(n) instead of O(1) for the source of knowledge, where n is a number of knowledge recipients.

### There should be continuous processes automation
Processes automation is an essential activity that must have dedicated resources. Every trivial, repetitive activity, that is done by humans is a waste of organization resources. Such type of activity is especially ironical in software development companies.
#### Problem description
Often, while almost everyone in the organization aggrees that "automation is good", there are no actual measures regarding this. Assigning developer or two to the process automation tasks seems to be a waste of resources, especially when deadlines are approaching (and they always are). Or, in case of outsorcing companies, time of such developers can't be sold to a customer. Instead, company hires more line managers or assistants to do the trivial job. And even if some automation attempts are made, they are quite clunky and demand the machine-like behaviour from the humans ("this form must be filled exactly using this format in order for our script to work") instead of liberating them from the mechanical tasks and rigid interfaces by introducing some minimal machine learning. Symptoms:
* One of the responsibilities of line managers is to prepare reports by trivially recomposing summaries of the reports from their subordinates.
* Operations, that are atomic from the organizational point of view, are in fact non-atomic and require the fixed set of actions to be performed by a human each time when such operation is made. For example, passing the ticket with requirements to the develoment teams requires filling the same three (or five, or fifteen) fields with exactly the same values each time.
* People are obliged to perform periodical, formal reporting. For example, time reporting, where each day (week, month) same form is submitted with the same values (just filling some table with bunch of '8h').

### Meetings must either have small audience or be moderated
Non-moderated meeting with 5+ people is likely to be non-productive. With 10+ people it’s almost inevitable. These numbers are just empirical observations. There is no formal theory behind them.
#### Problem description
Large non-moderated meeting may indicate that problem was not decomposed enough, that organiser of the meeting is not aware about the roles and expertise distribution, or that architecture of organization is not effective, with lot of entagled departments and authority-expertise disbalance. Symptoms:
* Some or even majority of people keep doing non-meeting activities (such as checking emails). This simply means that these people are not required on this meeting, no matter their titles or roles.
* Audience is split into two or more groups, trying to discuss different topics simultaneously.
* No cocrete decision is made, except the one that one more meeting is required (or even series).
* As it turns afterwards, some people had important pieces of information but didn't share them during the meeting because they didn't have a chance to speak.

### Only actually working processes
If the process is unrealistic and clunky, it must be reviewed and changed asap, instead of ignoring the fact that everyone is working around this process. If the process in its current form is considered essential (for example, it’s related to security), then enforcing mechanisms should be introduced. One way or another, there must not be the case that process exists, but people are not working by it.
#### Problem description
If company doesn't have actually functional feedback loops, it will tend to produce a lot of processes that are not realistic or usable. This often happens when company hires some consultant in order to "setup the process". Or when some framework is adopted by higher management without adapting it to this specific organisation. Or one department is producing processes for other departments. This means that people, who create the process, are not the ones that would be affected by it. Symptoms:
* Nothing is done by the process and everyone knows it. 
* If process is documented, no one really reads it. It is perceived as something either obsolete or from parallel reality.
* Artifacts, that process supposed to produce, are created only before an audit or assesment. 

### Removing, not just adding
Often much more can be achieved by removing a process, role, implementation, specification, then by adding a new one. Therefore there should be a continuous (rather than stop-the-world) process of refactoring of the technical systems and organization itself. People tend to avoid removing things because they don’t feel they have an authority to do so. Also, removing something requires a detailed analysis of the context while adding something seems more comfortable and safer. 

### Avoiding redundant information
Information must be referenced, not copy-pasted. In the case of documentation, this means that it should be created as hypertext, not text. In the case of communication, this means that proxy-mailing and similar practices must be avoided.

### Reusing external knowledge
Establishing internal mentorship and knowledge sharing is a good thing, but it’s important not to forget that there is a whole world out there. There is no need to re-invent internal best coding practices or project management essentials course. There is enough high-quality public information on that topic.

### Calendar instead of TODO list
