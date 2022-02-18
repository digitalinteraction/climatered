# Climate:Red

This repository contains information about ClimateRed OSS project.

## About

Climate:Red was a international virtual conference run between [Open Lab at Newcastle University](http://openlab.ncl.ac.uk) and the [IFRC](https://ifrc.org/).
It was a 36-hour continuous multi-timezone, multi-lingual conference with official and user-submitted sessions around the subject of the Climage Crisis.
This code is open source except where explicitly stated in the relevant licenses.

**Core team**

- [Rob Anderson](https://www.r0b.io/) - Lead Engineer
- [Tom Nappey](https://openlab.ncl.ac.uk/people/tom-nappey/) - Lead Design and Coordinator

**Collaborators**

- [Tom Feltwell](https://openlab.ncl.ac.uk/people/tom-feltwell/) - Chatbot Engineer
- [Simon Bowen](https://openlab.ncl.ac.uk/people/simon-bowen/) - Project Coordinator
- [Ed Jenkins](https://edjenkins.co.uk/) - Frontend Engineer
- [Andy Garbett](http://andygarbett.co.uk/) - Coffeechat Engineer
- [Gerard Wilkinson](https://gerardwilkinson.com/) - Coffeechat Engineer

## Overview

Climate:Red OSS is made up of several repositories:

- [digitalinteraction/climatered-client](https://github.com/digitalinteraction/climatered-client) -
  A Vue.js based web app to experience the conference
- [digitalinteraction/climatered-server](https://github.com/digitalinteraction/climatered-server) -
  A Node.js based server responsible for registration, attendance, coffee-chat and more.

And since the 2020 conference, continued development has lead to:

- [digitalinteraction/deconf-ui-toolkit](https://github.com/digitalinteraction/deconf-ui-toolkit) -
  A Vue.js component library and [storybook](https://deconf.openlab.dev/) environment
- [digitalinteraction/deconf-api-toolkit](https://github.com/digitalinteraction/deconf-api-toolkit) -
  An Node.js library for creating conference backend servers.
- [digitalinteraction/deconf-shared](https://github.com/digitalinteraction/deconf-shared) - 
  A package of TypeScript types to be shared between the ui and api toolkits

## Features

The [climate.red](https://climate.red) conference featured the following:

- An atrium, which was the homepage for attendees with live stats and helpful links to get about
- A What's On page to preview the schedule before the conference goes live
- A chronological schedule for the conference with temporal aspects to show the live sessions during the conference
- Detailed pages for each session with relevant links and embeds, for example, embedding a YouTube video or a Zoom call-to-action and linking to a Miro board
- Registration and magic-link based login pages to quickly get into the conference via an email
- WebRTC-based coffeechat with match-making based on the conference's topics
- Real-time interpretation during live events, so attendees can tune-in to live interpretation and experience the conference in English, French, Spanish or Arabic
- An interpretation portal for interpreters to enter live booths and broadcast audio over a live YouTube or Vimeo video for attendees
- Everything is translated into English, French, Spanish and Arabic and supports right-to-left and left-to-right orientations


## More information

The Climate:Red project lives on in Deconf, more information can be found at [digitalinteraction/deconf](https://github.com/digitalinteraction/deconf).
