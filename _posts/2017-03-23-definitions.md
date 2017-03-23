---
layout: post
title: "Developer/Engineer/Hacker/Architect"
categories: trainings
date: 23-03-2017 08:00:00
---
Are all these, just different words meaning the same thing?

---
If you work in the software *industry*, or you know people who work in that industry,
or you have any job related social media thingy (i.e linkedIn) you will probably
have come across the terms **Software Developer** or **Software Engineer**. If
you don't work in the industry you will rarely hear the term **Software Architect**
and you probably have your own definition for the term **Hacker**.

Are all these, just words meaning the same thing? For me they're not the same at all.
Here's my version of what each word means and how I use these words for me or
for other people.

## Everything starts with a building
If someone asked you to make a model of a building -let's say a house- how would
you model it? There are a lot of ways to model this depending on how you think.

One can say that a building is the following:

- Cement
- Bricks
- Paint
- Windows
- etc

Another can say that a building is the following:

- Construction things
- Entry related things
- Decoration things
- etc

Anothe might say that a building is the following:

- A sum of Things -where Things can have a category to define a group things etc

## Who is right and who is wrong?

### It's not a matter of right or wrong

Well nobody is really wrong about the building model. All three models will be
able to construct a building. There is a big difference though.. As we see these
models we can spot the difference immediately.

![alt abstraction][abstraction]

So you can clearly spot that as we go down on the three models, we deepen the
abstraction. So all of them can create a building and some of them can be used
to create other things as well.

## Why do we abstract?

Clearly making things overly explicit is easier to understand. So why do we
abstract things? There are a lot of answers to this question.

Some of them are:

- Because we want to be able to extend and reuse things
- Because we predict that some day we might want to build straw buildings
- Because we like to have patterns in things we create and group them under
these patterns
- Because we believe abstractions will make our lives easier

## How much should we abstract?

Well, this is the million dollar question.. You might abstract things until a level
called **entity**. And  then you will say
>a building is an entity comprised
of entities. And you can have entities like paint, cement which may in fact be a
submodel of entities, say organic entities.

![alt more abstraction][more abstraction]

So you can model everything as a thing comprised of things etc etc.
When should you stop abstracting things? Well the real question is: **How deep
in the rabbit hole do you want to go to create something and at the same time
feel comfortable?**

## How are all these related to the subject?

Until now I haven't said anything about programming or IT-stuff. It turns out
that people who create software are usually involved in a modeling process.
Because in the software industry, you want to build things easy, fast --be able
to build things at scale, be able to extend these things.. Reusability, scalability,
extendability are very very **very** important matters in the software business.
So here's how I understand each software *mason* title in relation with the
things I described above.

## Developer / Coder / Programmer

As the title says, a developer develops software, a coder codes software, a
programmer writes programs. What do all these things have in common? They are
related to the procedure of **building / writing**. But when you build a house,
you first want to design how it will be built and after that (usually) others will build it.
A developer doesn't really care to design something. They just want to build the
damn thing. Make it useful. Raise the skyscrapper now. They design something
without putting much thought about the future and usually have an excuse ***we can
check how to integrate extra features in the future. it won't be difficult***
to stop thinking too much. Agile masters tend to love them because a developer
never really spends much time thinking and designing things..

Developers focus on tools not methodologies/patterns/way of building
things. They see a *shiny* tool and find a way to integrate it.
Like a builder who doesn't really pay attention to the design of a building.
All that matters is that the building process is easy and has the correct tools
for it.
Can builders design and build a house from scratch?
If they have years of experience they might be able to build a house that wont
fall apart. Can they do it consistently and build ten houses with extra stuff?

In software industry the developers usually design a **part** of something but this
is more closely related to the construction **procedure** than the realy design.
So if you spot someone who always wants to have bleeding edge tools and technology
and is very happy to use in production every new blinky blinky pre-alpha version
just because it has a nice presentation, it's definitely the coder guy. The
problem with this category is that when you focus on having a shiny gold hammer,
everything will eventually start looking like a nail..


## Software Engineer

