# Iris intro

## Description

Iris is a web analytics project (yes, yet another one). It aims to provide flexibility, simplicity without reinventing the wheel.
It's composed by the following projects (which can each one be easily replaced):
- `iris-client`: a lightweight JavaScript library that will trigger the events to be tracked
- `iris-backend`: a simple application that will store the events triggered by `iris-client` into a database
- `iris-db`: a `ClickHouse` database schema where `iris-backend` will store events
- `iris-dashboards`: a collection of `Grafana` dashboards to visualize events stored in `ClickHouse`

## Reason to exist

Not many attempts have been made to create web analytics projects. Services as Google Analytics are hard to replace (if not impossible) and the resources required to handle such enterprise were, until now, very expensive in both time and money.
Things, however, have changed. It is now possible to run your own analytics project and it has never been so justified to do it.

### Ad-blockers

Ad-blockers penetration is growing and there's nothing suggesting this is a tendency that will change.
According to marketing researches, [+26% of users in the US](https://www.statista.com/statistics/804008/ad-blocking-reach-usage-us/) use ad-blockers, [+30% of Germans](https://www.emarketer.com/content/ad-blocking-in-germany-2018) use them and in certain countries the [penetration is beyond 40%](https://www.statista.com/statistics/351862/adblocking-usage/). Read more: [2019 infographic](https://www.socialmediatoday.com/news/global-ad-blocking-behavior-2019-infographic/551716/), [The rise of Ad-blockers](https://econsultancy.com/the-rise-and-rise-of-ad-blockers-stats/), [Ad-blockers against analytics](https://www.brainsum.com/blog/adblockers-against-analytics).

It is hard, then, to measure properly user bahaviour with these numbers and there's no way to tell if the adoption of ad-blockers is evenly distributed across all demographics.

### Software

Web analytics, for any website that heavily relies on data, belonged to the realm of `big data` and by big data I mean the amount of data you cannot handle with traditional tools (if you have a better definition please share!).
The way to handle big data was very cumbersome (very steep learning curve - yes, I'm looking at you, hadoop) or expensive (I'm now looking at your big data SaaS). 
Now new software allows everyone to run complex analytical queries in SQL (and dialects) in very modest hardware.

### Ownership

It's your data. You own it. Don't give it for free to someone. Remember, when the something is free you are the product.

### Customizable

You should be able to change your analytical software depending on your very specific requirements

## Help wanted

If you are interested into participating in this project, let us know. We'll strongly need `Gophers`, `ClickHouse expert`, `JavaScript guru` and `web analytics masterminds`.
Just contact us in any way you prefer. 

Let's change things!

## Immediate TODO

- TODO list
- roadmap