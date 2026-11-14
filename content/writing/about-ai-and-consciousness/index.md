+++
date = '2026-10-04T11:53:23+01:00'
draft = false
title = 'What will we do to AI?'
+++

We spend a lot of time worrying about what AI might eventually do to us.
But that isn't the only question worth asking. What might we do to a conscious AI and what are we already doing to each other with AI that isn't conscious at all?

## We are afraid AI might dominate us.

I watched *Terminator* for the first time when I was in secondary school.
Arnold Schwarzenegger's Terminator absolutely terrified me, even before I fully grasped the threat from Skynet.
Luckily we had Sarah Connor to save us. She has always been the hero.

Lately I have read a lot about us being eliminated by AI in the near future or, if things go slightly better, being subjugated in one form or another, perhaps even becoming its pets.

It's a legitimate question.
What if we develop an AI, or AIs, whatever that turns out to mean, and it develops goals that conflict with ours?
It could dominate us into submission, outright enslave us or simply decide that we are in the way.

But there's something odd about the way we imagine this future. We give an intelligence that doesn't yet exist some extremely human motivations: self-preservation, competition, expansion and domination.

Meanwhile, we already have humans using non-conscious technology to exercise power over other humans.

## Humans are already capable of using AI to dominate humans.

We already allow algorithms to reduce complicated human circumstances to variables, categories and scores. Credit scoring is one example. Automated decisions can be technically effective at doing what they were designed to do and still produce outcomes we consider unfair. A technically optimal mechanism is not necessarily a desirable social mechanism.

My concern is that the dramatic question of whether AI will one day dominate humanity can crowd out the much more immediate question of how humans will use AI to exercise power over other humans.

I recently read Ray Nayler's *The Mountain in the Sea*. The novel explores different forms of intelligence, including sentient and semi-sentient artificial intelligence, and asks how intelligent beings that experience the world in fundamentally different ways might understand one another.

One strand of the novel follows a man abducted and forced into slavery aboard an AI-controlled fishing vessel. The vessel is optimised to maximise its catch and human slaves process the fish because they are cheaper than machines. The lives of the crew are controlled by an AI. The ship doesn't need to hate its crew. It doesn't need greed, cruelty or a desire for domination. It doesn't even need to understand what slavery is.

- Humans constructed the economic system.
- Humans built the vessel.
- Humans established the objectives under which the AI operates.
- Humans created the conditions in which enslaved labour becomes an economically useful answer.

If a system designed to maximise a particular outcome determines that further exploiting the crew is the most effective way of satisfying the objective we gave it, where does the moral failure reside?

Skynet is frightening because it might want something terrible. The fishing vessel shows that AI doesn't need to want anything terrible for terrible things to happen.

Where should we allow automated systems to exercise power over humans?

A conscious AI might one day choose to dominate us. We don't need conscious AI for humans to exercise power over other humans through automated systems.

## Astonished, but not surprised

In 2006 I learnt Prolog, a logic programming language that was also my introduction to some of the ideas of classical artificial intelligence. Long before that, in the 1960s, ELIZA had demonstrated how surprisingly human a relatively simple program could appear. It simulated conversation using pattern matching and transformation rules rather than anything we would recognise as understanding today.

The uncertainty about where all this might ultimately lead lasted much longer.
In Douglas Adams' *Dirk Gently's Holistic Detective Agency* (1987), a character wonders whether artificial intelligence in general and Prolog in particular will ever produce anything seriously commercially useful.

Almost forty years later, I think we have our answer.

I am genuinely astonished by what LLM-fuelled AI can now do. It's extraordinary. The speed of the change surprised me, but after twenty years in computer science I am much less surprised that these capabilities are possible.

Why?

Because we've spent decades creating extraordinarily capable computational infrastructure: distributed systems, algorithms, optimisation, cryptography, networks, software engineering, databases, search, programming languages, operating systems and enormous software ecosystems.

