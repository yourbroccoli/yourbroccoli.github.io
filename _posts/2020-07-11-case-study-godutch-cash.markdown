---
layout: post
title:  "Case study: GoDutch.cash"
author: Paul
github_comments_issueid: 5
---

This is the first post that will actually talk about a real
SaaS-attempt.  As some commenters have pointed out, previous posts
were a bit more.. meta.  That's fine, we own that, we were just
setting the scene a bit.  Today we'll be talking about
[GoDutch.cash][gd], one of our projects.

<div class="deerbox">
  <figure>
    <img src="/images/case-study-godutch/godutch-landing.png" class="black-border">
    <figcaption>The GoDutch landing page.</figcaption>
  </figure>
</div>

## What is GoDutch.cash?

Very simply, [GoDutch.cash][gd] is a platform where users can enter
expenses they've incurred in shared situations (unfortunately named
"Trips", we didn't have the foresight of global pandemics and things
unfolding.. it'd work for flatmates, split grocery bills, restaurant
outings, holidays, etc.), and the tool tells you who owes whom how
much.

## The background story

We didn't just sit down and start building GoDutch.  It actually
started life as a humble Google Sheet.  At some undefined point in the
past, we both used Android phones, so that worked well.  However, in
about December 2018 i got an iPhone and wanted to keep it Google-free.
It turned out that Apple Numbers (their spreadsheet product) didn't
work on Android, and i was being obstinate, not wanting Google on this
new phone.  We might have briefly looked around at apps to solve the
issue, but we're privacy nerds, not to mention extremely cheap, so we
ended up whacking something together for our own use.  I think it was
something like a Thursday evening i sat down, before planning to leave
on a weekend away on Saturday morning.  I mostly just used a whole lot
of `rails generate` to get my way out of a sticky situation, chucked
HTTP Basic Auth in front of the app, and flung it on
[Heroku](https://heroku.com)'s free tier.  Life was good, life was
simple.

Fast-forward a few months, and we were still using the app ourselves,
made an actual login and authentication system with sharing of trips
between users, occasionally polishing rough edges and improving the
styling, to the point that we realised that with only a little more
effort it could reasonably be used by anyone.

It mostly languished a bit, because we didn't go on trips _that_
often, and then the lockdown happened of course.  A few weeks ago, a
friend suggested we dust off GoDutch and perhaps try and actually
monetise it.  Why not, we thought.

## Is there even a market?

There are quite a few competitors out there.[^compet]  We haven't done a
serious competitive analysis, but it's apparent to me even more
clearly than when we originally built GoDutch that competition would
be.. stiff.

### There are established competitors in your market. Do you give up?

I think the answer is a resounding **no**.  Just think how many
successful businesses not only thrive with under competition, but
would have had to start up amid stiff competition.  Almost every
business out there, from car manufacturers, to banks, to corner
grocery stores -- at one point, each one of them didn't yet exist, and
at one point (or so i firmly believe) it all started with a few folks
around a table (kitchen, board room, whatever) saying "let's do this
thing".

Of course, some of them had backers with ultra deep pockets, or
mountains of combined experience starting businesses.  But not all of
them.  There would've been people with language disadvantages, a lack
of connections in a new city or country, or perhaps just someone
recently out of a job and in desperate need of something to feed their
kids -- all kinds of stress, we don't know that.  Something i like to
remind myself of, is we often see other people being happy, or
successful, or doing their thing, and we imagine they must be so
confident, and so knowledgeable, while we're just muddling along.  I
call that the front stage--back stage divide: you're looking at
everyone else putting their best foot forward, performing for all the
other monkeys, while you're aware of all the difficulty, uncertainty,
that goes on in the kitchen, behind the scenes, to make progress.  I
might be wrong, but at least i'll be optimistic.

This whole topic reminds me of an article i read,[^mktg] entitled something
along the lines of "thinking like a marketer versus an engineer".  The
gist of it was that the engineering mindset might say, "Oh no, that
brilliant idea has already been done!  Well, i'll just have to invent
some other, _untested_ idea!"  Whereas the marketer might say, "Aha,
successful competition means that there's a validated market there,
i'll build something similar with a small differentiation or edge."

## Our angle, our differentiator

We hoped that by charging a small amount ($15 per year) and making
bold claims about privacy and lack of ads, we could convince folks to
use our system.  The design aimed to be fresh and cheeky, compared to
other apps that looked plain janky or were very stuffy.

We have a free tier where you can create one "trip", and a premium
tier that allows you to create infinite trips and collaborate on them
with other users of the platform.  So, if a group of friends goes
skiing together, only one of them needs to pay for GoDutch, the rest
of them can get invited and add and modify expenses on trips shared by
the premium user.

## So.. was it a success?

Not really, no.  I mean, we still use it to keep track of household
expenses (we GoDutched the purchase of the exsaasperated.com domain
name, in fact!), so it scratches our itch.  But as of today we have
one "premium" user, and that's a guy i know with a tech blog who was
kind enough to feature us.

### Why?

I hazard a few guesses:

* Very well-SEO'd competitors, that offer a free product that does
  pretty much all of what we do -- no margins to eat.

* Not many people actually sweat this stuff! They probably just take
  turns paying for lunches.

* Ineffectual marketing campaign -- we haven't been able to get enough
  eyes on it, perhaps.  But i think this point is probably less of an
  issue than the first two.

## What we tried

We spent a small amount ($44.49) on ads.  Specifically on Facebook and
Reddit ads.  We found that Facebook's targeting was super broad and
clunky, whereas Reddit allowed us to pick particular subreddits (such
as personal finance-related) to narrow our audience.  While almost
nobody touched our ads on Facebook, we actually got a fair few clicks
(in the hundreds) from Reddit.  **None** of them even signed up for our
permanent free tier though, which really surprised us.  Probably we could try
to optimise the landing page some more, but i actually think that a)
people don't really have this problem, and b) if they do, they'll use
Google Sheets or one of the many other apps that are free.

