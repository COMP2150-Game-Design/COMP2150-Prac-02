# Week 02 - Iteration, Greyboxing and Playtesting
Today we will be getting familiar with the use of iterative design in our game making process. We will be touching on playtesting, experience goals and encounter design. Don't worry too much about your knowledge of these concepts: this is all about getting stuck into the idea of designing iteratively and taking on feedback. In future weeks, we will formalise your understanding of both playtesting and encounter design.

## Tools used
Today's task uses (but is not limited to):

* Github Desktop (or your Github client of choice)
* Unreal Engine


## Task 0: Opening the new project
Today we'll be started with a (slightly bug-fixed) version of the template project, found inside this repo. Open it up as you did last time. You'll notice there is no level this time! So let's make one. As per last week, head to `File > New Level` and select `Basic`. This will give you the player, lighting and the floor to get started with.

## Task 1: Challenges (10 min)
Directed by your instructor, discuss the different kinds of challenges that this game can provide, based on your analysis from last week. One way to frame this is to think about a few different "Betcha can't..." statements. Some examples related to other games:

* Betcha can't get pass these guards without being seen (Assassin's Creed series).
* Betcha can't jump on three moving platforms in a row (Super Mario series).
* Betcha can't impress your date (Hatoful Boyfriend).

Try and come up with a few different options here. Think micro: What is something you can achieve through a few minutes of gameplay?

## Task 2: First Iteration (30 min)

### Paper-prototype
Either by picking or being assigned, you should now have a challenge you want to turn into a series of small "encounters" for the player to run through (we'll talk more about encounters in future weeks, but for now just consider them as gameplay sequences). Start by planning this out through a pen-and-paper prototype.

Try drawing out your encounter using whatever tools make the most sense to you. This might be a top-down map on grid paper or using a website like [Virtual Graph Paper](https://virtual-graph-paper.com/).

Consider both the geometry and kind of items you want the player to encounter here, but don't go too high fidelity: this is a very rough "sketch" of what you want to achieve.

### Engine implementation
Start building this out in the engine. As you go, it's okay to make some changes. When your prototype is built, ask yourself:

* Does the player know where they are going?
* Are there any "leaps of faith" or other times the player has to enter a space with no prior information (like turning a sharp corner). If so, are these moments surprising and exciting, or frustrating and annoying?
* Are all the jumps or other necessary movements reasonably possible? If not, why?

Jot down your thoughts on this. It is tempting to make some changes, but let's resist for a moment.

## Task 3: First Playtest (10 min)
Now, enlist another student to come and playtest your game. Play each other's encounters.

While playing your peer's game, consider the same questions as above. You may wish to jot down some notes as you play to share with your peer. Don't worry about going too in-depth: this is a relatively exploratory playest to get you familiar with the process.

Once you've both played each other's games, discuss. Describe your experience and findings with your partner about their prototype, and make sure you are noting down anything they have to say about yours. Pay special attention to anything they say that you didn't notice about your prototype.

## Task 4: Second Iteration (15 min)
With this feedback in mind, start iterating on your prototype while also considering higher-level experience goals. Consider:

* Is that "betcha can't" challenge really clear and engaged? Or is the player spending their time doing something else?
* What kind of challenge is this? Is it about slow and deliberate path-choosing? Or something more fast paced? How can additional elements add to this, or aggrivating elements be removed?
* Are you aiming for something difficult, or something a bit more chill? Which elements are you using to achieve this?

The idea here is to better identify the kind of game you are crafting. With these answers in mind, re-work your prototype.

## Task 5: Second Playtest (10 min)
Jot down a couple of questions to ask your next playtester. These questions should relate to the changes you've made, but also your high-level experience goals. For instance, if you were going for a game that was meant to be physically challenging (quick reflexes, etc) you could ask them if they found any part of the prototype particularly hard, what kind of skills they thought they needed, etc.

Repeat the process of swapping with a peer. This should be someone different to last time.

Once you've played each other's prototypes, take turns answering each other's questions and recording the feedback.

## Task ∞: More iteration! (Remainder)
For the remainder of the class, keep iterating on your prototype with new playtesters. If at any point you are getting feedback that what you've made is "perfect", you either weren't asking deep enough questions, or your playtester was being too kind! Do some self-refleciton on what needs to be changed to better achieve your goals.

At this point, you might be reaching the limits of the encounter you've created, so feel free to add more complexity to it: new goals, new areas, etc. But always iterate deliberately: make changes, test them, improve them, repeat!

## Before you go...
Take a moment to compare the prototype you started this class with and the prototype you have now. You might want to take screenshots/photos of your in-engine sequence and your pen-and-paper draft. Documenting your work and process will be important for the upcoming assessments, but is also just good practice for industry. It'd also be great to see you sharing these on the weekly Show-And-Tell post on iLearn!

See you next week!