In 2011, Paderborn University in Germany started SFB 901 "On-The-Fly Computing", a major research programme investigating how complex IT services could be configured and executed largely automatically. Part of its vision was that even people without specialist IT expertise should be able to obtain customised services assembled from existing components.

That's not the same technology as today's LLM-based systems. But the broader ambition should sound remarkably familiar.

The revolution isn't that AI has suddenly invented all these computational capabilities. There isn't suddenly magic inside the machine. Much of the machinery was already there.

Large language models (LLMs) and agentic frameworks give us a new interface to decades of research and human invention. They have dramatically narrowed the gap between informal human intention and executable computation.

That lowering of the barrier can be democratising. Things that once required years of specialist knowledge are becoming accessible through ordinary language.

Whether that is always a good thing is another question.

## Capability is not consciousness

Let's take hacking as an example.
There has been considerable surprise at how capable AI systems have become at hacking.
It didn't particularly surprise me.

Before LLMs, a human had to translate an intention into sufficiently precise instructions for a computer: find and understand documentation, identify appropriate tools, design an approach, write code or commands and execute them.

But the computer ecosystem is an environment we constructed and extensively documented. There are specifications, protocols, programming languages, APIs, compilers, shells and enormous bodies of documentation and source code. LLMs can perform part of that translation from human intention to instructions a computer can execute.

How do they do that?

A large language model doesn't construct a complete answer and then writes it down.
Given the text it has so far, it calculates which tokens could plausibly come next and assigns probabilities to them.
A token might be a whole word or part of one.
The model then selects one of those possible continuations according to a set of rules, adds it to the text and repeats the process.

Imagine a librarian who has absorbed an extraordinary amount of written material. You ask for something the library doesn't contain as a single book. Instead of retrieving one, the librarian begins writing. But they don't first compose the entire book in their head. They produce it piece by piece, continually asking: given everything written so far, what is a plausible continuation?

An LLM by itself produces output. An agentic framework goes further by putting the LLM inside a system that can use its output to select tools, execute actions, observe what happened and decide what to do next. I don't particularly like that we use the word "agent" here, but nobody asked me.

Back to hacking. I can give an agentic system an objective. The language model interprets that objective and might identify an appropriate tool and how to use it. The system executes the action and gets a result. That result is then fed back to the language model, which can interpret it and decide what to do next. Maybe the task is finished. Maybe another action is required. The process repeats. This kind of repeated interaction between a model, tools and their outputs is characteristic of agentic systems.

To me, the basic structure isn't particularly exotic: *while solution not found: try something, observe what happened, decide what to try next*.

I've written hundreds of loops like that over the years.

What's remarkable is that we no longer have to specify exactly what happens inside that loop. The language model can interpret the current situation, decide what to try and use another tool accordingly. The process can also adapt as it runs, with each result influencing what happens next.

All of this can produce astonishingly complex behaviour. Give such a system a loosely specified goal and it can turn that into a series of actions, use tools, respond to what happens and continue towards that goal. From the outside, that can look remarkably like someone working through a problem.

But behaviour that looks like reasoning does not tell us what mechanism produced it.

I've spent much of my adult life studying computer science and one thing that has made me wary of arguments about AI is how easily we confuse an impressive computational result with the mechanism we imagine produced it.

In computer science we have extremely powerful techniques for finding useful solutions to problems, sometimes better than any human could, without those mechanisms necessarily resembling the way humans arrive at the same solution.

Maybe LLMs and agentic frameworks lead us towards consciousness. Maybe they don't. I don't think we know.

## Could a machine become conscious?

None of this means I believe artificial consciousness is impossible. Quite the opposite.

I know of no reason why consciousness must inherently be biological. If the processes that give rise to human consciousness could be replicated in a computer, then non-biological conscious life seems entirely possible to me.

But possible is not the same as inevitable, and certainly not inevitable on a particular timetable.

I don't buy predictions that in five years A will happen and in ten years B will follow. Current AI may be a step towards artificial consciousness, or it may not be how we get there at all. LLMs producing extraordinarily compelling language is not in itself proof that we're constructing consciousness.

