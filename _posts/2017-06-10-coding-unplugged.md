---
layout: post
date: 2017-06-10
title: "Coding unplugged"
---
I recently took a flight across the country. Like most flights now, it had wifi. I planned to get some work done on the flight. Unfortunately, the wifi was out. Without StackOverflow, would I be able to get any work done? It turns out, a lot more than I was expecting.

The limitless resources of the internet provide a compelling reason to stay online. Every answer you could possibly need, just a google search away. If you're doing web development, you probably already have a browser open anyway. But with convenience comes temptation. Email, Slack, Hacker News, Reddit, and more are all right there, waiting to break your flow. I frequently struggle to stay focused in the late afternoon and after a few absent minded keystrokes end up at the mercy of the latest HackerNews argument. How can I keep my flow going without getting stuck, or worse, distracted?

## Making do

The two technologies I most frequently work in at Clever are golang and Node. Fortunately, both have easy ways to access documentation offline.

Golang offers [godoc](https://godoc.org/golang.org/x/tools/cmd/godoc), which is a simple tool to print package documentation as plaintext or as webpage. Running ‘godoc -http=:6060' serves up documentation for the go standard lib as well as everything in your gopath. The godoc setup was more than sufficient to keep me in the flow.

Node also packages standard documentation in the tarball download. I have yet to find a good solution for local dependencies beyond opening up the Readmes in the `node_module/` path. There's also [npm docs](https://docs.npmjs.com/cli/docs), but that requires an internet connection.

One other useful tool is [Devdocs.io](https://devdocs.io/), which compiles a lot of useful documentation into a single webapp.

## Results

I managed to finish most of what I was planning to do during the flight anyway, without having to continuously stave off the endless distractions of the internet. I found golang to be much more fluid than node, likely due to godoc. I need to look for better local dependency node documentation tools.

But all in all, I would consider it a success! Since the flight, I've tried it for periods at work shorter than a nonstop SFO to JFK flight with fairly good results. Two takeaways:

- This forces you to do a bit of planning about what you want to do ahead of time. I like this, as I occasionally rush right into programming. Although it may slow you down in some cases, I think the payoff is worth it.
- Fending off distraction is costly, even if you don't get distracted. Just resisting the temptation can drain your focus.

Everyone has different tricks to help them stay productive. This one is worth trying out.
