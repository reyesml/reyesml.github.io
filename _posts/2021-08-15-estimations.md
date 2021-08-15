---
layout: post
title:  "How good are your estimates?"
date:   2021-08-15 09:58:36 -0700
categories: management
---

As engineers, our work is inherently difficult to estimate.  It’s highly contextual, it’s complex, and sometimes we are tasked with solving problems that we’ve never encountered before. Despite these challenges, our teammates need us to provide the most accurate estimates that we can.

We can think of estimates like a game.  If we estimate correctly, then planning our work becomes much easier.  Estimates allow our teammates and our stakeholders to come to a better understanding about the work we intend to do, which is a crucial component of clarifying expectations.

If we estimate wrong, then we can waste a lot of resources and cause a lot of frustration for our teammates and our customers.

## How do we improve at this estimation game?
On my current team, we improve our estimates by keeping score.  All of our estimates are recorded within our work-item tracking software, and we can check the score by looking at these things called “control charts”.

Control charts are pretty useful.  They can tell you a lot about how a team or organization operates, but for right now I want to focus on what they tell us about our estimates.  Take this control chart for example:

![Small item control chart](/assets/estimations/control_chart_small_items.jpg)

This chart represents all of the tasks that we have estimated were "small" over the last 6 months.  This chart tells us that, most of the time, the tasks we classify as "small" take about 2 days to complete, _give or take a day_.  That “_give or take_” is also known as our standard deviation.

## Standard deviation is key
A narrow standard deviation means that our estimates are precise.  A wide standard deviation means that we are unpredictable.  As you can imagine, items that we classify as “medium” and “large” have increasingly larger standard deviations (currently 3 days and 7 days for my team, respectively).  This is typically due to larger goals being more complex, more risky, and by extension: more unpredictable.


## So what do we do with this information?
Without these measurements, it’s not entirely clear how good we are at estimating things.  The charts can help ground us to reality.

Control charts give us actionable information.  For example, if we notice a trend that our “small” tasks start becoming more and more unpredictable, then it could be a signal of a larger underlying issue.  That issue is 100% context-specific, but from my experience I’ve noticed 5 common mistakes:
1. Not fully exploring the scope of a task before it is estimated
1. Scope creep, either from stakeholders or from the engineers themselves
1. Overconfidence in our abilities
1. Ambiguous requirements
1. Technical debt

Control charts make it easy for us to spot outliers, which usually lead to fruitful discussions with the team.  Questions such as “Why did this seemingly simple task take 5x longer than we estimated?” can lead to productive outcomes, provided we’re in a safe environment.

Lastly, charts serve as a regular reminder of the value of breaking large tasks down into smaller tasks.  Not only are smaller tasks easier to estimate, but they are faster for us to complete, which makes it easier for us to pivot to new priorities, and capitalize on new opportunities.


Interested in starting a discussion about estimates?  Reach out on twitter: [@{{ site.twitter_username }}](https://www.twitter.com/{{ site.twitter_username }})