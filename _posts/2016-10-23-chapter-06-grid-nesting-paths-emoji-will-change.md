---
layout: post
title: "Episode #06: Grid Layout, Sass properties nesting, SVG paths with CSS, Emoji silhouettes/outlines, will-change bug"
date: 2016-10-23 21:10:00 -0300
categories: podcast
excerpt: "Episode #06 goes back to basics and reviews a bit of everything, from the CSS Grid Layout module turning into a Candidate Recommendation, passing through Sass propertis nesting, SVG paths with CSS, emoji silhouettes and outlines, and ending with an article about the will-change bug introduced in Chrome 53"
audio_url: /audio/Episode-06.mp3
audio_size: 17138664
audio_duration: "00:17:45"
music_credits: http://www.bensound.com
---
Hey there, thanks for tuning the sixth episode of _Show and Learn_. In this episode we talk about a pretty wide set of stuff, so let's dig in!

_126Kr_ revises the status of the *CSS Grid Layout Module*, talks about the different states a draft could be in, and dives into the future of this implementation.

After talking about the *Grid Layout Module*, we have _Martin Wolf_ showing us how we can *nest properties* in Sass, which is great given that I'm pretty sure not much people is aware of this.

Moving on, we have _Chris Coyier_ tweeting a demo where we can see how an SVG path is manipulated using the `d` property in CSS. This is rather shaky, yet interesting, territory!

And then we can see _Guillermo Rauch_ and _@mahemoff_ playing around with CSS `text-shadows` in order to get emoji silhouettes and outlines 🙊.

Finally, we go through a post created by the folks at _GreenSock_ talking about the `will-change` property bug introduced with Chrome 53, and how you can deal with it.


**Editor's note**: I may have said "article" instead of "episode" at the ending, excuse my momentary brainfart 😅.

&nbsp;

{% include player.html mp3=page.audio_url %}

&nbsp;

### Links list
* CSS Grid Layout Module Level 1 at Candidate Recommendation - [http://126kr.com/article/7kskemtiixi][grid-layout]
* WICG Discourse - [https://discourse.wicg.io/][wicg-discourse]
* Sass properties nesting - [http://codepen.io/martinwolf/pen/3a795bc563d84dfff8e96d343e160256?editors=1100][sass-prop-nesting]
* Changing SVG paths with a CSS property - [https://twitter.com/chriscoyier/status/781913529716711424][css-prop-path]
* CSS emoji silhouettes - [https://twitter.com/mahemoff/status/781582366510817280][emoji-silhouettes]
* CSS emoji outlines - [https://twitter.com/rauchg/status/781590245720494080][emoji-outlines]
* "will-change" must change? Animators beware. - [http://greensock.com/will-change][will-change]

&nbsp;

Download this podcast:

* [MP3 file][mp3]

Music:

* [Bensound][music-credits]

[grid-layout]: http://126kr.com/article/7kskemtiixi
[wicg-discourse]: https://discourse.wicg.io/
[sass-prop-nesting]: http://codepen.io/martinwolf/pen/3a795bc563d84dfff8e96d343e160256?editors=1100
[css-prop-path]: https://twitter.com/chriscoyier/status/781913529716711424
[emoji-silhouettes]: https://twitter.com/mahemoff/status/781582366510817280
[emoji-outlines]: https://twitter.com/rauchg/status/781590245720494080
[will-change]: http://greensock.com/will-change
[music-credits]: {{ page.music_credits }}
[mp3]: {{ page.audio_url }}
