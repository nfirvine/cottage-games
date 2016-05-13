# Cottage Games

TL;DR: I'm part of a largely underserved midcore board gamers market segment, and I want to fix it myself.

As a kid growing up in southwestern Ontario, everyone had a cottage up north to escape the oppressive summer heat. And once it got dark out, it was time to bust out the games. Euchre was the family favourite, but the kids played stuff like Risk, Monopoly, and Payday.

Maybe it was because we couldn't read or maybe because we didn't care, but we found it was more fun making our own modifications of the rules, with huge jackpots on Free Parking and infinite reinforcement blitzkreigs in Risk.

But we grew up. We're all (nominally) adults now. I for one still love board games. I love the human expression of ideas through systems, ideas like "railroads are like the Internet of the 1800s" or "the Mayan knew calendars cold". And I love a system implemented with coloured blocks and cardboard hexes and little tokens for money: that tactility really helps cement learning.

Board games have their problems though. Namely, they can't evolve quickly enough: they can't keep pace with software with its monthly or weekly or daily or even hourly release cycles, since board games live in the physical world and have to deal with shipping logistics.

The design of the game suffers from lack of iteration. Prior to full production, game designers certainly prototype and play test a lot, but naturally this is only with a small sample of the player base since we're constrained by the reality of physical goods. And this playtesting costs a lot of time and money, inflating risk. Making board games is expensive.

There are really only two types of successful board game makers: the big players like FFG, Plaid Hat, and Rio Grande; and the Kickstarter-rich amateurs. 

The pros mitigate the risk by a) having their fingers in a lot of pies and b) expansion-driven design. FFG's line of "living card games" and their X-Wing Miniatures game take this to its logical conclusion: the "core set" is just a taste of the whole game. The great part of expansion-driven design is that you get to iterate. Start with a solid core, and then expand on that; you can even use expansions to nerf earlier expansions. 

The bad part is that players have to be pretty invested, both in terms of money and in terms of cognitive load. If you haven't been there since the beginning, how do you get started? XWM has a core set that will start you with the rules and a few basic units, but it hardly gets you up to speed. And if you consider the whole game and all its expansions as one game, it's *massively* complex.

My experience with Kickstarted board games has been largely disappointing. You can feel the wall-of-text-laden rulebooks oozing rich amateur, both in terms of production quality and design. You read a dense 50-page rulebook only barely grasping what the author is getting at, only to realize it's just a Warhammer Quest clone plus 20 pages of random tables.

I don't know how to fix the problems with the two avenues. Probably, I'm just not the target demographic. I'm not looking for every game I buy to be a full-fledged hobby, where I have to sink 10 hours just to find out if I like it.

Some games are broken just a little bit. Maybe the rules just need more explaining. Or maybe there's a mechanic that isn't quite as fleshed out as it could be.

Lots of people like fixing these things, adding their own house rules or writing their own campaigns or whatever. The tool of the trade for this sort of work is Word docs converted to PDF on Board Game Geek forums.

Wouldn't it be nice if we could collaborate together on this sort of thing? How is there not a Github for board games? Instead of having a Word doc describing my mod, why can't I just publish a patch? I wonder how a 3d6 version of Settlers of Catan would work; how do I fork it without redoing all the work?

That's what cottage games are: a common system used to make and collaborate on making board games, making modification and extension accessible to everyone with design ideas.

## Features of cottage games

### A common language to express rules

It seems to me there are data structures common to many games: a number of one-sided paper cards shuffled together to form a FIFO queue with a discard pile (a deck of cards); some number of number-faced podyhedra rolled simultaneously and their face-up numbers summed (XdY dice rolling). Rulebooks end up describing these subsystems over and over, where if we had a common language we could shortcut this significantly, decreasing both the time to write and the time to learn rules.

This common language should have two parallel specifications: one strict, canonical representation (akin to a programming language) and one in more accessible English. The strict language should in fact *be* a programming language, or some subset or variant thereof.

### The dual nature of rules: learning and referencing

Rulebooks must serve two masters. On one hand, when we're learning to play, we want to do so with as little friction as possible, avoiding annoying details and trying to get the big picture. On the other hand, as we get into more advanced play and corner cases, we'll need to reference the rules and get very specific answers.

One common approach to this problem is to write two rule books: one for getting started, and one for reference.

However, as rules writers, we don't want to have to write the rules twice: this is tedious and error-prone.

Cottage games have one "platonic" form for the rules, but one or more representation of these. You could have a "getting started" book, a book with rules ordered by when they tend to happen, and a book with rules indexed by topic, all referencing the platonic rules.

### Design charter

A cottage game has a design charter that describes the guiding design principles for the game. All systems are created to enforce these design principles. If a modification is created that goes against these principles, one might consider forking it instead.

### Implementation tiers

A cottage game should be materializable; that is, made in the real world.

The trouble with non-cottage games is that they require some level of production quality including 


