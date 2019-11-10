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


### Day 5: November 4, 2019
##### 

**Today's Progress**: Restarted the react-native project using the full build instead of the Expo version - made good progres setting up the react-native project, adding it to x-code and working through some of the config to get the iOS Spotify-SDK working with my project    

**Thoughts:** Having missed a couple of days because of a weekend away I was keen to jump back at the task of figuring out how to use an SDK in a react-native app. The documentation for doing this with react native projects isn't as specific as I had hoped and relys more on xcode than I'm used to with developing web-apps. But made some good progress and it's just a case of being a real detective to find out where config has to go and navigate the environment I haven't used before. Also some of the documentation seems out of sync with how xcode looks now so potentially it's out of date and things are in different places now too making things a bit more difficult. 

**Link to work:** 
[Restart of React-Native App](https://github.com/tobywinter/playthru-mobile/commit/30d8c05a181bb4b34b0a5603308624ec55e11494)
[Adding config to iOS Section](https://github.com/tobywinter/playthru-mobile/commit/901f06abebc4cc0e35f1f4ff6e8101c5952a9745)

### Day 6: November 6, 2019
##### 

**Today's Progress**: Read up on the difference between npm and npx and why they are useful in different situations. More refactor practice.    

**Thoughts:** Worked on a private repo today but the main learning was investigating what the difference between the npm/npx commands are as they often seem interchangable and they are the kind of command we tend to run without querying how they work or what they do just because the docs on how to set something up tells us to. 

### Day 7: November 7, 2019
##### 

**Today's Progress**: Added error handling for non-premium spotify accounts using Playthru - extended graphql layer to return premium/free status and added an instructional page to handle the situation. 

**Thoughts:** Simple changes today - nothing too challenging - but only because of our experience learning the ins and outs of graphql and the spotify api over the past few months. Great how practice and experience speeds these things up! 

**Link to work:** [Playthru](https://github.com/jackbittiner/play-thru/commit/f3a3ebd8d6694310cc41b1729f943a95f6ceeced)

### Day 8: November 8, 2019
##### 

**Today's Progress**: Solved first Python codewars code kata - [Equal Sides Of An Array (Python)](https://www.codewars.com/kata/equal-sides-of-an-array/python)

**Thoughts:** I wanted to start improving my Python skills in preparation for a new project. Working through the challenge was great problem solving practice and improved my knowledge (in python) of a number of array/list methods, the convention for variable and method naming / definition, how to import a python module (e.g. math), and some built in python methods (e.g. print, sum, len, range) and while & for loops. 

**Link to work:** [Kata Solution](https://www.codewars.com/kata/reviews/567ad7a5e9a74b5cba000036/groups/5dc76d8fcb9f1900013b2fd2)


### Day 9: November 9, 2019
##### 

**Today's Progress**: Refactored yesterdays Kata solution - [Equal Sides Of An Array (Python)](https://www.codewars.com/kata/equal-sides-of-an-array/python)

**Thoughts:** After reading a couple of the solutions to yesterdays Kata I realised there were some handy points of syntax in the range function e.g. it starts at 0 by default. And the array slicing colon sytax also had handy default for beginning and end meaning I didn't need to specify those either. Was great really digging down into the other solutions as it helped me see the thinking behind them and simplify my own. 

**Link to work:** [Refactored kata Solution](https://www.codewars.com/kata/reviews/567ad7a5e9a74b5cba000036/groups/5dc84d6ba613a800013fc43c)



### Day 10: November 10, 2019
##### 

**Today's Progress**: Continued working on Python Kata's - completed this [Array.diff codewars kata](https://www.codewars.com/kata/equal-sides-of-an-array/python)

**Thoughts:**  Discovered and implimented a List Comprehension which is pretty different to javascript syntax but not too tricky to grasp once some of the equivolancys are made between that and for/if/filter functions in JS/Ruby. Somehow managed to impliment a very idoimatic answer which was satisfying. On route to that solution I explored Collections, Lists and Sets which all have unique behaviors I'm sure I'll learn more about as I continue. 

**Link to work:** [Python Array Diff Kata Solution - Codewars](https://www.codewars.com/kata/reviews/5520ac91933cd0a1560002d2/groups/5520cb79ecb433d4890003a0)
