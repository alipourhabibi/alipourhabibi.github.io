+++
date = '2026-09-24T16:26:34+04:00'
draft = false
title = 'Why I decided to start a blog: Distributed systems'
tags = ['distributed systems', 'deterministic simulation']
summary = 'Why I decided to start this blog'
+++

A month ago, I was thinking about how I can learn the distributed systems
not just the theoretical parts but implementing things, see how they fail in action 
and test them in the proper way.

So I did a little bit of research and found out about [FoundationDB's Deterministic 
simulation testing](https://apple.github.io/foundationdb/testing.html).

I decided to write my own and then test my already implemented 
and newly written protocols with it.

I started to write the simulation first (It is a WIP). You can take a look at 
it [here](https://github.com/alipourhabibi/detsim).
It's called detsim (Deterministic simulation). Then I decided to also write about 
the steps I went through, what I learnt along the way, what surprised me 
and write about other random things.

And that's the reason I started this blog.

Right now I implemented some parts of the simulation and am currently testing the 
[raft](https://github.com/alipourhabibi/raft) implementation I wrote before. I 
plan to write about the simulation first then about the raft port and tests.
