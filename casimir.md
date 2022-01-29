# CASIMIR

Casimir is an "idle multiplary" game set in a futuristic space universe that integrates natively into Discord. It allows Discord Server members to play directly from their Discord client. It’s a text based universe operating at the fingertips of Discord community members.

At it's core, it's a space exploration and resource gathering game, where discord servers compete both individually and collectively to control resources. It draws inspiration from games like Elite Dangerous and EVE Online, but adds idle mechanics (time based and resource based gating) which is perfect for the way people use Discord.

As NFTs have exploded in popularity, Discord is the clear the winner in the space for building community, beyond just gaming, it's become something that’s critical to how people interact with each other in communities. Engagement in Discord is incredible. People hang out all day, on their phones, on their computers, in the office or on the toilet. Servers regularly attract 10’s to 10'000’s of users, but in a community space like NFTs, it's hard to hold attention too.

Casimir taps into this energy. For server members, Casimir is a fun way to spend time and engage with the community while having fun. For server owners, Casimir provides an activity that brings members back. It promotes stickiness and through its server-to-server competitive mechanics, promotes discoverability of new communities while also promoting loyalty to your own community.

## Back story
Wormholes, tears through space time, connect the univers of Discord Servers. The Casimir effect is the quantum stabilising force that allows the wormholes between the various Discord Servers to be maintained.

In our universe, a Discord Server is analogous to the home planet of a tribe (think Discord Server when you read World from now on). To play Casimir, you "register" in a server and now compete and represent this world.

By entering the Casimir wormhole from the comfort of their server, players can travel and explore the universe of servers to mine, trade and battle for resources that they can use for a variety of purposes within game, levelling up their home world and community. 

NB - We initially thought to tie this more directly to NFTs and promote whitelist access as the ultimate prize - we haven't ruled this out, but instead we want the game to be intrinsically fun without a specific focus on NFTs. If NFT whitelists could be a game reward, equally other digital or real world experiences could be too. The competition rewards (if any) need to be separate from the intrinsic game rewards, we want people to play because they like it, not just because they might win X.

## Gameplay inspiration

Checkout the following games for inspiration

1. Elite Dangerous, Eve Online - Space Trading Games.
2. Adventure Capital on mobile - Classic Idle Game.
3. CBCreepz - Blockchain based P2E game.
4. Satisfactory / Factorio - Mining and automation.
5. Classic MUDs - Moria, dawrf fortress etc

It's a grab bag of games and styles - but I think that the commonality here is that they all involve a sense of progress through developing and trading up...

## Gameplay Loop

As an idle game the basic loop is something like:

1. Action e.g. mine
2. Time
3. Reward

Each level rewards with faster accumulation of resources at a cost of the resources earned. For example, a simple levelling loop for mining might be:

1. /mine - takes 5 seconds, returns 5 minerals.
2. /upgrade - Costs 25 minerals to upgrade...
3. /mine - takes 10 seconds, returns 20 minerals...
4. /upgrade - Costs 100 minerals to upgrade...

etc...

## Basic Gameplay Idea


```
Welcome to Casimir. !help for commands


> !help

The following commands are available:
	!warp #<WORLDID> - Warp to a server through a wormhole.
	!open #<WORLDID> - Create a new casimir wormhole to a world. Costs $LFG
	!mine - mine the resource on this world. Takes 2 minutes to complete.
	!about - About the current world you're on
	!where - Shows your current location
	!rob - Attempt to rob resource from another player who is on a world.
	!spy - Try to uncover a hidden world ID
	!bank - Place resources securely into a bank. Can only be done on your own world.
	!home - Warp home. Has a cool down of 60 minutes.
	!list - Shows known wormholes on this world.
	!boost - Boost a wormhole with $moons
	!who - Who is on this world (active)
	!donate <currency> X - Donate X amount to the world bank on this world. WARNING - You cannot retrieve it.

> !list

WorldID  Name.         Tier Stability
CASDEV   Casimir Dev.  3.   THIS WORLD
HUMNFT	 Humans of NFT 2.   %50
MOM      Moons of Mars 3.   %20
MORIES   CryptoMories  1    %100

> !boost MOM
You don't have enough $moons to stabilize MOM. Wormholes deteriote 10% per day. 2 days until collapse.
> !who
PlayerID           Home World 	 Resources
RabidBunny#3678.   Moons of Mars h: 10, l: 0, m: 100

> !rob RabidBunny#3678
You can't rob yourself.

> !open
Usage: !open <WORLDID>
It costs 10 LFG to open a wormhole to open a T2 world, 1000 LFG to open a wormhole to a T1 world.

> !open KAIJO 10
Whoops! KAIJO not found.

> !open KAIJU 10
Congratulations, you've opened a wormhole to KAIJU.

> !list
WorldID  Name.          Tier Stability   Resource
CASDEV   Casimir Dev.   3.   NA			 NA
HUMNFT	 Humans of NFT  2.   %50.        $LFG      
KAIJU	 ChubbyKaijuDAO 2.   %50         $LFG
MOM      Moons of Mars  3.   %20         $HOP
MORIES   CryptoMories   1.   %100        $MON

> !warp KAIJU
>>>>>> WOOOSH >>>>>>
Arriving on KAIJU

> !list
WorldID      Name.          Tier Stability   Resource
(H)CASDEV   Casimir Dev.   3.   %50. 		 NA
KAIJU	    ChubbyKaijuDAO 2.   NA           $LFG
<HIDDEN>	<HIDDEN>       1.   %100         $MON
<HIDDEN>	<HIDDEN>       3.   %100         $HOP

> !spy
You don't have enough $LFG to power your spy device. Need at least 10 LFG. You can spend between 10 - 100 LFG, each amount boosts your success chance by 5% to a maximum of 70%.

> !mine
You start mining for 2 minutes.

Congratulations you've discovered 120 $lfg

> !spy 20
You spy with a %40 success chance. Success! You've discovered a new WORLDID.

<< SERVER ALERT RABIDBUNNY SUCCESSFULLY SPIED >>

> !list
WorldID      Name.              Tier Stability   Resource
(H)CASDEV   Casimir Dev.   	3.   %50. 		 NA
KAIJU	    ChubbyKaijuDAO 	2.   NA           $LFG
<HIDDEN>	<HIDDEN>       	1.   %100         $MON
MON	    Moons of Mars       3.   %100         $HOP

<< ALERT - YOU WERE ROBBED BY peter#2456 OF 30 $LFG >>
