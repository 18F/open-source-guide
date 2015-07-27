---
permalink: /using-the-wiki/
layout: default
title: Best practices for using the wiki
---

Some of our teammates recommend turning off a repo's Wiki unless you have a proactive use for it. But there are many ways to use a Wiki and use it well.

If you’re using GitHub, you can enable a wiki on every GitHub repo by going to its settings and checking the ‘Wikis’ box under ‘Features.’

<img src="{{site.baseurl}}/images/wiki1.png" alt="Turn the wiki feature on by going to settings and clicking on Wikis under the box labeled 'Features'">

What does this get you? Tons! You can now put all the great information that would have made your README way too long and complicated into separate, clear pages. For example, the 18f.gsa.gov team uses the wiki for all their “how to do this” work, and catalogues items like decisions on which blogging tags to use across our sites.

<img src="{{site.baseurl}}/images/wiki2.png" alt="This is the 18F site wiki, which catalogs how to use tags on their platforms.">

Another really great use for the wiki is to house your product roadmap and user research goals. 18F’s Michelle Hertzfeld is a huge proponent of keeping these documents in the repo with the codebase so they’re easy to find, share and get feedback on.

<img src="{{site.baseurl}}/images/wiki3.png" alt="A screenshot of the roadmap for USEITI website, which is located in a wiki">

## Tracking user research on GitHub

Speaking of user research, some of our project teams also like to keep their research process and findings in the repo along with the code. This helps keep all project documentation together in one place and also makes sure that we’re not only *building* in the open, but also *researching* in the open. This way, team members, and anyone else who is interested, can track the research that went into project decisions.

Naturally, this does not include posting confidential interviews with people or anything else that should not be shared. What it includes are things like:

* Research plans
* Interview scripts
* Summarized research findings

One way to do this is to create an “orphan branch” to keep your research in. An orphan branch is a branch that you name that sits within the repo. Creating an orphan branch lets you have a completely different file structure from the rest of the repo in that branch, and you can put all of your research within that branch, as follows:

* First, create a new branch under branch:master and label it with a new name. Michelle chose research. ([Example](https://github.com/18F/doi-extractives-data/tree/research))

<img src="{{site.baseurl}}/images/wiki4.png" alt="Create a new branch under branch:master">

* You are now on a branch of the repo, where you can store information.

<img src="{{site.baseurl}}/images/wiki5.png" alt="A screenshot of the research branch">

* Michelle stores information like user research for various sprints [in this repo](https://github.com/18F/doi-extractives-data/tree/research/research/sprint17).

<img src="{{site.baseurl}}/images/wiki6.png" alt="Screenshot of user research for Sprint 17">

* This makes it easy for others to [find and use the user research](https://github.com/18F/doi-extractives-data/blob/research/research/sprint17/sprint17_results.md), and remains within the project repo.

<img src="{{site.baseurl}}/images/wiki7.png" alt="Screenshot of usability tests conducted during Sprint 17">
