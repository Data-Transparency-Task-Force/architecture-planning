Brainstorm DOC - https://docs.google.com/document/d/1h1tq6URVTEinGAatKxs6Adybji50wT9O8ceLaoPGd0E/edit?usp=sharing

[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/Data-Transparency-Task-Force/architecture-planning)
![CI](https://github.com/Data-Transparency-Task-Force/architecture-planning/workflows/CI/badge.svg)

# 5/1 TODO
- [ ] 1UP Health setup - **WIP**

# April 30th TODO
- [ ] intros
- [ ] react js demo
- [ ] discussion points
- [ ] phased approach to metric creation/feedback gathering
- [ ] decide on 1st 3 phases criterion
- [x] mascot
- [ ] iterate on github workflow - https://gist.github.com/blackfalcon/8428401
- [ ] zk snarks discussion

# Discussion Points

## Official team doge/mascot "Henry" for inspiration!

![Henry](img/FullSizeRender.jpeg)

## Metric (DTS??) - The metric itself should instill confidence. Calculations should be as transparent as possible

1) Current colloquial metric is number of people deceased - lags several weeks behind what's happening

2) The second metric we all know is the number of cases tested positive. This too isn’t helpful because it ignores the number of people who could already be infected but haven’t yet ‘tested’ positive, or could soon be infected because of a particular relationship between population density infection rates. It ignores the context that number is couched in.

3) It is also critical to know how many people have been tested;

- current testing data is wholly inadequate to provide for any of the needs listed above, and indeed our current struggles reflect this

## Phased Approach to metric creation

### Phase 0.0 - A ok or maybe not so good (MVP) confidence metric

Metrics to focus on for a given area (state):
Deaths
Confirmed cases
Tests administered
Risk factors - don’t see a lot
Resources available - don’t see a lot

We need help in determining where to pull our data from and how to synthesize this into our ELI5ish confidence metric:

MVP - map of location w/ heatmap radius and statistics on hover (aggregated from AWS data lake)
- one state
- county specific information
- can scale up to phase 1 or 2

### Phase 1

### Phase 2

### Phase 3

# How to contribute <- TODO: made need updating

1) Click "Gitpod Ready-to-Code" badge to start up a new coding workspace.
2) Under the Source Control: git menu select "Fork" - 
3) Press enter to confirm selection

![Confirm Selection](img/switchFork.png)

u should receive confirmation you successfully switched git url in the lower right cornern
4) Make modifications
5) `git add *`
6) `git commit -m <DESCRIPTION_OF_WHAT_CHANGES_I_MADE>`
7) `git push` <- from here you can make a pull request w/ changes between our org repo and the forked repo.

# Architecture Planning

Discussion of DTF Software Architecture Repo

    - Application for Healthcare Workers - MAP w/ Data Transparency Score (DTS) - create mockup w/ react - **WIP**
    - Data Models for Storing Factors - 
    - Query Resource Databases - compile list

    - Verified Real-Time Data Guaranteed Via Smart Contract  
    - Secure File Storage with Agile Referencing  

use **JS** based tech

    - NodeJS - https://github.com/nodejs/node
    - SQL - https://aws.amazon.com/blogs/big-data/a-public-data-lake-for-analysis-of-covid-19-data/   
    - IPFS-JS - https://github.com/ipfs/js-ipfs
    - ReactJS - https://github.com/facebook/react

**UI** - web dashboard (world map)  

    - Google Maps API  - https://www.npmjs.com/package/google-map-react
    - HTML5  
    - Google Maps Reach Component gives us a lot of functionality for free but is not open source
    - new forked https://www.newline.co/fullstack-react/articles/how-to-write-a-google-maps-react-component/

**IPFS** for storage  

    - Hash Based Linking  
    - Secure SHA Encryption  
    - Scalable File Structure
    
**ZK-snarks**

    - TODO:
        Determine whether we should use zero knowledge proofs to preserve user privacy
        Review ZKP presentation: \
        - [ ] reach out to expert and ask for her opinion? - Hadas Zeilberger, ConsenSys Health's ZK specialist to present on ZK's and lead a Q&A session about privacy and zero-knowledge solutions
	    - [ ] thoughts?
        - ZKP's are complex

# Data lakes/sets etc.

## 1UP
https://1up.health/dev/fhir-analytics <- this look interesting and has office hours tom

## CALIFORNIA

https://healthdata.gov/dataset/california-covid-19-hospital-data-and-case-statistics

## AWS
COVID-19 data sets provided by AWS: <- need to query Amazon COVID-19 data lake w/ SQL.

- https://aws.amazon.com/blogs/big-data/a-public-data-lake-for-analysis-of-covid-19-data/

- https://covid19.healthdata.org/united-states-of-america

- https://github.com/CSSEGISandData/COVID-19

- https://datascience.nih.gov/covid-19-open-access-resources

Other:

- https://c19hcc.org/resource-library/

- https://covidtracking.com/data


As we are watching this unfold we are getting mess of metrics
scientific community + individuals
what does this mean 
huge limitations
cases per day is not reliable
deaths per day when they die they die more clean cut
death data on mondays -> 

risk and uncertainty calculation

a (un)certainty metric

existence of metric should make people want to increase testing
testing key 

## Meeting Flow

Intros

overall metric idea

react google maps library - UI dev

metric discussion

moving forward, questions, and feedback

# Meeting w/ chris morning 30th MVP discussion
MVP - map of location w/ heatmap radius and statistics on hover (aggregated from AWS data lake)
- one state
- county specific information
- can scale up to phase 1 or 2


CDC for data - state level data - local health department
private clinic data - having trouble getting data
under reporting gon federal level
non centralizd health system
hopkins
uva 
supply data
GIS
hospitals, race, sex
demograhic data

green/red - recommend trends
positive or negative correlation
not sure on data source for public measures

PPE might be tough - facilities and beds
local or state health department resources

# 4/30/10
- [] github cleanup
- [ ] gitcoin response data scientist
- [ ] schedule discussions w/ chris
- [ ] @ 5:30 sync make sure to update chris + max on schedule

