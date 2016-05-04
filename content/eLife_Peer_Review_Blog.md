Title: The peer review process of eLife
Date: 2016-04-14
Category: Science
Tags: scientific publishing, open science
Slug: peer-review-at-eLife


Together with my colleagues Marco Giordan, Andy Collins, and Attila Csikasz-Nagy
we just published an analysis of the peer review process of eLife on
F1000 [here](http://f1000research.com/articles/5-683/v1).

It was an interesting experience, and it was my first time leading a project from
the start all the way to publication (and now, post publication peer review, as
it should be).

The idea to critically analyze peer review came after NIPS (one of the most
prestigious machine learning conferences) decided to do a very brave experiment
and publicly examine their own peer review process.  Briefly: for a subset of papers, NIPS
assigned two completely independent teams of reviewers to review.  After, they
examined the overlap in the agreement between the two sets of reviewers, and
the results were pretty bleak.  For a longer summary, there's an excellent
write up [here](http://blog.mrtz.org/2014/12/15/the-nips-experiment.html).  The
key message is this: **"about 57% of the papers accepted by the
first committee were rejected by the second one and vice versa. In other words,
most papers at NIPS would be rejected if one reran the conference review
process (with a 95% confidence interval of 40-75%)."**  Publishing a paper at NIPS
can completely change the arc of your career - so the idea that someone's future
career is at the whims of chance is fairly discouraging.


Although the results were bleak, they were not surprising.  Scientists
tend to be a fairly rational bunch <sup>[citation_needed]</sup> but when it
comes to getting papers published and grants accepted, they fall back on superstition
and paranoia.

[![img](http://www.smbc-comics.com/comics/20120324.gif)](www.smbc.com)


I know this first hand: with collaborators, we currently have two papers under review in
fairly selective journals, and we spent months worth of work in trying
 to parry possible comments from reviewers/editors.  For example, we had
 conversations like: "If we get X to review our paper, we need to make sure
 that Y is done because that's their theory and they will instantly reject
the paper if we don't discuss it".  Or "If our reviewer is a person who doesn't
like mathematical modeling then we need to show the simpler simulations
in the main text and the more complex ones in the supplementary."  A truly
embarrassing amount of work is done not because the authors think it makes the
paper stronger, but because scientists are utterly paranoid about what will
happen during the peer review process.


There are two main reasons for this paranoia.  The first one is the
disproportionate influence played by grants obtained/impact factor when evaluating
scientists.  The current system really sucks, but this is an area where only
people with actual power to change the incentive structure (professors on tenure
committees, leaders of funding bodies, etc) can make a difference.  The second
reason is that **the peer review process is remarkably un-transparent and in the
absence of real information people fall back on anecdotes and superstition**.  I
thought that this was an area where I could actually give a small contribution.


With that in mind, after NIPS published their experiments, I reached out to the
eLife editorial team (I had an excellent experience publishing a paper there
previously, and they have a strong commitment to improving publishing) about
doing a serious statistical analysis of their peer review process.  Their team
(Mark Peterson, Peter Rodgers, and especially Andy Collins) was incredibly
pleasant to work with, and really cared about improving scientific publishing.
Unfortunately, we were unable to actually do randomized controlled experiments
the way NIPS did.  eLife is growing very quickly (data in the paper!) and
splitting up papers with dual review tracks would have been too taxing for
their resources at this point.


What we ended up doing instead was looking at what factors influence how quickly
a paper gets published, and what influences how often a paper gets cited.  More
importantly, we make a [very interesting dataset](https://github.com/FedericoV/eLife_Editorial_Process/tree/master/data)
available for everyone to analyze however they want, and we have the
[code](https://github.com/FedericoV/eLife_Editorial_Process) to reproduce almost
every step of our analysis.


Further Steps:
--------------
The data I published is a snapshot of the situation of eLife as of early 2016.
Since all the scripts I used are online, it will be interesting to monitor the
situation and see how things change in the future.  Further, F1000 makes it very
easy to add new versions of a paper, so I am planning on trying to extend the
work and examine other effects, such as:

- http://www.nature.com/news/papers-with-shorter-titles-get-more-citations-1.18246
- http://www.nature.com/news/rejection-improves-eventual-impact-of-manuscripts-1.11583
- http://link.springer.com/article/10.1007/s11192-016-1936-z