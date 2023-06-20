+++
title = "Episode #98 Chad Barraford. Transcript"
date = 2023-06-16

[taxonomies]
tags = ["podcast", "transcript"]
+++

Episode link:  
[https://www.citizencosmos.space/chadbarraford](https://www.citizencosmos.space/chadbarraford)

<iframe width="560" height="315" src="https://www.youtube.com/embed/TvwbpcFkOyM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<iframe src="https://player.fireside.fm/v2/7d8ZfYhp+XItrW_VM?theme=dark" width="740" height="200" frameborder="0" scrolling="no"></iframe>

Episode name:
The Web3 Puzzle: Decoding Scammers, Web3 lending, and Scalability with Chad Barraford

In this episode,  Chad Barraford The Technical Lead from THORchain is interviewed. Chad gives us his story behind the birth and ethos of THORchain, as well as giving details on their unique lending product. Chad explains how he managed to get a super user account at Twitter. There is also a discussion around scalability of chains, as well as what it would take to get THORchain to consider being part of IBC.

--------------------------------------------------------------------------------------------------------

Citizen cosmos:  
Good Space time yall and welcome to a new episode of a Citizen Cosmos podcast. A source for educational insights into the world of Web3. In today's episode, we are speaking with Chad Barraford, the CTO of ThorChain. We delve into a wide range of Thought provoking topics, including the early applications of AI and their potential impact. Explore the concept of a ten hour work  week and discuss the shifting landscape of web3 lending, including the dangers of Defi designs.
We delve into the importance of separating money from the state and address the challenges surrounding scalability. During our discussion. We also touch upon the role of crypto in advancing human rights and the significance of ethical development practices and the need for the crypto community to continuously explore new possibilities.


chad_barraford:  
You want the next evolutionary step in your product, ask your customers if you want the next revolutionary step, ask yourself. In nature 97% of all life is extinct, right? Only 3% actually exist in the world today. That's because of, you know, trial and error trying new things. Whoever is a validator or a relayer has to do it in an altruistic fashion because there's no way for that person to make an income.
Now, that's a scalability issue, because obviously, if you're doing one swap every 30 minutes, it's like, you know, what are you even doing? I was like, Oh, what's this about? I looked into I'm like, Well, that sounds like one of the worst things ever, One of the worst designs I've ever heard of,

<!-- more -->

citizen_cosmos:  
Hi everybody, welcome to a new episode of the Citizen Cosmos Podcast. And I have with me today Chad from Thorchain, the technical lead of Thorchain actually. Chad, hi, welcome to the show.


chad_barraford:  
Hi, how are you? Thanks for having me on.

citizen_cosmos:  
Yes, I'm glad having you on. I'm very good. How are you?

chad_barraford:  
Good, good, good.

citizen_cosmos:  
I hope it's a good time. Not too late, not too early, not too cold, not too hot, not too...

chad_barraford:  
We're right in the middle of the row there. We're doing well.

citizen_cosmos:  
Yeah, Chad, let me go with the traditional thing. I'm going to ask you to introduce yourself. And when I say that, it's not just to tell me and all the listeners, what's your name, but feel free to add anything you want to that. What you do, what keeps you busy at daytime and nighttime. Well, nighttime may be safe, but all yours, all yours.

chad_barraford:  
Well, yeah, so my name is Chad Berreford. I'm technically on the Thorchain Project. I don't know what else is about me. I'm a world traveler, like the climb. I used to run, although not so much these days, don't have time for it, but, you know, do whatever I can to get along with life.


citizen_cosmos:  
Let me help you out. Let me help you out. What's going on technically? Not just technically, but in general, what is currently keeping you busy at work at thorchain? What are you working on these days?

chad_barraford:  
These days, it's primarily, a lot of my time is focused around a lending design and protocol that we're trying to put out there. So that's very exciting because this lending design is just very different, structurally very different than everything else we've seen in the space. And this one actually uniquely has the ability to do 0% interest, never liquidates, there's no liquidations whatsoever, and there's no expiration of your loan as well. You can keep it open for as long as you want. And so like that's a very unique... attributes to a leanding design. And it's just fundamentally the way it's designed and structured is very, very different than everything else we see in this space. So it allows us to do things that most protocols can't.

citizen_cosmos:  
When you say, I'm sorry, I'm gonna go, it was supposed to be a bit more chit chat, but you know, let's dive into it. When you

chad_barraford:  
Yeah.

citizen_cosmos:  
Two things come to mind. First, the word lending as in the lending page. And I remember way couple of years ago, Thorochain had the craziest lending page. I might ask you about that, but feel free to, it's like a relevant thing. Another thing, when you say lending as in to lend with zero and blah, blah, blah.

chad_barraford:  
Mm-hmm.

citizen_cosmos:  
straight away, like kind of, you know, being a cosmonaut and all that, you know, alarm bells, ah, ta-da-da, what do you mean 0%? What are we going to do? We're going to die

citizen_cosmos:  
Can you maybe explain a little bit?

chad_barraford:  
Yeah, I get what you're saying. It's good to have healthy skepticism. So I always encourage people to actually read about the concept of the design. I know it doesn't make sense because, in the traditional DeFi sense, if you have no liquidations, for example, what you hear is, oh, there's no liquidations, and then it becomes insolvent, and the whole thing collapses, blah, blah, blah. That's the thinking. I get that. But it's just design and structure very, very differently. So it's like when When Elon talked about creating a new car that had an electric motor instead of a gasoline one, a lot of people are like, oh, what do you mean? There's no pistons. Like, how would the car ever be able to go? Like, how can you, you know what I mean? Like this, it's just like, if you're applying the old logic of what you think about like automobiles, like, you know, and then you're talking about something completely different, although they structurally do the same thing. They're both cars, they get you from point A to point B, but the way they work fundamentally is different. And so you try to apply the old thinking to the new design and just becomes, you know, just breaks your... breaks your brain in a sense. So this design is structured very, very differently. So it's able to do things that nobody else can. So we talk about no liquidations, no expiration, and no interest rates. That is literally what it means.

citizen_cosmos:  
a joke comes to mind, I'm sorry, I'm gonna go with it, I'm sorry. It's a terrible joke, I really apologize to everybody for saying that, but the idea was something like a university, engineering university invites all of its professors for a free flight, let's say, I don't know, New York to California, whatever, you know, just before the board, everybody up, all the, all the professors, all the engineering professors and all the flight school professor and everybody, just before the flight takes off, there's an announcement. Oh, by the way, we forgot to tell you this plane was designed by your students. So suddenly you see like everybody running out the plane, you know, and just

chad_barraford:  
Hahaha
 
citizen_cosmos:  
one guy standing there, just one guy, just one professor, he stays. And, you know, they come up to him and say, so why didn't you run? He says, well, if my students are going to design this, this ain't taking off. So I'm safe about it. You know. So... Yeah, of course it's a joke, but...

chad_barraford:  
Yeah, yeah, yeah. Well, I mean, as a project, we've done some pretty incredible things in this space. We actually did deliver cross-chain swaps in a completely decentralized way. We delivered on single asset yields, for example. We delivered on proving the slip-based fee model, which we created, worked very effectively. So we have the track record to say that you shouldn't just like just cut this out the door.

citizen_cosmos:  
Absolutely.

chad_barraford:  
Do the research, read about it. I've created like an hour long video that we can link to in this show notes or whatever


chad_barraford:  
later on that digs into some depths, not to the nitty gritty, but just the high level explaining how it all functions and work, which is a very complicated concept unto itself. So do your research. If you think it's too good to be true, excellent. Come on by, read about it, explain to me why it doesn't work. I'll be happy to listen to you. I've already heard a hundred people try this thing and almost no. Nobody's been successful to actually understand how it wouldn't work.

citizen_cosmos:  
Perfect. No, no, it's good. It's good because like our goal is always to try to get the guests to be with more more passionate About what they do. So I like I like that you're coming up with the answers. Those answers.

chad_barraford:  
Hahaha

citizen_cosmos:  
I love it and definitely Let's let's link that up. But but what generally Chad because I know I know you you I know I've heard I don't we haven't met personally But I've heard interviews with you before and actually you have done an interview two years ago for Jack Zampolin on our YouTube channel And I've read other things from you and I know how passionate about you, about those designs and about your work. And let me take the question a bit more general maybe. At what point in your opinion is a DeFi design or a DeFi design, whatever way you pronounce that, becomes too dangerous? Like at what point me, a user, you know, I forget about Thorough Chain, for example. Let's

chad_barraford:  
Mm-hmm.

citizen_cosmos:  
go general here. What stage am I saying to myself, wait a second, stop. This is not, might work, might not, but at which point is it too dangerous?

chad_barraford:  
Yeah, that's a good question to ask. I think it's the imperative of us as a community, as a crypto community, to experiment and explore. You might think that some designer idea is too dangerous, right? And if you hold that position, you hold that position, there's nothing wrong with that, right? That just means that you don't invest in that particular token. But we should always encourage people to say, like, I don't really agree with what you're doing. I don't think it'll work. But I think it's worth trying. I think it's worth to exploring it. And if it doesn't work, we'll find out why and how it doesn't work. And if that happens, we learn a lesson as a community, right? Like Terra was doing their UST design and there are a lot of people saying it would work and a lot of people saying it wouldn't work. And, but the reality is we don't know which one would, which one's correct and which one's not correct until you actually do the thing and try it out in the real world, right? And either it'll float or sink, but in either case, we will learn a breath of information and knowledge that the rest of the community can say. You know what? That algo stable design didn't work because X, Y, and Z. And that other algo stable design didn't work because of A, B, and C. And every time somebody tries something and fails, we always learn something from it. So we can, we can grow and evolve. This is what's great about the DeFi is that we don't have to ask permission to experiment and try new things. We will grow as an industry, like exponentially, we will evolve so efficiently and so quickly, much faster than the TradFi world could ever even dream of accomplishing. We can do that because of the freedom of experimentation. So I always say there is no limit to what is too dangerous of a design. As long as you're a very clear and honest and transparent to the community about what is happening. If you're hiding information, if you're like this little secret bit of codes being skewed over here that nobody knows about, or like this kind of thing, or it's like owned and operated by a single entity, they can just rug pull the whole fucking thing over. Like that's a completely different thing. But like even with Terra, like Do Kwan was clear. The design was clear, the code was open source, everybody was available to know all the bits of information and if you invested into it and it didn't work out, that's just what investment is. Sometimes you get invested in projects and they don't work out and that's okay too. I mean, it's not okay if you lose a bunch of money, obviously like I feel a sorrow for those people who did. But like, you know, other than Do Kwan's kind of attitude on Twitter, which was a little bit kind of harsh, I think what he did was experimenting an idea and a concept and it didn't work and that's okay. 

citizen_cosmos:  
I absolutely agree with you. I agree, I agree.


chad_barraford:  
Like take for example, take for example that like in nature, 97% of all life is extinct. Right? Only 3% actually exists in the world today. That's because of, you know, trial and error, trying new things. Some things work. Deer with bright pink spots does not really work so well. They're all going to die out. Right? But that's okay if things are failing. What we care about is what things are. What we're learning for and how we're growing as a community.

citizen_cosmos:  
I absolutely agree with you. I think that, well, personally, I have lost like a bit of money. The project has suffered a lot with UST, but still, and I've been around crypto for a while since pretty much the very beginning. My saying always goes the difference between a scummer and not a scummer. And this is what
 
chad_barraford:  
Yes.

citizen_cosmos:  
blockchain has allowed us to do is saying I'm a scummer. Like if I'm in blockchain, which is completely open source and everything is open and not just the code, but if everything you're doing is exactly what it is, and I'm saying, Hey, I'm planning to fuck some people over. This is what I'm planning to do. If you're following me because you're greedy and you want to make some money, don't be calling me a scummer later. Yes, that says I'm a scummer straight away. Of course, it's not the correct thing to do. I wouldn't do that, but

chad_barraford:  
Right, of course.


citizen_cosmos:  
I think we should all be responsible for our own actions. So I totally agree with what you say there. Um,

chad_barraford:  
I mean, FTX would be the opposite of that, right?

citizen_cosmos:  
gone.

citizen_cosmos:  
Yes. Yes.

chad_barraford:  
That's a scammer, that's a rugging bunch of people, that's completely horrible. That's very different from what I consider Do Kwan, which was trying an idea and it didn't work out, unfortunately.


citizen_cosmos:  
Do Kwon is an ass. Do Kwon is an ass. I must say that because I've been in contact with him for some years and you know, some things I've seen him change say and personally to me at least. And he's a bit of an ass, but I don't think he's a scammer. Definitely not.

chad_barraford:  
Yeah, yeah,

citizen_cosmos:  
He's

chad_barraford:  
yeah.

citizen_cosmos:  
a bit of a...

chad_barraford:  
I can see that.

citizen_cosmos:  
In fact, it's funny, me and a friend of mine in crypto, we did like a scammer ladder and we had like five or six layers of how to understand the... But

chad_barraford:  
Hahaha!

citizen_cosmos:  
anyways, anyways, anyways, wait before we get to go into that, I want to go back to you.

chad_barraford:  
Yeah, yeah, yeah. Ha

citizen_cosmos:  
I want to go back to you. So talking about dangers though, I know that this might be a bit of a strange question to you now, but I know that back in 2011,

chad_barraford:  
Mm-hmm.

citizen_cosmos:  
you were already working with smart homes. And I think it was called Jarvis, right? This is what I managed to find on the internet. This is going to be a very strange question. And of course, let's talk a little bit about it. I would love to hear how you got from that to doing ThorChain. You know what, let's start with that. And then I will get

chad_barraford:  
Okay.

citizen_cosmos:  
to the question. So first of all,

chad_barraford:  
Okay.

citizen_cosmos:  
how did you get from 2011 from Jarvis at Smart Host to Th  orChain? And then I will go with a danger question. So, how did you get from 2011 from Jarvis at Smart Host to TorChain? And then I will go with a danger question.

chad_barraford:  
So Jarvis was kind of like an AI that I built a long time ago, back in 2010, 2011, where it was. And that was like really my first real software project. Like I was actually wanting to learn how to code. And at that time, the language that I had learned was Apple script, which was kind of a funny little language, right? And so I had to learn how to like, you know, code in other languages. It's like my first time getting into it. And so I had seen the movie Iron Man in 2008, right? With Robert Downey Jr., right? And so there's a Jarvis character, if you may remember. And I thought that was really fascinating. And I thought it was really cool about having a, you know, what I call a PDA back then, a personal digital assistant. That's what I referred. This is like pre Siri, this is like pre, you know, like all this kind of stuff, right? So I had coined this phrase of a personal digital assistant. And so, you know, I could talk to Jarvis, to my voice. through text tweets, I had remote controls, I had all sorts of different things for them. And so it just was an exploration of like, if your house had a Twitter account, what would it tweet, what would it say, right? Like, and it was just kinda like, as I came in contact with things like, oh, I wanna track a package being mailed to me, oh, I'm getting a migraine, I want drivers to help me with my migraines, and oh, I wanna know when Netflix sends me a new, this is back when DVDs were like a physical media, back a few years ago. And so I would let me know when, you know, when small things happened on, on, you know, my internet accounts, whether it be Netflix or my bank accounts or like this kind of thing, like, hey, Chad, there was a deposit into your bank account of $2,100 or something like this. And it was like a fun little exploration of just like computational science, right? I kind of got fascinated by the idea of computational science in the sense of like solving really difficult problems. And so that was my first one. I got my 15 minutes of fame, quote unquote, I was in Gadget and Gizmodo and I was, I think Cracked wrote an article about me. I was invited to speak at various universities and colleges in the Northeast just to kind of share the thing that I spent a year building. And then I moved on to other projects. I started to get into like, what are other some kind of fascinating topics to do? So I got hit a bunch of times for some like, you know, Twitter spam, you know. asked me to click a link to some scammy thing, whatever the hell it is. And so I built what I call Twitter spam assassin, which was just like processing the main timeline of Twitter and analyzing individual tweets for the likelihood of them being spammed. And so I started reporting on mass quantity to Twitter, like all these spam accounts, and they reached out to me. The security team reached out to me. They're like, hey. Whatcha doin'? I was like, I don't know, I was annoyed by all the spam on your network. I wanted to just, you know, report it all.

citizen_cosmos:  
This is hilarious.

chad_barraford:  
So I wrote like, this is where I learned Python program, by the way, for this particular project. I built a multitude of servers all working in 10. This is like high performance Python computers. This is my exploration with my academic sandboxing of high performance Python computing with a multi- on a distributed system concept, right? Because there's a lot of time, there's a lot of stuff. So they reached out, we had a conversation. They wanted to know what my heuristics were, like what are my algos, you know, and I just gave it to them, I don't really care. I don't know if they actually used them or not, or whatever, maybe they did, maybe they didn't, I don't really know, but I just gave them how I structured my design.

citizen_cosmos:  
This is fascinating.

chad_barraford:  
And then they gave me like unique access to their API, like my Twitter account has like super access to like... you know, like, like high, I can do high throughput. And so once they gave me high throughput of like API access to it, I could start like really, like, cause I had a problem with, I would hit the eight, I've got rate limited by the API. So I had to be very smart about, you know, which ones, which tweets do I want to get more detailed history from that particular user, which ones I do not, because I don't want to waste an API request. But once they gave it to me, like, like advanced access to their API, I just like, all right, let's turn this shit up to a fucking 11. This would crank the fucking dial. In the end, I think I found almost like a million spammers on their network or something like this. It was actually a really fun project. Before I shut it down.

citizen_cosmos:  
It's crazy. It's crazy. But how did you progress then from finding a million spammers on Twitter, getting like a super access account on Twitter to Thorchain? Wait, we lost there. Wait.

chad_barraford:  
So after that point, I started to actually work in the, I was actually working in the tech industry before that point. I mean, I worked in the IT industry, which is a little bit different. And so I got a job at a place called Brightcove, which was kind of like a YouTube for business. Let's call it that for simplicity's sake. And I got hired there as a job as an infrastructure guy, actually, not as a coder, but as a, doing like servers and infrastructures. what we call system engineering, right? I did that for a few years before I got bored of it. And then I went on to another company, eventually going to a company called RStudio, which was actually my first time doing dev work professionally, being paid to actually write code. Before that, it was mostly infrastructure, which is again, infrastructure as code is still technically code, but like it's a little bit different. And so I worked for a company called RStudio for about six years and I helped build their flagship products. And so RStudio Connect and what was called Shiny Apps I.O. at the time, although I think it's called RStudio Cloud today, I wrote all that code with one or two other devs and that was kind of my first time building things professionally within a corporate environment mentality. And, you know, eventually I quit just because I got into crypto. In 2017, I discovered. cryptocurrency and Bitcoin, all this stuff. And I quit the job. And I worked for a higher dev for like basically 10 hours a week because I was living in Southeast Asia at the time, for the most part. It's cheap to live out there. So I didn't really do that many hours to work. I could just work a few hours and live life and explore other countries and such. And then eventually, actually, this is... This is a slightly embarrassing, but it'd be an interesting story. So

citizen_cosmos:  
drum rolls.

chad_barraford:  
drum rolls. So I was working 10 hours a week, and I don't know if you know this, but American tax law, if you live outside of the country for 330 days of the year, you don't have to pay income tax, right? So I was living on 10 hours a week of income, not really expecting to pay much income tax because as I said, the country for 330 days. And then I realized later on that that only applies to W-2 income, does not apply to 1099 income. Oh shit, I'm fucked, right? So I was actually living in Germany at the time, I was in a startup competition for a friend of mine who asked me to come out and just build their prototype for him. And I owed the government some taxes, which I wasn't expecting to owe them. I didn't have much money at the time. I was basically pretty close to broke. And the government went in my bank account, took everything I had. This is a true story. Literally put my bank account into a negative balance, my checking account into a negative balance. Because I just woke up one day and all of a sudden, literally every dollar I had was just like gone out of my bank account, right? So I'm like panicking. So I like go on my PayPal and my Venmo, like random places like this on the internet to try to like, to get my bank account back into a positive. So I think I had like 600 bucks at that point, right? $600 to my name, this is true. $600 is my name. I'm in Germany. I'm working at a job that doesn't actually pay me because I'm just doing it as a favor for a friend to build their prototype. So I didn't even have an income at that time. They just give me a place to stay and this is the life that's Germany. So like, all right, shit, I got $600 to my name. I'm kind of fucked.

citizen_cosmos:  
Fuck man.

chad_barraford:  
So thank you government for taking out my money.

citizen_cosmos:  
hahahaha

chad_barraford:  
I appreciate that. That's a very... That was great. I started looking for a job, but of course I was in the crypto space and I wanted to stay in the crypto space. And so I started looking for stuff on some Angel List website, whatever the hell it was. And I found this CTO job for a company called Sky Network, skyy.network. And they were looking for a CTO to help them build what they were doing, which is basically like... air traffic control on a blockchain. That's the simplest way to probably explain it. So like the drones could fly in airspace and have agreement upon who's gonna occupy what part of the airspace at any given moment so that they could communicate with each other to figure out like how drones are gonna fly in the sky without, you know, ramming into each other, you know, in a hypothetical future. And so the CEO of that company and the advisor of that company were gonna be in Berlin at the time, and I had just moved to Berlin. like a few weeks earlier. And they were like, oh, we're coming to Berlin, we're doing this Cosmos hackathon. This is in July, 2019. Why don't you come out? And this will be like your job interview. Like, this is like, you know, we'll come out, we'll hack for a couple of days, you know, we'll see how it goes. Like, all right, this is very convenient. So yeah, I'm already in Germany, y'all see you next week. Let's do it. And at that time, I actually didn't know anything about Cosmos, I hadn't learned about Cosmos yet, right? And so I read the Cosmos documentation like the day before the hackathon, just to kind of- brush up and try to understand the SDK and how it all works and functions. And so the advisor and I were just, we really spent the most time together. Him and I were hacking away at some things. And he kind of asked me like, Oh, what do you want to build? And I was like, I don't know, what should we build? And he says, Oh, I had this idea last year that didn't work out. This was thing like this cross-chain swap concept that the special signature is not existing yet, all that stuff. And it's like, what do you want to work on this? I'm like, yeah, actually sounds like a really good idea. So we hacked on it for two weeks and we were one of the winners of the hackathon from that event. And that was the first, like that was the birth of Thorchain in a sense, right? That was the first lines of code we committed at that point. The BEP2 token was created and minted, I think a week later, two weeks later, something like that. We got a few investors. We had about 1.5 million, I think initially, or 700, another 700, like a few weeks later, something like this, uh, of investment. And that was all we needed. Like we don't, we didn't ever hired a big team. Like we don't have a hundred devs, like some other projects in the space. The most we've ever had within the original team was maybe nine, right. At the, at the height, right. Which is still quite small. Like

citizen_cosmos:  
It's not a lot, no it's not a

chad_barraford:  
not,

citizen_cosmos:  
lot.

chad_barraford:  
it's not a lot. Like the actual chain itself, the Thor chain. chain was built by myself and one other dev. And that was two years of work to get it there, to even get it to what we call single chain chaos line, which was just an alpha release. Let's just connect with Binance chain only and prove the technology works, prove that the economics of the slip-based fee model, prove that all this stuff actually works in reality and then we'll scale up to main net, which took us another year and a half or two years to get there. Right. So it's been a long road to get where we are now, but you know, it's been a lot of energy and effort.

citizen_cosmos:  
We were in Leipzig and Berlin at the same time. I was around there a thousand. And in fact, a lot of my guests that come on the show ended up in Germany in 2018, 19, 20, obviously due to the same reasons.

chad_barraford:  
Yep.

citizen_cosmos:  
So ironically that a lot of us have only meeting years and years later, but it's, you know, the, the wheels of, of, of life, I guess. But wait, wait,

citizen_cosmos:  
I have a question now back to the question because

citizen_cosmos:  
now. Now that you gave me more of your background, I'm more and more sure that this question is very good for you.

chad_barraford:  
Okay.

citizen_cosmos:  
So considering you have DevOps and infrastructure experience, not just experience, not any experience, I mean, but, you know, particular experience building even your own things like Jarvis. Considering myself being a validator and considering a lot of validators these days, and some of them listen to this show, I know that. try to move away from cloud

chad_barraford:  
Mm-hmm.

citizen_cosmos:  
and slowly start more and more experimenting with not just in the name of decentralization, but also in the name of security and decentralization

chad_barraford:  
Mm-hmm.

citizen_cosmos:  
with bare metal. And by bare metal, I don't mean bare metal in the cloud. I mean, you know, home bare metal. Considering though our lives now, a parallel second thought, you know, more and more in our lives, smart devices. and things like, you know, lumps or Jarvis or, you know, its future, well, today's ancestors,

chad_barraford:  
Yep

citizen_cosmos:  
sorry, not ancestors, but the children, you know, more and more in our life. So long, long, long story short, you already probably guessed the question. The question is, how are people who are either trading cryptocurrencies, you know, holding validators in the houses, of course, they should be aware of those things. But how do you make sure that smart network devices don't become a danger to the house network and cannot be accessed especially if you're doing something sensitive like validating like trading and so on and so forth. What is your advice in that direction if any?

chad_barraford:  
Oh, that really is a networking question, I suppose.

citizen_cosmos:  
Yeah, it's a bit of a networking question.

chad_barraford:  
Yeah, because within your house, you have lots of devices. Some are IOTs, the internet of things, like your refrigerator might be an IOT device, for example, or your fan or whatever, right? Baby monitors. And then you have your devices, right? Which is usually your laptops and your iPhones and your iPads and things of that kind of context. And then you have other kind of... systems in there like might be an Xbox, PlayStation, these kinds of things. And then you might have services you're running that are what you want to secure. It might be a validator, it might be a full node, it might be, maybe you're hosting, if you're hosting a validator, it means you have a public IP address that's kind of communicating with other validators. And so you have an entry point into your network. So if there's an exploit within that validator, whether it might be like an overflow or something of this nature, whatever you can do, and break through one of those kind of ports in a matter you know, an RCE, that's obviously a problem. So the trick to all those things is all those things can become malicious, right? An IoT device can be exploited because their security and those things tend to be very, very small. And we've seen Russia do that many times. You can download malware or some sort of thing on your laptop or your phone that could cause something. And also this service you're running that needs external access. can also be a point entry into your network. So the cleanest way to do that is just creating what we call VLANs or virtual networks. And so that you isolate the traffic between things. So you don't actually allow your IoT devices to get direct access to your laptop, but your laptop can access the IoT devices, or that kind of stuff. So anything, if I was running a bare metal node in my house, if something like this, then I would... I would probably just make sure that the network is actually separated entirely. And I may even go the extra step of actually creating a second ISP for that purpose, just so that the bandwidth that I'm utilizing my house when I'm, you know, bit torrenting something or using something that uses a lot of network, it doesn't infringe on the network of that validator and it caused validator slow down and maybe collect slashes or something like this. Like it's a difficult thing to do and it does require a technical knowledge understanding to do that in a secure way. And there are. If you don't do it in a secure way, you're running your own risk.

citizen_cosmos:  
Yeah, it's crazy how much time and effort those things require, especially when, you know, our lives become more and more involved with smart devices. Sometimes you don't understand you have a smart device until you sometimes go on your network and you're like, whoa, where is all that's coming from? Of course,

chad_barraford:  
Yeah.

citizen_cosmos:  
being a validator, you're more aware of those things, you know, being like technically up to date, so to speak, but You know what? What? I think what you're saying is very important for anybody out there who isn't just a random validator. But I think if you're doing crypto, I think having separate networks, like you say, you know, for for doing your business with crypto is, in my opinion, essential, you know, and just it's I don't know. It's getting more and more and more and more and more and more becoming part of our life, I guess. What

chad_barraford:  
Absolutely.

citizen_cosmos:  
about? What about scalability and tendermint and how you guys solve this? Maybe in thorchain? Because I mean, I've been, I mean, Tendermint has allowed for many, many, many, many, many, many things that were not there before it.

chad_barraford:  
Mm-hmm.

citizen_cosmos:  
Well, IBC being one of them, you know, which is another thing topic I will want to get with you before we finish. But I don't know because I'm going to be honest, I am with Thorachain. I don't have as much knowledge of Thorachain. I have experience using Thorachain. But. It's not as much as I would like to make a comment on. So my question is, I know that you guys have had some twitches to this colorability, or am I wrong here?

chad_barraford:  
Well, so in single chain KS, we had a limit of validators. I think that limit is at 35 or 36. And the reason why that is is because when it's securing external assets, extra genius capital, that's Bitcoin, Ethereum, like layer one real assets on some other blockchain, it needs a wallet to store in that connects to their BC1 address or an OX address, something like this. And the way that ThorChain does it, these are something called threshold signatures, which is a relatively new cryptographic It's kind of like a multi-sig, but a little bit different. And with a threshold signature, the more members in that group of people that are signing, you have a quadratic relationship to the time it takes to sign and the number of people. So if you have 36 people or so in a threshold signature, it'll probably take about 15 seconds or so, maybe 20 seconds or so to sign. But if you were to scale up to 100 people... which you totally can, it would take minutes, maybe 15, 30 minutes, right, to sign a transaction, a single transaction. Now that's a scalability issue, because obviously if you're doing one swap every 30 minutes, it's like, you know, what are you even doing, right? It's like, it's pretty much useless. So in the initial version of ThorChain, all the validators also had to be a part of the same, what we call an Asgard, the same threshold signature in order to be, to do this. We had a limit on the initial thing to be 35 to 36 validators. That's not true today. Today we have just multiple threshold signatures. Each one has 20 members per what we call an Asgard vault. I think there's about five or six in total, something like this. And so we have close to a hundred validators on the threshold. So we can scale up to whatever tenderment will allow us to, whatever the max that tenderment allows, which that's debated in the community. Some people say 150, some people say 250. It's probably around that area somewhere. I think Cosmos Hub has the most. Whatever that is, I think it's like 200 something, I think.

citizen_cosmos:  
I think it's 175, 175

chad_barraford:  
Yeah, almost just shy of 200. I think they have the most validators on any given set.

citizen_cosmos:  
Omniflex, Omniflex, I think went on their testing, they went to something crazy. Like, I don't know how they did it and how it worked. But it was something like 500 600. I don't ask me, don't ask me questions.

chad_barraford:  
Yeah, yeah, yeah.

citizen_cosmos:  
I will not be able to say anything. But I know they were doing experiments. And I actually, I would like to talk to them one day about it to see what are those experiments and what are they doing there


chad_barraford:  
I was talking to a guy named Michael O'Rourke, who's the guy behind Pocket Network, and he was telling me that he forked the tendermint, Cosmos SDK, and I don't know what he changed. He didn't explain it to me. That he could get like 30,000 validators. I don't know what he actually...

citizen_cosmos:  
30,000.

chad_barraford:  
This is what he told... That's what he said to me. So like maybe I misunderstood him. Hopefully I did. But like,

citizen_cosmos:  
How did it test it?

chad_barraford:  
excellent question. I don't know the answer to it. But

citizen_cosmos:  
Uh.

chad_barraford:  
he did tell me he was going to rip it out though and drop Cosmos and use another framework that's called Hot Stuff that Facebook created,

citizen_cosmos:  
Okay.

chad_barraford:  
which I've never used that one personally or know that much about it. But he said he was going to rebuild Pocket Network off of Cosmos and move to this other thing called Hot Stuff.

citizen_cosmos:  
I've heard of pocket network. I've never heard. I

chad_barraford:  
Yeah.

citizen_cosmos:  
mean I heard hot stuff the song. I know this song hot stuff, baby the same hahahaha

chad_barraford:  
I think it's a bit different.

citizen_cosmos:  
damn

chad_barraford:  
It's an open source blockchain framework that Facebook came out with a

citizen_cosmos:  
Yes, yes, yes,

chad_barraford:  
while back.

citizen_cosmos:  
yes, yes, yes, yes. I don't know much about it. I've heard the name.

chad_barraford:  
Yeah. Yeah,

citizen_cosmos:  
I've

chad_barraford:  
yeah, yeah.

citizen_cosmos:  
never read the

chad_barraford:  
I

citizen_cosmos:  
documentation.

chad_barraford:  
never looked at it. Yeah, me too.

citizen_cosmos:  
Okay, cool. Cool to know the cool something to explore. Maybe I can go and try to talk to him to invite him on to see if he wants to talk about it. And you know what other topic I've seen that is you kind of touch on a lot. No, no, before we go to that. Wait, wait, wait. Sorry, sorry, sorry, sorry. Before we go to that, I will I will be not myself if I don't ask that. Thorchen and IBC, can you briefly give me like a 101 on the whole deal of why and I'm sorry if I'm getting anything wrong here. But as far as I'm aware, thorough chain doesn't want to be IBC enabled, right? I have heard this somewhere before. Could

chad_barraford:  
Mm-hmm.

citizen_cosmos:  
you give me and all the listeners like the 101 as to why that is?

chad_barraford:  
Yes. So, IBC was something that myself and other people were actually very interested in integrating for a long period of time. And we worked on it for months, myself as well as the Nine Realms team, which is another kind of dev team that's associated with Thorchain. And we found that it just didn't really do what we needed it to do, right? In the sense that it didn't uphold the standards of what we require for decentralization, right? Because in... IBC requires a relay, which is oftentimes one of Jack's servers and his strange stuff, which there's nothing wrong with that. For us, we wanted to make sure that we did not rely on any single entity to do anything. It also came with some security issues around, like, whoever is a validator or a relayer has to do it in an altruistic fashion because there was no way for that person to make an income and as well, they have to spend gas, I think, on both chains to make this whole thing work. There's always the risk of them getting spammed with just, you know, burning gas. And so there's just, there's some elements to it that didn't make sense for us. Uh, and I think they'll fix those things. I think they're already down the road of like fixing those issues, those bugs. And I'm sure, I'm sure IBC is going to get a lot stronger and then in the future, uh, as well as the other thing was that we already have a bridging model that we designed called Bifrost, right? And Bifrost is very different in terms of how it's structured, how it works than how IBC works. And. There are a lot of advantages to IBC over Bifrost, and there's advantages of Bifrost over IBC, but for our purposes in case what we're trying to accomplish, we want to be able to connect with any chain in the world. Didn't care if it's an IBC, a Cosmos chain, or a Polkadot chain, or a Crypto Note, or a UTXO, or EVM, or like whatever. It could be even something, you know, crazier, like, you know, IOTA is not even really a blockchain in some sense, you know. It's structured very differently. So... We wanted to be able to be much more flexible to connect the world because if we just connected a bunch of Cosmos chains together, that wouldn't solve the problem that we're trying to solve, which was true cross-chain connectivity. That makes sense within the Cosmos space, but for us, we wanted to not forget about Bitcoin first. Bitcoin is obviously the elephant in the room. Obviously, that's the most valuable asset. That's the one people want to be trading the most. That's the one we wanted to help. IBC for the Rune asset specifically and not using it for the pools and the swaps and that kind of thing But he's like just for the Rune asset, but then that became a couple problems with that in the sense that It it goes against some of the security concepts of the postures of Thorchain. So Thor chain does delays its outbound transactions up to one hour to say to say as a safeguard to protect itself from some sort of Exploits so if somebody were to exploit Thor chain right now and try to steal, you know $50 million, the outbound transaction to receive that $50 million would be delayed for an hour. That would give the community time to be like, whoa, hey, there's alerts that go on in our Discord that notify the community when something kind of weird like that happens. So that's there for security purposes so that funds are never lost. And IBC becomes a problem in that regard because then you can leave the network very, very efficiently and quickly. We don't want that. We want to have a more secure posture. And then if that's not enough, then we can't do that. to support multiple bridges on a network, it just creates more surface area of exposure, right? There's a dev you that understand how Bifrost works, there's a dev you have to understand IBC works, you have the surface area of security issues with both Bifrost and IBC. I mean, IB C had a security issue, you know, not too long ago. Again, I'm not like judging or anything like that. Everything's gonna have security issues because everything's just code that's being baked. But like, we don't wanna overexpose ourselves to more surface area or risk because we already have... such extreme surface area risk to begin with, with Bifrost, with Bitcoin, with Ethereum, with Litecoin, with everything else, our own chain, our own math and logic. There's already enough surface area of security to be concerned about. To add another bridge on top of that just seems like unnecessary.

citizen_cosmos:  
Do you think that after IBC will fix the things that you're mentioning or some of them, or it might have another look, will you guys be open to... Well, you guys, when I say you guys, of course, we're talking about a whole network governance. But in your opinion, we're talking right now, Chad, we're not talking about Thorchain  

chad_barraford:  
Yeah, so I'm open to doing that. I would not want to do it for the layer one assets. I think how the Bifrost works is the way we want it to work. I'd be open to do it for the Rune asset and sending the Rune asset external, or maybe one of our similar Synths or other assets on the network to have synthetic Bitcoin, for example, or synthetic Ethereum or Ether rather. That I'm open to doing so, but we also need to have a customized that IBC because I want to make sure we ensure the security. So I want to delay those up on transactions. So if you want to send Rune to some other chain, I want it to delay it up to an hour based upon some mathematics that determines how long it's delayed for. So there'd be some kind of custom rolling that would need to happen. And when we need to figure out how the relay would be run, like, you know, we can't just have me run a relay in my basement and that be the relay, like that just doesn't, you know, adhere to the centralization requirements. We'd have to get each individual validator to also be a relayer, so that if any one of them are around... then everything would still work and function just fine. So if they fix all these kind of like things we should, I know and I think they already are, which is great. I'd be open and open and doing it, but again, it's not my choice per se. It's up to a larger community.

citizen_cosmos:  
Devil's advocate question. You mentioned like the dangers of relays sometimes and it's kind of obvious, but you mentioned validators in the same sentence.

chad_barraford:  
Hmm?

citizen_cosmos:  
Same thing, isn't it? I mean, validator is still the same centralized dangerous entity, isn't it?

chad_barraford:  
Well, no, it's different because most of the time there are relayers just like, there's only one relayer in most scenarios, maybe two if you're lucky. And so one of those relayers goes offline for some purpose or if that one realtor says, I don't like this address for some reason, and I want to block this address because I'm going to adhere to the OFAC something or other or it might be, that's different. But a validator is different because anybody can become a validator. Anybody can leave as a validator and most can come right back in. And there's all close to a hundred of them, you know, lying around.

citizen_cosmos:  
Okay.

chad_barraford:  
So if, if one relay goes down or one really says, I don't want to transact this address and blacklist this address, then some other relay will do it. So I hope that they actually change how IBC itself works and that validators are the relayers either that, or everybody becomes their own real layer. Like I can go to a UI, do a transaction and I become my own relayer between the two chains. That would be another. valid way of going and hopefully they're going to be doing that at some point in time. But get rid of, and I don't mean this negatively against Jack, but get rid of Jack and Strange Love in that sense. Like they should not be running relays for the entire community. Like that just, if that doesn't set off red flags in your head, it probably should. And so

citizen_cosmos:  
Thanks.

chad_barraford:  
we should instead improve IBC's design to allow the validators of individual networks to do it or for everybody to be their own relay or for their own transaction that they're doing in the, whatever you will. you either interacting with, do one of those two things and you solve a lot of the issues of.

citizen_cosmos:  
Are you referring to a little bit what IOTA is doing?

chad_barraford:  
I don't know what I always do, maybe I am, maybe I'm not.

citizen_cosmos:  
Okay. No, no, no, no, no. I'm not gonna go into it because technically, well, they are, but then they have the, what's it called? What it's called? The thing that is actually helping because it's not scalable enough. Basically, when you do a transaction, you have to validate two transactions next to you. And that basically creates that each device, like this is in a very cutting corners right now, right?

chad_barraford:  
Yeah.

citizen_cosmos:  
And then basically creates a network where you have to validate transactions. in order to make a transaction. So that's kind of everybody being a relayer. And yeah, it doesn't really work for them. That's why they're still solving all this problem. And then they have like, I forgot what they call it. But it's a centralized kind of relayer that does those things.

chad_barraford:  
Yeah.

citizen_cosmos:  
Yeah, but I understand what you mean. It would be interesting to see that. I'm hoping that, to be honest, I'm hoping to see a very good proof of an implementation of some... type of proof of work on top of proof of stake. That will help to scale because I can think of them, but yeah, I haven't seen anything like that yet. Not with today's cryptography.

chad_barraford:  
It'd be fascinating to see someone come up with a design that kind of mixed multiple...

citizen_cosmos:  
No.

chad_barraford:  
I mean, it'd be complicated to sell for obvious reasons, and the security would be hard to keep tight,

citizen_cosmos:  
Yes,

chad_barraford:  
but...

citizen_cosmos:  
the cryptography is not there. Yeah, for sure. For sure.

chad_barraford:  
Yeah,

citizen_cosmos:  
Chad,

chad_barraford:  
maybe

citizen_cosmos:  
because

chad_barraford:  
one day.

citizen_cosmos:  
we are like a bit of like,

chad_barraford:  
Yeah.

citizen_cosmos:  
so fun time, I'm going to go to the last question. It's a blitz of three questions.

chad_barraford:  
Mm.

citizen_cosmos:  
So you don't have to answer them super quickly, but it is a blitz. So one first one, give me three projects that you technically interested in. Please don't say Thorchain, please don't say Cosmos or Bitcoin or Ethereum. but three projects

chad_barraford:  
Hahaha.

citizen_cosmos:  
that you're technically interested in, that you saw and like, wow, that's pretty cool.

chad_barraford:  
Um... I'm hesitant to come on, to speak about other projects just because I don't want to put my weight behind something.
 

chad_barraford:  
Oh, from a technical perspective, I'm interested in Lightning Network. I think that's one of the most important projects in crypto. I think that's really kind of fascinating. I actually started working on a new project myself outside of ThorChain that's called Archeo, which is decentralizing the node, access to node data, right? To get access to Ethereum full nodes and Bitcoin full nodes without going through being KYC or asking permission or any kind of centralized service whatsoever. That's another one I'm obviously interested in. I'm trying to think of anything else that's really fascinating. I mean, I always see things happening in this space and 99% of the time I'm just like, yep, that's not going to work. That sounds,

citizen_cosmos:  
I know what

chad_barraford:  
that

citizen_cosmos:  
you

chad_barraford:  
sounds,

citizen_cosmos:  
mean. I know

chad_barraford:  
that

citizen_cosmos:  
what

chad_barraford:  
sounds,

citizen_cosmos:  
you mean. 

chad_barraford:  
or maybe it's going to work, but it's just because it's a fork of something else and it doesn't really offer anything interesting or unique. And so it just becomes, you know,

citizen_cosmos:  
People forget

chad_barraford:  
like I'll,

citizen_cosmos:  
about

chad_barraford:  
I'll

citizen_cosmos:  
computing laws when they talk about blockchain sometimes, you know.

chad_barraford:  
I was looking at like Canto yesterday, cause it was kinda, I saw a bunch of tweets in my feed or whatever, I was like, oh, what's this about? I looked into them like, well, that sounds like one of the worst things I've ever heard. One of the worst decides I've ever heard.

citizen_cosmos:  
I haven't checked it out yet, but I have seen my Twitter feed is starting to like Cantor's got more than a hundred thousand accounts! Cantor's got a million accounts! And you're like, okay,

chad_barraford:  
Nah

citizen_cosmos:  
yeah,

chad_barraford:  
man,

citizen_cosmos:  
I see where it's going.

chad_barraford:  
nah man. I

citizen_cosmos:  
Okay.

chad_barraford:  
read up on, nah.

citizen_cosmos:  
Okay, okay, okay, okay. I feel you. I feel you, bro. Second

chad_barraford:  
Yeah.

citizen_cosmos:  
one, give me two things in your daily life that keep you motivated to keep on building, you know, the decentralized world to keep on building DeFi tools and designing new things. Something that keeps you motivated. Two things in your daily life.

chad_barraford:  
For me, it's like, so the value of crypto in general to me is not about money or getting richer or these things, although obviously those things are a thing too. I mean, for like Eric Voorhees, for example, he talks about separating money from state, which is a very noble and valuable thing to do. But for me, what makes me excited about the space is not so much that also that is very important. For me, it's about human rights.the idea granting new financial instruments or usability of services that are just public goods. They exist purely to support humanity and allow humanity in a way to interact and empower them. Right? Like doing in a way that does not know or care what your, you know, if you're old or young, black or white, male or female, polka dotted or whatever, like there's no way to actually to treat those people differently. than anybody

citizen_cosmos:  
Absolutely.

chad_barraford:  
else. And so when I talk about crypto, what I talk about often is like, we are literally granting inalienable human rights for the entire planet all at the same time. Not just these group of people who are born in these borders and those people who were born in those borders, but across the space, across the spectrum, across every man, woman, child, across this entire planet. And granting them access to yield, checking in savings accounts, loans and lending. access to, you know, Archeo's node data. I don't know, it could be anything, right? That is so critically important. So that's what gets me excited about the space. It's when I like think about things I want to build. That's what I think about. I was like, how does this, what hair on fire problem are we solving by, you know, that we're trying to solve? ThorChain did that by getting rid of centralized exchanges from being required to move across chains, right? Archeo is doing it by removing, you know, Infira and similar services from being able to spy on you. You know, even that project wants to move forward and decentralize the rest of the application after the protocol, right? Including getting rid of domain names, including getting rid of, um, websites and, and centralized points of, of UIs completely decentralized the entire stack of every DeFi application from the, the protocol, the smart contract or whatever, the cost most chain, whatever it might be. to the front end and literally everything in between of those two things and decentralized everything. Because just a few weeks ago, Congress was talking about, you know, KYC in the front ends. Fuck no. Fuck that shit. And fuck no. Let's decentralize the front ends the way that cannot be, you know, KYC. Let's do that. That

citizen_cosmos:  
Absolutely.

chad_barraford:  
seems like a really valuable goal. So to me, that's what I think about like, what are the hair on fire problems of this industry that we need to be solving that better improves human, like humans access to empower themselves. This is why I'm so excited about the lending protocol, by the way, because the lending protocol is giving you no interest rates, no conditions, and no expiration dates. Now you can actually buy a car. You can go on a vacation. You can buy a house with your crypto without dumping your crypto and selling it and removing your exposure to it. Because if you do that with Aave or Compound, you're just going to get liquidated. People get liquidated. Anybody who's taking it alone knows how stressful as fuck that is. Ethereum's price is going down, you're just dumping more eth into it like, oh my God, am I going to lose all my ether? It's stressful and you really can't have a... It's great for degens to degen it up, but it's not a really good useful thing to actually improve your actual life to go out and buy a car. A guy actually told me on Twitter basically the other day that he had 44 emails between him and a bank trying to get a $10,000 loan that he still hadn't gotten yet. And he tried to get a loan on Aave and he got one, but he felt so stressed out about it, he just like closed it and like, I can't even do this. I'm just going to be like, I won't even be able to sleep at night. Like, you know what I mean? And he's trying to buy a $10,000 car so he can get to work. And he was telling me like that this loan is the exact thing he was looking for, because you can't get a loan like this and TradFi, CFi, or even DeFi. And it allows him to actually buy a car with his Bitcoin, right, and be able to know that his Bitcoin is available to him tomorrow. so that he can buy back his Bitcoin whenever the fuck he wants to do so. That's super empowering. That changes so much about this space in such a significant way, in my opinion. That's something to be proud about. It's something to be excited about. We all should be excited about the idea of being able to do that. Not only just do that loan attributes, but also do it in a cross-chain way with every major asset, including Bitcoin. That's so important. So that's what I think about.

citizen_cosmos:  
That's lovely. I hope that, you know, some from the beginning remind me of Pale Blue Dot, Carl Sagan, you know,

chad_barraford:  
Yeah,

citizen_cosmos:  
and

chad_barraford:  
oh yeah.

citizen_cosmos:  
empowering, understanding that the problems we have are not really, you know, the problems, but we should think of the bigger things. Last one, Chad, last one, I promise. Give me one person, dead or alive, that is an inspiration to you. It could be a developer, it could be a writer, it could be an influencer, it could be a Degen, it could be a book author, it could be a movie maker, I don't know, dead or alive, Julius Caesar, I don't know, one person that inspires you.

chad_barraford:  
One person that inspires me? I don't know, man. I look to people like, one of the things I love about Steve Jobs, not just because he was obviously a great innovator and an inspiration for me and for countless other entrepreneurs, is that the way he thinks about the problem is so different. He thinks about, he used to say, if you want the next evolutionary step in your product, ask your customers. If you want the most revolutionary stuff, ask yourself. It's the idea that all the things that do exist today around us are just temporary walls that can be knocked down anytime. Oftentimes, we think about those things as just walls that exist, we can't go through them. But he was saying those walls were erected by people just like you, and they don't have to stay up. I just love this concept of go back to first principles, what are the problems you want to solve? It doesn't matter that nobody else has solved it or thinks it's not possible to solve, right? Thor  Chains solved the problem that people yelled at us that it was literally not possible to solve. And go out there and innovate. Think of new ways, creative ways to make it work. That stuff is so inspirational. And I think Steve Jobs helped me to see that.

citizen_cosmos:  
I love it. I love it. I love it. Absolutely in the spirit of the podcast, I would say for sure.

chad_barraford:  
Yeah.

citizen_cosmos:  
In spirit of crypto, you know,

chad_barraford:  
Yeah,

citizen_cosmos:  
Chad,

chad_barraford:  
absolutely.

citizen_cosmos:  
thank you very, very much for coming. I know went a little bit over time. I hope it's okay. Again, my gratitude for finally we made it. Thank

chad_barraford:  
Yeah.

citizen_cosmos:  
you. And thank you, everybody for listening. Join us next time. Thanks.

chad_barraford:  
Yeah, thanks for having me.

citizen_cosmos:  
Let me just stop that. Wait, wait, wait.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

If you would like to support our mission in creating educational content and aligning the goals of different communities, please stake with us [here](https://www.citizencosmos.space/staking): 

- [EVMOS](https://wallet.keplr.app/chains/evmos?modal=validator&chain=evmos_9001-2&validator_address=evmosvaloper1mtwvpdd57gpkyejd566s24afr9zm5ryq8gwpvj) 
- [ATOM](https://wallet.keplr.app/chains/cosmos-hub?modal=validator&chain=cosmoshub-4&validator_address=cosmosvaloper1e859xaue4k2jzqw20cv6l7p3tmc378pc3k8g2u) 
- [BOOT](https://wallet.keplr.app/chains/bostrom?modal=validator&chain=bostrom&validator_address=bostromvaloper1f7nx65pmayfenpfwzwaamwas4ygmvalqj6dz5r)
- [FLIX](https://wallet.keplr.app/chains/omniflix?modal=validator&chain=omniflixhub-1&validator_address=omniflixvaloper1wnpak7sfawsfv9c8vqe7naxfa4g99lv7djfn8n)
- [BCNA](https://wallet.bitcanna.io/validators/bcnavaloper1ngt4atd3qlgcwfv7fkjdjxhz7k0vl2rejrvzye)
- [LIKE](https://dao.like.co/validators/likevaloper136r5phdpc02gmtmyampl9qkv0mdq385xxsaadu)

Join our [community](https://discord.gg/kJaG3EucCX), to build a future where communication is decentralized. May the code be with you!