## Take aways

I think there are two lessons for us here:

* Talk to users first, build an audience before building an app.  In
  the time since we launched GoDutch we've been reading a lot more
  about small business, and that's the advice we keep hearing.

* Don't over-build before releasing.  Although, i don't regret the
  effort we spent on GoDutch, and i don't think it has been wasted.
  It's working as a legitimate tool for our own use, and we've learned
  random technical things from putting together another Rails app from
  scratch.

* Our name is better than the competition.

Time for our next project!

## Appendix

You've read this far.  It has turned into a long post.  I'm verbose,
sorry.  As a reward, here are some of the entirely silly ads i came up
with sitting on the couch.  We were purposely going for a mysterious /
gonzo feel.  I'm not sure they're that great, but hey, we had fun.

![](/images/case-study-godutch/ad-parrots.jpg)
![](/images/case-study-godutch/ad-chick.jpg)
![](/images/case-study-godutch/ad-geese.jpg)
![](/images/case-study-godutch/ad-cat.jpg)

<br>
<hr>


[gd]: https://godutch.cash
[^compet]: Some of the ones we know of are
    [Splitwise](https://www.splitwise.com/),
    [Splid](https://splid.app/english) (what a name!),
    [Kittysplit](https://www.kittysplit.com/),
    [Splittr](http://www.splittr.io/),
    [Billr](http://billr.me/) (somebody buy these folks some vowels!),
    [Settle Up](https://settleup.io/),
    [Tab](https://www.tabapp.co/) (completely un-googleable),
    [Divvy](http://www.divvythatup.com/). Quite a few, for
    sure. We're not in
    the USA so [Venmo](https://venmo.com/) isn't an option for
    us. It's also owned by PayPal, so i'll pass on that.

[^mktg]: Much to my chargrin i cannot find the article now.  I'll be
    sure to report back if i do.  My poor summary will have to
    suffice.
