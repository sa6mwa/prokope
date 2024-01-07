[![Prokope](prokope.jpeg "Planeringsstödet Prokope")](prokope.svg)

# Prokope

> *Everyone approaches courageously a danger which he has prepared
> himself to meet long before, and withstands even hardships if he has
> previously practised how to meet them. But, contrariwise, the
> unprepared are panicstricken even at the most trifling things. We
> must see to it that nothing shall come upon us unforeseen. And since
> things are all the more serious when they are unfamiliar,
> **continual reflection will give you the power, no matter what the
> evil may be**, not to play the unschooled boy.*
>
> — Seneca, Letters From A Stoic, Letter 107 (On Obedience To The
> Universal Will)

Over the course of about three yaers, I have developed a *routine* or
tool named *Prokope* (progress in Greek) illustrated above (currently
only in Swedish) and briefly described step-by-step in English
below. The *routine* is inspired by the Prussian or German Army
leadership philosophy Auftragstaktik, Swedish Armed Forces
*Uppdragstaktik*, John Boyd's
[Patterns of Conflict](http://www.projectwhitehorse.com/pdfs/boyd/patterns%20of%20conflict.pdf),
and the research by [Gary Klein](https://www.gary-klein.com/) et al on
naturalistic decision-making with inspiration from Peter Senge's
learning organization described in
[The Fifth Discipline](https://en.wikipedia.org/wiki/The_Fifth_Discipline).
It has similarities to and is compatible with eXtreme Programming
specifically (by Kent Beck) and Scrum (mainly by Jeff Sutherland), but
includes Klein & Schmitt's Recognitional Planning Model (or *Planering
Under Tidspress* by Peter Thunholm), The Five Paragraph Order, Klinger
and Klein's
[Situation Awareness Calibration questions](https://journals.sagepub.com/doi/epdf/10.1177/106480469900700305),
[Pre-Mortem](https://www.gary-klein.com/premortem), and the military
way of conducting a retrospective, albeit a shorter version, called
the *After Action Review*.

The original *auftragstaktik* was an early form of far-reaching
delegated decision-making where disciplined initiates are not only
encouraged, but expected, even if they fail as in-action is considered
far worse than failure. It focuses on quick decision-making at *the
front* by the people who experience the situation first-hand. Trust
and giving up control is key, as is the courage to take initiative by
and componentence of the trustee.

The input "mission" can be a new project, a single task or a sprint,
the method is the same, but with less effort and less planning time
for tasks and more time-consuming for sprints, quartely planning, etc
for obvious reasons. The idea is to promote shared understanding,
reflect, and learn in every iteration, meaning there is an After
Action Review after every User Story or even task, not just after a
two week sprint for example. The smallest team to use the method is a
pair, two people, the philosophy is that there are to be no explicit
individual work. Pair-programming or frequent dialogue and check-ins
daily about your work is implicit for this method or the situational
awareness assessment and After Action Review is of little use.

Download [Prokope SVG](prokope.svg).

> prokopê
> προκοπή: progress, on the path towards wisdom.
> <https://en.wikipedia.org/wiki/Glossaamry_of_Stoicism_terms>

`Prokope` means progress in Greek, or more specifically *improvement*
in the *Stoic* tradition (towards the four cardinal virtues: practical
wisdom, courage, temperance, and justice).

— *Fine, but what does that have to do with the process chart above?*

There are seven steps in (what I like to call) the *routine* above,
there are seven characters in `prokope` aswell as in the word
`routine`, and it's all about *intuitive and ingrained continuous
improvement* in execution towards an objective (*mission*). As a
Westener and part of the western tradition, I like to promote my own
heritage, and Stoicism is one of its major theological and
philosophical creations. Many Westerners have appropriated ideas and
traditions from far away, but have neglected our own. That is my
reason for making this connection.

Several concepts in modern software development can be found as key
tenets in Stoicism, for example, its central tenet is - in essence -
[systemic thinking](https://en.wikipedia.org/wiki/Systems_thinking) on
a massive scale with reflection built-in (e.g Seneca, Letters From A
Stoic, Letter 33). Small incremental progress is to be sought and
praised decisevely (e.g: Aurelius, Meditations 9:30), and the
blameless retrospective (the After Action Review even more so) where
failure is praised as a learning opportunity (an opportunity to
respond with the four virtues) - key practices in a *learning
organization* - are soaked in Stoicism (e.g: Epictetus, Discourses
3:22). Negative visualization - *premeditatio malorum* - (Seneca) is
pre-mortem before being rediscovered and re-branded as pre-mortem. The
idea of the *daily stand-up* and the retrospective are washed-out
versions of the Stoic morning and evening reflection practice. It is
the
[philosophical origin](https://www.routledge.com/The-Philosophy-of-Cognitive-Behavioural-Therapy-CBT-Stoic-Philosophy/Robertson/p/book/9780367219147)
of cognitive behaviour therapy, but perhaps it has influenced software
development even more as it is a perfect fit for the modern rapidly
changing environment. A world that *demands* agility, flexibility and
an iterative way of working with frequent throw-away-your-darlings
refactoring (*returning* it instead of loosing it followed by a sense
of separation anxiety). Nothing is lost as the routine involves
continuous learning and reflection towards incrementally better
solutions.

— *Roger, but what if I would prefer a more... formal name?*

— *How about `ISARPFEA`?*

— *But that's eight characters.*

— *Fine, `ISRPFEA` then...*

## ISARPFEA

The seven steps in the outer loop: INI, SAC, RPM, PRE, 5PO, EXE, AAR.

### 1. INI: Initial Tasking

This is the input into the *routine* coming from a *senior commander*
or business executive, customer, product owner, self-organizing team,
yourself intending to execute on the purpose of the organization,
etc. The mission/task should be summarized as one sentence with no
more than a paragraph of context. Could be...

* The output of point 5, the Five Paragraph Order (mission)
* Objective w/o the Key Results, the planning activity can be used
  to set the KRs
* A top-level OKR (where the planning activity will result in a new
  subordinate OKR)
* A dialogue meeting in a self-organizing team attempting to
  conceptualize an actionable plan supporting their purpose

The tasking should preferably include a summary of the mission of the
executive's higher level command (called *commander's intent* in a
Five Paragraph Order). This could be the higher-level OKR connected to
this tasking, the purpose of the organization or subsystem.

Output: Verbally communicated tasking is preferably written down and
briefly answers the question *why?* with the supplementary words
*"...in order to..."* (can be abbreviated IOT). Example: *We shall
deploy API component X into production no later than (DTG) in order to
support the delivery by Team B who rely on our API*.

### 2. SAC: Situation Awareness Calibration

> *This idea, however, clear though it is, must be strengthened and
> implanted more deeply by daily reflection...*
>
> — Seneca, Letters From A Stoic, Letter 16 (On Philosophy, The Guide Of Life)

Input: Initial Tasking with context and any clarification given by
questions asked when given the task.

From the article
[An accident waiting to happen by David Klinger, Gary Klein](https://journals.sagepub.com/doi/10.1177/106480469900700305).
This step is intended to confirm common-ground and shared
understanding exists in the current situation. Every member of the
team should answer the questions and reach a common understanding
(common ground) via dialogue of the current situation. Examples (from
an interview with Gary Klein):

* What is happening right now?
* What has changed since last time?
* What do you expect should happen next?
* Which is the most significant threat right now?
* Are you missing any critical information?
* Are there any unconfirmed assumptions?
* Are there any anomalies or contradictions in gathered information?
* What are your collegues doing right now and how does that affect the
  situation?

The SA calibration in the article linked above contains five questions
to be frequently synced with all members in the team (in the case of
the nuclear facility, every 15 minutes). Those five questions may not
entirely be applicable to software development and there is seldom
need to sync each 15 minutes (unless during a major incident or outage
in production perhaps). What is important is to be *on the same page*
and target the same issues mentioned in the article. There is no daily
standup ceremony recommended with this approach, but if you have one,
that is the time to ask these questions. This approach recommends
syncing up using these or similar questions before initiating work,
especially if not pair-programming the whole day. The calibration can
be performed one or several times per day depending on the task at
hand.

Output: Team is prepared for planning.

### 3. RPM: Recognitional Planning Model

Input: Task/mission/objective.

The
[Recognitional Planning Model](http://www.dodccrp.org/events/1999_CCRTS/pdf_files/track_3/105klein.pdf)
was created by John Schmitt and Gary Klein. The method is based on
recognition-primed decision making, how planners (especially
experienced planners) actually plan, quote from the paper...

> ... planners naturally identify the mission and conceptualize a
> rough COA (Course Of Action) simultaneously.  In fact, based on our
> observations, we believe that effective planners conceptualizing a
> COA helps to clarify the mission: planners gain a better
> understanding of the problem by posing and then working through
> potential solutions. As a result, there is a very tight and
> continuous mutual feedback loop between mission identification and
> COA creation.

The *senior commander* (or business executive, customer, product
owner, etc) who gave the team the task should not be part of this step
as it involves *how* to solve the task (or that it can not be solved
with given resources or constraints). Involving the customer or senior
external from the team will inevitably lower the team's level of
psychological safety which is detrimental to this way of working. The
*how* is entirely owned by the team (given constraints and guidelines
in the tasking). If the task was conceptualized by a team-member in
your team on the same level of hierarchy as the other team-members,
then that person can and probably should participate in this step
(same for a self-organizing team giving itself a task,
obvisouly). Seek advice from the most knowledgable people when
conceptualizing the plan. The people involved in executing the plan
should be part of the planning process.

The Swedish Armed Forces equivalent Planning Under Time-pressure by
Peter Thunholm involve three steps:

1. Understand the mission/objective/task (observe), create a
   preliminary *target image* (directly translated from Swedish) -
   what I have chosen to call the *Effective Final Outcome* (EFO) in
   English. How does the situation look like when the task is
   completed?  This is preferably where you define *preliminary*
   Acceptance Criterias (yes, they should be defined early in the
   planning)
2. Understand the situation (orient), how *can* the task/mission or
   objective be solved, accomplished or reached?
3. Decide. How *should* the mission be accomplished or the task be
   solved? (*Nota bene:* This is a team-activity and a
   team-decision reached through *dialogue* **not**
   discussion). The *Course Of Action* (COA) can be separated into
   phases:
   * Initially...
   * Thereafter...
   * Finally...
   * In a later phase/stage... (if there is another task, objective or
     mission immediately following the current task being planned,
     this is sort of mentally preparing for it, it is **not** about
     committing to the next sprint, do not commit to multiple sprints)

Output: Effective Final Outcome (EFO) and Coarse Of Action (COA)

### 4. PRE: Pre-Mortem (Premeditatio Malorum)

Input: EFO and COA from the RPM-stage.

*"We are in the future and the plan has failed, in what way did it
fail?"*

The pre-mortem is not a stand-in for
[wargaming](https://en.wikipedia.org/wiki/Professional_wargaming),
which should have been performed after conceptualizing the Course Of
Action in the previous RPM step, but is connected and can act as an
alternative for smaller tasks or time-constraints.

Read the article [Performing a Project
Premortem](https://hbr.org/2007/09/performing-a-project-premortem) by
Gary Klein how to perform this. Quote from the article...

> In a premortem, team members assume that the project they are
> planning has just failed—as so many do—and then generate plausible
> reasons for its demise. Those with reservations may speak freely at
> the outset, so that the project can be improved rather than
> autopsied.

This is a team activity. After the exercise, does any team-member have
strong objections against the Course Of Action from the RPM step and
can motivate why? If yes, revise the EFO and/or COA and put the
revised version through the pre-mortem, otherwise you have a plan.

### 5. 5PO: Five Paragraph Order

Input: Effective Final Outcome and Course Of Action with original
mission statement.

The [Five Paragraph
Order](https://en.wikipedia.org/wiki/Five_paragraph_order) is a
military standard for an Operational Order (OPORD) with origins in the
Prussian Army where Helmuth von Moltke introduced leading by
directives (*weisungen*) rather than detailed or micromanaged orders
(from ca 1857). In 1897, US major general (then colonel) Eben Swift
took inspiration from Moltke's *weisungen* and organized its
information into five sections.

> "The order in the field is issued under peculiar conditions of
> emergency and inconvenience. It is received sometimes in the midst
> of great excitement and danger; perhaps it must be read in a rain
> storm where no shelter is near, or at night by a poor light. Every
> care must be taken to make it brief, in plain phrase and short
> sentence." Eben Swift, 1897.
>
> <https://apps.dtic.mil/sti/pdfs/ADA210966.pdf>

The headings of Swift's original five paragraphs have changed slightly
due to modernization. An adaptation to the *routine* can look like the
following:

1. Situation
   * A paragraph describing the situation, could be elaborate with
     images, data, anything needed for the team to facilitate reaching
     shared understanding and executing towards the main objective and
     in accordance with the intensions of the higher command, company
     vision, larger mission, overarching OKR, etc
2. Mission
   * A sentence or short paragraph
   * *Effective Final Outcome* from the RPM activity
3. Execution
   * *Course Of Action* from the RPM activity
   * The bigger team is preferably devided into sub-group sections of
     at least two people each where each sub-group probably works on
     one part of the COA (vertically) or one horizontal *slice* or
     sub-system/sub-task of the COA
   * In defense forces the leader is usually the one who assigns the
     sub-tasks to sub-groups, but self-organization should be
     preferred
   * Having a facilitator coach this activity is recommended, unless
     you are in a very well developed team
4. Administration/Logistics
   * Relevant if there are acquisitions or ordering to be made of e.g
     servers, services, travel, etc
5. Command/Communications
   * Top-level command, who the *customer* is
   * How to communicate within the team, but more importantly, how to
     communicate with the *customer*, etc

Output: An OPORD clarifying the mission and the team's dissposition.

### 6. EXE: Execute

Input: An *operation order* the team has simulated (wargamed) or at
least have received a briefing on.

Communicate the team's *intention* to the *senior commander*,
customer, product owner, etc by summarizing the Course Of Action, then
execute, reflect, learn, iterate (fast-tracked SAC, RPM, PRE, EXE,
AAR).

### 7. AAR: After Action Review

An [AAR](https://en.wikipedia.org/wiki/After-action_review) is a form
of retrospective focusing on how team-members experienced the
work-effort, sharing their individual perspectives of what the plan
was, what was supposed to be achieved, what was achieved, and why. The
plan and it's execution is to be *replayed* through mental simulation
on a team-level. The goal is not only to learn from each other, but to
share each member's perspective of the work-effort
(operation). Sharing perspectives is perhaps the most important
activity in the after-action review.

Unlike some retrospectives in other *"agile"* methods or
way-of-working, an AAR is not about the technical details and what was
technically learned, but how the personal interactions were perceived
by the team-members and their perspectives on their teams'
performance. It should help facilitate improvement in shared
understanding, learning more about each individual team-member in
relation to the team, and building better team-cohesion.

There are several variants of the After Action Review, the one I have
most experience with asks four questions, usually drawn on a board in
four sections/squares. The AAR facilitator allows each team-member to
speak without being interrupted (interruption is not allowed) before
asking the same question to the next team-member. You should think of
each question as a chapter rather than a list. The team does not move
to the next *chapter* before all team-members have answered and
processed the current question. A good facilitator will know who
should go next and how to create a psychologically safe environment
allowing for constructive blameless dialogue. No member is allowed to
mix up the questions and answer two or more questions at a time, only
one. For example, it is very easy to slip into the *why?* while
answering the question *what happened?*. Do not drift from the current
square. An AAR can be performed entirely verbally, but writing down
the answers to the final question (*what what learned?*) is crucial
for future reviews and creating actionable tasks from an AAR.

1. What was supposed to happen?
   * The plan or the Course Of Action of
     the subtask, etc
   * Each team-member gives his/her perspective and understanding of
     the mission
2. What happened?
   * Did the COA go according to plan or deviate from the plan?
3. Why did it happen?
   * Tip: recursively ask *why?* (including COAs that went exactly as
     planned, why did it go that well?)
   * Here is where dialogue can be most intense and the facilitator
     may need to slow down the process in order to let each member's
     perspective sink in with the team
   * It may be required to write down each answer to *why?* if they
     are many in order to have a constructive outcome of the next
     question
4. What can we do next time?
   * Write each item down as an idea to develop further into
     actionable tasks in a later stage

The final AAR should include any sub-AAR the team or sub-team has
performed along the way (daily AARs, User Story AARs, etc) and those
ideas should be lifted into the 4th question (*what can we do next
time?*) of the main AAR. There should be no names assigned to any
notes, ideas or actionable tasks as there is to be no blame (or
praise) in an AAR.

## Epilogue

Remember! Set all blame aside when using this routine - especially
during the After Action Review. Read or listen to the abridged
audiobook about systemic thinking: The Fifth Discipline by Peter
Senge or alternatively, listen to
[this](https://open.spotify.com/episode/590zQuCxlQgrNP3CqZshbG),
[this](https://open.spotify.com/episode/5p40RHs4yfMJzngy07G6ty),
[this](https://open.spotify.com/episode/39URVmrrBmy0fS8Af02KCu), and
perhaps especially
[this](https://open.spotify.com/episode/1YBRoEaZZyWcpvgZwbFjlD)
podcast.

Seneca on reductionist thinking...

> *Look into their wisdom as a whole; study it as a whole. They are
> working out a plan and weaving together, line upon line, a
> masterpiece, from which nothing can be taken away without injury to
> the whole. Examine the separate parts, if you like, provided you
> examine them as parts of the man himself. She is not a beautiful
> woman whose ankle or arm is praised, but she whose general
> appearance makes you forget to admire her single attributes.*
>
> — Seneca, Letters From A Stoic, Letter 33 (On The Futility Of
> Learning Maxims)

The goal is to perform this routine intuitively without elaborate
process adherance. It's the dialogue-based learning process that is
most important, not which cermonies are performed when or where. Using
the reflective tools in the routine on a team-level allows the
team-members to be more situationally aware of changes, unconfirmed
assumptions and biases in order to make timely adaptations early to a
potential new reality (i.e *"be agile"*).

The more formal Five Paragraph Order following the Recognitional
Planning Model is supposed to establish a shared understanding of the
task at hand and in which way to solve it by simulating and
*rehearsing* a story in mainly three stages (*initially, thereafter
and finally*). The 5PO also contains out-of-band information such as
who is to arrange deploy-pizza and beer after successfully shipping
the software (just kidding), which cost-center to bill, who the
customer or product owner is and how to communicate with him/her.

Execution is to be iterative with concurrently running inner-loops
(each sub-team solving sub-tasks) within the whole routine which is
also an inner-loop in the big picture. Execution is basically
`ISRPFEA` run recursively. The sub-team would calibrate their
situation awareness (could be a daily stand-up, or something
else). The SAC serves a similar purpose of how a commander's order to
*repeat* i.e *collate* (in his/her own words) the order given
confirming the subordinate has understood it, a very good practice
helping keep common-ground intact and facilitate shared understanding.
This followed by a quick RPM (understanding the task, formulate a
COA - course of action), a quick PRE-mortem (how did the COA fail?),
short 5PO (e.g agree when to take breaks, lunch, other logistics,
etc), and execute the inner-COA. Each sub-group should perform an
After Action Review when the task or sub-task is completed.

— *Wait, this is too complicated!*

What if I told you that many platoon or squad-level planning-sessions,
5POs and AARs are done verbally or using anchor-points on a small
piece of paper? There is a reason the
[naturalistic decision-making research by Gary Klein et al](https://naturalisticdecisionmaking.org/new-ndm-tools/)
is utilized and referenced in `ISRPFEA`. After practicing this
approach with a good facilitator, the team will be able to execute and
ingrain this routine fairly quickly, i.e intuitively (but do not
expect to change organizational culture over night if your current
process differ from this approach). Perhaps the main task for the
iteration should be written down as a 5PO unless the team is highly
effective and cohesive, but the subtask 5POs can be communicated
verbally within the sub-team. AARs should be written down, at least
the final step (*what can we do next time?*), in order to review and
incorporate these actions in future iterations. `ISRPFEA` is not a
bureaucratic process, on the contrary, it is a tool to facility
naturalistic decision-making, delegated responsibility, *disciplined
initiative*, team-cohesion, and an intuitive way of working while
still providing structure.

The *routine* is supposed to be recursive, meaning a
mission can have sub-tasks and sub-sub-tasks hooked into the main task
or mission, similar to how OKRs are intended to be used. Each stage or
phase in the Course Of Action can be illustrated as an actual Story
Map where each subtasked team can visually see where they fit in into
the bigger picture. None of this is new, it's how most or probably all
western defense forces around the world structure their planning and
is probably the most intuitive approach in modern software
development. The origin of this type of planning is - as previsouly
stated - nearly 200 years old from after the Prussian Army reformed
it's doctrine and most western defence forces adopted it.

### No estimates

Well, maybe not entirely, but it is a total waste of time to estimate
individual stories or subtasks, and stressful for developers. Estimate
the whole tasking at hand, given no time-constraints were issued, and
use that as an increment interval if deemed realistic (whether it is 3
days or 3 weeks). `Prokope` does not advocate any fixed sprint cycle,
but there need to be more emphasis on SAC and AAR if the increment
continues after the weekend (or similar time off). From my experience,
short sprint intervals add more pressure on the team, the feedback
cycles are faster and that may not always be sustainable while long
sprint cycles become tedious and boring risking to blur the team's
focus. Right-sizing the sprint cycle to the task at hand is my
recommendation. Quick intervals for quick and simple increments will
encourage working efficiently towards the goal, longer or more
Kanban-like for sprint goals deemed to need to take more time will
(hopefully) lower the stress-level of the team.

> Only the poor man counts his flock.
>
> *— Seneca, Letter From A Stoic, Letter 33 (On The Futility Of
> Learning Maxims)*

### Jira Issues

No, not issues in Jira, but issues *with* Jira. The philosophy - or at
least recommendation - with `ISRPFEA` is to never ever assign a task
to a single individual as all work is supposed to be team
efforts. There are ways to add additional assignees to an issue, but
still always with a *main* assignee. Ideas around this would be to
color-code each sub-group (*team blue, red hats, agent oranges, pink
floyds, red barons, yellow subroutine*, etc) and not assign any task
to any assignee in Jira in the Scrum or Kanban board. Colors on cards
can be assigned to JQL queries or you can use colored labels. You may
need to add fields to show on the cards in your board.

Why? There is no smaller unit in `ISRPFEA` than a pair. Obviously, I
have taken that rule from the Swedish Armed Forces (*stridspar*,
meaning *combat pair*). In the US Army, I believe the smallest unit is
a *fire team* of 3-5 soldiers. A pair is probably ideal for - as the
name suggests - pair-programming, which is encouraged in this
approach, but 3 developers could be more ideal for other tasks.

## Background

I work as a software engineer and/or solutions architect with a keen
interest in the military leadership philosophy called Auftragstaktik
or Uppdragstaktik as it is called here in Sweden. In the US it is
called Mission Command, but there are many differences from the
original doctrine. I have a military background as a radio operator
(and a short period as a group/squad leader) at both company and
battalion C2 levels where I have come in contact with many aspects of
how operational orders, planning, wargaming and retrospectives (After
Action Reviews) are conducted by senior officers.

Mission Command, or *mission-based tactics* - *uppdragstaktik* in
Swedish - was conceptualized and implemented by the Prussian Army 200
years ago and later - after the reforms and further development by
Helmuth von Moltke - called Auftragstaktik (Führen mit Auftrag).

My bookshelf contains about a dozen books specifically about
Auftragstaktik or related topics with titles as Adopting Mission
Command by Vandergriff, Moltke on The Art Of War by Hughes,
Auftragstaktik by Oliviero, On War by Clausewitz (translated by
Jolles), Raising The Bar by Vandergriff, Auftragstaktik by Jochen
Wittmann, Truppenführung by Beck (with Fritsch and Stulpnaegel), John
Boyd by Coram, and Certain To Win by Chet Richards.

The original *mission-based tactics* (Auftragstakik) was an early form
of far-reaching delegated decision-making where disciplined
initiatives are not only encouraged, but expected, even if they fail
as inaction is considered far worse than failure. Over time,
decision-making was gradually delegated further and futher down into
the Prussian/German Army and finally to the individual solider during
the interwar period as auftragstaktik became exceptionally more
maneuverable due to tanks and airplanes (sometimes erroneously called
*blitzkrieg*, which was never a concept or doctrine, but rather
auftragstaktik with modern technology). Similarly, decision-making was
delegated far down into the Swedish Armed Forces and it is said it was
the most *mission tactical* around 1920 to be slightly rolled back
after World War II and not reintroduced until modern times. I am not
saying auftragstakik transformed the Prussian, German or Swedish Army
into a [teal organization](https://www.reinventingorganizations.com/),
but I am saying it is highly compatible with *teal* ideas and has many
of it's qualities. The focus on timely decisive discplined initiative
is not compatible with a *green organization* as the approach does not
seek concensus which would stifle quick decision-making. It is
similarly far from the *amber organization* Laloux places *the
military* into as a stereotype. However, there are modern western
defence forces that think it is a good idea to use *normaltaktik*
during peace-time (in barracks, on exercises, etc) and only utilize
*auftragstaktik* during war-time - they certainly fit the *amber
organization*.

## PUT/RPM

The following video is in Swedish from my podcast
[QZJ](https://open.spotify.com/show/50gMmT5X99LS8MfOv2VHXK) and
broadly describes *Planering Under Tidspress* which is the Swedish
Armed Forces implementation of Gary Klein & John Schmitt's
Recognitional Planning Model by Peter Thunholm. The planning model is
the base of *Prokope*.

[![QZJ - Planering Under Tidspress](qzj-put-screenshot.jpeg)](https://youtu.be/foIKvqghdgQ "Planering Under Tidspress")

## The military stereotype

In the introduction to the English translation of Truppenführung by Beck,
Fritsch, and Stulpnaegel titled *On the German Art of War* the editors Bruce
Condell and David T Zabecki writes...

> To a certain degree, there is a level of validity to many of the
> commonly believed characteristics of the German society and
> character. These include an almost unquestioning acceptance of
> authority, social rigidity, and an intense preoccupation with record
> keeping, paperwork and all forms of bureaucractic procedure. Nowhere
> are these characteristics so prominent as in the German civil
> service. And while the U.S. Army tends to reproduce faithfully most
> of the worst features of the U.S. civil service, the German Army was
> remarkably free of such afflictions.
> ...
> One of the most important concepts of the post-World War I German
> military system was that of Auftragstaktik. The term can be
> translated loosely to "mission-type order," but there is no real
> English equivalent that adequately conveys the full
> meaning. Auftragstaktik is based on the principle that a commander
> should tell his subordinates what to do and when to do it, but not
> necessarily tell them how to do it. In accomplishing their missions,
> subordinate commanders are given a wide degree of latitude and are
> expected to exercise great initiative.
> ...
> Prior to World War I, the German Army operated under a principle
> known as *Weisungsführung* (leadership by directive), which was
> similar to Auftragstaktik, but only entrusted commanders down to the
> army level - or sometimes the corps - with broad discretionary
> powers in the execution of their missions. Auftragstaktik, which was
> a post-World War I creation of *Das FuG* (by Seeckt) and carried
> forward into *Truppenführung*, extended that principle down to the
> lowest squad leader and even, when necessary, to the individual
> soldier. Writing in his 1925 Observations of the Chief of the Army
> Command, von Seeckt noted:
>
> *The principal thing now is to increase the responsibilities of the
> individual man, particularly his independence of action, and thereby
> to increase the efficiency of the entire army ... The limitations
> imposed by exterior circumstances causes us to give the mind more
> freedom of activity, with the profitable result of increasing the
> ability of the individual.*
>
> For Auftragstaktik to work, a subordinate leader or even a common
> soldier given a mission must fully understand his commander's
> intent - and in most cases, the intent of the next higher
> commander. This, of course, implies that the subordinate leader must
> understand "why." If he doesn't understand, he has the obligation to
> ask. Conversely, the superior leader issuing the order has the
> obligation to explain. Such a process does not fit the popular
> stereotype of military organizations in general, nor especially is
> it characteristic of German society. Thus we find in Truppenführung
> passages that would still be considered radical in many of the
> world's armies today...

On the back-cover of Jochen Wittmann's Auftragstaktik (ISBN
978-3-937885-58-2) Christian E.O Millotat, maj general (retired) of
the Germany Army writes:

> ... Many allied armed forces have tried to introduce Auftragstaktik
> based on the German experience and adopted it to their specific
> military cultures. Misinterpretation and misunderstanding, however,
> very often accompanied this attempt and process, and the intent to
> use Auftragstaktik very often degenerated to a lip
> service. Lieutenant Colonel Wittmann identifies a broad variety of
> definitions of Auftragstaktik in his literature analysis. Since
> Auftragstaktik lacks from theoretical foundation, he tries to ground
> it theoretically in an interesting and convincing manner. His work
> has, undoubtedly, extraordinary relevance to the present and future
> dimensions of leadership in the mulinational structured armed forces
> of today, but also in areas outside of the military sphere.

I think it is very relevant outside the military sphere. On page 48 in
Auftragstaktik, Wittmann has drawing comparing "befehlstaktik"
(command guidance or command control) and Auftragstaktik where the
characteristics of Befehlstaktik include *details of order*, very
little learning effect, low trust, little self-initiative, little
freedom of action, top-down-orientation, low flexibility (rigidity
rather than agility), etc, while Auftragsktik push on the following
characteristics:

* Decentralization
* Delegation
* Freedom of action
* High cost-benefit ratio
* Bottom-up-orientation
* High learning effect
* Trust
* Self-initiative
* Self-regulation
* Flexibility
* Intrinsic responsibility
* Creativity / improvisation
* Speed of decision-making
* Low details of orders
