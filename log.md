# 100 Days Of Code - Log

### Day 1: January 1, 2017

**Today's Progress**:

* Working on a Hubot script to easily allow for using the URL shortener https://tr.im from Slack. I added the framework using yeoman.io, and added Code Climate to point out where I can use better style. Published to npm at https://www.npmjs.com/package/hubot-trim

![I created a repo and made an initial commit, so as you can tell, things are getting pretty serious.](https://pbs.twimg.com/media/B9B45qUIQAAAJKJ.png:large)

* Made a modification to https://github.com/OperationCode/town-crier, to allow it to broadcast to multiple channels.

**Thoughts** I try to find the fastest and easiest way to do something, rather than the most aesthetically pleasing, emphasizing effectiveness over efficiency. That has certain drawbacks.

**References**

1. [Hubot tr.im script](https://github.com/hollomancer/hubot-trim)
2. [Slack announcer w/ Airtable backend](https://github.com/OperationCode/town-crier)
3. http://ben.straub.cc/2016/02/18/hubot-lessons-learned/

### Day 2: January 2, 2017

**Today's Progress**:

* Looking at ways I can integrate https://github.com/OperationCode/town-crier with the API for Meetup Pro.

**Thoughts**

* The idea here, is that announcements for our local Meetups will go directly to the pertinent location channels in our Slack chat, as long as they're on the schedule.
* I've wanted to map each of our Meetups to individual locations, as well as Slack channels and zipcodes. It looks like I'll need to create that lookup table sooner rather than later.
* Stretch goal: As the event draws closer, announcement frequency will increase.

**References**

1. [Slack announcer w/ Airtable backend](https://github.com/OperationCode/town-crier)
2. [Meetup API](https://www.meetup.com/meetup_api/)
