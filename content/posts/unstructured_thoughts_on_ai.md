+++
title = "unstructured thoughts on ai"
date = 2026-08-06
+++

AI as we all know it these days has already been around for a few years ago at 
this point. I'm sure most of us can remember how insane ChatGPT felt like around
that time. For all its faults and idiosyncracies, it was a genuinely awe-inspiring
piece of software, one such thing that you see few of as the years pass. That
awe has faded away a little after years of hundreds of models, debates, policies,
and all that has gone on in the space. Regardless, the truth remains the same:
AI is pretty damn cool.

Regardless, I am still not one hundred percent sure what it is actually the best
for, weirdly enough.

# AI in programming

This has been one of the focal points of discussion in the space ever since GPT-3.5
came out igniting the whole thing. Many people, well known and indie, have put 
out their views over time on the whole thing. Some have been claiming from the
start that it is the goldmine and will take all jobs, some have kept an air
of caution, and some have been negative of it from the start.

After using AI tools for some programming work in my own personal projects and
just for learning stuff and research in general, I have come to realize that
AI CAN be a useful tool but it is really, really easy to misuse and completely
mess everything up. One case where it all came crashing down was my own
project [zen](https://github.com/pes18fan/zen), a little programming language;
I took quite a lot of AI help during the project for design as well as code in a 
really large PR I completed recently to add typechecking to the language, 
admittedly quite irresponsibly and impulsively. In the end it just resulted in 
the whole thing crashing down and the PR ending up merged in a poorly designed,
incomplete and probably even somewhat buggy state, I just had to merge the thing
because it went on for too long. In the end I just archived the project because
I was much too dissatisfied with what the PR left of the project.

One problem I have really faced with AI in programming is that it is quite
difficult to get it to do just what you want. Every time you attempt to use
it to implement something; there always seems to be one part that is not quite
right or one that you just don't feel good about, if you know what I mean.
Trying to get the agent to fix it just adds fuel to the fire in many cases.
The same is often true for design and working on architectural ideas.

The main problem for me though is the fact that you cannot follow what is going
on and it makes you lose track of the entire project. The AI might have saved
time by shipping a feature quickly, but now you have to study it anyway to make
sure you understand its behavior and assumptions correctly, and interact with
it in the way you are meant to. But the time needed to do that directly cancels
out the time you saved previously; you might as well have implemented the thing
yourself! Some would say "well, just don't read the code, trust the agent on
the task!" Not at all a good idea; it is like that one meme of the dog being
engulfed in fire in a house while saying "this is fine".

## So... how do you use it?

Basic answer is: don't let it program. Don't let it touch your code. The best
use for it is as a tool to augment your research. Like a better search engine.

One thing LLMs are really good at by their nature is aggregating the meaning
of language that is has all the meaning scattered around. Such scattered meaning
is evident when you are trying to teach yourself something or information on how 
to do something specific. It is a nightmare to parse all Google results yourself!
So you better use the tools for the job here: get your LLM to gather all the info
for you in a pretty little box. I think this is the best way to use AI in general,
not just in the programming domain.

One thing to really make sure of though, is that the LLMs are not lying to you.
ChatGPT is really bad at this specifically in my experience; while it is actually
really good for this "augmented search engine" / "information declutterer"
role, it is really poor at knowing when it doesn't know about something. It
prefers to just spit out ridiculous things instead of verifying things with
a simple search. When you know about the problem domain it is often easy to find
out if an explanation does not look right, but if not then this is a rather big
problem.

Solving this would be based on the specific thing you are using, for ChatGPT it
is just expliticlty indicating that you want it to look something up. It's a bit
annoying but it works.

# In general

I think that it is better for all of us if AI moves to local devices. Given
how much personal information we give out to these models every day, which are
almost always running on some server in the middle of nowhere with god knows
what's going on; it is imperative that this is made a priority. 

Therefore it makes me rather dissatisfied to see all the AI teams just focusing 
on making the largest models out there with the most parameters. I will admit,
I am not particularly knowledgable in the field of AI; so perhaps th researchers
know more about why this is being done. Regardless though I am not convinced
that this is the right direction to go. We cannot be continuing this trend and
allowing dumb basic chats to be consuming ridiculous amounts of energy and
causing so many real-world problems.

The direction should be on how we can make this whole thing more efficient. I
like how some labs like DeepSeek make this more of a focus. The other labs should
watch and learn. The ideal should be to have highly capable AI that can run
perfectly fine even on just our mobile phones without any of the unnecessary
network requests. Ideally cloud AI should not be a thing. I hope this is a future
that can eventually come to fruition.