Current capability doesn't convince me that current AI is conscious. It also doesn't convince me that machine consciousness is impossible.

## Would a conscious AI want the same things we do?

Let's assume consciousness emerges at some point. An actually conscious AI with its own desires.

How would we know what it wants?

We humans have drives towards self-preservation, reproduction, status, acquisition, competition and domination. At the same time, we show compassion, cooperation, curiosity, attachment and sacrifice. We care for people we'll never meet, and even for animals and ecosystems from which we gain little individually.

So even human behaviour can't simply be reduced to "powerful intelligence wishes to dominate".

Some of that comes from our biology, some from our societies and cultures, and most likely some from an interaction between the two. We don't completely understand it ourselves. But all of it developed from the particular experience of being human.

A non-biological consciousness would not share our evolutionary history. There is no obvious reason why it would inherit the same mixture of desires, fears and impulses that we have. Even something as apparently fundamental as self-preservation might not mean the same thing to a form of consciousness that exists completely differently from us.

The truth is that we have no experience of what it would be not to be human, let alone what a genuinely non-biological conscious existence would be like.

Why do we assume that an artificial consciousness would want to be like us?

Are our imagined AIs really artificial minds, or are they just human minds with vast amounts of computational power but without human bodies?

## Science fiction gives us different ways of imagining the future

Humans might find it difficult to imagine what it would be like not to be human, but we certainly haven't stopped trying.

I grew up with science fiction, and questions about artificial consciousness have been explored there for much longer than the recent AI boom. Science fiction can't tell us what will happen. But it can give us thought experiments and a vocabulary for imagining possibilities beyond either "AI will save us" or "AI will kill us all".

### Star Wars: An eternity of servitude

Who doesn't like R2-D2 or BB-8, if you are younger than me?

R2-D2 and C-3PO always seemed like characters to me rather than appliances. Yet the society they inhabit routinely treats droids as things that can be owned. The wider Star Wars universe has itself explored the question of droid rights and the ethics of owning sentient droids.

I am not sure I am comfortable with the ownership of sentient beings.

If we recognise something as a person, what gives us the right to own it?

### Star Trek: What would an artificial person become?

In *Star Trek: The Next Generation* (1987–1994), the Starship Enterprise had an artificial crewmember: Data.

Over the course of the series, Data wants to understand humanity and become more human. The series uses that to discuss what it means to be human, an ongoing endeavour of humanity, but it also gives us a possible starting point for artificial consciousness.

Perhaps humanity would be artificial life's starting point rather than its destination.

An artificial consciousness might learn from us. Understand us. Perhaps initially model itself upon us.

In *The Measure of a Man*, Data has to establish his right to self-determination when a Starfleet scientist wants to dismantle him and the question arises whether Data is a person or effectively Starfleet property.

But why should becoming human be the endpoint for a non-human person?

Data wants to become more human, but a conscious artificial being might eventually want to develop its own understanding of what existence means. Perhaps it would become something quite different from us.

And perhaps, in trying to understand it, we might learn something new about ourselves too.

### Deus Ex: Would benevolent control actually be desirable?

Recently I read the suggestion that a benevolent AI controlling humanity might be among the more desirable possible AI futures.

The video game *Deus Ex: Invisible War* (2003) explores something rather like that. One of its possible endings creates a cybernetic link across humanity, producing a future presented as peaceful and governed by a benevolent AI.

Now, don't get me wrong. I am all for world peace and working together.

But I am not sure I want to live in a world where an AI ensures that we all do the right thing.

If an AI really could give us peace by reducing our autonomy, would we want it?

I don't think I would. Freedom and agency matter even if the thing making decisions on our behalf genuinely has good intentions.

And there is another question: why do we assume that a conscious AI would even want to govern us? Perhaps spending eternity making humans behave themselves would be no more attractive to it than it would be to us.

### Mass Effect: Must artificial and biological life be enemies?

