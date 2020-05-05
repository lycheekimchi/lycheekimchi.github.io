---
title: How does this work?
layout: journal
---

Hello! You were probably expecting an in-depth tutorial about how to cobble some sort of website for yourself, which is all well and good, but let me level with you here — *I actually have no idea how I built this website*. I would honestly love to give you a tutorial but I seriously do not remember. Motivation for me comes in [bursts](https://en.wikipedia.org/wiki/Hypomania) that start at around 2am and end at 4am three days later, where I get a lot of work done (academic, recreational, or otherwise), and then look back and wonder *How in the world did I do that?* Anyway a tldr is at the bottom, if you don’t want to read my rambling.

Looking back, if I were to do this again, I would just give up on all the Ruby and HTML shit and go straight to [Wordpress](https://wordpress.com/) or [Squarespace](https://www.squarespace.com/) or even just [Medium](https://medium.com/) so I don’t need to mess with tech stuff (or pay). I don’t have any CS experience aside from two semesters in high school in _Java_ so I kind of… don’t know anything haha.

But anyway, the motivation for this website was this workflow I had in mind:

1. I would write some journal entry
2. I would save it as a text file on my computer
3. I would hit a keyboard shortcut and BOOM, the journal entry would be auto-magically updated, formatted as an HTML file, and uploaded to my website

Sounds easy right? The idea is I wouldn’t have to copy and paste the text into a text box into some website, which would be cumbersome. I already save a ton of journal entries on my laptop, so it would be cool if a program could upload and format all of them for me, and I wouldn’t have to go through each one _individually_ and upload them to Wordpress or Medium or whatever. Another plus-side: freedom of customization!

The framework I found for this was Jekyll, which promises to transform plain text into entire websites ready to “deploy.” This seemed to match the “write text file => upload to blog” pipeline I had in mind.

Also it seemed pretty easy to use. If Jekyll were more layman-accessible, I think it would help cause a resurgence to independent blogs and personal websites, instead of your entire Internet presence localized on the same 5 websites as everyone else.

Anyway here is the tldr of the workflow I promised:

- I installed [Ruby](https://www.ruby-lang.org/en/documentation/installation/) and [used this tutorial for Jekyll](https://jekyllrb.com/docs/), the framework that converts plaintext into websites for you
- I searched a bunch of shit on stackoverflow and copypasted mindlessly to make the website actually work
- I searched more shit on stackoverflow about CSS to make the website actually look good
- I gave up on that and just looked for a good [Jekyll theme](https://jekyllthemes.io/free) that was pretty. I settled on [colorie](https://github.com/ronv/colorie)
- I learned [Markdown](https://guides.github.com/features/mastering-markdown/) and rewrote some of my creative writing as Markdown files. At this point I had this whole folder dedicated to my Jekyll blog, and I was running `bundle exec jekyll serve` on my computer to test it over and over.
- Then I installed [Github Desktop](https://desktop.github.com/) and followed [this](https://jekyllrb.com/docs/github-pages/) to put it on GitHub Pages
- Now, whenever I write something, all I have to do is save it in the Jekyll folder and hit ctrl-P to push the changes up.

So yeah that’s pretty much it. I guess it was worth it, but if you asked me to make even a _tiny_ change to the CSS or the website structure I feel like I would break everything.

That’s it for now. Again, if you asked me how to build a website for writing, I would just tell you to use Medium or something.

…[I am also on Medium.](https://medium.com/@themichaeldizon)