# domains
Organizing and publishing the web domains of the US federal government


## Background

The federal government expresses itself through its web presence.  Much of an agency's mission can be seen through the information it publishes and the functionality it offers.  

## Goals 

The goal of this project is to inventory and account for the full web presence of the US federal government.  

## Primary Resources

### [.gov Registry Export](https://github.com/GSA/data/tree/master/dotgov-domains)

The [.gov Registry](https://www.dotgov.gov) offers a recurring export of [.gov second level domains](https://github.com/GSA/data/tree/gh-pages/dotgov-domains).  These include federal, state, tribal, and local .gov websites.  Not included are .mil and .fed.us websites, as well as .com, .org, etc. websites that are used by government agencies.  

### Secondary Resources

* [Webharvest.gov](https://www.webharvest.gov/)
* [Dotmil-domains project](https://github.com/esonderegger/dotmil-domains)
* [DAP participants](https://analytics.usa.gov/data/live/sites.csv)

## Subdomains 

While an agency may register second level domain (e.g. state.gov), its web presence may expand well beyond the content located at the second level domains' homepage (e.g. www.state.gov) to other sections and subsections located at subdomains (e.g. americanenglish.state.gov, blogs.state.gov, and adoption.state.gov).  A truly comprehensive analysis of a domain must extend past the initial second level domain to the subdomains as well.  

At the moment, though, there is not a published directory of .gov subdomains.  Therefore, it is necessary to derive such lists by open source means.  The following represent some initial efforts.  Anyone is welcome to improve upon them or suggest new efforts.  

### Participants in the Digital Analytics Program 

* Note [list of participant domains](https://analytics.usa.gov/data/live/sites.csv)
* Goal would be to derive from that a list of subdomains
* Note that this will only show information from [where the Digital Analytics Program has been implemented](https://pulse.cio.gov/analytics/domains/)

### Exports from Censys.io

* Note [process here](https://github.com/18F/domain-scan/pull/85)
* Goal would be to aggregate all of the data that is now [available by agency](https://pulse.cio.gov/https/domains/#q=gsa.gov)

### Crawling the .gov List with Wget

* [First Try](https://github.com/unitedstates/domains/blob/master/projects/wget-subdomain-survey.md)
