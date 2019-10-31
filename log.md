# 100 Days Of Code - Log

### Day 1: October 28, 2019
##### 

**Today's Progress**: Migrated production build of Playthru app from Heroku to Now

**Thoughts:** Getting the client up and running on now was almost as simple as one command but the GraphQL endpoint was a struggle and needed more config because it uses Apollo - which wasn't well documented on the Zeit/Now docs. Ended up being a frustratingly small change to the routing that was the last hurdle we eventually got right. (Paired with JackBittiner)

**Link to work:** [Playthru - DJ/ Song Recommendation App](https://github.com/jackbittiner/play-thru)

### Day 2: October 29, 2019
##### 

**Today's Progress**: Not a lot of code but a good impact. Researched git config and set up Playthru to use git pull-rebase as default.

**Thoughts:** Was good to find a way to do this to create consistency between people working on the app since a few people are now involved and we all prefer working in a trunk based way. Have had some feedback from @richardkotze that prestart is maybe not the best place for it - maybe preinstall since it only needs to run once? 
Resource on trunk based dev & setting git pull-rebase config: https://megakemp.com/2019/03/20/the-case-for-pull-rebase/

**Link to work:** https://github.com/jackbittiner/play-thru/commit/16f1a4ab3d7a246c5c6ae16dd3d0aece1493f6d1

### Day 3: October 30, 2019
##### 

**Today's Progress**: Learned how to run up a react native app with Expo and Expo CLI - also learned that Android SDK's are written in Java these things may not play well together easily  

**Thoughts:** Probably spent a bit too much time on today - setup a project with ExpoCLI which was really cool, but struggling with understanding about app fingerprints for the spotify SDK and realising it's all written in Java, so might not even be possible to integrate with React Native, damped the pleasure of seeing the react native app hot reload on my phone as I change the code. A lot more setup and less progress that I anticipated. 

**Link to work:** https://github.com/tobywinter/playthru-mobile


### Day 4: October 31, 2019
##### 

**Today's Progress**: Spent time this evening refreshing my understanding of the render props method of component reuse and worked throught a big refactor of some complex step management code   

**Thoughts:** Although technically work from 'work' the problem was tangled enough that it was really satisfying to solve so I used my learning time today and this evening to work through it and feel I accomplished a lot and reminded myself how renderProps works as a pattern. (resource here: https://reactjs.org/docs/render-props.html) Even though I'm likely to be able to use hooks in our codebase soon as I am in others - it's really good to cement my understanding of ways that may become 'legacy' as they won't be going anywhere in old codebases anytime soon. 


**Link to work:** https://github.com/findmypast/titan/commit/37775187f2d02dca4a3cda25bd420c31dbf44f99 (private repo)
