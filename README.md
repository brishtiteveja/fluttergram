# Peergram
Peergram is a Decentralized social media app. It envisions to have instagram-like follower-followee relationship to encourage users across the world to share, promote contents. Peergram is designed to be a social platform with no central database or central authority like Bitcoin. It is based on a blockchain that generates Instacoin as the smart media token. Instacoin is generated by the users, for the users in each block that acts as the ledger for proof of online social interaction (posts, tags, votes, follows, comments). Peergram is inspired by Bitcoin, Ethereum, DTube, Fluttergram to disrupt the ad-based revenue generation model and bring trust and direct interaction between content creators and content consumers online.

Peergram app code base currently relies on Fluttergram which is an Instagram clone written in Flutter using Firebase / Firestore
Fluttergram project page: https://github.com/mdanics/fluttergram

## Getting started

#### 1. [Setup Flutter](https://flutter.dev/docs/get-started/install)

#### 2. Clone the repo

```sh
$ git clone https://github.com/brishtiteveja/Peergram.git
$ cd Peergram/
```

#### 3. You may have to finish various steps related to Firebase from Fluttergram github project page. At the initial phase we are still using Firebase backend as our database. But we are working on creating our blockchain "Instalon" based on DTube blockchain Avalon.

#### 4. Connect your phone and run (or use Android studio to run the app)
```sh
flutter run
``` 

# What's Next?
 - [ ] Instalon blockchain + Instacoin generation 
 - [x] Notificaitons for likes, comments, follows, etc
 - [X] Animations (heart when liking image) 
 - [ ] Improve Caching of Profiles, Images, Etc.
 - [ ] Better post creation, add filters to your image
 - [ ] Custom Camera Implementation
 - [ ] Firebase Security Rules
 - [ ] Delete Posts
 - [ ] Direct Messaging
 - [ ] Stories
 - [ ] Clean up code
