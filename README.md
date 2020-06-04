# Harm Reduction

[![Build Status](https://travis-ci.org/codeforboston/harm-reduction.svg?branch=master)](https://travis-ci.org/codeforboston/harm-reduction)

[Demo App](https://cfb-harm-reduction.web.app/)

### About the Project

We are developing a tool for the communities of Chelsea, Revere, Saugus, and Winthrop to improve multi-sector and multi-jurisdictional coordination for outreach, response, and recovery to overdoses. We will do this by improving the efficiency of existing systems, speeding up access to critical data, and aiding in cross-jurisdictional  communication, in order to help these four communities save lives.

### About our Partner

Our partner in the project is the City of Revere Substance Use Disorder Initiatives (SUDI) office. They are working with three other communities – Chelsea, Saugus and Winthrop – on fulfilling a newly-provided grant to scale up their existing overdose response outreach programs. The project that we create will ultimately take into account the workflows of all four communities and would be shared amongst them to meet all of their needs. 

The SUDI office offers support and resources as well as ongoing care in these communities via direct outreach with individuals who have experienced a nonfatal overdose.

### Contact Us 

[cfb-harmreduction@codeforboston.org](mailto:cfb-harmreduction@codeforboston.org)

### Important Links

[Welcome Document](https://docs.google.com/document/d/1_yO1GpPvAFnRMpydOWtpd19yDq7Tr0t0ZJdet0WwJpY/edit?usp=sharing)  
[Trello Board](https://trello.com/b/E93Cmx9n/harm-reduction)  
[Google Meet Room](http://www.codeforboston.org/rooms/harmreduction)  
[Shared Google Drive Folder](https://drive.google.com/drive/folders/14Q1e3VCWJSqldykqSxwEAwAdSq6dMnl3?usp=sharing)  

### Getting Started

1. Join us on [Slack](http://slack.codeforboston.org) at #harm-reduction
2. Log in to our Trello
3. Request access to our Google Drive Folder (instructions [here](https://docs.google.com/document/d/1_yO1GpPvAFnRMpydOWtpd19yDq7Tr0t0ZJdet0WwJpY/edit#heading=h.sve3pgxt3iph))
4. Jump into our Google Meet Room and hang out with us!

### Github Setup

//TODO 

### CI/CD Setup

We use [Travis](https://travis-ci.org/github/codeforboston/harm-reduction) for automated testing and deployment.

Tests run on all branches and for pull requests. On master, after tests pass, we deploy the [site](https://cfb-harm-reduction.web.app/) using Firebase.

The deployment is configured with environment variables set in [Travis settings](https://travis-ci.org/github/codeforboston/harm-reduction/settings):

- `FIREBASE_PROJECT`: The name of the firebase project to deploy to.
- `FIREBASE_TOKEN`: The token used to authenticate with Firebase, generated by `firebase login:ci`. The user that generates the token must have permission to deploy to the firebase project.
