# 100 Days Of Code - Log


### Day 0: April 04, 2023

**Today's Progress:** Added logic to change background color and make label text content match the new color value.

**Thoughts:** Watching too much tutorials makes the fact of coding without guidance really uncomfortable for me. That's why i want to start that challenge with small projects that i can manage and research on my own. Today i researched the basics of using DOM plus some tips about module (wasn't necessary but i felt eager to use modules and following that impulse felt like a nice idea) and managed to code the main logic of color flip the document's background color. It wasn't hard but took me more time than i expected. If anything i wish this challenge helps me getting a little faster at coding. 

**Link to work:** [Color Flipper](https://github.com/joanFaseDev/100-days-of-code-projects/commit/bdfc71ca11470bae9890601d7fef4de78c92b187)


### Day 1: April 05, 2023

**Today's Progress:** Added logic to switch color systems, to initialize a random background color when document is refreshed and to change the document's font color based on the overall intensity of the documen's background color. Also gave the document a proper styling.

**Thoughts:** I ended up spending more time on this project than initially planed because i wanted to add features that were new to me but felt manageable (converting hex colors into rgb ones, adapting font color to background's color overall intensity, ...). I think this 'let's try and we'll see' state of mind is something i want to develop during this challenge. I'll make a ton of mistakes that way and mistakes are good because you can learn from them. 
This project is now finished, i'm satisfied with the result and will take some time today to plan tomorrow's next project.

**Link to work:** [Color Flipper](https://github.com/joanFaseDev/100-days-of-code-projects/commit/9f3322f13c382ad0b4ed0992f3d8aca61fa1b1ff)


### Day 2: April 06, 2023

**Today's Progress:** I made a counter using vanilla JavaScript. A simple app where one can increment, decrement or reset the counter (by clicking on it). I added a very basic styling that automatically switch according to the counter being lesser or not to zero.

**Thoughts:** The whole project was basic, just simple DOM manipulation and a little bit of styling. I learned how to access CSS variables from JavaScript which is something i never tried before. Even if i knew where i was going with this app it still took me a couple of hours to finish it. Probably because i have a tendancy to try and read things along the way. I don't think that's a problem, i'll get faster with practice. What's important is consistency and trying new things. Tomorrow will bring both.

**Link to work:** [Counter](https://github.com/joanFaseDev/100-days-of-code-projects/commit/ecb2c80181b48fcb93be57a80147d33fd3006fef)


### Day 3: April 07, 2023

**Today's Progress:** I started an application taking a user input and checking if it's a palindrome, using vanilla JavaScript. The JavaScript part is as good as finished. I added a palindrome generator, mainly to help me debug my code, but ended up leaving it to help users lacking imagination (like me).

**Thoughts:** A few weeks ago, i wrote a function checking palindrome for codewars.com so i thought this project was going to be easy. Turn out i was wrong, my lack of knowledge on regular expressions cost me a lot of time and errors. Plus i used HTML elements i'm not familiar with like **details**, **summary** and **blockquote**, i had to double check on https://www.w3.org/ that i was using them properly. It was frustrating because i spend a lot of time reading when actually what i really wanted was to code. Which is stupid. Reading documentation/tutorial/guide is part of the learning curve and i'm clearly in the wrong for thinking that the time spend on it isn't worth it. I need to take my time and consolidate what i learn every day. Tortoise and hare, tortoise and hare...

**Link to work:** [Palindrome Checker](https://github.com/joanFaseDev/100-days-of-code-projects/commit/ebe51d89091c1a58019904e2ae749edf9e97d88f)


### Day 4: April 08, 2023

**Today's Progress:** Added stylesheet to the project plus some minor JavaScript corrections.

**Thoughts:** I finished the palindrome checker application and am pretty happy with the result. I experimented a bit with CSS and ended up using a cursive font for the app because it suited the theme. Usually i'm careful with this kind of font because if it is often pretty to look at it's also often 'unreadable'. I chose a font that in my opinion take the best of the two worlds. I only know the basics about CSS but for now it's enough. I don't want to try complicated animations yet because i want my main focus to stay on functionnality, not on render. I'll probably take some time to experiment with flexbox though, i think it's an incredible tool which can help create great layouts with little knowledge.

**Link to work:** [Palindrome Checker](https://github.com/joanFaseDev/100-days-of-code-projects/commit/ab18f79a594d8092f132f0f1f134e7840702c0c7)


### Day 5: April 09, 2023

**Today's Progress:** I started a To do List application using vanilla JavaScript. Html and JavaScript parts are almost done, currently one can create as many entries as needed, each entry can be cleared (meaning it is done) or removed (meaning one is giving up on it) throught its associated pair of buttons. I also included a random task generator for debug purpose.

**Thoughts:** I did a to do list a couple of months ago. It is a simple project but it requires basic understanding of the DOM, that's why i wanted to redo it before tackling bigger projects. That being said, i tried to add some features to push myself and refactor where it was possible. One of those features is the ability to drag and drop entries of the list. I just started reading MDN about it but i'm gonna try to implement it on this project. I feel pretty enthusiastic about it because it's completely new to me. 

**Link to work:**[To do List](https://github.com/joanFaseDev/100-days-of-code-projects/commit/edc6d7f91281f7a5f9e85b049066faf18abf067d)


### Day 6: April 10, 2023

**Todays Progress:** To do List application is finished. I added some simple styles and a few lines of JavaScript.

**Thoughts:** I didn't accomplish much today. After some reading, i now have a basic understanding of the drag-and-drop API but unfortunately i didn't find any way to use the feature in my application without changing its global design. After some thoughts, i concluded that it was better to use the API on a project centered arount it from the get-go (good news is i already have an idea). Without the drag-and-drop, i didn't have much to add except some styles. I try to innovate but my understanding of CSS is weak, average at best and things like 'animated transition of background-color from left to right' are a little too complicated for me at the moment. I think it's ok thought, if i practice a little each day i'll gradually become better. I like to think that at the end of that challenge i'll laugth at some struggles i had along the way.

**Link to work:**[To do List](https://github.com/joanFaseDev/100-days-of-code-projects/commit/77ba6d34a18a010d74b1dd699efffc63c1797541)


### Day 7: April 11, 2023

**Todays Progress:** I started an application, Word Unscrambler, using vanilla JavaScript that generate a random word (from a predefined list) related to programming concepts, shuffle this word's letters and render them to the screen with as draggable entities. The goal is to drop them in another box in the correct order. The generating random word and shuffling its letters part is done, i made the letters draggable but i still need a lot of work on the drop containter.  

**Thoughts:** This project is really interesting because there's a lot to learn from it. The way to use the drag-and-drop API correctly, the Fisher-Yates algorithm (used to shuffle the letters) that i used but didn't fully understand and the destructuring assignement syntax from JavaScript that is also used in Fisher-Yates and that i also have troubles with. I'm gonna stick to the MDN docs for this project and try to understand as much as possible. 

**Link to work:**[Word Unscrambler](https://github.com/joanFaseDev/100-days-of-code-projects/commit/91c94fccb9ff576d0797e6d8f681808b1b247de4)


### Day 8: April 12, 2023

**Todays Progress:** I added the 'droppable' part of the application logic. Letters can now be drag from their parent paragraph into the 'dropzone' paragraph. I also implemented a victory condition of sort. If letters are drop in the correct order (meaning if the end result is stricly equal to the random word chosen) then a congratulation message appears with some styling for juice. Speaking of styling i also implemented media queries with mobile and desktop design.  

**Thoughts:** I left this project half-finished. I started a job today (i'll be working five days a week during a month, nothing to do with programming) and the lack of time/rest made it difficult to focus on what i wrote yesterday. I still did enough for the application to be functional and visually decent. Unfortunately, there's still big flaws in my code but i feel refactoring/correcting at this point wouldn't accomplish much. Instead i will try another project and leave this one in that state. I accomplish my primary goal which was using and learning the basics of the drag-and-drop API. I also had good opportunities to work with the DOM API which is always a good thing at my level. I'm gonna try to gain some rest and come back with more ideas for projects. I also need to work on my schedule so i can code more effectively. 

**Link to work:**[Word Unscrambler](https://github.com/joanFaseDev/100-days-of-code-projects/commit/567ab412da5ae53913cf558b6dd5a722cc803eb2)


### Day 9: April 13, 2023

**Todays Progress:** I started an application requesting data from an API (Random User Generator API) and displaying this data on screen. I finished the JavaScript part, 5 random users are requested when the page is loading and one user is displayed on screen at a time. Through buttons and listener, one can go to the previous user, the next one or generate a new user which is then added to the existing pool of users.

**Thoughts:** Having less time to code, i tried to focus on important concept / feature / technology i could learn and test rapidly. Ajax seemed like a good choice. I started simple, something i knew i could manage with the few hours i've currently have per day. Also something i could built upon. The present application only request data, next time i'll try an API where i can actually send data to the server. No yet there though. First, let's finish this one!   

**Link to work:**[Random User Generator](https://github.com/joanFaseDev/100-days-of-code-projects/commit/0c25d747a893e949cc281ab17fef66cf253b4fa5)


### Day 10: April 14, 2023

**Todays Progress:** I finished the Random User Generator application. I added some styling and change a few lines of JS.

**Thoughts:** I don't feel like i accomplished much today. Probably because i only used CSS. Not to say the language is poor or not interesting, quite the contrary actually. But he thing is i know little about CSS so my stylesheets often look the same from one project to another which made me feel depressed on that particular project (more precisely my inability to create good styles). That's something i plan to work on in the futur but it'll have to wait a little. Good thing is: tomorrow's Saturday which means i'll have more time and rest to work on projects!   

**Link to work:**[Random User Generator](https://github.com/joanFaseDev/100-days-of-code-projects/commit/84bdd2931bdd8696efec188d909fc985833e1286)


### Day 11: April 15, 2023

**Todays Progress:** I choose to learn JavaScript properly to improve my coding ability and hopefully develop better programming skills and habits. I choose to focus on the website [JavaScript Info](https://javascript.info/) which is a ressource i'm fond of. Their articles are well written without being suffocating which can be the case for MDN (another source i consult daily). I also started a Multiple Choice Questions application using vanilla JavaScript. The question's source and the way to render the questions and their answers to the screen (through integration in the DOM) have been wrote. I now must write the logic to evaluate the user's answers and increment or not its score.

**Thoughts:** I mainly did research today which is something i always feel bad about because the time spent 'not coding' seems like 'unproductive' to me. It's stupid of course, smart planning makes you gain time in the long run and help boost your productivity, not the opposite. Following a MDN's article on goals and learning curve, i started writing my objective for the futur (getting a front-end developper job) and how i could accomplish it. While i was writing, i realize i never really wondered what kind of developer i wanted to be or what exactly do i prefer in developement. I think i need to answer these questions first before finishing my plan.

**Link to work:** [Multiple Choice Questions](https://github.com/joanFaseDev/100-days-of-code-projects/commit/ce47c55103b5b78ad3fe6d8b6f7b5e4a1577a0c3)


### Day 12: April 16, 2023

**Todays Progress:** I added some features to the Multiple Choice Questions application. Now the content of the web page is automatically reset after each question. Then if there's still question unanswered, the next question is displayed on screen. If all question have been answered, a summary i'm still working on is suppose to be displayed on the page.

**Thoughts:** I didn't progress that much on the application but i'm satisfied with what i wrote, i think i'm going in the right direction. I'm not using any new knowledge on this particular project but i'm still working on my problem solving skill and it feels like valuable work. Aside from that, i keep reading [JavaScript Info](https://javascript.info/)'s content. Hopefully, the next projects will capitalize on what i picked up along the way.

**Link to work:** [Multiple Choice Questions](https://github.com/joanFaseDev/100-days-of-code-projects/commit/f6a7dbd7efb9f9620490c687094d93894ee53957)


### Day 13: April 17, 2023

**Todays Progress:** The summary part of the Multiple Choice Questions is done. I also added a complete reset of the application if user want to start the challenge again. I started the CSS part but there's still work to do. I also need to add more questions to the pool so i'll probably focus on that tomorrow.

**Thoughts:** I could barely code a couple of hours today but still there's real progress on the application and i think it might be over tomorrow depending on what i can accomplish before going to work (it's the time where i'm the least tired and the more focused). Having a job makes this 100 days challenge more complicated yet i feel i'll be ok as long as i can do my best every day. Even two hours of coding daily is fine, what matters is consistency. That's what makes the difference in the long run.

**Link to work:** [Multiple Choice Questions](https://github.com/joanFaseDev/100-days-of-code-projects/commit/41170f1e76388de449369e3b210b037cbb3b5879)


### Day 14: April 18, 2023

**Todays Progress:** I finished the multiple choice questions application. I added some styles plus a few entries to the question pool.

**Thoughts:** I kinda rush the last part of the application (a bit of JS logic but mainly the CSS part). Having so little time to pratice coding made me eager to work on various projects and so i felt compelled to finish this app and start something new. It's kinda disapointing but in the end i think i did ok. The app would have definitely benefit from a few more hours of work but the logic part is fine. For once i think i did something kinda scalable and that's definitely an achievement i can be proud of. Also i learned that styling a table isn't as easy as it seems. I will definitely look into that in a near future. 

**Link to work:** [Multiple Choice Questions](https://github.com/joanFaseDev/100-days-of-code-projects/commit/6999fd0af124fc51d388a5cd0f68c01d5a8b7ad4)


### Day 15: April 19, 2023

**Todays Progress:** I started a vanilla JavaScript application taking a date plus time as input and outputting a countdown between the current time and the input time. I read a tutorial plus part of the MDN documentation on the Date object. I wrote the logic to change the user's input into a valid date format then convert this date into days, hours, minutes and seconds between the current time and the date. 

**Thoughts:** For this application, i'm coding along a written tutorial. Initially i was scared that relying on guides/tutorials prevent me from searching/developping my own solutions but i made a point of testing/refactoring what i read and in the end, i find the process rather enjoyable. It's a good opportunity to learn from more experienced developers and hopefully pick up some valuable informations concerning clean code, programming, ...
Since i started this challenge, i did almost all projects on my own so it's really refreshing to see ways of solving problems different than my own. 

**Link to work:** [Countdown](https://github.com/joanFaseDev/100-days-of-code-projects/commit/3249decc97afe613f6a64af13f7aae250770c384)


### Day 16: April 20, 2023

**Todays Progress:** Countdown application is almost over. The JS part is finished meaning the countdown is now displayed and updated on screen. There's also the possibility to cancel a countdown before its end or to start another one once a countdown is finished. 

**Thoughts:** Today was really interesting. I learned about the setInterval() function and decided to instantly like it. It's easy to use and open far too many possibilities to count. I also want to try a 'new' method of learning where i basically make pair of projects: the first one in a guided 'safe' environment (throught tutorials) and the second, based on the first's knowledge, where i code alone and must think by myself. It seems like a good method of 'learning then checking if i understood correctly'.  

**Link to work:** [Countdown](https://github.com/joanFaseDev/100-days-of-code-projects/commit/8fa54a56f595d818f2014a28926900f41ec2cbbd)


### Day 17: April 21, 2023

**Todays Progress:** Countdown application is finished. I added enough styles to make a decent mobile and desktop responsive design. I also corrected a problem cause by the setInterval() function, more precisely the idInterval value used with clearInterval().

**Thoughts:** This project was really interesting. Following a guide gave me good tips on clean code and let me discovered useful features like the setInterval() function or more generally how to convert milliseconds into seconds, minutes, hours and days. I also learned a good use of the modulo operator!

**Link to work:** [Countdown](https://github.com/joanFaseDev/100-days-of-code-projects/commit/5986005fbd0024bcc1ab5f59ea6fb9c5228bfbfb)


### Day 18: April 22, 2023

**Todays Progress:** I started out a Pomodoro application mimicking the one from the website [Pomofocus](https://pomofocus.io/). This time, i tried to do things smartly by writing my process before actually coding anything. I also try to write code more 'spontaneously' alterning between HTML, CSS and JavaScript to gradually 'shape' the app (usually i do the appearance at the end when all is functional). I don't know if it's good or bad but i'll probably have a clue by the end of this project.

**Thoughts:** This project will probably be the biggest one yet. There's a lot of features to test and implement so i'll probably work on it for quite some time. I'm using Pomofocus as a visual reference as i quite like this website and find it well designed. Looking at it more closely, there's a lot of small features / styles i never take notice of before (e.g box-shadow on a button being pressed, a tiny icon indicating a task is now completed, ...). It's kind of cool to rediscover under new lights something you thought you were quite familiar with.

**Link to work:**[Pomodoro](https://github.com/joanFaseDev/100-days-of-code-projects/commit/16760553f2f3b7b024107fb2ec0d8ea69a3a2b59)


### Day 19: April 23, 2023

**Todays Progress:** I implemented the Short Break state that is automatically executed at the end of a Pomodoro countdown. I also added a visual update of the page when the user is on short break. I've rewritten the to-do list of the application to make things clearer for the following days.

**Thoughts:** I'm quite satisfied of what i implemented today or more precisely how i implemented it. I listed what i wanted to accomplish and break down each task into smaller steps. Written down my process before actually coding anything made me feel way more in control than usual. Of course, i wasn't always right and sometimes things turned out wrong but at the very least i had a plan to follow which is both reassuring when coding and extremely enjoyable when the coding is done and what was written is actually working correctly. I like coding this way so i'm gonna stick to it from now on.

**Link to work:**[Pomodoro](https://github.com/joanFaseDev/100-days-of-code-projects/commit/34ee601fd8a5bab63680fec86cd2154fce8291d6)


### Day 20: April 24, 2023

**Todays Progress:** The application now smoothly transition from 'Pomodoro' state (25 minutes of work) to 'Short Break' state (5 minutes of break) then, every 4 Pomodoro, to 'Long Break' state. Each state has its own visual theme and every time a countdown end, a ring sound can be heard.

**Thoughts:** I keep writing down the tasks i must work on then try to divide these tasks into smaller units. I really want to make this process a habit as i truly think it'll will make things so much easier in the long run (and not only as a developer as this skill can probably be applied to a lot more areas). I'm progressing well on the application but today i copied/pasted a lot of code and i feel that some refactoring will soon be needed. I really need to learn how to use classes and objects in JavaScript, my code always looks like a giant dish of spaghettis and it's getting more and more troublesome as project goes. Next weekend, i will also learn how to use branches in git. My projects becoming bigger, branches will soon be very valuables.

**Link to work:**[Pomodoro](https://github.com/joanFaseDev/100-days-of-code-projects/commit/5a3eadeb3951b41feffdcca99e0b9e4e20384f3b)


### Day 21: April 25, 2023

**Todays Progress:** I implemented a new feature to directly choose the 'state' of the application, meaning the type of the next countdown (between Pomodoro, Short Break and Long Break). It's accessible through a set of buttons located at the top of the countdown. Pressing one of the three buttons also update the document's style.

**Thoughts:** I think i'm gonna rewrite several parts of the application. My messy code is one thing but i feel the way i built this project is wrong. Adding the new feature was difficult because i couldn't built on what i previously established. It seems i didn't plan well enough so the best thing i can do is recognize my poor judgement / building skill and try to correct what i can as best as possible.

**Link to work:**[Pomodoro](https://github.com/joanFaseDev/100-days-of-code-projects/commit/f735fa5fe9cabfbd26b59cd96349a2ab3b429300)


### Day 22: April 26, 2023

**Todays Progress:** I created a new script and rewrote / refactored most of the logic. Apart from the pause button and its behavior, all features have been reimplemented.

**Thoughts:** While i clearly lack the knowledge to rewrite efficiently my previous code, i'm somewhat satisfied of what i accomplished today. It's far from perfect but still way better than my previous implementation, it's less verbose and more reliant on functions. I also tried to make my code more scalable by writing function that can be use in more than one case. Overall, i found that refactoring is acutally a pleasant experience and  probably a very good exercice for anyone trying to improve its code writing skill. 

**Link to work:**[Pomodoro](https://github.com/joanFaseDev/100-days-of-code-projects/commit/678ae946d4047b6ac1f21fc5dd13bc6dc282242b)


### Day 23: April 27, 2023

**Todays Progress:** Refactorization is now complete. The application is functionnal which is more than it was in the previous version. I added the logic/style for the start/pause button plus the logic for the change of mode when a countdown ends.

**Thoughts:** The application is still missing some juicy features (ring sound at the end of a countdown, a task manager,...) but the default functionalities are here and i think it's possible to build on it. Initially i planned to keep working on the app, mainly to add the task manager, but now that i have something working i must confess that i'm eager to work on something else. Maybe something smaller where i can actually work on my basics. If anything, this project made me realize that programming language isn't worth much without proper planning and smart decision making. To acquire that, i need knowledge of my pairs and small projects i can test it out!  

**Link to work:**[Pomodoro](https://github.com/joanFaseDev/100-days-of-code-projects/commit/46ebc78a40800677d51a9236d467b15e51471857)


### Day 24: April 28, 2023

**Todays Progress:** I started a new application called Party Games. The end goal is to chain three small scope games (like the Hangman game) so two users can compete together. 

**Thoughts:** I'm not really set on the how and what of this application. I just wanted a project i could use to test out what i'm currently learning on [JavaScript.info](https://javascript.info/). My goal with this project is to focus on writing clean code and developping my problem solving skills. It's the last day of the week (which mean my fatigue is at its peak) but tomorrow i'll have a more concrete idea of the direction i want to go with this application.   

**Link to work:**[Party Games](https://github.com/joanFaseDev/100-days-of-code-projects/commit/3eccf2e6caed8f827cb19c1646bfb95b832adfc6)


### Day 25: April 29, 2023

**Todays Progress:** I created a new project dedicated to the proper learning of JavaScript (through the website [javascript.info](https://javascript.info/)). I also started coding the logic for the Hangman game of the Party Games project. For now, a random word is fetched from an API and several divs are created, each containing a letter from the random word. 

**Thoughts:** Lately i realized my learning plan is a mess. More accurately, i don't have an end goal. I wish to get a job as a developper but i didn't really research the kind of skills needed to get it. I think that realization in itself is a progress. Once i figured out the skills needed, i'll research projects that are using theses skills. Projects that can actually help selling myself. For now, i'm learning JavaScript. I created a project where i can test examples and snippets in a small environment. I'm currently revisiting functions and it's really unbelievable how i can use them daily and know so little about them!    

**Link to work:**[Party Games](https://github.com/joanFaseDev/100-days-of-code-projects/commit/f9808fa4e5aa9f4d842a677909f14905bf54d389)


### Day 26: April 30, 2023

**Todays Progress:** I refactored some of the code i wrote yesterday to implement the Hangman game of my Party Games project. To draw a proper set of gallows / hangman, i started learning the basics of the Canvas API. I now know how to set up a canvas element and its context, how the canvas coordinates system works and how to use the rectangle functions properly. 

**Thoughts:** Truth be told, the Canvas API is probably not something i should spend a lot of time now. I don't think it's a useful skill to rapidly get a developer job... but it's fun! I had a blast this morning introducing myself to the API using the [MDN Tutorial on the subject](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial) and there seems to be a lot you can actually do with it. Plus, having an interest in game development and animation, i'm quite fond of this kind of technology. My plan for now is to learn the basics of the API, use it on the current project then try more complex things with it in the future. Writing this, i realize i planned a lot of things lately but rarely follows on it!     

**Link to work:**[Party Games](https://github.com/joanFaseDev/100-days-of-code-projects/commit/f6d667c9da2493a6bbfd2b0bca573dd3b4325cf6)


### Day 27: May 1, 2023

**Todays Progress:** I learned a bit more about the Canvas API, more specifically how to use paths. I finished the drawing of the gallows / hangman and set up a function to show step by step how the drawing was build. I'll use this function as a foundation to the hangman gameplay loop. 

**Thoughts:** I spend a lot of time on the drawing but i'm actually happy with the result. I now have a basic knowledge of the Canvas API. While reading an article on MDN, i saw a list of libraries for the canvas elements. I'll probably try to use one next time as the process of drawing with the default functions is very time consuming. And i'm saying that when what i drawn was actually very simple shapes!     

**Link to work:**[Party Games](https://github.com/joanFaseDev/100-days-of-code-projects/commit/c8ed0abb62ec5f689521debd101a60bfd09c152c)


### Day 28: May 2, 2023

**Todays Progress:** I added a field so users can send their pick plus an input validation to check for user's answer: one character only and it must be a letter.

**Thoughts:** I have a lot of difficulties navigating my code. I said it (and by 'it' i mean my spaguetti code) won't happen again but i guess i didn't act on it. Contrary to what i initially annonced, i will limit that project to the Hangman game. There's already a ton of stuff to do, no need to add more complexity on a code which is barely manageable as it is. For now, i'm going to add a few features and refactor as much code as possible so i can finish this smoothly.     

**Link to work:**[Party Games](https://github.com/joanFaseDev/100-days-of-code-projects/commit/7517254cc5bff96c45a4e56236be7a177b74622c)


### Day 29: May 3, 2023

**Todays Progress:** I focused on two things. First, i refactored most of the application's functions. I rearrange them in calling order and i tried to redefine each function to do one task while renaming the ones that didn't seem explicite enough. Second, i added a feature at the start of the application to get the player's names, check their format, store them then transition to the game's core loop. 

**Thoughts:** I refactored as much functions as possible. It's not ideal but it's still a huge improvement compared to yesterday. The code is now clear enough so that i can finish this application without losing too much time. I think i'm slowly getting better at writing 'decent' functions ( by that i mean functions with a clear name and focused on one task). That's the impression i have anyways.     

**Link to work:**[Party Games](https://github.com/joanFaseDev/100-days-of-code-projects/commit/cdf4e1d91d5047ae41c33109810d504516325647)


### Day 30: May 4, 2023

**Todays Progress:** I added logic to sort player's answers between valid and unvalid one. Previous answers are also stored in valid/unvalid pools. Finally i integrated a feature to automatically switch turn between players every time an answer is send.

**Thoughts:** The script have now more than 800 lines of code which makes this application the 'bigger' i've done until now. This size is a problem though, i lose a lot of time double checking my code even with dual screen. This morning, i spend 20 minutes on a simple error caused by a function i created twice. Turned out that the one being called in that case is the one being declared last. It's logic but it never happened to me before so i was still surprised. This project is a nest of mistakes. That's good, i'll learn a ton from it!     

**Link to work:**[Party Games](https://github.com/joanFaseDev/100-days-of-code-projects/commit/955fddad27eb3a13285509c2f26d6486fab84878)


### Day 31: May 5, 2023

**Todays Progress:** I added a score system which reward good answers and penalise the wrong ones already proposed. When a penalty occurs, a warning is automatically displayed. I also added a color system plus an array of the hangman's images to the game manager object. Every wrong answer is followed by a display of the 'current frame' registered by the game manager. At the end of the round, if the current frame isn't the last one in the array, the next one is loaded for the following round.

**Thoughts:** The end is near! I just noticed that i started this application more than one week ago which makes it the one i've worked on the longest (others will follow!). I did good progress today and, unless there's big complications ahead, i think i can finish this project tomorrow.      

**Link to work:**[Party Games](https://github.com/joanFaseDev/100-days-of-code-projects/commit/3bf810ddeef012202a773c7a3fb3a7a56f600b7f)


### Day 32: May 6, 2023

**Todays Progress:** I added a penalties count's feature to break a score tie. I also finished implementing the conditions to end game, either revealed the last letter of the mystery word or displayed the last image of the hangman. When the game ends, part of the document is removed to let some place for a message revealing both victor's name / mystery word and congratulating both players for their participation. 

**Thoughts:** As of now, i considered this project finished. There's a lot more i could do here but it has to end eventually and i'm satisfied with what i built here. This project was supposed to be a chain of three games but in the end i only delivered one. That being said, this game was the hardest i planned out of the three and i think a learned a lot from its development. I now give my functions a proper name reflecting what they do and only that. I also designed them to do one thing and if i need something else i just create another function. I will improve a lot more once i'll have learn to make them more scalable, more reusable depending of the circonstances. I also need to learn classes and modules as soon as possible. My JavaScript file on that project have more than a thousand lines of code and i don't want to work with that again. I need to abstract more, hide complexity so that i can better focus on just implementing each features without causing a ton of problems elsewhere.
I have a three days weekend so i'm going to take the time to think about the projects i have to do. No more random applications, i need to select projects that i can learn the most from. Projects i can actually use in a portfolio to secure a job!       

**Link to work:**[Party Games](https://github.com/joanFaseDev/100-days-of-code-projects/commit/859f33e0f3a1f514a78912cbb4352739089c2214)


### Day 33: May 7, 2023

**Todays Progress:** I didn't start any project today and instead focused on learning more about JavaScript objects. Yesterday, i reviewed some basics, how to create them using object litterals (constructors will be tomorrow) and how copying an object merely copy the reference to its address in memory (by opposition to primary data types which are copied in value only). Today, i studied the 'this' keyword. I knew it was primarily used to reference an object inside its own methods but there was a lot i wasn't aware of, the biggest discovery being that 'this' in JavaScript is evaluated at run-time! Which actually explains a lot of things now that i think about it... 

**Thoughts:** I'm trying to use my three days weekend efficiently. The goal is to come up with a well thought learning plan i can follow for the next weeks. To be honest, i'm still on it. Aside from that, i tried to think about a way to find a job in web development as fast as possible. My best friend recommended i build a good CV, motivation's letter and portfolio then send copies to all valid potential employers i can find. I wanted to learn how to use Figma (i think it's a good line on a front end's developer curriculum) so i started building my cv using it. The ideal would be to finish it in the next 24 hours so i can concentrate on the letter but i'm not sure i can do it...      

**Link to work:**[Learning JavaScript](https://github.com/joanFaseDev/100-days-of-code-projects/commit/c311cca8dc60e28f88a9e8325805e248357db80d)


### Day 34: May 8, 2023

**Todays Progress:** I learned the basics of the 'new' operator and constructor functions. What is the difference between creating objects through object litteral versus creating them through constructor functions, what happens in a constructor function when one explicitly returns a value,... 

**Thoughts:** Learning more about JavaScript is definitely a good thing, the more i read the more i realize i'm actually using a lot of JavaScript features without really knowing what happens in the back of the store. Best thing is that a part of what i'm currently learning can be applied to other languages (i'm trying to learn Lua, specifically for game development and the two languages have a lot of similarities) which helps a lot. I'm going to spend the rest of the day working on Figma, finding a new JS project i can start tomorrow and, hopefully, starting some real game development / prototyping. There's a lot to do, have to go!      

**Link to work:**[Learning JavaScript](https://github.com/joanFaseDev/100-days-of-code-projects/commit/48a4c07959f4cd2bc8208aef74fba09840e2a6c6)


### Day 35: May 9, 2023

**Todays Progress:** I started a Calculator application using vanilla JavaScript. Using HTML & CSS, i created a basic layout based on a mockup i did on Figma yesterday. I also experimented with JavaScript objects to implement the calculator logic.

**Thoughts:** Working with Figma to prototype an application's design early in a project seems like a good idea. Sure it takes some time and research but the design obtained that way works like a roadmap and make the HTML & CSS part way more simple.
I'm trying to use JavaScript objects on that project to apply what i learned this weekend. I'm not sure about the implementation yet but experimenting is a good way to learn so wait and see!    

**Link to work:**[Calculator](https://github.com/joanFaseDev/100-days-of-code-projects/commit/ab98426afec836ab4916f9c59b5237f184b8cc8c)


### Day 36: May 10, 2023

**Todays Progress:** I kept experimenting and finally set for a simple system where i keep a trace of the user's last input and base the application's entire logic on what this last input can accomplish combined with the current one. I implemented some basics like updating the calculator's screen with the user's input if it's a digit. I also started setting the social medias features which were added to the calculator's header. 

**Thoughts:** I experimented some more today. Erased as much lines as i created but i very much prefer taking the time to find a decent implementation early in the development. I don't want to spend hours in writing codes to finally hit a wall and realize i have to start on more solid basis. Most on my reflections were actually wrote on paper which makes me realize studying pseudo code or languages like UML may be incredibly worth in the long run.    

**Link to work:**[Calculator](https://github.com/joanFaseDev/100-days-of-code-projects/commit/ab98426afec836ab4916f9c59b5237f184b8cc8c)


### Day 37: May 11, 2023

**Todays Progress:** I implemented the logic related to the github and twitter icons using the load() method of the Window interface. I also finished the 'no previous key' use case and set a limit to the number of characters displayed by the Calculator (max 16). I started experimenting with ways to handle the calculator's calculations through three properties: leftOperand, rightOperand and operator.

**Thoughts:** There's too many flaws in my current impementation, i'm gonna start something different based on simple conditions focused on three properties, one for the first value (left operand) another for the second value and a last one for the operator between them.    

**Link to work:**[Calculator](https://github.com/joanFaseDev/100-days-of-code-projects/commit/2a6f3144f205db5b03bd52125844a8d0c7bd86d7)


### Day 38: May 12, 2023

**Todays Progress:** I rewrote a big part of the application to make it more manageable and more fit to handle the different use cases. The idea is that every time a calculator's key is pressed, three things are evaluated: is there a left operand? If yes, is there an operator? If yes, is there a right operand? Depending of the results, the same key will display a different result.

**Thoughts:** The way i'm currently coding this application is probably not the best but that's the one i found by myself and if i can finish this project with it i'll be satisfied enough. I kept using pseudo-code to wrote most of the logic i implemented today. I really enjoy this process, i found it useful because i'm someone who's pretty bad at 'thinking logically'. Write on paper helps me see the flaws in my design (not all unfortunately) and partially correct it which is a definite improvement!

**Link to work:**[Calculator](https://github.com/joanFaseDev/100-days-of-code-projects/commit/2dbedfabf3cd880ad38527a39e5bbb839139a71c)


### Day 39: May 13, 2023

**Todays Progress:** I wrote all use cases for configurations where the left operand and operator are known as well as when left operand, operator and right operand are known. The JavaScript part is finish and the application is functionnal. What's left is the CSS part.

**Thoughts:** The application seems to work fine. I tested various things manually but it's time consuming and far from being efficient. I'll probaby have to learn how to write and configure proper tests in the long run but it's not a priority yet. I reused lots of code near the end which is not ideal but i was eager to finish the JS part and play with styles. I'm probably gonna review some basics of HTML and CSS in the next days. As of yesterday, i'm unemployed and i wish to use my free time to 1) work on my CV and job research 2) list what i currently know and what fundamental web developer skills do i miss at this point.

**Link to work:**[Calculator](https://github.com/joanFaseDev/100-days-of-code-projects/commit/c6e3efa71a61ac8aa2b0319e0a8330628eef86cd)


### Day 40: May 14, 2023

**Todays Progress:** Added styles to make the application looks as similar as the mockup created on Figma. With this, the project is considered finished.

**Thoughts:** The task today was surprisingly easy. All i did was follow what i've done on Figma last week. At this point, i think i'm gonna include Figma (or any other apps dedicated to prototyping user interface) in my workflow for all futur projects. The gain of time is massive and the synergy between the application and CSS makes styling easier and more enjoyable.

**Link to work:**[Calculator](https://github.com/joanFaseDev/100-days-of-code-projects/commit/ad72a5b5f9e9f25eeb48ad8a9f73b9d9ffc19e0b)


### Day 41: May 15, 2023

**Todays Progress:** I set up the Anki application to try to learn/remember important web development concepts. I started the freeCodeCamp's responsive design course and i also begun working on my new project for the 100 day of code challenge: an images carousel.

**Thoughts:** The goal with working on memory through Anki is to slowly prepare myself for job's interview. I focus on concepts only, not languages syntax. The carousel project is something i thought of after realizing i actually enjoy working on and with UI interfaces. I wanted to reuse Figma, which i did, to set up the habit of doing a mockup every time i start a new project. I want something of a workflow and i want an application like Figma in it. This project will propably be centered on CSS but i'm gonna try to make some time to work on JavaScript daily. 

**Link to work:**[Images Carousel](https://github.com/joanFaseDev/100-days-of-code-projects/commit/bbace69960c9e551d1b46a98e2d6807ef41991e2)


### Day 42: May 16, 2023

**Todays Progress:** I created a repository dedicating to testing various ideas/technologies/concepts before implementing them in projects. I used it to practice the CSS position property that i may be using in the Images Carousel application.

**Thoughts:** I know that there's really good coding environment online (like CodePen) to create prototypes but i wanted to keeps things locked and controlled, not be bothered every time i decide to test a JS library (i'm gonna test [rolly.js](https://mickaelchanrion.github.io/rolly/) soon) and can't for compatibility issues. For now, i'm gonna try various things with **position**, **opacity** and **animation** properties, the last one being something i anticipate quite a lot!

**Link to work:**[Images Carousel](https://github.com/joanFaseDev/100-days-of-code-projects/commit/53a2cbaec88c9206aa0a136efb9ddbfc8dc676eb)


### Day 43: May 17, 2023

**Todays Progress:** I created a second demo for the images carousel project based on the mockup i built on Figma. I used the opportunity to experiment more with CSS **position**, **opacity** and **z-index** properties.

**Thoughts:** The second demo is basically what i planned as the current challenge's project but i don't feel like stopping there. I have fun working with JavaScript AND CSS. Working on visuals and design is something i really enjoy so i decided to expand the project's scope. I'm gonna do a set of images carousels with sightly different implementations and group them all on the same page. Then i'll add a nice scrolling effect to slide from one carousel to the next. It looks like a good project because i can train on nice scrolling and sliding effects that i will reuse on other projects like, for example, building my personal website! Well not now but in a, i hope, not so distant future!

**Link to work:**[Images Carousel](https://github.com/joanFaseDev/100-days-of-code-projects/commit/1071409732901fa1e576b946523c3153eff597c0)


### Day 44: May 18, 2023

**Todays Progress:** I added a navbar and configured it to smoothly scroll from one demo to another. I tried to use the [slick](https://kenwheeler.github.io/slick/) library but couldn't implement it properly. I started the data types part of the javascript.info guide on JS and am currently learning a lot of new things about number data type.

**Thoughts:** Today wasn't really the productive day i escompted but what really matters is being consistent and i did worked today so that's probably good. I lost a fair amount of time trying to implement the **slick** library. There's no doubt that i lack experience with APIs but i found the documentation lacking in clarity (again it's probably my fault in the end). Tomorrow i'll try another API with similar features. That way i can compare both implementations and maybe be a little less biaised.

**Link to work:**[Images Carousel](https://github.com/joanFaseDev/100-days-of-code-projects/commit/e7cf2bd830377313682bc2833873965bd4ceea89)


### Day 45: May 19, 2023

**Todays Progress:** I created an images slider using HTML, CSS and JavaScript. I learned many useful CSS properties like object-fit, overflow-x & overflow-y, scroll-snap-align & scroll-snap-type and the webkit pseudo-elements to style scrollbar.

**Thoughts:** I'm pretty satisfied with the slider i've built. There's no JS or CSS frameworks involved here so, even if i do end up using some later, at the very least i now know the theory and that kind of knowledge is never useless. I also understood one very important thing about the **object-fit** property, it only works if the img element have a defined size! I used the property in many occasions but never actually bother trying to understand why it only worked half the time...

**Link to work:**[Images Carousel](https://github.com/joanFaseDev/100-days-of-code-projects/commit/8917c93d7638124bc385bb23556823a9d8d2498b)


### Day 46: May 20 2023

**Todays Progress:** I finished the javascript.info part on number's data-type and created a repository to test various JavaScript libraries. I tested some features from the Flickity library, which is an API dedicated to carousels and sliders. I also progressed on the freeCodeCamp's course i started a couple of days ago.

**Thoughts:** I tried to do various things today and i achieved most of them (freeCodeCamp course, testing Flickity, adding front-end developer's interview questions to Anki, reading some article about SOLID principles) but didn't progress very well on the carousel application. Considering i already learn quite a lot on carousels and sliders since the beginning of this project, i'm gonna try to finish fast so i can focus on something else, something more relevant in term of 'finding a front-end developer job'! 

**Link to work:**[Images Carousel](https://github.com/joanFaseDev/100-days-of-code-projects/commit/9713d38d94c9b6697c11d0cf8a9837a175fa0649)


### Day 47: May 21 2023

**Todays Progress:** I used the Flickity library to create a webpage showcasing various artists work (from [Concept Art World](https://conceptartworld.com/)) through sliders and carousels. I used features provided by the API like autoplay, custom width and style for the slides, custom buttons, pseudo-element for the slide currently displayed on screen, ... I added a sticky navbar using what i learned of the position property this week.

**Thoughts:** I'm ending the images carousel project with this work. I ended up doing much more than what i initially planned and still it doesn't feel like enough considering what i read in the Flickity documentation. There was a lot of features i didn't explore starting by the JS ones i didn't touch at all. Globally, i didn't like this project and i know why. That's because i didn't have a precise scope and a plan to follow. Like i said, i didn't stick with what i have planned and ended up doing things randomly which is something i'm not confortable with. I like to plan things, stick to it and, once finished, plan more things on top of it or not. That's something i realized this week so i guess this discovery in itself is worth the trouble because now i know the recipe to create a confortable situation for myself!

**Link to work:**[Images Carousel](https://github.com/joanFaseDev/100-days-of-code-projects/commit/54db2d4a5b263267f5397e70ccc0519bade12417)


### Day 48: May 22 2023

**Todays Progress:** I started learning/reviewing CSS Grid and the CSS animation property through the MDN guides on these subjects. I did two demos and intend to make a couple more, just enough to have the basics of Grid and some notion of animations.

**Thoughts:** I decided to spend a couple of days on Grid and the animation property. The first is an incredible layout tool that have great synergy with flexbox (which i use a lot) and the second is greate to create visual appeal which is something i have a keen interest in. I intend to use this new knowledge to create an interactive quizz focused on layout and smooth transition.

**Link to work:**[Prototypes/CSSGrid](https://github.com/joanFaseDev/100-days-of-code-projects/commit/c21f418ba06b3824ee0e9040f176c1047290a1be)


### Day 49: May 23 2023

**Todays Progress:** I finished reviewing the basics of CSS Grid. I started training my problem-solving skills on [code kata](http://codekata.com) and I also finished the first part of freeCodeCamp's course on responsive design. The survey I produced was approved before I even got the time to style it though so I'll finish it tomorrow.

**Thoughts:** I took a decision a few minutes ago. I'm going to commit and complete two full courses on freeCodeCamp.com, the one on responsive design and then the one on JavaScript. The reason why is that I need to learn how to use a front framework (React, Vue, Angular, one of these) and I need it because I feel it'll be way easier to find a job if I can add and demonstrate that skill on my resume. But I want to be sure I have a decent level of HTML, CSS, and JS before focusing on frameworks. I can't wait forever so I'm setting up a clock. I commit to these two courses, finish them then framework, no more delaying. I don't know if that's a good plan but it's a plan and it's something I need. I wrote it before, I need a clear direction. So let's try this!

**Link to work:**[Prototypes/CSSGrid](https://github.com/joanFaseDev/100-days-of-code-projects/commit/1c1f1124763a60328a26137137e2e432c0f87007)


### Day 50: May 24 2023

**Todays Progress:** Spend all my available time on the survey's styling. It's decent but not responsive which is something i'm not satisfied with. I intend to correct that this weekend.

**Thoughts:** Styling this survey took me a lot of time but i learned a few things along the way. For example, the CSS at-rule **@font-face** that can load a custom font to display a text or the fact that radio and checkbox buttons are complicated to style because they're native elements of the browser.

**Link to work:**[Survey Form](https://github.com/joanFaseDev/100-days-of-code-projects/commit/95b591830bda39dd31ba0e254c4780e8d163e866)


### Day 51: May 25 2023

**Todays Progress:** I finished the rothko painting, the photo gallery and the nutrition label courses of the responsive design cursus.

**Thoughts:** I enjoy freeCodeCamp active teaching's style. The user is constantly coding, following instructions that are first very detailed and then later more concise. That way we are learning by repetition and then by memory. Also, I could gain a lot from their coding habit. The way they use CSS classes for example, as simple components dedicated to one task they can reuse on multiple elements, seems simple but efficient to me.

**Link to work:**[Responsive Web Design](https://github.com/joanFaseDev/100-days-of-code-projects/commit/55422d8181890bcd7f9923f78901aa3032b105b4)


### Day 52: May 26 2023

**Todays Progress:** I finished the quiz course of the responsive design cursus.

**Thoughts:** Today's course was focused on accessibility which is a main subject of modern web development. I'll remember the various meta tag and the informations they can provide (description, mobile viewport, character encoding, ...), the role attribute but also the placeholder attribute being somewhat bad for accessiblity.

**Link to work:**[Responsive Web Design](https://github.com/joanFaseDev/100-days-of-code-projects/commit/f5639290c27a9364b8d0b0a08f2a3a517347c824)


### Day 53: May 27 2023

**Todays Progress:** I created an image gallery to practice what I learned this week on accessibility and responsive design.

**Thoughts:** Today's focus was on responsive design and accessibility. I used CSS at-rules, media queries, and HTML meta elements to apply the basics I learned this week. freeCodeCamp's curriculum feels right and I'm enjoying the learning process but I also need to regularly practice aside from the courses to test my new knowledge. I feel I can progress faster that way. 

**Link to work:**[Responsive Web Design](https://github.com/joanFaseDev/100-days-of-code-projects/commit/c6ac9bebb463aaaf623da3161a0bffbae52dbe6a)


### Day 54: May 28 2023

**Todays Progress:** I updated the survey form I did a couple of days ago by implementing the basics of accessibility I learned since then. I also made the web page fully responsive and tried out the [Open Color](https://yeun.github.io/open-color/) CSS API.

**Thoughts:** To update the survey, I used the mobile-first design method where one builds the mobile design first before focusing on the desktop one. I like this method, it feels more intuitive to me and makes it easier to use CSS's natural responsiveness. I also read an article [UX best practices for developers](https://blog.openreplay.com/ux-best-practices-for-developers/) mentioning the Open Color API that is simple and easy to use, particularly once combined with a [Color Contrast Checker](https://coolors.co/contrast-checker/ffffff-188074).

**Link to work:** [Survey form](https://github.com/joanFaseDev/100-days-of-code-projects/commit/2f6d9a7a739b86c044a847eb873110cdfca8071f)


### Day 55: May 29 2023

**Todays Progress:** I created a tribute page dedicated to Shigeru Miyamoto as part of the freeCodeCamp's certification. I tried to include what I learned until that point on the subjects of accessibility and responsive design. I also completed the course asking to build a balance sheet.

**Thoughts:** I think that my web pages are less flashy than they used to be because I focus more on readability and accessibility than pure design. It's probably for the best though, don't matter how nice and alluring a product is if half of the customers can't use it.
The balance sheet course was kind of strange because I felt we could have obtained the same result without that many complications. Thinking about it, it was probably just an excuse to introduce some new CSS properties to us.

**Link to work:** [Tribute Page & Balance Sheet](https://github.com/joanFaseDev/100-days-of-code-projects/commit/0ae0bbc6fb1167965688402726b468ca795a3655)


### Day 56: May 30 2023

**Today's Progress:** I completed the Picasso painting and piano courses on freeCodeCamp curriculum. 

**Thoughts:** Both courses had a heavy focus on CSS's position property. This is great because I have difficulties keeping a page responsive when there are elements with absolute positioning. The next course is a certification one and apparently, I have to build technical documentation, looks fun!

**Link to work:** [Picasso & Piano](https://github.com/joanFaseDev/100-days-of-code-projects/commit/9f4419787caa4e3e3a888605243a05a86e4147a1)


### Day 57: May 31 2023

**Today's Progress:** I started a certification course on freeCodeCamp curriculum. The goal is to create fake technical documentation. The subject being free, I chose to target the game engine Construct 3 as I am currently learning it. The HTML part is pretty much done as all the content has been implemented. CSS is underway.

**Thoughts:** I used ChatGPT to generate the documentation content. I like using AI that way because it helps to deal with unsavory tasks so that one can better focus on learning what matters.

**Link to work:** [Technical Documentation](https://github.com/joanFaseDev/100-days-of-code-projects/commit/739ab7a8721f510d7677c4ac2010eaab4ab4e4a8)


### Day 58: June 01 2023

**Today's Progress:** I finished the technical documentation course on freeCodeCamp. The page is fully responsive and all user stories have been reached.

**Thoughts:** I'm satisfied with what I achieved on that challenge. I used a few colors (3) and, except for the transitions and some icons from [Font Awesome](https://fontawesome.com/), there's nothing fancy in the document. Yet, it is pleasant to the eyes, fully responsive, and relatively accessible (I used [::webkit-scrollbar](https://developer.mozilla.org/en-US/docs/Web/CSS/::-webkit-scrollbar) which is a feature considered **non-standard** by MDN as it doesn't work for every user). What I like about this project is that I can revisit it later to update it once I'll learn more about CSS.

**Link to work:** [Technical Documentation](https://github.com/joanFaseDev/100-days-of-code-projects/commit/e6ca21a13ea5c6d482cd9eb98249bd00325a868a)


### Day 59: June 02 2023

**Today's Progress:** I finished the City Skyline course on freeCodeCamp.

**Thoughts:** The goal of this course was to introduce CSS variables as well as gradients by building a responsive city skyline that switches from day to night based on the screen's current resolution. I enjoyed this project because there's much to learn from it, particularly the naming convention for classes and the unit lengths used to make the page responsive.

**Link to work:** [City Skyline](https://github.com/joanFaseDev/100-days-of-code-projects/commit/4e0ff7cbcad9169d952f7bca5a491304eeeab80d)


### Day 60: June 03 2023

**Today's Progress:** I finished the Magazine course on freeCodeCamp.

**Thoughts:** This course was an introduction to CSS Grid as well as various CSS functions specific to this layout method like repeat() and minmax(). I had to check MDN a few times because some pieces of information (e.g. what exactly is min-content?) were missing but overall the project was interesting and did a good job at laying out (did you get it?) the basics of Grid. I'm probably gonna use CodePen to practice setting up layouts with Grid, I'll also force myself to use it on the next projects. Grid is mandatory in modern CSS and I want to get good enough with it that I can combine Grid and Flexbox to create easy and intermediate layouts without much difficulty.

**Link to work:** [Magazine](https://github.com/joanFaseDev/100-days-of-code-projects/commit/14ae7d4a8403ea936db41600bf672fd82519ac3f)


### Day 61: June 04 2023

**Today's Progress:** I started the product landing page on freeCodeCamp curriculum. All the content is created and the HTML part is as good as done. Currently working on the hamburger navbar.

**Thoughts:** This project is a certification one which means I have some freedom to experiment on the subject, the layout, the design, etc... I am going to build a page focused on a fake game engine whose features were created by ChatGPT using the characteristics I provided. Using IA to generate content is something I'm going to integrate into my workflow. The gain of time is tremendous. Plus I have always found this kind of work time-consuming and very frustrating as it finally have little to do with coding.
On a separate note, I started the creation of a hamburger menu for the page. I'll display on it a game logo I created through Figma.

**Link to work:** [Product Landing Page](https://github.com/joanFaseDev/100-days-of-code-projects/commit/1cdd3f1c144cbe5bcc50021a38a5d9ca8d3bbb8c)


### Day 62: June 05 2023

**Today's Progress:** I finished implementing the hamburger navbar and did most of the CSS rules for the mobile design.

**Thoughts:** I created a Codepen account so I don't have to set up a new repository every time I want to test a feature. My first pen was the hamburger navbar which isn't as pretty as I would have hoped but is decent enough for now. I'll try to find some time next weekend to practice interactivity with only HTML & CSS.

**Link to work:** [Product Landing Page](https://github.com/joanFaseDev/100-days-of-code-projects/commit/1cdd3f1c144cbe5bcc50021a38a5d9ca8d3bbb8c)


### Day 63: June 06 2023

**Today's Progress:** I finished the product landing page project and got my validation from freeCodeCamp.

**Thoughts:** I rushed the project toward the end because I was depressed after I realized I used a lot of code duplication in it. It's entirely my fault, I worked the CSS rules from top to bottom instead of going from general rules to specific ones. Because I worked like that, it became increasingly difficult to progress among the many duplicated rules I created. The lesson is valuable though and this project taught me a lot so I'm satisfied overall. I'll probably upgrade this project in the future, there's a ton of improvements I could think of.

**Link to work:** [Product Landing Page](https://github.com/joanFaseDev/100-days-of-code-projects/commit/cc7b49e305ec27f9fda22f62709c804eacaa5431)


### Day 64: June 07 2023

**Today's Progress:** I completed the ferris wheel and the penguin courses on freeCodeCamp responsive web design curriculum.

**Thoughts:** I just had one more required project to complete to earn my responsive web design certification. The last project is about building a personal portfolio, which I am really excited about. It's great to practice all the things that were covered in this curriculum. I initially planned to pause a little and practice CSS Grid and animations before tackling that project but I changed my mind. I want to start working on it now so I'm going to follow that feeling!

**Link to work:** [Building a ferris wheel & building a penguin](https://github.com/joanFaseDev/100-days-of-code-projects/commit/e07e78d658980e9da6883358e72e15fd30231eec)


### Day 65: June 08 2023

**Today's Progress:** I started the portfolio project on freeCodeCamp. Most of the content is implemented, I've built the navbar and am currently in the process of creating a small avatar I can animate in the first section.

**Thoughts:** This project is HTML and CSS only so this portfolio won't be used for job hunting. Yet, I hope it can serve as a foundation for a more 'job research oriented' portfolio. For now, I'm going to implement in this one what I learned during the freeCodeCamp responsive web design curriculum.

**Link to work:** [Building a personal portfolio](https://github.com/joanFaseDev/100-days-of-code-projects/commit/41c838ae55d4e4cfa9836e5f83c282ea68918fa4)


### Day 66: June 09 2023

**Today's Progress:** I worked on some animations for the 'about' section of the portfolio. I learned how to bend text using only plain HTML & CSS.

**Thoughts:** I don't know where I'm going with these animations but I have fun doing them and coding wasn't particularly fun lately so I suppose it's a good thing. I learned that bending text in an HTML document isn't as easy as it seems. The recommended way is to use jQuery but this project doesn't include JS. There's also the possibility of using SVG but I'm not confident in manipulating vector. That leaves the time-consuming method of using the CSS transform property to translate/rotate each letter of each word. It's long but, again, I have fun doing it!

**Link to work:** [Building a personal portfolio](https://github.com/joanFaseDev/100-days-of-code-projects/commit/9552a27fe0af5663a2a97fbedb98530f1d75c216)


### Day 67: June 10 2023

**Today's Progress:** I'm halfway through the desktop design of the project section. I did a basic layout using CSS Grid and I added a couple of animations when a project screenshot is hovered.

**Thoughts:** Still having fun building this small portfolio of mine. I do most of the work on CodePen which is not as versatile and efficient that Visual Studio Code but is still pleasant to use. Plus I'm learning the shortcuts along the way which is nice because I want to familiarize myself with CodePen to make fast prototypes in the future.

**Link to work:** [Building a personal portfolio](https://github.com/joanFaseDev/100-days-of-code-projects/commit/ef7a417fe3c04835d4251d952955aff1a9fc875a)


### Day 68: June 12 2023

**Today's Progress:** I finished the personal portfolio project and got my certification from freeCodeCamp for completed the responsive web design curriculum.

**Thoughts:** By the criteria of freeCodeCamp, my personal portfolio project was indeed finished but, let's be honest, it wasn't responsive. Not in the least. I worked a lot on the animations but neglected to think about how said animations would react to different screen sizes. The answer is: bad. I mean really BAD. Using percentage length unit and absolute positioning turned out to be a mistake because it's really difficult to make the elements responsive if the layout wasn't planned properly... which I didn't.
So instead of spending a considerable amount of time trying to right my wrongs, I decided to validate my work to freeCodeCamp and start another curriculum while perfecting my HTML/CSS through small projects on CodePen. I think it was a good decision. At least, I know it's the least frustrating one.

**Link to work:** [Building a personal portfolio](https://github.com/joanFaseDev/100-days-of-code-projects/commit/86bbf6cee186eaa4402deedd19c7b3b0480bfd92)


### Day 69: June 13 2023

**Today's Progress:** I started and finished the freeCodeCamp course on JavaScript basics. I also did a couple of tests on CSS animations.

**Thoughts:** I reviewed JavaScript basics like data types, loops, conditions, objects, arrays, etc, ... I found the spacing of the JavaScript course quite good and, starting tomorrow, I'm going to learn/review ES6 concepts and more modern JavaScript stuff. There are a couple of courses I need to finish before starting the freeCodeCamp JavaScript projects. I want to start it as soon as possible but I don't want to rush the learning phase so it'll probably take a couple of days.

**Link to work:** [Cards Animation](https://github.com/joanFaseDev/100-days-of-code-projects/commit/f718371b06c3d013b5db0c743f611b938931fad7)


### Day 70: June 14 2023

**Today's Progress:** I started and finished the ES6 course on freeCodeCamp. I also started a tutorial project on CSS Grid.

**Thoughts:** Today's course took me a lot of time to complete but was really interesting. I discovered some ES6 features I wasn't aware of (classes, promises) and reviewed some I rarely use (spread syntax, Rest parameters, and destructuring assignments). I didn't have much opportunity to test all of these features but I'll force myself to implement them in the future freeCodeCamp JS projects. For now, I'm going to follow the course's next step which is RegEx!

**Link to work:** [CSS Grid Demo](https://github.com/joanFaseDev/100-days-of-code-projects/commit/0af4d10979640573423a9f56af9f8bd1dc369641)


### Day 71: June 15 2023

**Today's Progress:** I started the regular expressions course on freeCodeCamp.

**Thoughts:** I planned to finish the regular expressions course today but I spend a good part of the afternoon on one of the challenges that, honestly, felt out of place among the other ones. I'm the first to admit that I don't have a programmer mind (I'm working on it) and that I lack logic at times but even then I checked the comments on this particular challenge and apparently I'm not the only one who felt something was wrong. That being said, there are always people to whine so maybe I'm just frustrated and searching for excuses... 

**Link to work:** [Regular Expressions](https://github.com/joanFaseDev/100-days-of-code-projects/commit/0a415587db7fb0aac5b8a291cb56b6afd9d5b0eb)


### Day 72: June 16 2023

**Today's Progress:** I finished the regular expressions course on freeCodeCamp. I also did the debug course and I started the basic data structure one.

**Thoughts:** There are still no projects as I dutifully follow freeCodeCamp JavaScript curriculum. For someone like me that often move without an end goal, following a plan and not distracting myself with other things feel great and peaceful. For now, I'm enjoying the slow pace and trying to practice as much as I learn (I'm piling on Anki cards).

**Link to work:** [Regular Expressions & Data Structures](https://github.com/joanFaseDev/100-days-of-code-projects/commit/09235a443b17587892542f6e53e0a890c792862d)


### Day 73: June 17 2023

**Today's Progress:** I finished the basic data structure course on freeCodeCamp. I also am halfway through the basic algorithm scripting course.

**Thoughts:** I really like how the algorithm course is thought of. Most of what is asked, i already did on [codewars.com](https://www.codewars.com/users/joanFaseDev) but on freeCodeCamp you have to complete the challenge without using methods like reduce(), map(), or filter() which means each problem must be thought of step by step to reach the end goal. That course is designed to make users think like programmers and that's something I am lacking tremendously so I am really enjoying the process here.

**Link to work:** [Data Structures & Basic algorithm](https://github.com/joanFaseDev/100-days-of-code-projects/commit/2a74e75ea65c620193c59def035286249e64cf35)


### Day 74: June 18 2023

**Today's Progress:** I finished the basic algorithm course on freeCodeCamp. I also did more than half the content of the object oriented programming part.

**Thoughts:** The algorithm course made me realize how much I missed JavaScript (I used only HTML and CSS these last weeks). It also made me wonder what a backend developer's work looks like. I thought about becoming a front-end developer because that seemed more visual and appealing to me but now I'm contemplating trying a backend course so as to see by myself if I like it or not.
I also started the Object Oriented Programming course and am currently learning about prototypes which seems like an interesting subject.

**Link to work:** [Basic algorithm and Object Oriented Programming](https://github.com/joanFaseDev/100-days-of-code-projects/commit/825c12a7a790ef7e3a5cefa017644d94150d6802)


### Day 75: June 19 2023

**Today's Progress:** I finished the Object Oriented Programming course on freeCodeCamp.

**Thoughts:** Finishing the OOP course took me longer than I expected but it was interesting. I wondered about closure for a while now but today I learned that I used closer multiple times in the past. I just didn't know it was named like this. I discovered IIFE which means Immediately Invoked Function Expression and feels like something simple to use to solve complicated problems. I'm pretty sure I won't use it for a while. I also learned about mixins which, if I understood correctly, is a smooth way to pass behaviors (methods) when inheritance isn't the best solution. I learned/reviewed a lot and I hope it sticks to my brain because tomorrow I will begin the Functional Programming course and I smell trouble along the way!

**Link to work:** [Object Oriented Programming](https://github.com/joanFaseDev/100-days-of-code-projects/commit/fb2f23c582420eccc027415fc75e915c3750539c)


### Day 76: June 20 2023

**Today's Progress:** I started the Functional Programming course on freeCodeCamp.

**Thoughts:** Functional Programming seems like a deep and exciting subject. The dedicated freeCodeCamp course is well thought and the pace at which each concept is introduced is good. I spend a good amount of time reading articles about function types: pure function, first-class function, higher-order function, lambda function, etc
It will probably take a fair amount of time for me to really get the concepts of declarative paradigm and side-effects but I feel like I may be more interested in functional programming than in object-oriented programming. Time will tell I suppose.

**Link to work:** [Functional Programming](https://github.com/joanFaseDev/100-days-of-code-projects/commit/0563a9cad1392595799fed3ddd317a8f3e87131a)


### Day 77: June 21 2023

**Today's Progress:** I finished the Functional Programming course on freeCodeCamp.

**Thoughts:** So far, the Functional Programming course is one of my favorites on freeCodeCamp. I have learned a lot and had plenty of opportunities to practice reduce(), filter(), map(),... Tomorrow, I'll start the last course on algorithms and, after that, I'll have five projects to focus on to gain my JavaScript certification! 

**Link to work:** [Functional Programming](https://github.com/joanFaseDev/100-days-of-code-projects/commit/beffbb23d795a8e5b74cb1aef1d7acdfb7a1db84)


### Day 78: June 22 2023

**Today's Progress:** I started the Intermediate Algorithm Scripting course on freeCodeCamp.

**Thoughts:** I didn't accomplish much today as I had to deal with personal business. Today is also the day when I switch my OS. Goodbye Microsoft, hello Ubuntu! I had to stop working earlier as I expect that change to bring its share of troubles. More on that tomorrow...

**Link to work:** [Intermediate Algorithm Scripting](https://github.com/joanFaseDev/100-days-of-code-projects/commit/61d7a519717b58bebccad98a60d808e245d24098)


### Day 79: June 23 2023

**Today's Progress:** I continued the Intermediate Algorithm Scripting course and I am now halfway through it.

**Thoughts:** First and foremost, I managed to change my OS from Windows 10 to Ubuntu. It wasn't as simple as I have hoped and to be honest, I didn't quite get how I finally managed to succeed but the result is there, and it's good! Ubuntu is really pleasant to use. I have a lot to get accustomed to but with time and patience I'm sure I'll get the hang of it.
I set up the minimal requirements to work properly (text editor, ssh key, some extensions) and continued the algorithm course. One surprising thing I learned while solving a problem is that the 'y' character isn't always considered a vowel in English!

**Link to work:** [Intermediate Algorithm Scripting](https://github.com/joanFaseDev/100-days-of-code-projects/commit/f9c7c474774b234a92928954dfa7e6b1cbfdeec7)


### Day 80: June 24 2023

**Today's Progress:** I continued the Intermediate Algorithm Scripting course. I'll probably finish it tomorrow.

**Thoughts:** Today I racked my brain on mathematical algorithms. Things like primary number, factorial and Fibonacci always elude me and, it took me a lot of time to understand correctly what was asked in these exercises and how to solve them. I'm slowly getting better at it though.

**Link to work:** [Intermediate Algorithm Scripting](https://github.com/joanFaseDev/100-days-of-code-projects/commit/b56217be23b64b365561b353667c2d4c708540d2)


### Day 81: June 25 2023

**Today's Progress:** I finished the Intermediate Algorithm Scripting course.

**Thoughts:** I managed to finish the algorithm course while completing my personal goal: only use functional programming and const declaration. I think I did ok on most exercises except the last one which was focused on Kepler's third law of planetary motion. I didn't understand a single thing about the formula which makes me feel bad because succeeding without 'earning' is pointless to me.

**Link to work:** [Intermediate Algorithm Scripting](https://github.com/joanFaseDev/100-days-of-code-projects/commit/f54262989b0644b2ecd73d28ba0f05d1335159b1)


### Day 82: June 26 2023

**Today's Progress:** I started the projects required to obtain the certification in the JavaScript Algorithms and Data Structures curriculum. Out of the five projects, I completed the Palindrome Checker, the Roman Numeral Converter, and the Caesar's Cipher.

**Thoughts:** These JavaScript projects are enjoyable because they feel like an extension of the previous course. I could add HTML and CSS to each of these projects to make them more visual but I'm eager to start the next curriculum and the projects are only focused on JavaScript anyway. I have already coded a Palindrome Checker a few weeks ago but the two other projects were new to me and I had a ton of fun on them. I hope I feel the same with the last two projects. 

**Link to work:** [Palindrome Checker, Roman Numeral Converter & Caesar Cipher](https://github.com/joanFaseDev/100-days-of-code-projects/commit/61a1dac2effbaade5789d78d3a8d3e568ffef2e1)


### Day 83: June 27 2023

**Today's Progress:** I finished the Telephone Number Validator project and started the Cash Register project.

**Thoughts:** The fourth project was easy to complete with regular expressions but the last one, the Cash Register, makes me painfully aware of my poor problem-solving skills. I need to find an efficient way to practice it. 

**Link to work:** [Telephone Number Validator & Cash Register](https://github.com/joanFaseDev/100-days-of-code-projects/commit/ea7e367b5cebf52ef366e8bfd54f28c735466e25)


### Day 84: June 28 2023

**Today's Progress:** I am still working on the Cash Register Project. I'm currently looking for problem solving methods I can use right away.

**Thoughts:** When working on a project, I have the habit to start coding without having a plan. I have generally an idea and try to follow through but this kind of approach can't take me much further. More and more, I am confronted with projects/exercises I can't solve precisely because of my attitude. That is why I've started looking for methods/bits of advice I can transform into habits to help me solve any problem in the future. 

**Link to work:** [Cash Register](https://github.com/joanFaseDev/100-days-of-code-projects/commit/a0f0a31bef50d33d11403e0e5f6b97c3617fe50a)


### Day 85: June 29 2023

**Today's Progress:** I wrote a plan to solve the cash register project using pseudo-code and I am currently in the process of implementing it.

**Thoughts:** I read an article about training problem-solving skills by:
    1. Make sure to understand the problem correctly. What are the inputs and the outputs, create simple examples and more complex ones,...
    2. Using pseudo-code to devise a plan for the specific problem.
    3. Carrying out the plan. Don't try to optimize too soon, keep things simple and let what can't be solved yet for later.
    4. Improve the solution by refactoring or seeing how others solved that specific problem,...

I applied that method to the cash register project and, while I am still unsure of how it will turn out, I can at least say that writing about the problem helped me clarify what I am suppose to do. It also reveal problems that can easily be overlooked.

**Link to work:** [Cash Register](https://github.com/joanFaseDev/100-days-of-code-projects/commit/6a66e936254c553cfbd58ede1ec730bf66f2199b)


### Day 86: June 30 2023

**Today's Progress:** I finished the cash register project and got my certification for completing the JavaScript curriculum on freeCodeCamp. 

**Thoughts:** This last project was probably the most important I did on freeCodeCamp because it taught me the importance of planning before coding. I have to turn that lesson into a habit to prevent doing the same mistake in the future. To be fair, I should have refactored my code once I completed the course but I have been on this exercise for more than three days and I am eager to start something new. 

**Link to work:** [Cash Register](https://github.com/joanFaseDev/100-days-of-code-projects/commit/04ced8061d97268d4444a347dd76407e0385cca4)


### Day 87: July 01 2023

**Today's Progress:** I started the front-end development libraries curriculum on freeCodeCamp, more specifically the introduction course to bootstrap. I also started the course on Linux to pick up the basics of Ubuntu now that I have switched my OS. 

**Thoughts:** I didn't code much today because I focused more on theory with basic concepts in computer science like ROM/RAM, kernel, distribution, and apt. Many words that I often read but am unable to define. That makes me a lousy programmer so considering I just finished the JavaScript curriculum I thought it was a good time to try to rectify some of my (numerous) flaws. I just hope learning multiple different things at the same time won't turn out to be a huge mistake in the end.  

**Link to work:** [Bootstrap & Introduction to Linux](https://github.com/joanFaseDev/100-days-of-code-projects/commit/5c26269078b7cb9a54306ca1acdb585657a884d2)


### Day 88: July 02 2023

**Today's Progress:** I finished both the Bootstrap and jQuery courses of the Front-end Development Libraries curriculum on freeCodeCamp. 

**Thoughts:** This curriculum is pretty interesting so far. Bootstrap is a great tool and I understand why people love it but I find it too verbose and lacking in variety. From what I saw, it's pretty obvious when a web page uses Bootstrap.
jQuery, on the other end, really strikes me as a formidable tool. The syntax is short and very easy to understand which makes coding faster and simpler. For now, I'm going to chain the different courses. Once I'll start the project, I think I'll try to use jQuery on each of them to familiarize myself with its syntax and particularities.   

**Link to work:** [Bootstrap & jQuery](https://github.com/joanFaseDev/100-days-of-code-projects/commit/e51f54fa6306b07ceb8de5751c91e74251940022)


### Day 89: July 03 2023

**Today's Progress:** I finished the Sass course of the Front-end Development Libraries curriculum on freeCodeCamp. 

**Thoughts:** I didn't expect much from the Sass course because I figured that with the actual state of CSS Sass wasn't as relevant as before. I don't know if that is true but I really enjoyed Sass features. The variable syntax is simple and less verbose than CSS's custom properties. The fact that you can nest CSS is great for readability and mixins are just incredible! If I forgot the fact that it took me one hour to install Sass (.bashrc, x64, PATH are new to me), the whole experience was pleasant and I'll probably include Sass in my next projects so I can play around with it!   

**Link to work:** [Sass](https://github.com/joanFaseDev/100-days-of-code-projects/commit/05153958ddb4821b8426df6b587f8a520bbcabec)


### Day 90: July 04 2023

**Today's Progress:** I started the React course of the Front-end Development Libraries curriculum on freeCodeCamp. 

**Thoughts:** Honestly, I feel overwhelmed. I just learned about Bootstrap, jQuery, and Sass. I didn't spend much time on any of them even if I plan to do so in future projects. Now, I'm learning about React which introduce new concepts like components, props, and hooks (I don't even know what the last one is) and I'm wondering if my modest skills in JavaScript are enough. I thought a little about that and concluded that if I wait to be ready... I'll never be. So I'm going to dive head first into this React course and, when I'll meet JavaScript concepts that elude me, I'll stop to review them until I understand and can go further. Not sure if it is a good plan but I tried the opposite and I think it is a dead end so... let's go!   

**Link to work:** [React](https://github.com/joanFaseDev/100-days-of-code-projects/commit/1729424711f772604378adaaabf2826e9c574313)


### Day 91: July 05 2023

**Today's Progress:** I kept working on the React course and I am now more than halfway through it. 

**Thoughts:** Today I learned about state in React which seemed like a pretty important subject. The main idea is that updating stateful components automatically updates the UI's parts that depend on it. At least, I think that is how it works. The course introduces a lot of concepts quickly so I'll probably have to spend some days on React documentation once I am done with this part so as to check and double-checked what I learned. 

**Link to work:** [React](https://github.com/joanFaseDev/100-days-of-code-projects/commit/0ecf34f7c60b377d308fa5ce3c65dbee11a3725b)


### Day 92: July 06 2023

**Today's Progress:** I finished the React course on freeCodeCamp.

**Thoughts:** The next course is supposed to be an introduction to Redux followed by more React. It is going a little too fast for my taste. I am not feeling confident enough about React (or Sass for that matter) to pursue the curriculum so I am going to take a few days to practice React, review the basics, and learn how to set up a React application (the course automatically set up an environment so I have no idea how to do it),...

**Link to work:** [React](https://github.com/joanFaseDev/100-days-of-code-projects/commit/419a84663a6ec4343eeafc737c0e415611dcf3bc)


### Day 93: July 07 2023

**Today's Progress:** I started the Next.js introduction guide on React/Next.

**Thoughts:** I didn't have much time to code today (being night shift has some drawbacks after all) but I still managed to practice creating basic components and props. Not much to say here except I really like the declarative programming approach of React, it feels more intuitive to me.

**Link to work:** [Next.js guide on React](https://github.com/joanFaseDev/100-days-of-code-projects/commit/6d7bfae1150914bf8c523d3f3d3dcf8b72938197)