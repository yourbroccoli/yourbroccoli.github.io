---
layout: post
title:  "Case study: HospoSafe"
author: Caitlin
github_comments_issueid: 7
excerpt: >-
    What did we do after our first unsuccessful attempt at launching a
    product? We tried to make another product and made a lot of the same
    mistakes again! This experience taught us that we needed to get more
    serious about learning about marketing and building our audience.
---

Our previous [blog post about GoDutch.cash][godutch] talked about our first unsuccessful
attempt at launching a product, and how we learned that it's important to talk to users
first, and not over-build before releasing. So what did we do next? We tried to make
another product and made a lot of the same mistakes again!

To be fair, the timeline explains that a little bit.  We started building GoDutch more
than a year ago for our own purposes, and started work on HospoSafe about a month ago.
In the meantime, through discussions with other aspiring businesses, reading a lot
online, and also speaking with readers of this blog, we've gained a much clearer
understanding of how we should be approaching these projects.

Nevertheless, we now know we'll need to be a lot more strategic in the future.

<div class="deerbox">
  <figure>
    <img src="/images/case-study-hosposafe/hosposafe-landing-page.png"
         alt="The HospoSafe landing page."
         class="black-border">
    <figcaption>The HospoSafe landing page.</figcaption>
  </figure>
</div>

## What is HospoSafe?

[HospoSafe][hosposafe] is an app designed to help cafés and restaurants to comply with
COVID-19 contact tracing regulations in Victoria and New South Wales, Australia.
Hospitality businesses need to record a contact name and phone number for all visitors,
store this data securely for 28 days, then destroy it. A lot of businesses are doing
this using pens and paper.

HospoSafe gives businesses a unique check-in URL and generates PDF posters to print out
with a QR code. Customers scan the code at the door, fill out a simple web form, and
show a green "successfully checked in" screen to staff members. The data is stored
securely, and purged after 28 days, but can be downloaded in the interim if government
tracing teams need the info.

## Background

About a month ago, things were looking up here in Melbourne.[^lockdown] COVID-19
restrictions were easing and restaurants, cafés and bars were opening up again. We had
heard about the new contact tracing requirements for hospitality businesses and thought
that a self check-in app could be a great idea.

We searched the web and found a handful of competitors. Most of them were free, but they
looked pretty janky[^jank] and weren't clear about security or how they were handling
private data. There was one very slick competitor, but they were very expensive, and it
seemed that you needed to request a call from their sales team before you could even
sign up. So we thought there was a market, and we could differentiate ourselves as a
fellow Melbourne small business, offering a privacy and security-focussed, lower-priced
option that people could start using straight away.

## The Launch

We set ourselves the deadline to launch an MVP by 1st July, giving us about a week to
build it. And we did! 🎉

But, we then had to grapple again with the question of how to get eyes on the product.
It seems like a silly oversight now, but we still hadn't really thought that part
through. We don't have any direct connections with restaurant owners. The thought of
cold-calling businesses made us cringe, but we were OK with the idea of sending emails
or Facebook messages.

We were also starting to read more about marketing and landing page optimisation, and we
realised our landing page could use a lot of work. We decided to start with Google Ads again
while we were improving the landing page and planning how we would reach out to
businesses directly (we might have been procrastinating a bit here!).

<div class="deerbox">
  <figure>
    <img src="/images/case-study-hosposafe/hosposafe-landing-page-initial.png"
         alt="The first iteration of the HospoSafe landing page."
         class="black-border">
    <figcaption>As a point of reference, this was the first iteration of the HospoSafe landing page.</figcaption>
  </figure>
</div>

## The reality check

As all this was happening, community infection rates of COVID-19 in Melbourne were increasing.
Lockdowns were re-imposed on parts of Melbourne on 2nd of July, and the whole city a week
later. Restaurants and cafés were back to serving take-away food only.

Our original idea was to market ourselves in Melbourne as a fellow local small business.
Restaurants in regional Victoria and other states were still open, so we weren't
completely deterred by the lockdown.

But doing more customer research finally gave us a reality check. We found a Facebook group
offering support and advice for local hospitality business owners during the
pandemic. As we scrolled back, we found other competitors that we had never seen before,
including a slick-looking one built by university students who were offering it for
free.[^uni] We also found posts from a month ago where restaurant owners were complaining
about being inundated with sales calls about contact tracing apps.

Infuriatingly, a lot of the offerings were explicitly suggesting restauranteurs could
use the contact details collected for exposure tracing, as a marketing tool.  Apart from
the underhanded ethics, this is disallowed by the guidelines.  But what can you do --
the temptation to use customer contact details for marketing is probably too great to
resist.[^privacy]


## What we tried

We spent $68.11 on Google ads, which got us 34 clicks and one person signing up for a
free trial.

## Was it a success?

No. We had one sign-up to HospoSafe from a pub owner in regional Victoria via Google
Ads, but it looks like they decided not to use it, and they didn't respond to our email
checking in on how they were going.

We've thought about trying to promote the app to restaurants outside of Melbourne, but
at this stage we think we were probably too late to the party with HospoSafe.

## Take-aways

* **We still weren't thorough enough about research on the competition or validating demand before we started building.** We should have made more effort to try to find the
  places online where our users go, before building anything. If we had found that
  Facebook group back in June, we might have had a chance to make connections and find
  potential users before starting to code, or we might have still concluded that it was
  too late, and not wasted time building an app.

* **We spent too much time messing with CSS.** We used the [Bulma](https://bulma.io/)
  CSS framework, which is a helpful tool, but we ended up arranging columns and buttons
  by hand, and the app still looked more janky than we would have liked. Using a UI kit
  with pre-made UI components would have saved us valuable time and given a more
  polished result. If anyone has recommendations for this we'd love to hear them!

* Next time, we should **first** find a community of potential users, such as a Facebook
  group or a Slack channel, where we can gather input before building a product.

### In Conclusion

As usual, we're battling the feeling that we wasted time and effort, but we must remind
ourselves that we would approach it quite differently if we were to start now.  That
means we've learned something, which is worthwhile in and of itself.

<br>
<hr>

[hosposafe]: https://hosposafe.com.au/
[godutch]: ../11/case-study-godutchcash.html

[^lockdown]: [Not so much anymore](https://www.abc.net.au/news/2020-07-07/victoria-reimposes-lockdown-as-coronavirus-cases-rise/12429990)

[^jank]: One of them even required the restaurant patron to search for the establishment by name, and the others looked like 2002-era websites.

[^uni]: Unfortunately, while it looked slick, their app was actually fairly broken.  The download-a-QR-code feature just didn't work.  Of course, we have no idea how many users they actually had.

[^privacy]: While the [government
     instructions](https://www.business.vic.gov.au/__data/assets/pdf_file/0006/1903308/Fact-sheet-Keeping-visitor-contact-safely.pdf)
     don't *literally* forbid you to use the contact details for marketing ("Visitor
     and patron contact details should be shared only with representatives of the
     Department of Health and Human Services for the purpose of contact tracing.
     Additional information should not be collected for privacy reasons."), this clearly
     isn't what they had in mind.
