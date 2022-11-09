---
title: "Building a blog with Jekyll and Github Pages"
sub_title: "A bundle of bits"
categories:
  - Blogging
tags:
  - Jekyll
  - Github Pages
  - Webtech
elements:
  - content
  - css
  - formatting
  - html
  - markup
last_modified_at: 2022-11-05T10:16:49-05:00
---

Usually when I've blogged in the past, I've used Wordpress. I'm used to it - I develop (private) Wordpress plugins for a living - and I generally like it, but - weirdly - I find Wordpress to be overkill for personal blogs now, especially ones where you just want to write; you're not worried about SEO, or image galleries, or anything plugins will offer you.

Then hosting is an additional cost, unless you use Wordpress.com but even that has its limitations.

## Finding the right tools

So, I was looking at what else I could do. Obviously, a free host would be nice, and [Github Pages](https://pages.github.com/) was obvious to me (not least because I already use Github every date for version control).

Static site generators are something I've also been dabbling in lately - namely Gatsby - and something similar but on a smaller scale (ie, not requiring its own data source like GraphQL) would be good. I've toyed with static site things via Netlify the last time I tried to spin up a blog, and found it a bit... meh (it's me, Netlify, not you).

[Jekyll](https://jekyllrb.com/) kept coming up in searches, not least because Github uses it itself, so it was a pretty obvious choice. The reason I'd gone with Netlify before (I now recall) was because I wanted an admin interface for posting, rather than adding text files to a repo, but that was a layer of complication-for-the-sake-of-convenience that I'm ready to do without. Being happy to use Markdown also helps.

## The How of it all

So here we are. It was all rather simple; the most annoying bit was finding and implementing a nice theme, as some documentation is out of date, some themes are older and still have old instructions, or I just fucked things up on my own.

The [Jekyll instructions on setting up in Github Pages](https://jekyllrb.com/docs/github-pages/) is very helpful in giving a quick overview.

See also [Github's Quickstart guide](https://docs.github.com/en/pages/quickstart), which is even better.

* Set up a repo in Github calls `<your-github-username>.github.io`
* Set up pages within your repos Settings section
* Voila your new site will be done

(Yes, it's more complicated than that, but only in details - ready [the documentation](https://docs.github.com/en/pages/quickstart))

Then it came down to choosing a theme; Jekyll by default had me using one called **Minima** which is nice enough, but not NICE nice.

I ended up going with [So Simple Theme](https://github.com/mmistakes/so-simple-theme) and as it supports Github Pages' remote theme option, it was super-simple (HA) to get up and running. The biggest faff I faced was getting my logo to show.

## And now...

And now we're here. I have a blog again. It's costing me NOTHING. It's easy to update, it just takes a few minutes to commit my post, and wait for the site to rebuild. I could, if I wanted, add new posts directly in my repo via Github rather than locally, if I wanted to.

Yes, it's a bit lo-fi in a high-web-tech kind of way, but as I'm recently [revisiting how I do things in my digital life](https://losfer.com/mastodon/update/2022/11/03/starting-over-in-social-media-terms.html) it's another piece I get to toy with.