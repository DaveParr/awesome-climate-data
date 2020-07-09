## Mission

> We are making a human curated index of easily accessible, comprehensive and up-to-date data sources, maintained and relevant programming libraries, and mission focussed open-source organisations to increase our awareness and ability to act on the climate emergency.

## Motivation

This project was inspired by a conversation in the breakout rooms of [useR2020](https://user2020muc.r-project.org/) relating to an issue about visibility, discoverability and awareness of data sets, technology and tools to combat the climate emergency. [This twitter thread](https://twitter.com/useR2020muc/status/1280777655785226240) captures some of the content. In the breakout room it was discussed starting a [slack channel which you can join](https://userstackling-uny5880.slack.com/join/shared_invite/zt-fkocefo6-kkRLrPqPI5WQR5P~HLdm9A#/).

Afterwards, I thought making this might be a useful additional resource.

Please, please, please contribute. I only have part of the puzzle, and the discussion demonstrated that lots of people have lots of knowledge about lots of useful resources.

## Scope

To make this maintainable, relevant and able to be kept up to date, these are some guidelines for useful content:

* publicly accessible data sets
    + ideally these are data sets that are relatively comprehensive in scope, and/or likely to be kept up to date over time
    + ideally they should be clearly present on the page, and require very little user registration to access
    + a good example is a government data base on Environmental Performance Certificates for buildings
    + a less good example is a csv at the end of a blog post behind a pay wall
* open source organisations contributing to analysing, predicting, or solving the climate emergency
    + a good example is an organisation with many open source tools hosted on github
    + a less good example is a web page with a paid for access product
* interfaces for accessing and processing relevant data
    + a good example is an R package or python module that wraps a freely available api and returns a usable data object, such as a pandas or R data frame
    + a less good example is an api that restricts access to a subscription plan only

## How to contribute

* Sign up for a GitHub Account
* [Fork this repo](https://guides.github.com/activities/forking/) to your user
* [Edit the READ.ME](https://guides.github.com/features/mastering-markdown/) using markdown
    + Where possible try to maintain the existing structure of the document.
    + Link to the most _generic and applicable_ location. e.g. if a company has multiple open source tools, link to the companies organisation level github account, not to the hosted front end implementation of each tool
    + Keep text as short as possible, using the name the project uses for itself. e.g. for [this site] use "Live tables on Energy Performance of Buildings Certificates" rather than "UK EPC certs (click download)"
* [Issue a pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/proposing-changes-to-your-work-with-pull-requests) and [make your branch up to date with this fork](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork)

## What happens then

We'll make sure that the links you've suggested are relevant, and merge it into our project :)

## Things that are probably out of scope, but mostly to keep our sanity :)

There is a lot of information out there, but if we try to index all of it, we may as well be google. Our aim is to find the _human curated_ best resources.

Some things will snowball very fast, and so are likely to not be included. These are things like:

### Twitter statuses

They are probably very insightful, and written by intelligent people, however they can't be realistically relied upon to stay _current_, contain _easily accessible data_, or _contain useful software_. If the tweet is links to any of those things, submit that instead <3

### Searches in large document data bases for key words

Many governments have large databases of white papers as pdfs, and data sets as csv. However, _searching_ these for terms like `climate change`, `flooding` or `carbon emissions` creates problems for this project. Firstly, where do we draw the line on search terms. Is "global warming" acceptable but "natural hazard" not? Secondly, a list of search terms in a markdown file doesn't help people discover _good_ information, and simultaneously dilutes the other items in the document. If the data base is _reasonably focused_ on the topic of this project, then submit the data base. If the data base contains some useful items, submit the items. 

This is going to be quite hard to manage, for instance the UK has very extensive data available at [data.gov.uk](data.gov.uk) which is only partially relevant to climate change, data access and technology. However there are far too many items to make it worth indexing each individually. For now a good compromise is a 'Topic' view, for instance the 'Environment Topic' of data.gov.uk.

## Feedback

If you have any ideas about how to improve this project (or the process around it), please let me know. You can open an [issue on the repo](https://guides.github.com/features/issues/) get me on [twitter](https://twitter.com/DaveParr), or on the [useRs Tackling Climate Change](https://userstackling-uny5880.slack.com/join/shared_invite/zt-fkocefo6-kkRLrPqPI5WQR5P~HLdm9A#/) slack group.


