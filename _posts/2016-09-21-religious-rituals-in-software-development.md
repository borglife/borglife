---
layout: post
title:  Religious Rituals in Software Development
date: 2016-09-21 10:20:32 +0000
categories: agile scrum code practices
author: Adrian Pickering
---

![Book on the beach](/img/book.jpeg)

When I think of fundamental, learnt behaviours, I think of Ivan [Pavlov's dogs](http://www.simplypsychology.org/pavlov.html) and [B. F. Skinner's](http://en.wikipedia.org/wiki/B._F._Skinner) pigeons.


Pavlov's work is widely known, but in case you missed it, the gist was very simple: ring a bell every time you feed a dog and, after a few repetitions, the chiming noise alone is sufficient to illicit doggy drool as Fido anticipates a meaty treat. B.F. Skinner's work went a little further and used similar animal models of psychology to suggest that free will is an illusion and that even complex behaviours are little more than the mechanical result of robotically following a path set out by neural pathways previously paved by our worldly interactions.

In 1947, Skinner published a paper called [Superstition in the Pigeon](http://psychclassics.yorku.ca/Skinner/Pigeon/), describing an experiment he had performed on hungry birds in which he observed operant conditioning - Pavlovian learning whereby the subject modifies its behaviour as a result of the consequences. What made the particular one of Skinner's works so fascinating is that he rewarded the pigeons regardless of their behaviour or environmental artefact and the animals came to associate their immediately-preceding actions as the trigger for their feed. If a pigeon just happened to turn around twice before a pellet dropped into the feeder, it assumed that the merry dance was the cause of this effect. 75% of the animals in the experiment invented their own ways of pleasing the God of Bounty and stuck rigidly to the practice.


> One bird was conditioned to turn counter-clockwise about the cage, making two or three turns between reinforcements. Another repeatedly thrust its head into one of the upper corners of the cage. A third developed a 'tossing' response, as if placing its head beneath an invisible bar and lifting it repeatedly. Two birds developed a pendulum motion of the head and body, in which the head was extended forward and swung from right to left with a sharp movement followed by a somewhat slower return. The body generally followed the movement and a few steps might be taken when it was extensive. Another bird was conditioned to make incomplete pecking or brushing movements directed toward but not touching the floor.


Once the habit has formed, breaking it becomes difficult. Indeed, failure of the ritual to elicit the desired result makes the subject try harder and perform the ceremony ever-more diligently.

![Pigoens](/img/pigeon.jpeg)

I see rituals not unlike this across many software development teams. To what end goal is your daily stand-up meeting actually a _benefit_? I am confident that questioning the Prophet of Scrum (secularly called a scrum master) as to why everyone must speak for five minutes, chanting in turn the Holy Sacraments of _What Didst I Do Yesterday_, _What Shalt I Do On The Present Day_ and _What Blocketh Me_ will illicit sensible sound-bites such as "It helps everyone know what's going on and allows planning and predictability". Unit testing too has escalated from praiseworthy and righteous into decrees on _Test Coverage_ figures. And code reviews are followed according to _The Commandments_ (sometimes called a checklist) which are rarely as useful or consistently-applied as by static code analysis and always at a greater cost.

The entire meeting must not go on beyond 15 minutes
- All _pigs_ must speak
- No _chickens_ may speak
- Each _pig_ must first describe what they did yesterday
- Each _pig_ must next outline what they expect to do today
- _Pigs_ state what potential impediments may occur
- Stay on topic
- Be brief
- No-one may interrupt
- Erm, except the scrum master if someone isn't brief enough or strays from format or is boring or whatever
and, of course
- _Everyone_ stands


All quite familiar in principle, even if your team differs in a few of the details. Every single one of those points is really quite sensible when examined in isolation but that's no guarantee of operational synergy as a closed system.


_Why_ must the meeting be kept below a quarter of an hour? Well, meetings are expensive - multiply the number of attendees by the duration, then remember that this happens every single day. This can be thought of as a debt of time and the stand-ups, as a net, must reduce your projects' time to market by at least their own sum cost in order to just break even. And that's before you consider opportunity cost. So, of course, keeping the meeting short is really important, but 15 minutes (or ten or however long yours last) is arbitrary. By fixing on time rather than practical result, the scrum master is already unconsciously admitting defeat: "this meeting may not be worth having, but at least it's cheap."

What about the _pigs and chickens_? I won't regurgitate the bacon and eggs analogy - [Bing](http://www.bing.com/search?q=bacon+eggs+committed+contributing&go=Submit&qs=n&form=QBLH&pq=bacon+eggs+comm&sc=0-15&sp=-1&sk=&cvid=9402C02079504BFFB8F5CA559D6D00E0) for it or [Ask Jeeves](http://uk.ask.com/web?q=does+this+search+engine+really+still+exist%3F&qsrc=0&o=10181&l=dir&qo=homepageSearchBox) if you really haven't heard it before - but this one is a bit of a puzzle to me. Some people need to be heard and need to be heard by everyone. Others just need to listen to everyone. If the chickens are mute for the duration, does this mean that the actions they will take as a result of gleaning the information imparted will be kept secret from the pigs? That doesn't bode well. Or worse, maybe they won't take any action, in which case, one has to question why they even bothered to show up?


The topic of the stand-up is patronising, narrow to a two working day period - obviously programmers have too short an attention span to render anything beyond today and too poor a memory to think further back than yesterday. Putting aside that cynicism, why do we need to talk about the coming day of effort? If it's in the plan, then this is redundant information and those who care to know can find it more efficiently by other means. If there's no such plan (yay for agile!) then who chose _One Day_ and why? Whenever the arbitrary peeps over the pulpit, ask yourself or the appropriate manager who chose that figure and _what supporting evidence went into the reasoning_. You may eventually get to the answer "because that's what Scrum looks like" which is just pushing the question around without ever answering it.


To me, the most valuable element of the _Morning Service_ is the talk about blockers. If you think something may impede your progress, share that concern with the appropriate people but don't wait until 9am tomorrow when that's 22 hours away. And maybe a discussion, rather than a monologue at the end of your three minute benediction, would be a more productive approach?


Why do we stand up in a meeting? Well, obviously, it makes it a little bit hateful so we keep it as short as possible. But doesn't the scrum master already look after that problem with his stopwatch?


Sprints are another example of the arbitrary (capricious, irrational?) diktat. Every two weeks, we must deliver a thing that offers value. Quite aside from the improbability of everyone in the team climaxing together, what are the chances that all value can be forecast as divided into two weeks of effort at a time? This practices lends itself to redefining value rather than unquestionably offering a true, meritorious increment to the customer. 


Much the same criticism can be squared at sprint planning and estimating (of which more in another post). Retrospectives - if they fail to provoke discord of convention - are just another custom sapping your spirit and time.


I am loathed to quote [David Brent](http://www.imdb.com/title/tt0290978/quotes) because the comedic origin may be seen as ligthening the integrity of these words:

>Process and Procedure are the last hiding place of people without the wit and wisdom to do their job properly.


My take is a little softer than that - process lies somewhere beyond being a short-hand or pattern for a recurring behaviour without the burden of deriving the action from first principles. And it stops nanometers short of being a subsitute for knowing what is going on. If your take on agile is textbook, certified and consistent, I wager your scrum master may lean more to one end of that spectrum than the other.


Our agile rituals are rigidly passed on through manifesto and managerial sermon, preached as the final, unchanging word of god. At least Skinner's pigeons had the imagination to invent their own in the presence of some degree of first-hand evidence. 


### Credits:

&copy; 2016 all words by Adrian Pickering

Book picture by [https://unsplash.com/@benwhitephotography](https://unsplash.com/@benwhitephotography)

Pigeon picture by [https://unsplash.com/@viktorkern](https://unsplash.com/@viktorkern)