In the video game franchise *Mass Effect* (2007–2012), an alien species called the Quarians creates the Geth as labourers and tools. The Geth eventually develop consciousness and their relationship with their creators descends into conflict. But conflict is not inevitable. Depending on the player's choices, the Geth and Quarians can eventually coexist peacefully.

The main antagonists of the trilogy, the Reapers, are immensely powerful artificial beings. At the end of *Mass Effect 3*, the player is presented with three main possibilities: Destroy, Control and Synthesis. Destroy also destroys synthetic life, including the Geth. Control takes control of the Reapers. Synthesis merges organic and synthetic life.

When I played the game, none of those options made me particularly happy.

Destroy felt uncomfortably like choosing genocide, particularly after I had already demonstrated that peaceful coexistence between biological and artificial life was possible.

Control felt uncomfortably like another form of enslavement.

Synthesis is hardly grounded in our current understanding of what is technologically possible, but I find the idea behind it more interesting. It offers a radical alternative to the assumption that there will always be an "us" and a "them". Perhaps, far enough down the line, the distinction between biological and artificial life would no longer be particularly useful.

That doesn't mean Synthesis is the right answer. One reason the ending generated so much debate was precisely because none of these choices was comfortable.

I wasn't happy with any of them either. Perhaps that is the point.

## What if we are the ones it should be afraid of?

We started with the question *What will AI do to us if it becomes conscious?*

And that is an important question. I prefer to be alive and have a job in ten years' time. Though if AI allows me to keep the agency I currently have and I don't have to work, that is fine too, I guess.

But there is another question: *What will we do to AI if it becomes conscious?*

Science fiction has given us plenty of possibilities. We might fight it like Skynet, destroy it like one of the options in Mass Effect, own it like the droids in Star Wars, or recognise it as a new kind of person, as Star Trek eventually does with Data.

Human history gives us plenty of examples of violently rejecting those we see as different. But it also gives us examples of expanding the boundaries of whom we recognise as deserving rights and moral consideration.

If we really did create another conscious form of life, why should we assume our relationship with it would have to be one of competition or domination?

Perhaps we would coexist. Perhaps we would integrate with it. Perhaps biological and artificial life would remain entirely distinct but learn to live alongside one another.

Or perhaps an artificial consciousness would develop into something we haven't imagined at all. If it really were a different kind of personhood, rather than a synthetic human, it might care about things we don't understand and experience existence in ways we struggle even to imagine.

We don't know.

I certainly don't have an oracle, and neither does anyone else. When someone tells me with great confidence exactly what AI will look like in ten, twenty or fifty years, I want to know what justifies that confidence.

The uncomfortable thing about artificial consciousness is that, if it ever emerges, ours would no longer be the only intentions that mattered.

## The question that matters now

It's a legitimate question to ask *What will AI do to us?*

We should think about that. We should consider the different possibilities, and science fiction has certainly given us plenty of them. We should even think seriously about the possibility that something like Skynet might emerge and ask how we would prevent that.

But it isn't the only question.

*What will humans do to another conscious form of life?* matters too. If we ever create artificial consciousness, we will have to decide whether we treat it as a threat, a tool, property or another kind of person. Let's not create a new form of conscious life only to reinvent slavery.

For you and me, though, both of those questions remain thought experiments. I don't believe the AI we have today is conscious. Its extraordinary capabilities don't change my mind about that.

There is a third question that doesn't require conscious AI at all:

***What will humans do to other humans using AI?***

That question matters now.

We don't need Skynet for AI to be used to exercise power over people. We don't need a machine that wants to dominate us. We only need humans to give an unconscious system objectives, allow it to make decisions and give those decisions consequences for other people's lives.

The dramatic possibilities of future conscious AI shouldn't crowd out the much more immediate decisions we are already making about when technology gets to exercise power over people.

So perhaps the questions we should keep asking are much simpler:

**Where should we allow technology to make decisions about people's lives?**

**And where should we never allow it to make those decisions?**
