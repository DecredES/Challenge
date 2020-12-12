# Evaluation by bee

This is my evaluation of 6 final project for Decred Blockchain Learning Challenge, Oct-Dec 2020.

## Summary

Project | Procurement and use of data | Relevance and specific findings of Decred | Functionality, usability and accessibility | Execution | Documentation | Total
---|--:|--:|--:|--:|--:|--:
Digital Identity powered by Decred | 9 | 8 | 7 | 6 | 5 | 35
People of Pi | 13 | 14 | 15| 17 | 17 | 76
Dcrtime explorer | 14 | 14 | 17 | 17 | 18 | 80
iPati | 4 | 5 | 5 | 4 | 3 | 21
Bitmoney | 6 | 5 | 10 | 11 | 6 | 38
Decred Memories | 9 | 9 | 11 | 12 | 8 | 49

## Digital Identity powered by Decred

- pitch: https://youtu.be/HwjgUemRL-g
- src: https://github.com/eliseoabelcarh/NodeJs-MongoDb-ChallengeAPI-DecredBlockchain

### Evaluation

- Use of data: 9
  - it only uses timestamping data if I got it - huge area to explore by itself but timestamps is a limited subset of all data possible
- Relevance and specifics for Decred: 8
  - I couldn't find any feature that can be uniquely done in Decred and not Bitcoin/Ethereum/etc
  - the problem is legit but I'm skeptical about the solution, it essentially creates another KYC oracle, which is a huge responsibility and risk (and +1 third party for the user to worry about)
- Functionality, usability: 7
  - blindly putting 7, I hope something is working, actually N/A
  - couldnt test or even guess about without using the app
  - pretty design shots give hope that UX would be ok
- Execution: 6
  - blindly puttin 6, actually N/A
  - I could not determine at what stage it is
  - a glimpse at code suggests the MVP is 60% ready
  - many statements suggest the lack of expertise for many attempted features, but it could be due to poor translation
- Documentation: 5
  - many key parts are not documented given the sensitivity of the data handled (at least for English)

## People of Pi

- pitch: https://youtu.be/EYh4YJjEkTI
- src: https://github.com/Pandogrammer/people-of-pi

### Evaluation

(based on video pitch alone)

- Procurement and use of data: 13
  - not using chain data, but using a lot of Pi data in a useful way
  - chain data could be used in the future e.g. treasury
- Relevance and specific findings of Decred: 14
  - problem is legit
  - not using chain data
  - obviously unique and original to Decred because using Pi data
  - Pi data is used quite well and there is potential to go further
- Functionality, usability and accessibility: 15
  - the video mention 4 views which is pretty good for an MVP that can already deliver value
  - web based UI can be used with only a browser without too much special knowledge
  - some objectives are ambitions and will require a ton of work, but may be very useful
- Execution: 16
  - I see understanding of Decred and Pi
  - I think it does enough for an MVP
- Documentation: 17
  - at 1:09 I already have a good idea of what it does
  - pitch alone explained it well, README is pretty good
  - nice presentation overall

Notes:

- sadly the video was too blurry and I could not see who is the most valuable Pi user and his score... Wait, I have a guess
- haha ok it was funny but I swear I am not biased because of this, this project gets a #2 from me based on its own merit

## Dcrtime explorer

- pitch: https://youtu.be/CdRPrywc-WU
- src: https://github.com/yoandresaav/dcrtime-explorer

### Evaluation

(based on video pitch alone)

- Procurement and use of data: 14
  - limited to timestamping data, but that alone has huge potential so the rating must be good
- Relevance and specific findings of Decred: 14
  - looks like it adds signature verification on top of timestamping, very useful
  - not super original but it can win by just doing it right
  - I didn't grasp how it makes Decred unique but I have some ideas (e.g. Decred might offer better security due to PoS, block header commitments, better software, etc)
- Functionality, usability and accessibility: 17
  - UI is very good looking, browser-based is a low barrier (esp. if it scales well to mobile screens)
  - the pitch didn't talk about key management (big UX challenge), but if export/import is there that's a good first step
  - ideas for version 2 are reasonable
- Execution: 17
  - the video looks like the MVP works
- Documentation: 18
  - README is good
  - bonus point for Doge pics (always relevant)

Updates:

- 2020-12-08 The case of VotoLegal [using](https://twitter.com/Decred_BR/status/1328935726491312146) dcrtime to register electoral campaign donations suggests the importance of dcrtime explorer to help navigating timestamped data. Timestamping is possible on many other chains but I think winners will be determined by UX (for both developers and end users) and adoption.

## iPati

- pitch: https://youtu.be/vIMALr1xh0E
- src: https://github.com/manueldevmx/ipati-blc

### Evaluation

(based on video pitch alone)

- Procurement and use of data: 4
  - assuming it only checks dcrdata to query funding status
- Relevance and specific findings of Decred: 5
  - assuming it is crowdfunding only, it is not unique to Decred
- Functionality, usability and accessibility: 5
  - something about crowdfunding
  - almost N/A because I feel there is not much working stuff, could not evaluate the UX
- Execution: 4
  - I assume there is not much working because not much was demonstrated
- Documentation: 3
  - in the README I see a likely-autogenerated React app and some es text
  - no en subs :(, I used auto-translation

## Bitmoney

- pitch: https://youtu.be/IhAkr-J2vwk
- src: https://github.com/Carlos-Carballo/Bitmoney

### Evaluation

(based on video pitch alone)

- Procurement and use of data: 6
  - upon a quick look the use of data is limited to market metrics like price and volume
  - there is potential to use more Decred-specific metrics for recommendations
- Relevance and specific findings of Decred: 5
  - not too original and not too specific to Decred
  - if any Decred-specific models are used to make recommendations about DCR the score must be higher
- Functionality, usability and accessibility: 10
  - feels like a portfolio manager
  - the app looks UI-rich and easy to use
  - hard to judge how useful it is
- Execution: 11
  - they have something to show, it feels like the MVP is 60-80% ready
  - I hope the "models" mentioned in the repo are computed for real
- Documentation: 6
  - no en subs, no en docs
  - I see some es tech/math docs in the repo so the doc situation might be much better

## Decred Memories

- pitch: https://youtu.be/w-6C0tExLFI
- src: https://github.com/aeh-bonilla/decred-memories-api
- src: https://github.com/aeh-bonilla/decred-challenge-frontend

### Evaluation

- Procurement and use of data: 9
  - I see that ticket price and Pi data is used
- Relevance and specific findings of Decred: 9
  - it is quite original although I can't immediately see how I would use it, maybe in 10 years when Decred is a huge impactful DAO
  - the goodness highly depends on showing news that are relevant for Decred
- Functionality, usability and accessibility: 11
  - easy to use, nice UI
- Execution: 12
  - they have an app to show
  - bonus points for TypeScript
- Documentation: 8
  - en subs end after 3 min
  - no en docs
