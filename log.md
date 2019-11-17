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

**Today's Progress**: Continued working on Python Kata's - completed this [Array.diff codewars kata](https://www.codewars.com/kata/array-dot-diff/python)

**Thoughts:**  Discovered and implimented a List Comprehension which is pretty different to javascript syntax but not too tricky to grasp once some of the equivolancys are made between that and for/if/filter functions in JS/Ruby. Somehow managed to impliment a very idoimatic answer which was satisfying. On route to that solution I explored Collections, Lists and Sets which all have unique behaviors I'm sure I'll learn more about as I continue. 

**Link to work:** [Python Array Diff Kata Solution - Codewars](https://www.codewars.com/kata/reviews/5520ac91933cd0a1560002d2/groups/5520cb79ecb433d4890003a0)



### Day 11: November 11, 2019
##### 

**Today's Progress**: Continued working on Python Kata's - completed this [Format a string of names](https://www.codewars.com/kata/format-a-string-of-names-like-bart-lisa-and-maggie/python)

**Thoughts:** As much as it's a little weird to be solving simple problems like this - there's no doubt that I'm learning a lot about the basics of Python from each one. The little python I've written before has been primarily through passing parameters to various fairly usable API's to run as a script so didn't involve any kind of data manipulations like loops / arrays, filtering, reducing and if statements etc. I know how to do this stuff in javascript and the logic is the same, but it's good getting comfortable with it in a new language.

**Link to work:** [Format a string of names from a Dictionary of names - Codewars](https://www.codewars.com/kata/format-a-string-of-names-like-bart-lisa-and-maggie/solutions/python/me/best_practice)

### Day 12: November 12, 2019
##### 

**Today's Progress**: Learnt about and added a Prefetch performance enhancement using ApolloGraphql in Playthru to increase the response time. 

**Thoughts:** It's great when you learn something that will stick because you applied it - and it will also be useful as something to think about going forward. Apollo graphql provides an instance of the client when you do a query - which you can use to run a query early - prefetch the data that you predict your user will want and CACHE it. And then if you're right and they take the action you expect - the datas already in the cache and the response can be almost instant. No waiting! Docs here [Imporving performance with prefetch](https://www.apollographql.com/docs/react/performance/performance/#prefetching-data)

**Link to work:** [Playthru performance enhancement](https://github.com/jackbittiner/play-thru/commit/d670459052387e46c96004fc37ae63e98c9c52bd)

### Day 13: November 13, 2019
##### 

**Today's Progress**: Completed another python kata - recursive function to find length. 

**Thoughts:** Still getting to grips with the basics of the language which are easy to forget when I haven't used it much. 

**Link to work:** [Fun with lists - length](https://www.codewars.com/kata/581e476d5f59408553000a4b/solutions/python/me/best_practice)

### Day 14: November 14, 2019
##### 

**Today's Progress**: Solved [Form the Minimum codewars kata in python](https://www.codewars.com/kata/form-the-minimum/python)

**Thoughts:** Keeping my practice simple as coding at work has been heavy lately - still practicing basics and learning how to use basic functions in python - the variations between the versions means that sometimes finding out how to do simple things from docs is harder than it should be. Took a while to figure out how to join the list of integers when it felt like it should have been the simplist element of the problem to solve. 

**Link to work:** [Form the Minimum - solution](https://www.codewars.com/kata/5ac6932b2f317b96980000ca/solutions/python/me/best_practice)

### Day 15: November 15, 2019
##### 

**Today's Progress**: Solved [Filter out the geese](https://www.codewars.com/kata/filter-out-the-geese/python)

**Thoughts:** Solved this one in both javascript and python - simple stuff - but still learning fundamentals. This one I learnt about a property of Sets which allows you to get the difference between two sets - however it does not return the results in a reliable order - so in this case I had to use a simple List Compression instead. 

**Link to work:** [Filter out the geese](https://www.codewars.com/kata/57ee4a67108d3fd9eb0000e7/solutions/python)


### Day 16: November 16, 2019
##### 

**Today's Progress**: Solved [Descending Order kata](https://www.codewars.com/kata/descending-order/python)

**Thoughts:** Still working on python fundamentals, today contending with the problem of splitting a number into individual integers manipulating it, and then turning it back into an integer.

**Link to work:** [Descending Order kata solution](https://www.codewars.com/kata/5467e4d82edf8bbf40000155/solutions/python/me/best_practice)


### Day 17: November 17, 2019
##### 

**Today's Progress**: Solved [Equal sides of an array kata - javascript](https://www.codewars.com/kata/equal-sides-of-an-array/javascript)

**Thoughts:** Thought I would try solving one of the katas i've only solved in python in javascript - I feel like some of the algorithmic understandings of the solutions are good to explore in different languages in order to fully understand what they're doing - by solving it in two different languages its kind of cementing that I understand what I'm doing not just accidentally figuring out the answer without getting the inner workings of a solution. Also I don't want to forget my JS chops - I had to quickly remind myself what a vanilla JS `for` loop looks like because I've been writing so many in python recently. 

**Link to work:**
- [Equal sides of an array kata - javascript](https://www.codewars.com/kata/equal-sides-of-an-array/solutions/javascript/me/best_practice)

- [Very simple Beta kata - SpyText #1](https://www.codewars.com/kata/5dd1632d5ca66e0014e45a5e/solutions/python/me/best_practice)

- [Where my anagrams at? - Kata](https://www.codewars.com/kata/523a86aa4230ebb5420001e1/solutions/python/me/best_practice)