A software engineer can design and build things. They are really interested in
finding ways to design things better for more consistency, scalability,
reusability. You could say that they're kind of lazy. And they are. On the paradigm
with our buildings, a software engineer is the guy who wants to be able to find
a way to design and build buildings with some pattern that will allow them to
reuse parts of the design and easily adapt them. And they want to be able to do
this consistently. They are **master masons** who want to find a way to be able
to build any building they want without having to do anything at all if possible.

Software engineers usually like to spot patterns in things, make abstractions
and compartmentalize things as they see fit. They tend to think a lot about the
future and want to predict extra needs that might come up and find ways **now**
that will allow them to solve these needs easily in the **future**. They care
about thinking mechanisms, about ways of describing and solving problems. You
show them a cool new tool that can satisfy a need and they want to find out how
this tool is designed. You show them a smart car that can avoid accidents and they
want to find out how this is done. They usually (not always) don't get along with
agile masters who want results now and they might also get aggressive when you try
to push things fast-forward and jump into building things hastily.

> It took God seven days to create the world. Do you know how much time did God
spend to design how the world would be created and look like?

They try to find a harmony in things and want to design things that when built
they will look beautiful, elegant but at the same time really solid. They seek
**perfection**. The problem with them is that they get obsessed with the
solving-problems thing.

## Software Architect

A software architect doesn't design buildings. They design cities and countries.
They can design a building taking into account where the park should be and how the
whole city with people, buildings, parks, roads must look like. Years of experience
as a software engineer are usually needed along with a variety of the things they have
built as a software engineer. If you only design and build buildings, everything
will look like a building to you. So you might create beautiful buildings but
hideous parks. Or fill an entire city with buildings. An architect can design
the whole city up to the bench in the park. And they want everything to be
elegant stick to the other components and be able to scale (more citizens means you
have to expand the city).

They can also build stuff and they should do. Someone
who sits in an offices and designs cities will surely miss something. You have to
walk in the city to be able to understand what fits and what doesn't. Everything might
seem perfect on paper but when you try to really construct stuff you see that it's
not as easy as it seems. The problem with architects is exactly that. They (not
all of them) tend to avoid getting their hands *dirty*. This adds a nice tag for
them. *Ivory tower* architects are those who decide to only design things and
never implement anything (others will have to take care of the building process).
So they might end up designing impossible things because
they seem really easy in high level design. Of course a software
architect is the evolution of a software engineer. But one should never forget
that the engineering process is comprised of two things: **Design** and
**implementation**.

## Hacker

I left the difficult term for the end but at the same time I will provide the
shortest definition.
A hacker is a term that anyone can provide a definition about and they usually are wrong.
A hacker is not someone who steals stuff, someone who is involved in illegal
activities. A hacker is a tag for someone besides their main title. And it has two
meanings which are not always explicit when used in a sentence without having the
context.
1. A hacker is someone who finds really smart ways of doing things.
It usually involves something that most people can't really figure out. It's a
different perspective that someone uses and you can't see --until they show it to
you-- because your way of thinking is narrower. People who make break-through
inventions are pure hackers.
2. A hacker is someone who finds really weird ways to achieve things. It usually
involves something that most people don't do because it's illogical. Mr. Bean
driving his car with ropes while sitting on his armchair on the rooftop of his
car is a pure hack.

![alt mr bean][mr bean]

So it can mean a good thing or a bad thing. You (obviously) want to be on the good
side of this term. How do you become a good hacker then? Well that's a question
that doesn't have a clear answer. First you should want to think smart and then
you can try to enrich your way of thinking to provide you with (good) hacking
perspectives.

## Wrap up

In the beginning everyone is a Coder. Some people are forever Coders and they like
it. I don't like the term Coder/Developer because I don't think that way. I like
to consider myself as a Software Engineer. And at some point I hope that I will
be able to become a good Architect (who will always be a software engineer at
the same time and not an ivory tower architect).
I can't really say that I'm a hacker because it's a term that others usually
attribute to you. The way I see it, you can never really call yourself a hacker.

[abstraction]: /images/abstraction.jpg
[more abstraction]: /images/more_abstraction.jpg
{: height="400px" width="450px" }
[mr bean]: /images/bean.jpg
{: height="400px" width="650px" }
