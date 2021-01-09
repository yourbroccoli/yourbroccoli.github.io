---
layout: post
title:  "Retro Solitaire for iOS"
author: Caitlin and Paul
github_comments_issueid: 8
excerpt: >-
    We're still around and still thinking about ways to escape the desk-job
    grind. Here, we share the story of a cross-country move and a silly side
    project.
---

[![Download our Solitaire game for iOS on the Apple App Store.](/images/retro-solitaire/download-appstore.svg)](https://apps.apple.com/au/app/sol-exe-retro-solitaire/id1542164345#?platform=iphone)

Happy new year! It's been a while. When we last posted back in July,
Melbourne had just gone back into lockdown. It was becoming clear that COVID
wasn't going to be temporary, and that life wasn't about to return to normal
any time soon.

Since then we've moved across the country to Darwin, in Australia's tropical
north. That's taken up a fair bit of our time and energy over the past six
months, and so our SaaS plans have been on the back burner. But we wanted to
let you know that we are still around, and share what we've been up to
lately.

Long ago, we had developed something of an obsession with outdated OS design
(the visual kind, not systems architecture or whatnot) and pixel art — that
was a whole other rabbit hole. One of those projects was a silly card game
with zero rules, called DadaCards (there are a few examples of little projects on obsolete operating systems at <https://members.vistaserv.net/badcardgames>).
DadaCards used the original `cards.dll` sprites which we all know and love from the
early days of Windows 3.1 and 95, and we wrote it in Visual Basic 6.
Definitely pointless if we're trying to start a business, but then,
we can't always be thinking about productivity, right?

<div class="deerbox">
  <figure>
    <img src="/images/retro-solitaire/dadacards.gif"
         alt="A strange-looking card game in a retro Windows UI."
         class="black-border">
    <figcaption>DadaCards in action.</figcaption>
  </figure>
</div>

Fast forward to the two weeks of quarantine we had to sit out before being
allowed into the Northern Territory, and we thought it might be fun to
revisit that project, but this time for iOS. After all, wouldn't it be great
to be able to pass the time playing a nostalgic card game on one's phone
while waiting in line at the grocery store?

Within the first few evenings we had a working DadaCards implementation which
we could run in the iOS Simulator,[^simulator] and about a week
in we had an admittedly buggy version of Solitaire! After putting this effort
in, we thought it could be fun to try to release it on the App Store, so we
could show it to our friends, so that's what we did. Unfortunately it was way
more work than we anticipated (don't all crazy projects start with the words,
"let's simply..."), but in the end we managed — it's live on the App Store and you can [download it here][solitaire]!

<div class="deerbox">
  <figure>
    <img src="/images/retro-solitaire/solitaire-screenshot.png"
         alt="Solitaire cascading cards animation"
         class="black-border">
    <figcaption>I challenge you to name a more satisfying sight.</figcaption>
  </figure>
</div>

[![Download our Solitaire game for iOS on the Apple App Store.](/images/retro-solitaire/download-appstore.svg)](https://apps.apple.com/au/app/sol-exe-retro-solitaire/id1542164345#?platform=iphone)

While we did include a sort of "donationware" nag (which our friends tell us is much too subtle), asking for a once-off
payment of $4 to unlock lifetime access to some premium features (for now,
only an "undo" feature, multiplayer is under development), we don't expect
this ever to be a profit-making venture. For example, we have to pay $99 (annually!) to
Apple for the privilege of even being able to make submissions to the App
Store (grrr), so we'd have to sell 25 units per year just to break even,
which, without a marketing campaign... is unlikely to happen). Therefore it's probably a bit
off-topic for this blog, but it did represent a good excuse to provide our
readers with an update, to signal that we're still alive, still thinking
about ways to escape the desk-job grind.


<br>
<hr>

[solitaire]: https://apps.apple.com/au/app/sol-exe-retro-solitaire/id1542164345#?platform=iphone

[^simulator]: Unfortunately we couldn't develop on our iPhones because our
    macOS versions were behind, and Apple very aggressively deprecates support of
    XCode... serves us right for developing for such a tyrannical closed
    platform, right? I'm not much inclined to do that again, even though Swift
    was a very nice language to develop in.
