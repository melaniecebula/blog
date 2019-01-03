---
title: Starting a Blog and 2018 in Review
date: 2019-01-02T08:42:58+00:00
showthedate: true
draft: false
---

In 2018 I decided to engage more with the larger technical community. I had a
few goals:

1.  Speak at more technical conferences
2.  Engage with other people/companies on twitter
3.  Start a technical blog
4.  Contribute to more open source
5.  Attend more events aimed at women/non-binary folks (and maybe organize one!)


Here's how I did.

**Speak at more technical conferences**

I knew I
wanted to speak at a technical conference, but I had zero experience finding
conferences, filling out
abstracts, and submitting before CFPs close. I gave a first talk at FutureStack 2017,
but that was a bit different since it was a vendor conference and Airbnb was
invited to speak there. Also a manager signed me up before telling me about it
(thanks Joey!), so it wasn't planned. So I started submitting proposals in the
middle of summer 2018. I got a
rejection, and three acceptances (yay!), and I was surprised by a keynote
acceptance. I ended up speaking at ONS Europe in
Amsterdam in September, and KubeCon NA in December. The ONS talk wasn't
recorded, but it was also more of a practice run of the content I would finalize
for KubeCon NA. I couldn't squeeze in VelocityConf NYC into my schedule, and was
sad to miss it (but I was having fun in Hong Kong instead). I love giving talks,
but they're time consuming for me. In addition to practicing the presentation, I
spend a lot of hours drafting content and finalizing the slides. I spent even
more time polishing my KubeCon slides, because I knew a lot of people would see
it :).

What I was most terrified about was standing up there and saying something
universally Wrong or Bad. But people were engaged. There was note-taking,
picture-taking, "aha"s, and a lot of followup discussion both in person and on
twitter. What I loved most was meeting with people and other companies and
comparing/constrasting how we've tried to solve different problems. And there
are a lot of problems when you completely change your infrastructure to
Kubernetes. I walked away with a treasure trove of notes and ideas to share with
our infra teams, and feel re-energized about many of the technical and
organizational problems we've been facing.

status: super success!

**Engage with other people/companies on twitter**

I started picking up my twitter game shortly before the conferences. I put my
twitter handle on all my slides too :). I got a TON of engagement from KubeCon. I
went from ~400 to ~1000 followers, and finally feel engaged on the platform.
It's a great way to see where things are going in infra in real-time.

status: success

**Start a technical blog**

Well, I started setting up this blog on December 30th. I waffled a bit on how to
setup it up, but settled for using hugo.

status: kinda?

**Contribute to more open source**

I set up kubernetes locally and commented on and tried to work on an issue. Liz
Frost gave me a lot of 1:1 help reproing the issue. But the issue was too hard
for me to complete on a compressed timeframe at KubeCon :). So I'll have to pick
this up later.

There was an uptick on open source contributions from Airbnb engineers in 2018
(My coworker Ramya found a scheduler bug related to balancing pods across
availability zones, and her fix will be in 1.14!!), and we'll likely make more
contributions in 2019. For example, I know our Continuous Integration team is looking at current
open source image building solutions, and our Continuous Delivery team is
looking at moving us to Spinnaker.

status: failure, I can do better!

**Attend more events aimed at women/non-binary folks (and maybe organize one!)**

I also attended a few meetups and conferences, my favorite of which was Building
Upwards by Vicki Cheung at Lyft. I loved listening to and chatting with women
and non-binary folk about infrastructure. I wanted to plan one of these for late
2018 at Airbnb HQ, but we're pushing it to 2019.

status: mostly success

**2018 Contributions**

Overall, I did a lot of coding in 2018 at work:
![work github](/img/github_work_2018.png)

Although the darker green boxes were actually automated refactors of 100+
services (now you can run refactors as a bot user to not mess with your
contributions if you'd like).

**2018 Highlights / Lowlights**

Lowlights:

* Spectre/Meltdown fallout continued into January (we also experience peak load in early January-- fun!)
* This one guy in PR kept trying to stop me from speaking and was super rude about it
* Unexpected and sudden departure of two close teammates :(
* Imposter syndrome was a bitch, again
* People trying to get me to debug stuff by implying an issue is somehow my fault (just ask nicely and I'm usually happy to jump on an issue, I actually enjoy debugging)

Highlights:

* My project (new way of configuring and managing services) became general access for new services in April
* My project (streamlined way of migrating existing services to the new way) became general access in November
* Leadership of different engineering groups signed off on migrating their services!
* Business trips to Dublin, Amsterdam, Portland, and Seattle.
* I got promoted to senior software engineer! (well technically, from software engineer to software engineer since we use levels)
* I got to work all over infra this year (service discovery/networking, CI/CD, developer tooling, security, etc)
* Speaker training and keynote at KubeCon
* The CEO and CTO know my project :). The project does have a hype name and catchphrase, which always helps.
* People implying that I should debug issues because I touched the code at some point and probably broke it (this gets old after you've "proven" that your code works just as intended for the 10th time)

I worked on a lot of interesting problems this year, and look forward to sharing
my solutions now that the blog is up!
