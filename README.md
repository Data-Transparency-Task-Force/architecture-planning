Brainstorm DOC - https://docs.google.com/document/d/1h1tq6URVTEinGAatKxs6Adybji50wT9O8ceLaoPGd0E/edit?usp=sharing

[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/Data-Transparency-Task-Force/architecture-planning)
![CI](https://github.com/Data-Transparency-Task-Force/architecture-planning/workflows/CI/badge.svg)

# How to contribute
1) Click "Gitpod Ready-to-Code" badge to start up a new coding workspace.
2) Under the Source Control: git menu select "Fork" - u should receive confirmatoin you successfully switched git url in the lower right cornern
3) Make modifications
4) `git add *`
5) `git commit -m <DESCRIPTION_OF_WHAT_CHANGES_I_MADE>`
6) `git push` <- from here you can make a pull request w/ changes between our org repo and the forked repo.

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
        Review ZKP presentation: 

# Resources

COVID-19 data sets provided by AWS: <- need to query Amazon COVID-19 data lake w/ SQL.

- https://aws.amazon.com/blogs/big-data/a-public-data-lake-for-analysis-of-covid-19-data/

- https://covid19.healthdata.org/united-states-of-america

- https://github.com/CSSEGISandData/COVID-19

- https://datascience.nih.gov/covid-19-open-access-resources
