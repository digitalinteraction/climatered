# Climate:Red

This repository contains information about ClimateRed OSS code.

## About

Climate:Red was a international virtual conference run between [Open Lab at Newcastle University](http://openlab.ncl.ac.uk) and the [IFRC](https://ifrc.org/).
It was a 36-hour continuous multi-timezone, multi-lingual conference with official and user-submitted sessions around the subject of Climage Change.
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

- [digitalinteraction/climatered-client](https://github.com/digitalinteraction/climatered-client)
- [digitalinteraction/climatered-server](https://github.com/digitalinteraction/climatered-server)

And since the 2020 conference, continued development has lead to the development of:

- [digitalinteraction/deconf-ui-toolkit](https://github.com/digitalinteraction/deconf-ui-toolkit)
- [digitalinteraction/deconf-api-toolkit](https://github.com/digitalinteraction/deconf-api-toolkit)
- [digitalinteraction/deconf-shared](https://github.com/digitalinteraction/deconf-shared)

## Features

[climate.red](https://climate.red) and featured the following:

- An atrium, which was the homepage for attendees with live stats and helpful links to get about
- a What's On page to previews the schedule before the conference goes live
- A chronological schedule for the conference with temporal aspects
- Detailed pages for each session with relevant links and embeds, for example embedding a YouTube video or a Zoom call-to-action
- Registration and magic-link based login pages to quickly get into the conference via an email
- WebRTC-based coffeechat with match-making based on the conference's topics
- Real-time interpretation during live events, so attendees can tune-in to live interpretation and experience the conference in English, French, Spanish or Arabic
- The system is fully translated into English, French, Spanish and Arabic and supports right-to-left and left-to-right orientations


## Other uses

- The Deconf libraries were used to run [MozFest 2021](https://www.mozillafestival.org/en/)

## Future work

- More work on the deconf libraries, moving more features across and improving
- Detailed documentation for using the libraries
