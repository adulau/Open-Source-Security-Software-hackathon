# OS3 hackathon - 26th March 2018 in Luxembourg and Japan


## List of Projects, Team Members, Hackathon Page and Project Live Chat

This is the list of open source security software projects at the hackathon and the ongoing
project during this hackathon event. Feel free to add your project.

 - [AIL](https://github.com/CIRCL/AIL-framework)
 - WiP [BGPRanking](https://github.com/D4-project/BGP-Ranking)
 - [MISP](https://github.com/MISP), Core Team, [Hackathon Page](https://github.com/MISP/MISP/wiki/Hackathon) and [MISP Gitter](https://gitter.im/MISP/MISP)
 - [MISP dashboard](https://github.com/MISP/misp-dashboard)
 - [The Hive] (https://github.com/TheHive-Project/TheHive) (see also Cortex and Cortex-Analyzers on the github org (https://github.com/TheHive-Project ) page)
 - https://github.com/monarc-project/MonarcAppFO - MONARC - Method for an Optimised aNAlysis of Risks


## Outcome

List the current outcome including git repository, issue, notes, wiki or photo.

### TheHive Project
Ideas for the day:
    - Review Cortex 2 documentation, create a QS guide. Target release date of Cortex 2: Thu March 29, 2018
    - Make sure MISP will work with Cortex 2 (API update) for enrichment
    - Improve the Cortex FileInfo analyzer
    - Improve TheHive4py

### Telco ideas

- Objects review: ss7, gtp, diam
- PyMISP
- Feeds:https://github.com/MISP/PyMISP/tree/master/examples/feed-generator-from-redis
- Feeds definition: enable preview, per event (down arrow = import)
- Sighting idea https://github.com/MISP/misp-sighting-tools/blob/master/bin/pcapreader.py

    Strategies for watching new events: ZMQ Feeds pubsub with all activities, API REST list events (last) through PyMISP (examples/last.py)

- IDS flag : per attributes, indicates automation can be enabled for this event
- Download as... : standardized format - https://github.com/MISP/misp-modules/tree/master/misp_modules/modules/export_mod
- Expansion on value: modules / expansion: On Net / Roaming


Use cases:
- PTM Import Hot numbers "phone-numbers" attributes: PROTO WORKING
- Feed to import events
- Add "hits" to events: Sightings
- Expansion on values related to telco on P1 central db (GDPR friendly)
- VKB Expansion: module to match vague Title/Description/related topic to Precise Vulnerability record
- Tags fromt MISPobject (VKB)

Problem:
FIXED:    How to get same results as https://misppriv.circl.lu/attributes/search Results for all attributes of type "phone-number" --> 197 results
    with: ./searchall.py -s phone_number | jq . | grep 'phone-number' | wc
            39      78    1558
OPEN: Can a feed item have sightings?



## Practical details

### Venue Luxembourg

 - CIRCL - Computer Incident Response Center Luxembourg, c/o "security made in Lëtzebuerg" (SMILE) g.i.e.,   16, bd d'Avranches,   L-1160 Luxembourg

### Venue Japan

 - JPCERT/CC - 東京都千代田区神田錦町3-17 廣瀬ビル11 階

### Pad Japan

https://pad.riseup.net/p/OS1-Tokyo-hackathon

## Open Questions

Feel free to add your question below.

- How the transition of projects/ideas will be done between Luxembourg and Japan?

## Misc Contributions

### Phil: Let me share some great tool that we feel is better than etherpad now: HackMD https://github.com/hackmdio/hackmd

    docker-hackmd: https://github.com/hackmdio/docker-hackmd

test it here: https://hackmd.io/8IhqdQlqSQeCCdqac2t0rQ


### Fabien: I have a nice tool that we use in our day to day. If someone is interested in "Web Application Security Scanner Framework" -> https://github.com/Arachni/arachni

### MISP Notice

MISP/misp-noticelist : 
https://github.com/MISP/misp-noticelist






