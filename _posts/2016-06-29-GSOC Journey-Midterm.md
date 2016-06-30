---
layout: post
title: GSOC Journey - Midterm
category: GSOC
---

<s>Yeah, 28th of June it is, Google will either make a decision to end my GSOC journey or pay me the biggest check of my life.</s>Google chose the latter one. I passed! 52 conversations, personal messages and tonnes of github discussions, this was brainstorming. So on this day I decided to jot down the bittersweet memories which has impacted my life greatly. 
 

## <b>Man of the hour</b>
23rd April turned out to be the biggest day of my life. Getting selected for Google Summer of Code is the biggest victory ever achieved. This marked the end of continuous grapple and beginning of fresh journey. This day I realized that GSOC is not just an internship which provides a huge lot of money. It presents the opportunity to work with someone who is far more experienced and intelligent than me. I get the chance to work with  an exceptional organization and contribute a real world software. GSOC for me was full of sacrifices which turned glory.

## <b>First hurdle</b>

I am not a long time contributer of open source world. I started contributing open source with the soul purpose of cracking GSOC. So getting selected in <b>Ruby</b> organization was a serious challenge.
Let’s start by quoting my mentor’s first message : 

<i>" Congrats on being accepted!
For a start, we should start thinking about how we would be able to quickly benchmark across multiple commits.
From my previous discussions with @sam, we want to build a docker image for each commit made to Ruby and tag it with the commit's SHA1. So a few things to think about here:
How can we automate the building of those images?
How do we build each image fast? (One solution is to build each image using the previous image as the base so we don't have to recompile every thing each time)
Are we able to store everything on Docker hub?
Once this is done, we can start thinking about how to make the magic for bisecting happen "</i>
<br />

Agh! This was <b>scary</b>. Never heard any of these stuff before. Anyways, a Gsocer has to master the art of reading other’s code. And that’s what I did this whole period. I learnt docker and slowly figured out what each of these words meant. Went through thousands of lines of code inspecting the details. 

So, starting around mid-days of community bonding period we worked around 20 days setting up the docker images for each commit in ruby. I kept on learning new features, clarifying my doubts along the way. But one day mentor messaged me :

<i> " As of right now, I'll like you to stop working on the Docker integration stuff because I feel that we might have assigned you a task that is too difficult for you to complete given your current level of experience. Instead we will like you to focus on ... " </i>

and assigned me a new task. I need to take that as a failure!

## <b>It's different!</b>


Contributing open source for a short time and getting selected in Ruby which works on language itself was intimidating. During this time I observed many differences in the way other organizations operate and how I steered my journey. There are many organizations which have there prime focus on GSOC projects for development. In my case, its obvious that Ruby has many bigger activities to deal with. My mentor is mentoring two different GSOC organizations and is a core contributer of discourse along with rubybench. Again, its evident that he has greater problems to take care of. Besides, we don’t follow any specific timeline.

## <b>Last shot!</b>

My new task was :


<i>" What if all our benchmarks are implemented in Sequel? How fast would it be? How many objects would be allocated?
I feel we should split off all "database" specs from the Rails umbrella and make the suite of tests compare "sequel" to "Active Record", as it stands it is totally unclear how much performance is left on the table cause there is nothing to compare "Active Record" to.
So start looking at our ActiveRecord benchmarks and write similar benchmarks using Sequel. "</i>

This was my last opportunity to prove myself before midterm. Till now, no real contributions(PR’s) on github. Fortunately this time, I had previous knowledge of activerecord. All I had to do was take my time to go through all the activerecord benchmarks and convert them to sequel. 

6 days ago I got my greatest ever PR merged consisting of 593 additions and 29 deletions. This was exceptional and a huge relief. 


<a href="https://imgflip.com/i/16ix4v"><img src="https://i.imgflip.com/16ix4v.jpg" title="made at imgflip.com"/></a>
<br />

Task remains to tackle frontend and my sequel benchmarks will be up and running in rubybench.org.




