---
layout: post
title: Website Review - freddystudio.cf
description: I review FreddyStudio’s website.
category: site review
image: home.png
medium: https://blog.dnomaid.co.uk/freddystudio-website-review-7460cf19d885
---

Welcome to a new thing on this blog that I am creatively naming “website reviews” where I (attempt to) review websites that I think are rather bad. Basically Peter Day’s videos in written form.

For this first review, I thought I’d review a friend’s site as it is particularly special.

---

# The design and appearance

I am not a designer, but I like things that look pretty. This site does not look pretty. It is anything but pretty.

{% include quote.html quote="OH MY GOD, IT’S SO BAD" author="Haden (FletchXYZ)" short="" %}

{% include image.html path="home.png" caption="Yes, <b>this</b> is what we are dealing with." %}

First off, the font does not fit the page at all. It’s weird and bubbly and looks like it could come packaged with Microsoft Word 98’s WordArt feature.

{% include image.html path="skype.png" caption="This screenshot of Max Cross typing perfectly encapsulates my feelings towards this site." %}

Second off, you can see he’s got his social links at the top and the site’s pages at the bottom. This is all well and good until you notice that his status page is in the social links and that there is a link to the home page… on the homepage. Not so great.

---

{% include image.html path="faq.png" caption="The FAQ page" %}

Moving on to the FAQ page, we are blasted with bright cyan text and terrible grammar. I honestly thought that my grammar was bad, but in comparison to this, mine is godly. He’s attempted to make a menu however, it looks terrible as it only has 2 items in it and doesn't need to be there.

{% include image.html path="triggered.png" caption="Freddy hasn't capitalised ‘Twitter’" %}

---

# The Code
I’ve saved the worst thing until last. The code. It’s not bad. It is several times worse than bad.

{% include image.html path="code.png" caption="Here is the site’s HTML copied into my editor so we can look at it easier." %}

His semantics are terrible! If you know even a bit about HTML, you are probably screaming internally. I know I am.

It starts with the head section. This part is fine. But then the head section ends. And then everything falls apart.

Here is a list of things he is loading (in order):
- Bootstrap
- Respond.js
- Material Icons font
- Materialize (CSS)
- jQuery
- Materialize (JS)
- Font Awesome
- Chewy font

Can you guess how many of those he is actually using?

If you guessed 2, you are correct!

He is only using the Chewy font and Materialize’s CSS. All the others are just slowing down the page’s load time. To make things worse, the way he is using Materialize is just wrong. The only thing he is using it for is the button click effect, which looks absolutely atrocious.

{% include image.html path="hover.gif" caption="Freddy is loading the entire Materialize CSS file just for this button effect." %}

The body element is using the depreciated bgcolor attribute and is never closed.

{% include image.html path="tracking.png" %}

To top everything off, Freddy is hosting this site using 000webhost, which is owned by Hosting24, who are adding a tracking script to the bottom of his website. Oh yeah, 000webhost is free — so Freddy is using a free web host that inserts tracking codes into clients’ websites. Awesome!

---

# Conclusion

I think Freddy’s website is utterly abysmal and urgently needs to be improved and/or optimised. Hopefully, he manages to upgrade it fairly quickly.

Thanks to Haden for making this post less bad.

---

# Update:

I Tweeted this post’s title and Freddy responded with this.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">Dude its not the official site its just a black background with white text just stop talking about mah site I don&#39;t do it to your</p>&mdash; FreddyStudio (@FreddyStudio) <a href="https://twitter.com/FreddyStudio/status/797350712044879872">November 12, 2016</a></blockquote>
<script async src="https:////platform.twitter.com/widgets.js" charset="utf-8"></script>

---

# Update #2:

Freddy asked me how I got random images in the background of my site, so I told him. Then he just did the same thing as me.
His implementation is rather bad as the images he has picked are all really bright and clash with the light-coloured text.
Awesome.

{% include image.html path="dms.png" %}
