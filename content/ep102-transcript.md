+++
title = "Episode #102 Alexei Zamyatin. Transcript"
date = 2023-08-08

[taxonomies]
tags = ["podcast", "transcript"]
+++

Episode link:  
[https://www.citizencosmos.space/alexeizamyatin](https://www.citizencosmos.space/alexeizamyatin)

<iframe width="560" height="315" src="https://www.youtube.com/embed/anK4shpKDKY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<iframe src="https://player.fireside.fm/v2/7d8ZfYhp+Y_GvvY9j?theme=dark" width="740" height="200" frameborder="0" scrolling="no"></iframe>

Episode name:  
Bridging Digital Nations: A Discussion on the Corruption of Centralized Bridges, Academia vs field work & The Importance of Community in Decentralization with Alexei Zamyatin.

In this episode, Alexei Zamyatin Co-Founder of Interlay is interviewed. He discusses merge mining, the first cross chain protocol and how it contributed to domain squatting. Alexei gives his thoughts on the dangers of projects using their own token as collateral, the future of trustless bridges and the power of academia.  There is also interesting discussion regarding the innate corruption of man over time and how trust in software increases with use over time.

--------------------------------------------------------------------------------------------------------
Citizen Cosmos  
Hi everybody, welcome to a new episode of the Citizen Cosmos Podcast. And again, I love doing those intros and I love messing them up. But nevertheless, I have with me today Alexei. Alexei is the CEO and founder of Interlay. We will find out from him about Interlay and about himself in a second. But Alexei, hi, welcome to the show.


Alexei  
Hi, thanks for having me.


Citizen Cosmos  
I'm very glad to be having you. We are slowly, in Citizen Cosmos, have been trying to interview people outside of just Cosmos ecosystem. And in my opinion, you happen to be such kind of a person who's not just focused on the Cosmos ecosystem, but focused on the whole of Interchain. And this has been our object and goal all along. So first, I mean, I already said CEO and founder of Interlay, but please, if you could make your own intro with you know, whatever you are working on, whatever you fancy telling about yourself, please.

<!-- more -->

Alexei  
Sure. So I'm Alexei. I'm the co-founder of Interlay. We try not to use the word CEO, because Interlay is a network, so we actually don't have a CEO or anything. I am the CEO of the software company that is building the open source software for it. I'm a computer scientist by trade. I got into Bitcoin in 2015 and have been working in that space, on the research side. So I actually come from a research background.

got into Bitcoin through Namecoin actually. So I was actually doing my bachelor's thesis and one of the topics happened to be looking into Tor traffic and obviously what's the best place to figure out how people were using Tor. Well, you look at Silk Road and that got me really interested in what else you could do with Bitcoin. And yeah, I've been kind of going from one topic to the other. So basically doing a random walk in the entire space. So looking at what else can we do with blockchains like Namecoin, decentralized identities.

got really interested in merge mining, which happened to be the first cross-chain protocol that was deployed actually. And then kind of, you know, went from topic to topic, we looked at payment channels, commit chains, which later became all these L1s and roll-ups. And then I ended up doing a PhD out in Pure College in London. Again, by pure coincidence, I landed there. And the topic that we ended up working on in detail was cross-chain communication. So after the SegWit2X debate on Bitcoin, for me personally, I kind of realized

okay right the bitcoin is not going to change not a lot probably shouldn't in with like probably it is as good as it is let's put it this way but we still need innovation so the idea was well how can we get bitcoin to other networks and connect kind of the adoption and the values of bitcoin with all these new networks ethereum cosmos polkadot and so on where a lot of the innovation is happening and we wrote a paper we proposed the first economically secure bridge design back in 2018

Specifically for Bitcoin to Ethereum, we then went and followed up that work, providing a general overview of the cross-chain space, like the problem, different solutions, working together with quite a bunch of researchers that were at that time leading experts in the space. And then ended up spinning out into Interlay to really now build this in practice. It was the most rewarding thing really is to take the paper and then try to build it and make a product out of it. and we have been doing that for the past three and a half years now.


Citizen Cosmos  
Nice, nice. So you said Namecoin. I remember Namecoin is probably for me is the first real use case really for cryptocurrency apart from money. Okay. So obviously money is the obvious one. But well, what was your first, you know, a different question? What was the first shitcoin that you baught

Alexei  
I mean it must have been Namecoin because I needed it to play around with stuff. Yeah, I was never super fascinated with trading and so on. I was a student back then, I had no money or anything really. So the time investment was what really counted, especially everyone was telling me, oh, it's dead. The price had just dumped back to $200. Everybody was like, oh, it's Bitcoin, it's dead. What are you doing? Why are you wasting your time? So that was kinda already 

like, oof, OK, we're taking a risk here. So yeah, I guess it was Namecoin. And then, yeah, later, I don't remember. It's, yeah, I don't remember anymore. I think I definitely got some Dogecoin at some point, just again, just to play around, because I was doing analysis of MergeMined coins, showing that MergeMining can be good, but it can also be very, very bad. It's like Dogecoin was fully centralized partially because of that.

Citizen Cosmos  
No, no, no, don't worry about it. I was just curious. I was curious.


Citizen Cosmos  
Uh-huh.


Alexei  
So it was really like many for research purposes do some transactions, you know be able to kind of do something


Citizen Cosmos  
Oh, we definitely get to the mergemining part. Don't worry. Just like, I like trying to see how far away I was in my 2014-15 from the same kind of tokens that most of the guests that come to the podcast were. And sometimes it's hilarious that you find out because there weren't that many, right? I mean, of course there was like, you know, the Bitcoin talk, altcoin thread, right? And you could find thousands and thousands of them. But the big ones are more or less 

the same. You mentioned your in...


Alexei  
Yeah, I was just getting started, I think. I was like hanging out. I was more like observing. I wasn't, I was just getting started. I was more like watching and learning and like doing research. I wasn't as deeply involved in the ecosystem until a few years later, I guess.


Citizen Cosmos  
Oh, I understand. I mean, it took me three years to read the Bitcoin white paper from the point I actually started to use that stuff. So you mentioned your intro into the blockchain. And you mentioned computer science, you mentioned other several things that could be seen as techie related. What attracted you essentially to that area? Like why, why technical area? Why computer science? Why, why, why merge mine in the first place?

What was the X factor?

Alexei  
So I went to gymnasium in Austria. I grew up in Vienna in Austria and I went to gymnasium here and we really didn't have any like the technical education was very limited. It was more focused so people who graduate from that school they'd usually become like doctors, lawyers, economists go in that direction and so on. We barely had anyone doing tech and I kind of got interested in it. I don't know why so you know you always had like in a classroom you have like a beamer, a computer and you have to have

someone who volunteers to make sure it's turned on and then kind of fix it, like help teachers operate this. So I basically got to do that. And it felt cool. Like, oh, you know, you're the computer guy. And I had like, the computer science education was really minimal. Like my first time coding was actually my final year of school where my parent, I was already thinking like, you know, maybe all the computer science and parents like, well, you know, you've never done anything with computer science before you go and study that. Why don't you go in like there was a program where you could try 

university courses during your last year of school. So I went and tried to learn some C programming, C++. And that was the first time I actually got any coding experience. And it was super interesting because you get to build stuff. So I always want like, once I discovered this engineering aspect of, even if it's just software and you can't really see it, you're actually building and you get to be creative and actually have something that you can result pretty quickly. The other option would have been a doctor but

Yeah, that I think it's better this way. Let's put it this way

Citizen Cosmos  
It reminds me of, I don't know if you remember or if you've seen this, there is a movie from the 90s. I'm not going to say the name of the actors now. They are famous like 90s actors and it's like a romantic adventure comedy movie. The guy is like running through the jungle and he's like roaming and breaking stuff and everything is going wrong. And then he's like, damn, I should have listened to my mommy and been like a beauty therapist

earning, you know, whatever. So sometimes in our industry, like when you say the doctor would have been the worst option, I'm like, I don't know, you know, maybe a doctor would have been much calmer, you know.

Alexei  
Maybe. Yeah.

Citizen Cosmos  
Alexei, you mentioned merge mining and I know one of the papers you did was analysis and effects and implications of merge mining. I'm curious what has drawn you to research merge mining and why this particular paper? What did you find? What was your findings that led you to move on in your journey?

Alexei  
So when I started my bachelor's thesis, we were actually looking at Namecoin, and specifically was name squatting. So that was the first kind of research work we did. And we realized like Namecoin tried to do like decentralized identity, you know, like you could register a website, domain, whatever, and it was decentralized. What's the number one problem? Squatting. Like every name, everything was squatted. You had no real adoption at that point anymore. And we tried to figure out like, okay, why does it not work? Like what's the biggest problem? And we realized like miners were just buying these domains left and right.

scanning Alexa top 100 or 1,000 and just getting all of them in all combinations. And then we were like, OK, well, why do miners do that? And essentially, we saw, OK, they are just merge mining. It doesn't cost them anything extra because they're getting the name coins on top. So merge mining means you mine Bitcoin, and you can also reuse that prof of work for namecoin. And then namecoin was not worth a lot, especially when the market crashed. They were just buying domains, like some of the big miners, just, I guess, speculating that maybe the domains in the future

will be worth more. And then we kind of saw, well, merge mining, that's kind of a bad side effect, because you have miners doing stuff. They're helping your network, but they really don't care about it. And then we kind of dug deeper, and we saw, oh, wow, Namecoin was actually centralized for quite a significant period of time. Like, there were a few pools that had more than 50% of the hash rate. Because merge mining, it's not mandatory. So any miner can decide to do it. And what happens is typically the mining pool operators just, you know, they turn it on.

you update the software, but basically they will just also merge mine. So we realized, well, it's kind of curious and curing like back then it was like this was more with the security research center. So the idea was, okay, like where can we break stuff? Where can we show that things are not working? And yeah, that kind of got me more involved in the whole space. So we did a lot of data analysis, got to learn about different proof of work mechanisms and also realized, well, actually it's pretty cool because it's like it's cross-chain. Like you have two blockchains that

talk to each other. And I always found that interesting. And back then also saw, well, probably, you know, you already had so many blockchains, there's never going to be one coin to rule them all, right? There's always going to be different innovations coming out, and we'll definitely need to talk to each other. But it has to be decentralized. I was always very interested in this full decentralization. How can we solve this very tough challenge of not trusting anyone? And I think that's kind of what's sent me on this direction of really digging deeper into research

solve this interoperability problem, which turned out to be unsolvable. And you have to do a lot of complicated things to make it work through incentives. But that made me choose to go the academic path. There was the option to go work for one of the bigger consulting companies in the blockchain, doing blockchain for them. But back then, you know, consulting companies were looking into how to sell mastercoins to institutions, which was not super interesting.

So yeah, that's kind of the direction I went in.

Citizen Cosmos  
I actually have a question about academia here for you, but before that you said one interesting combination of words and I want to know what it means for you. You said the combination of words full decentralization a second ago. What does full decentralization mean for you or is there such a thing as full decentralization?


Alexei  
I mean, you've been, you're catching the right questions, I guess. So no, of course there is no full decentralization. I mean, there is no full trustlessness. You always trust something. Um, and like how I personally see decentralization is it means. I don't trust a single entity, but I distribute trust across many different people, um, and the set that this group of people can change. So even if a part of it becomes corrupted over time, it can be kicked out or new people can join. So you have this continuous growth and, or like change dynamic network

making it permissionless. So in theory, anyone can join, which makes it inclusive to everyone, which I think is a big, big property that is important here. And then it also means I don't trust that someone in a top of an organization remains honest for whatever, like for as long as I'm using it. Because for me personally, I think for a lot of people who've experienced, FTX, Quadriga, and all of these, like MTgoks, all of these things that have happened over the years, one lesson learned

I think for all of us is people tend to be corrupted at some point. It happens to everyone and if a temptation is great, so is the risk. And the trust in a certain organization doesn't, just because something has existed for five years and worked well, doesn't mean that it's not going to be corrupted tomorrow. There is no guarantee, right? You can trust people and that's great, but I generally am a very optimistic person. I try to say the best in people, but we've seen also that there's a lot of corruption. And I think the whole idea of crypto is to well,

let's encode as much as we can in software, get it, let thousands of people run the software and then the chance of all of them being corrupted and changing the software is very low. And I think the cool thing about that is, the longer the software runs, the more people run it, the more people join the network, the greater your trust becomes in it because you can actually see, look, it doesn't have bugs, it's been running for a while. There's a big enough community of people where the chances of them all suddenly being currupted

and trying to steal from me directly, one out of 100,000 users is very low. Of course, at a grander scale, if you're moving in with billions of dollars into a network that only has TVLs of a few hundred million, then it becomes risky again. And then that's where these things can break. But for a normal individual user, if I'm using Bitcoin, Ethereum, or even any of the smaller chains, I'm pretty safe. I mean, if it matches all the criteria of being decentralized and robust,

I know if it doesn't have some admin keys which some or two or three people control The likelihood of everybody colluding is very low and the longer the thing is operating the less chances of there being a bug That might affect me and I think this for me is like the upside of being decentralized Trust grows with time. Whereas the trust in an institution as we've seen with the case of FTX best example We all thought ah, they're really doing a great job. They're really doing it the right way Well, how I mean even myself

I count myself to the people who thought, well, actually they're playing the right, the long-term game right, they're doing regulations, and thankfully I didn't use them. But you know, I also got tricked. I thought they were doing the right way, right?

Citizen Cosmos  
Absolutely. I think people underestimate how communication develops over time. Considering blockchain is a communication tool, the more two people or three people or a group of people communicate between each other, the better that communication usually, right? That's the goal should become. And of course, the same happens here. Absolutely agreed. Before I move to the academia questions, though, again, something you mentioned that I would love to hear your opinion. You mentioned TVL's and Marketcaps

Citizen Cosmos  
And actually lately, well, lately, it's not like it's the first time in blockchain that we see this becoming an issue or a question. And this is my question. Is this the following the following example that I'm going to describe? Is it an issue and should something be undertaken? So what I'm talking about is a lot of projects where the TVL is higher than the market cap. And hence, a lot of people are afraid that, OK, if the Marketcap of a project with a TVL 

of 40 million is only like 400,000 and what stops people overtaking that project and using the total locked value. Now, is it a real issue to be concerned about or is this more something made up in the air kind of thing?

Alexei  
I mean, so it really depends. It is definitely, look, if I put on the academic hat, it's absolutely an attack vector, right? So from a theoretical perspective, it's like if you use a system that only has 10 million market cap for the need of asset that is needed to vote on certain things, you could be at risk because in theory, somebody could buy 7 million of it and try to steal the 40 million that you have locked in the network. Now, this is theoretical. Now, if you look at execution,

does often look quite different. So the question is, okay, I mean, if you try to, if the network was only worth $2 million, why? Because not many people are buying it. If you try to buy 50% of that of the market, you're gonna push the price. If you try to buy OTC, I mean, you have to find someone who's gonna sell you these 50%. So I think in practice, trying to acquire a meaningful position of an asset or a network is not that simple. You have to have enough people who want to sell it to you. It's similar, like,

Definitely, I would argue, easier than with acquiring 50% of the hash rate, because you need the other physical aspect. So in proof of work chains, you need to get mining power, mining the ASICs. But again, it's still possible if you know the producer or the companies that are building these ASICs to do it themselves. With proof of stake and coin vault governance, it does become potentially easier in theory. But again, I've not seen it. There has been hostile 

governance takeover attempts, but these things typically happen because people don't vote. That's the bigger risk, that people don't pay attention to governance and that just governance proposals pass without people being aware. So I think it's more on the way that governance is structured. If you're conservative and you're careful and make sure that, you know, and we don't need to reinvent things like democratic voting has been around for a while and you can add a lot of failsafe features like, okay, if it's a close vote, if there's a sudden last minute flip of the vote because somebody

like last few minutes, like change the vote. OK, extend the voting period or don't activate it and re-vote again. So yeah, I think maybe coming back to the original question, it's definitely something to pay attention to. It does not mean that all this thing will be attacked. I think it really depends on how the native token is used in the protocol. So if it's used like in the case of Luna, where it's really part of the protocol and there are a lot of emission, new emissions

can be triggered by some failures in the system, then it's difficult. Then it's dangerous. Because then the value fits use as collateral. So I think generally using your own token, like in the protocol as collateral, and that's so collateral is dangerous. So you just then you just speculate that the people or hope that the people who stake it have intrinsic value and want to be honest. And the majority it's statistical game then it's no longer economic security. We're not as strong because what's the first thing that loses in price?

protocol breaks. It's the native token. And if, as in the case of Luna, or there's other protocols, right, which will trigger, if something goes wrong and the token price goes down, if it triggers liquidations, for example, or more emissions of this native asset in attempt to stabilize, what will happen? You get into this death spiral. And that is risky. So that's basically what you should be, I think, looking out for in a system. If basically this economic securities or if, depends on the native asset

because then it's no longer economic. Then it's very weak. Let's put it this way.

Citizen Cosmos  
Yeah, yeah, absolutely.

Alexei  
So it's a bit of a flip side. It's not the governance aspect, but it's the governance side is slow. You will see somebody making the vote. And usually, if it's a proper governance system that is in place, it takes a lot of time. It's not that, OK, there's suddenly a proposal. And within minutes, everything's gone. It takes days, weeks. There will be a lot of people who are seeing this, if it's a bigger network, and raising alarms. What's more dangerous is these automated things. If it's a defib protocol and you just have a lot of escalating events

which happen automatically within a few minutes, which can happen in like we've seen like in the case of...


Citizen Cosmos  
No, it was interesting to watch, you know, it was interesting to participate in that and not the first time or the last time we I think participate in things like that. Let me let me ask that. I mean, I have a lot of questions springing out. I wrote them down that I will try to ask you in a bit. But I'm going to ask you the academia question. It might not be the most fasinating question. We do get a lot of researchers coming on to this show and I like

Citizen Cosmos  
to ask them this question. Now, what is your opinion as somebody who has a lot of research papers out there, a lot of research work out there and you can follow your kind of academia path, it's out there. What's your opinion? And I'm going to extend the question a little bit. The question itself is academia versus field work kind of versus doing things. But then kind of like extending this question, I would say that, you know, especially in Cypto

especially in a field or an area which is not always following the academic path, right? It's asking questions, it's asking a lot of questions, which is actually from academia, I guess. But still, you know, what's your opinion as somebody who comes from the academia side and identifies as the academia side? Is the correct way to do everything is following the strict rules that exist in academia?

Citizen Cosmos  
Or is it ok to go left right and experiment.

Alexei  
I mean, I don't think academia has strict rules. So especially in like in the blockchain Bitcoin space, academia is very, very fast. That it was a very, it's very stressful. So when you, when I started my PhD, I always had the feeling I got the classical imposter syndrome. Oh, everybody knows so many things. I have an idea. I check presented last year at a conference and you, you know, you go, you, you try out the experiment, you go in different directions and then you get closer at some point. Oh, you've suddenly you're doing completely new stuff that nobody has thought about

before. So I think if you look at the Ethereum research forum, the early Bitcoin talks, a lot of these things, a lot of the ideas that were turned into papers later have been actually mentioned already. They existed in some forum posts. It's a different beast to actually take that, build it into a full, like actually prove that it works and, you know, structure it in a way that it can be reproduced because it's a different thing to write an idea in a forum, hey, look, why don't we use, we could use, you know, do atomic swaps with light clients. So that existed.

And then I think what you're getting to, and I think I fully agree, you don't have to write a peer reviewed paper to have a brilliant idea and have a very valuable contribution. If you look at the Bitcoin sidechains paper, they did a really good work of taking what existed in the forms, adding on top of that, and putting it together in a comprehensive manner. And they were very fair in referencing existing comments and discussions in these forms, which is a very tough thing to actually do to find them all. And personally, I mean, when I was working,

coming from these forums as well, I would always personally try to see if we have a new idea, did it exist there? And if it did, fine, let's credit the people, but did they pursue it further? No. Well, then it's still actually, if it's a good idea and it has never been pursued further, maybe it should be, maybe we should try to extend on that and build a proper academic work. But what does academic work mean? It basically means you specify, okay, what are the assumptions? You challenge it and you try to put it in a structured manner so someone who wants to build this in practice can read through it and understand

okay, the assumptions are okay, we have, I don't know, this guy is honest or we don't assume any honest third parties. We assume that messages get delivered on time. So there's some basic things that you have to assume, but are very important for a system to work or not. So I think you have both. So you have a lot of stuff happening in crypto, which ignores academia. And I honestly think that's not a good idea. And generally, if you look at the protocols nowadays that are really successfull

they have a lot of researchers coming from academia working with them, because a lot of these problems have been studied before. So if you're ignoring academia and you're saying, oh, it's a bad thing, it's so social institutional, you're just going to be at a disadvantage. On the other hand, we have a lot of researchers who just completely who play this purely academic game. If it's not peer reviewed I'm not going to look at it. And I fully disagree with that approach. That doesn't work. And honestly, for me, there's a reason why I am no longer in academia, I like building 

Alexei  
things, I prefer to really focus on products and solving problems. And I don't care anymore as much about citations. It's nice, you know, as an academic, you get your citations and you get a bit, you know, get addicted to it. It's so great. I unfortunately I've seen in many instances and I still am on like committees for conferences and I review papers, there's often the case where it's just a paper for the sake of writing a paper and then it doesn't contribute anything. And that's the other side. And I think you, if you look at it here.

Ethereum today, and also Polkadot, Cosmos, and Avalanche, and all these L2s. There's a lot of research in there. There's a lot of academic work, like researchers leaving academia or still working with universities to actually prove that things are working, really dig deeper and build these more sophisticated systems. I think it doesn't have to be a university. If you look at Paradigm, for example, they're a very good example of hiring people out of academia to work in industry and still doing research and I think this is the way to go.

Citizen Cosmos  
I'm glad you said it because a lot of the people I talk to in crypto, the most fascinating minds are some of the most fascinating minds, sorry, come definitely from academia. Some of the other ones definitely are people who never touched, never spent a single day in university. And it's astonishing to see what other things are out there. Let me ask you a strange queastion

Citizen Cosmos  
like resume a question in the direction of academia, considering you've done so much research, considering the words you say right now that not everything has to be bound to academia, and considering that in the experience of a lot of crypto projects, starting crypto projects, unfortunately, a lot of the teams kind of miss out on research in the market. What would be your advice as sombody who has done a lot of extensive research

Citizen Cosmos  
for any teams that are starting their journey out there. They have an idea, they think it's the most fascinating idea and they need to implement it. What would be your advice on how to approach the research side?

Alexei  
This is why I still enjoy working in academia and a lot of my friends and former colleagues are now still in academia, I think they share the same ethos. It's about solving problems. So if you were to approach, so if you have a new idea and you're not sure if it has been done before, well, what's the best way on the internet to get validation, just post it. Hey, I have this idea. Does it work? If you're concerned that it might be such a great idea.

then you have to Google. Then you can go on Google Scholar and search for some papers. You can go on ePrint. The cool thing about academia in the crypto space is everyone makes sure that the papers are open access. If I see a paper that is not open source and I cannot read it without paying, I generally assume it's not a good paper because somebody is trying to hide. Why otherwise would you not make it publicly available where you know all the innovation, all the cool things are actually open source? So that's always a red flag, I think.

if you see papers that are behind paywalls in our space. So you can always find anything open, like it was open access and that was chat GPT-4. I mean, that solves a lot of problems. Ask the AI, right? Just throw in your question and it'll probably help you out, like point it towards existing works. I mean, and the better it gets, the easier it becomes. Or drop one of the researchers an email. I mean, let's say you want to do something with threshold signatures, right? And you Google threshold signatures

you will get a list of papers, right? Of course, it's hard for you to get started, like which one's the best, which works, which doesn't. Citations help, right? But you can drop an email to the authors and they will actually reply more often than not. And the interesting part is a lot of the authors of these works are somehow involved in other startups in the crypto space, so they know the game, right? They're super happy to help. So I think it's just talking, right? Just ask and then, I mean, for an academic, for a researcher,


Alexei  
I mean, the biggest gratification, I think, is if somebody is interested in your work and asks you questions and wants to build it. I mean, so for example, in Interlay, we publish the papers, but everything we do is open source. Even if we do it as a product and so on, all the papers, all the research we do nowadays, we publish it. Why? Because somebody else might be able to do something good with it. And in the end, there is no point of hiding it and isolating all the work you've done. I mean, patents are one thing.

I am not a big fan in this space of trying to hide information because in the end

If you came up with the idea, the chances of somebody stealing it from you are pretty low. If they improve on it, fine, it can happen, right, that somebody steals your use, but at nine out of ten cases, it'll end up you collaborating or there's a better solution and you learn from that. So I think it's getting there.

Citizen Cosmos  
Thank you for saying that, by the way. Thank you for saying that, man. I think it's very important for more and more people to say those things. For a long time, people were scared of opening things up due to limitations or what have been told, especially, it depends on where they come from in the world, right? If they come from originated, the origin, sorry, is especially Eastern Europe or Asia, unfortunately, due to the sociological issues.

kind of, oh, everything is going to steal my stuff, you know, and like, it's funny, you mentioned ChadGPT and just before we started to the recording, I was on crypto Twitter as usually and there was a letter, there is now an open letter with a lot of signatures from a lot of people to stop, that is calling to stop the research of AI models stronger than ChadGPT four for the next six monts because we are as humanity are not 

Citizen Cosmos  
prepared for it and it's signed by like now a lot of people and it's interesting. What do you think? Should people be afraid of going down the rabbit hole? Doesn't matter which research we're talking about now. I mean, of course we're talking chat GPT, but

Alexei  
This is a tough one. So I think there is no correct answer, right? And I think there's always been two camps, right? Like people who build stuff and want to just innovate and sometimes ignore the ethical questions around it, whether it is ready. And I think if you're a scientist and if you're building something and that is part of your job to think about the ethical implications. In our case, coming from like a secure research background, if I'm researching something

that might break? The ethical question is, should I be doing that? Do I need to communicate this before? Do I need to be careful? Do I need to talk to people who might lose money if I just go publish a paper that shows, oh, there's a bug in a protocol, right? So the ethical question is always present and should be. Whether we should hold off building, expanding chatGPT for the next six months, I do not know. I'm not an expert in this field. I don't know if it's really going to make a difference, honestly. Are we not ready as a

society, I don't know. I don't think it's the right or wrong answer. I think it's good that it's been challenged because if we never challenge things, then we never figure out what's the best decision. And we've seen it, I think, with privacy. I think on the internet is a very good example where we've seen that a lot of companies who just pursue innovation and really just also profits at the expense of individuals, like they're losing their privacy and being harmed

And I think it's good that we try to be proactive rather than just reactive. What is going to be the right decision in the end? I do not know. Probably not the spicy answer that you hoped for, but...

Citizen Cosmos  
That's I... No, no, no, no, no, I was curious about your opinion as a researcher not trying to make spicey content


Alexei  
I mean, I have seen both sides, right? If we at Interlay come up with something that could really, like that has a very positive impact on a lot of people, but could make a lot of people, you know, lose a lot of money or be at harm. Oh, it's a tough question. Do you, what do you do? Like you need to innovate. There's a lot that you have potential investors that want you to push forward. And there's a whole industry depending on you and really that wants this. On the other hand, like it's a tough position to be in. Like, could you live with yourself that you just say, oh, whatever, let's do it. And then people get harmed. But on the other hand, what if you, if you're too slow and you dont do


Alexei  
it, maybe industries or other people get down too. So it's a tough one. I think it's, the goal is just to talk to as many people as possible and then make an educated guess and then see what happens.

Citizen Cosmos  
Hmm.

I know one guy, Einstein, he made an educated guess. I know what happened after that some years, but nevertheless, let's talk bridges, right? Let's talk bridges, bro. Let's talk bridges. So, man, bridges. Here is, I'm gonna throw something at you and you tell me, I mean, of course your opinion is gonna be biased, I understand it, but since you're building one, but still I want to know what you think about this. So here is something that I've been,

and a lot of founders and you know we discuss a lot of things like really for many years now and one of them thoughts that I've been not just hearing but expressing myself and agreeing with and this is something I want to throw at you is that bridges what we call today bridges I'm not talking IBC the technology I'm talking actually things like interlay I'm talking I don't know Evmos, Gravity bridge

Citizen Cosmos  
Axelar, I don't want to name anymore. This is just random names. So yeah, whatever springs to mind first are to become more the next centralized exchanges really, because the more centralized exchanges are failing us. And if we see now Binance or Circle or anyone like that fail, or when we see one of them fail, probobly will push all the projects

Citizen Cosmos  
that have been building bridges and have been staying somewhat in the background like Interlayer or like Fusion, for example, to a much different positions where they're actually becoming not just a bridge, but they're giving APRs, they're working with staking, they're working with interchange technologies, they're giving user interface, user experience. What's your thought? I mean, I can carry on for a while, but what's your thought about this? What are your thoughts, about this idea 

that bridges will succeed a lot more like such as yourself.

Alexei  
So when we're talking about this topic, I always think about Vitalik's prediction that the future will be multi-chain, but it won't be inter-chain. And it's something I've been thinking for a long, long time. I mean, my PhD focused on how do we build trustless bridges? And one of the key results of the whole PhD, and it was like theoretically proven, peer reviewed, critically discussed, but in general, but not accepted, it is impossible to build a bridge between two networks, which is completely trustless. You always have

something in the middle that you trust. And that kind of, if you think about, is Vitalik right or wrong, it kind of first would lean us in the direction, OK, he might be right. He also will have these centralized bridges between all those networks. And it's going to be super challenging. And the future might look like, OK, well, they will become the next centralized exchange. Because what is Binance? You can use Binance as a bridge between two networks. You go to Binance, you withdraw. A lot of centralized bridges today are just the same, right?



Alexei  
But then on the other hand, we know since 2014, I think, is when the sidechains paper came up. Please correct me if I'm wrong. We know that there is a way to improve this. The best way to build a bridge is to have both networks verify each other. So you have two live clients. And this is how IBC, the standard, is ideally supposed to work. You have two Cosmos chains, and they verify each other. The same is the same case in Polkoredik CM.

we have a shared security model where the parent chain makes sure that the cross-chain communication works successfully between the two networks. So when I talk to, let's say, Akala or Moonbeam, I know that our transfers will be enforced by the Polkadot network. So these are these two models and they work. And we can make bridges trustless and then you don't need to have a centralized exchange anymore. But then what is a centralized exchange? So yes, you will trust, in the case of Polkadot, you have Polkadot, the relay chain, and the thousands of staker nodes

and so on that you will trust. Arguably much much better than centralized exchange like FTX. And you also obviously when you talk between two chains you trust each other. So my personal perspective and this is a bet I'm actually willing to actually take right. I think in the next five years we'll see big networks like Ethereum, Polkadot, Cosmos, Solana, Avalanche and so on build trustless bridges between each other. Trustless in the sense of being liteclient to liteclient. There


always some trust involved. You need to make sure the messages are delivered, the light clients need to work. Then my bet is within five years, this will be the main way of bridging between these chains. And then other solutions that are more centralized, they will focus on bridging from these big ones to smaller chains. Smaller chains which can't afford the sophisticated light client technology or which have some custom tech which where light clients don't work. And it's very difficult to build a good and safe and scalable light client as we've seen with the Ethereum

case with Altair, which has vulnerabilities. So I think it will be a transition. But the risk is, and that's what I'm concerned about, is that we rely too much on trusted bridges. And I think, but in all fairness, the more we move in this direction, the more bridge hacks happen, the more cautious teams become, and the more open they are about the risks. So if we look back at the 2017, or even Defi summer 2020

Alexei  
the bridges that we had, they would even have paths to decentralization, but they wouldn't openly admit that they're actually centralized. If I look at it nowadays, I think most projects are very open about their security. Not all, right? But most are very open and say, look, this is what we do, this is what we believe in, these are the risks, and we're trying to improve light clients, and that most of them are open to the light client to light client technology as well, once it becomes available, because most of them know they'll have to evolve into that to compete

with these light client bridges. But yes, I definitely see the risk, and these failures of these bridges have been known to wipe out entire ecosystems. Best example is what happened to Nomad. It was very unfortunate. It had nothing to do with the bridge technology, right? It was a very unfortunate event. And I feel very sad about it because I think they had a very competent team and still have, right? And there were a lot of smart people working there. Bugs happen. But then the fallout was

very big. We were also affected, right? Because it took a hit. The Polkadot ecosystem was affected and others. So it's definitely a risk. And I do think we need to be very careful and educate the community about, is it wrapped or is it native? And I always, when we work with the DEX, I would always like, this is the first question I'd raise. Okay, well, why are you not, if they don't do that, why are you not showing that you don't have native Bitcoin? You can't have native Bitcoin. You should not be showing the native bitcoin logo

unless you're really doing an atomic cross-chain swap where it's native Bitcoin. Because otherwise you're lying to people. And I think educating the community of, okay, hey, look, it's not native, it's deposited somewhere, it's somehow wrapped. Of course Binance also wraps their coins, right? It's wrapped on the Binance exchange. It's the same thing and they don't do it. But I think we as decentralized technologists have to be better than Binance or FTX. We have to showcase here the risks, this is what you're doing, educate

yourself and basically at least the user knows if a bridge breaks I might be affected. If I have no idea which bridge a protocol is using, if I hear bad news about the bridge I might be too late to get my funds out and then it's unfair because your core community of builders will know and they will basically get out but your users will not be able to.

Citizen Cosmos  
Absolutely. But by the way, 22nd of October, 2014, introduction to such and so you were absolutely correct. Let's do some basic education. Can you let's go back to some very basics. Can you explain in your own words the difference between wrapped and a native token?

Alexei  
I mean, it's actually very simple. So Bitcoin only exists on the Bitcoin blockchain. There's nothing physical. But if we were to use a physical analogy, think of it like this. If you want to trade a barrel of oil, it's actually physical. You know oil exists. It's in the real world. If you want to trade it in the stock exchange, you wouldn't drag the barrel in and put it there. If the stock exchange is digital, it's a different system. There's no way of you to start giving glasses of oil

to people and them giving you money. That's not gonna work. There is some standards of how stocks are traded. So it's your commodities. What you do is you put it somewhere in custody and this someone will give you a digital certificate saying, okay, we've deposited here, thousand barrels of oil. Now you can go and trade them. And if I buy one of these certificates, in theory I could go and redeem and actually get that barrel of oil. And this is the same thing, that this is the same way how wrapped assets work. You have things that exist on

Bitcoin, on Polkadot, on Cosmos, on Ethereum, so generally on the chain that they were minted on. I think it's a good definition to say a native asset is native on the chain that it was minted on and this also includes USDC. If Circle mints USDC on different chains then it's native because it was explicitly minted by Circle on that chain and it will be wrapped if somebody else except the minter moves from one chain 

to the other. And again, in most cases, it's always wrapped. So if you take Bitcoin, there is no Bitcoin minter. So nobody is issuing Bitcoin unless the entire Bitcoin proof of work consensus would say, oh, now we're also moving Bitcoin to some other chain. And this will not happen, obviously. Then Bitcoin is open, another chain is always wrapped. And wrapping means there's something in the middle that makes sure that the Bitcoins are locked up while you are using the wrapped asset and idealy when you 

Alexei  
want to go back, this thing or committee or whatever will guarantee safety and will guarantee that you can get the Bitcoin out. And that's how all of these bridges work in the end. And then the challenge of wrapping or bridging is how do you build this intermediary? Is it one person? Is it a group? Is it an entire network? And I think it's fair to name examples. You have Bitgold. WBTC is one company. You have multisig federative 

Alexei  
bridges like the Bitcoin bridge to RSK or you've had a few like other kind of systems. And then pretty close to that you have networks which is just a multi-sig but a bit bigger if and the difference would be that anybody could join right if you have a key rotation and bridge operators can change and like come and go then you get I guess systems like Axelar if it is really permissionless or other networks that you know use kind of some threshold or consesus model on top to have some 

kind of rotating set of operators. And then the ideal case is if you don't have anyone holding the assets anymore but you have smart contracts. That's the optimal case. That's the live client bridge model.

Citizen Cosmos  
Hopefully, we will see more projects actually move that way. And just for the record, when I said, I think I might have not been a little bit clear with what I said, bridges, in my opinion, will take the place of centralized exchanges. I guess what I meant wasn't trying to imply that there will be the bad actor. I was actually trying to imply that centralized exchanges will cease to exist and we will have decentralized bridges instead of them. Where users

are actually able to communicate in the same light way as they today. I mean, what was the only reason a user can go to a central exchange today? It's probably user experience or security kind of experience. So in my opinion, I think Bridges will catch up onto that in the next couple of years.

Alexei  
But to be fair, then I will say it. I agree with the risk, right? So there is a risk today that the bridges that we have today, which are more on the centralized side, will become the next FTX. FTX is a bad example because it was clearly fraud. It will become the next exploited or problematic centralized failing point, right? Because your security is only as strong as the weakest link. And our weak links today are Oracles which are 

Citizen Cosmos  
Yeah, of course.

Alexei  
bridges to the real world and bridges which are bridged between different crypto networks. And I think if we don't push innovation and unfortunately decentralized bridges are more difficult to build, they're not as profitable, you typically don't need a token, so it's not as easy for venture capital firms to invest in them. Decentralization has a price and unfortunately we only care about decentralization when it's too late. So we just have to hope that

enough smart people out there that are willing to go altruistic and spend their time or maybe there's networks and like I know that Interchain Foundation and Polkadot, Treasurys and so on, they actually you know they're more altruistic and they fund things like this and that's I think the right way to go.

Citizen Cosmos  
Yeah.

Yeah, definitely. And this is actually the last big topic before we move to the Blitz I want to ask you about is considering you guys are more focused... Well, at least you identify, right? It's very correct work to use in today's world, identification. So you guys identify as a Polkadot project to some extent. And I apologize, correct me if I'm wrong, of course, but...

like that. But what I was the question that I'm trying to get at is we haven't seen yet as many communications, in my opinion, at least. I mean, there are some developers talking between Cosmos and Polkadot projects, between Avalanche and Cosmos Polkadot, but there isn't like that, you know, that acceptance that, hey, this is all the same. This is just the Internet of blockchains. This is exactly what we were. This is exactly the reason why we came here for them to interact,

in a decentralized manner without any points of failure, blah, blah, blah. So what is the reason for it? What is stopping, apart from human greed, of course, and human tribalism? And if it's the only thing that's stopping, how do we get rid of it? What is stopping people from starting to understand that the interchange is wider than one single project?

Alexei  
I think economic interest and tribalism is definitely one big, big aspect. So it happens. And I think right now there is this push with app chains. I think Polkadot and Cosmos have very similar approaches. They just did it in different orders. Polkadot did shared security first. Cosmos was very successful positioning Cosmos as the key as a good way to build new chains. But no shared security. Now basically they're moving in this direction. So Polkadot is really pushing substrate. And it's getting like...

building on Substrate, Cosmos is working on Interchain Security. Who is going to be first? I don't know. What I can say is that we as Intelli, when we were just thinking of where to build, we were talking to both Cosmos and Polkadot. Because these two networks were like, hey, we'd like a really decentralized bridge. And we're willing to provide some initial grant funding so you can bootstrap. And then you can decide what to do with it. As long as you do it open source, you can build it or you just give it to us. We ended up building on Polkadot because we like rust

why it made sense. And I generally can identify with the ethos of being fully decentralized. But I see that ethos in Cosmos as well. And in fact, we have a still pending grant from the Interchain Foundation from a year ago to as soon as the Substrate IBC library is ready to bridge over Bitcoin. And I'm still waiting for that library. And we've really been going back and forth of like, OK, is it ready? Is it pending? And I know there's been multiple teams working on it.

The problem is it's not easy. And that's the second point. I think at this stage, what's holding us back is technical limitations. So all the tribalism aside, I think maybe that's on the outside. But behind the scenes, everybody wants to integrate because there is added value, right? Especially the teams that are actually building products and the users. The users don't want to care about am I on one chain or the other. They want to use a good product. And if it makes their lives easier to go between different products, if they're on different chains, they will come to the products that allow you to do that.

that are well integrated among each other. So I think it's a win-win situation. What's holding us back is technical challenges right now. So light clients and making these things work is difficult. And if you want to do it properly, you need light clients. So I know that, for example, Polkadot has been working. There's a team that is funded by Polkadot Treasuries been working on building a trustless Ethereum bridge. Again, maybe let's say decentralized Ethereum bridge with light clients for a long time now. And then Ethereum switch from proof of work to proof of stake

they have to rebuild the light client now, the light client on Ethereum has issues, so they need to fix that. It's bleeding edge technology. It takes time. And the thing is, if you're building this, you have to do it properly. Otherwise, what's the point? You could have just added a multisig, and just be a centralized bridge. And the same with Cosmos, like Substrate IBC, like you needed the Polkadot light clients, you need to make it work with the Cosmos libraries. There were problems with using STD and OSTD, right? Even with the rust frameworks

themselves and also someone to push it and provide funding. And I think the mix of all of this is why we still don't have it. But it's for me, like my personal goal is to figure out how we can contribute either in the dev side, but there's teams working on it, or in education and just advocating for it and advocating for more support from the core teams. But again, in absence of this, you actually have Axelor is working very closely with substrate 

teams and will likely end up being one of the systems used to bridge between Cosmos and Polkadot. In fact, it already works, right? So if you go to some Moonbeam Dexes, you can actually swap and go over to some Cosmos Dexes pretty quickly. And you have other bridges working from Ethereum to Polkadot and from Avalanche and Solana to Polkadot. So it's going to be solved and less decentralized very quickly and I was... It doesnt mean 

Alexei  
more secure because obviously if a decentralized bridge is launched, there's still the code risk. So something that has been operating even maybe not using LiteClient, but has been operating for a while, probably still more reliable for at least some time until the code matures. So it's going to be a slow transition, but I think it's definitely going to happen. First, it's going to be using some existing businesses, and with time, it's going to become more altruistic using really protocol-to-protocol LiteClient bridges.

Citizen Cosmos  
Amen. But, you know, by the way, just for the record, sorry, before we move on to the Blitz, Neutron, the first interchange security chain, is about to launch in a month's time on Cosmos Live. So it's a tight race, you know, considering we're talking about non-tribalism, using the word race is amazing. But no, this is definitely our goal here is that Citizen Cosmos is accually just that, its education to help

Citizen Cosmos  
people see that hopefully that there is nothing to be afraid. We all big family and the more we cooperate, the more we can achieve. Alexei, quick blitz. Well, quick, depending on you. But it's three questions. I say blitz, but they're not really blitzy blitzy because I'm a slow person. I talk a lot. So feel free to answer them as you wish. First question, they're going to go like three to one as in three things, then two things and one thing.

three projects kind of typical I know that technically interest you and they don't have to be blockchain projects by the way but please don't say typical things like Apple or Ethereum or things like that say something that you're kind of more interested in something innovative

Alexei  
That's a good one because I have to go outside of the bubble of what you're doing day to day. I think what I'm really interested in is custody projects. The project is that try to solve the custody problem using threshold signatures or also looking something that not many people know. Actually on Bitcoin natively, you can use like Schnorr adapter signatures and all that were enabled through Tapper upgrade. So I think that's super interesting. Projects that try to 

say, OK, we don't need to wait for five blocks, but go on a big players to integrate something to give us good security and for institutions to be able to manage their keys. Hey, we have a whole network of hundreds and thousands of nodes you can use. And we can plug into all of these different projects. And projects can plug into us. I think that's really interesting. And that's the next, I think, big push in terms of the custody problem that we'll see. I'm personally very interested in things that are outside of the DeFi bubble.

So the connection between DeFi and actually real world commerce. Also I guess I'm biased because we work on Bitcoin and you see that there's people using Lightning for payments, but it's still very difficult and not everybody wants to pay with Lightning and with Bitcoin itself. And I think finding this balance between using Bitcoin as a store of value and as a payment and giving people the choice to do this in an easy way and basically have this gradual

transition from fiat to crypto Bitcoin, not instantly like, oh, we're going to be all Bitcoin tomorrow. That's not going to happen. So projects that kind of move in this direction, and I'm biased because we try to do that as well. I'm very interested in that. And I think, again, this is what we really need for adoption. And the third one is probably, and I never thought I'd say that because I never really jumped on the NFT train. But exploring the creative side 

Alexei   
of NFTs for not just buying a JPEG and putting it on my profile and collecting it, although I think that's very interesting, but exploring, OK, how can we use that incentive model? So the slightly different definition of ownership and playing on the fact that, OK, I can have something digital and people like having things. How can we use this to not only the technology, so that's a technological problem, but it's more like a society problem. How can we use these incentives and get people

in doing more things in the decentralized way, in breaking out of like old kind of structures. So publishing for example, I've been talking to a startup that's doing that recently that I find super interesting, right? They're trying to do publishing in a decentralized way, incentivize people to work together so they're not as dependent on these big publishing houses and that I think is also super interesting.

Citizen Cosmos  
Nice. Two things that, two motivational things that motivate you in your daily life, day to day life to keep on building interlay and everything else you're doing.

Alexei   
I think the number one is that I can with good confidence and good conscience say that we have never really, that I have nothing bad to feel, but we've never really corrupted ourselves in that sense. We really have always been trying to be fully decentralized, transparent with what we're doing with our community and that I can say that I honestly believe that we're trying to solve a problem that will make lives of many people better. It sounds like very everone is trying to make the world a better 

Alexei  
of place and so on. But I think that our path so far has really been of really like each decision we've made, we've really kind of tried to find a good balance between business decisions and still staying true to the value of Bitcoin and the vision. So that I think is that that's what makes it very easy for me, even whether bull market, bear market, whether something breaks, whatever that, you know, if things don't work fine, you know, we're doing our best to really solve a problem that we honestly believe in. So that's number one, so I think believing in the

cause if you want to call it. And then the other thing is I think people using the product. So actually, you know, people coming into our chats and saying, hey guys, Binance was down. I had to get some Bitcoin out. I went through one DEX and Moonbeam. I went through Intela. It worked. This is great. This made my day. That's the gratification. So actually, having people use the product and having people like what your doing and actually 

Alexei  
giving you feedback and taking the time to say, oh, okay, I like this, but this was bad, can you fix this? So I think, yeah, I mean, that's the biggest gratification that I think you can get as a founder is people actually using this stuff and actually saying, hey, I liked it, or look, I liked this, but I didn't like that. Even if they say, look, it's shit, I like the idea, but you're doing a bad job, still, you know, they've tried it, I know I need to improve. So I think this is really like what makes it interesting.

Citizen Cosmos  
Absolutely.

Citizen Cosmos  
Absolutely, I understand totally what you mean to be honest. And last one, dead or alive, real or made up, a character, a person, a writer, a developer, an inventor, doesn't matter. A person that again, dead or alive, invented or not invented that influences you or has influenced you in the past or a character.

Alexei  
Who is this tough?


Alexei  
So I mean, for me, it was probably my, but it's not a famous person, right? I mean, it was my grandfather. So he was a researcher back in the Soviet Union and everything. And like he would always, so one thing he'd always say, right? And I think that really influenced a lot of like the way that I kind of approach things. You can have the smartest idea, the best product, but if you can explain it to people and explain why it works and why it's better, and also you can phrase it in a way that it can stand the test of time

Alexei  
smarter minds can look at it and find improvements, then you're never going to make it. And I think this kind of, this approach of, you know, like you can be this, you can think you're super smart, you're the best idea. And I know a lot of people that, you know, they don't want to talk about it and they're very secretive and they can't explain what they're doing. And if you can't explain what you're doing, it's never going to get built. It's never going to reach public. And if you want to hear something, I guess, more on the,

Alexei  
I guess fanboy stuff or like who I really like in crypto Twitter. I think like right now, like I think that also has influenced me recently is Udi Werthammer and Eric Wall doing this Bitcoin order NFT thing. Well, everybody was, you know, trying to, you know, hype and like sell, like do like NFT drops and make money. What they did is basically they created this program where you like, it's a wizard school, like where you have to sign up and you basically do challenges and you learn about Bitcoin. And then you could get one of those NFTs and they did it very, in a very smart way. And they, you know,

their influence to get people to learn more about Bitcoin. I hope I don't regret saying that. I hope they don't mess it up. But so far, this has been really cool to see actually, Hey, you know, people in crypto are not only in for the gains. I mean, probably you never know, right? And maybe they don't have to anymore, but still, you know, standing up and spending your time to increase adoption and just, you know, education and not getting any monetary value out of it. At least not imminently. I think that's cool. And I think that for me also kind of, I'd like to do something like that 

as well.

Citizen Cosmos  
I like both answers. I like the grandfather answer more, to be honest, but just saying. Alexei, thank you very, very, very much for your time. And it's been a huge pleasure. Thank you for your answers and thanks everybody else for listening and tuning in.

Alexei  
Thank you so much.

Citizen Cosmos  
Bye.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

If you would like to support our mission in creating educational content and aligning the goals of different communities, please stake with us [here](https://www.citizencosmos.space/staking): 

- [EVMOS](https://wallet.keplr.app/chains/evmos?modal=validator&chain=evmos_9001-2&validator_address=evmosvaloper1mtwvpdd57gpkyejd566s24afr9zm5ryq8gwpvj) 
- [ATOM](https://wallet.keplr.app/chains/cosmos-hub?modal=validator&chain=cosmoshub-4&validator_address=cosmosvaloper1e859xaue4k2jzqw20cv6l7p3tmc378pc3k8g2u) 
- [BOOT](https://wallet.keplr.app/chains/bostrom?modal=validator&chain=bostrom&validator_address=bostromvaloper1f7nx65pmayfenpfwzwaamwas4ygmvalqj6dz5r)
- [FLIX](https://wallet.keplr.app/chains/omniflix?modal=validator&chain=omniflixhub-1&validator_address=omniflixvaloper1wnpak7sfawsfv9c8vqe7naxfa4g99lv7djfn8n)
- [BCNA](https://wallet.bitcanna.io/validators/bcnavaloper1ngt4atd3qlgcwfv7fkjdjxhz7k0vl2rejrvzye)
- [LIKE](https://dao.like.co/validators/likevaloper136r5phdpc02gmtmyampl9qkv0mdq385xxsaadu)

Join our [community](https://discord.gg/kJaG3EucCX), to build a future where communication is decentralized. May the code be with you!