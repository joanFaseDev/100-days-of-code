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

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/ce47c55103b5b78ad3fe6d8b6f7b5e4a1577a0c3](Multiple Choice Questions)


### Day 12: April 16, 2023

**Todays Progress:** I added some features to the Multiple Choice Questions application. Now the content of the web page is automatically reset after each question. Then if there's still question unanswered, the next question is displayed on screen. If all question have been answered, a summary i'm still working on is suppose to be displayed on the page.

**Thoughts:** I didn't progress that much on the application but i'm satisfied with what i wrote, i think i'm going in the right direction. I'm not using any new knowledge on this particular project but i'm still working on my problem solving skill and it feels like valuable work. Aside from that, i keep reading [JavaScript Info](https://javascript.info/)'s content. Hopefully, the next projects will capitalize on what i picked up along the way.

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/f6a7dbd7efb9f9620490c687094d93894ee53957](Multiple Choice Questions)


### Day 13: April 17, 2023

**Todays Progress:** The summary part of the Multiple Choice Questions is done. I also added a complete reset of the application if user want to start the challenge again. I started the CSS part but there's still work to do. I also need to add more questions to the pool so i'll probably focus on that tomorrow.

**Thoughts:** I could barely code a couple of hours today but still there's real progress on the application and i think it might be over tomorrow depending on what i can accomplish before going to work (it's the time where i'm the least tired and the more focused). Having a job makes this 100 days challenge more complicated yet i feel i'll be ok as long as i can do my best every day. Even two hours of coding daily is fine, what matters is consistency. That's what makes the difference in the long run.

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/41170f1e76388de449369e3b210b037cbb3b5879](Multiple Choice Questions)


### Day 14: April 18, 2023

**Todays Progress:** I finished the multiple choice questions application. I added some styles plus a few entries to the question pool.

**Thoughts:** I kinda rush the last part of the application (a bit of JS logic but mainly the CSS part). Having so little time to pratice coding made me eager to work on various projects and so i felt compelled to finish this app and start something new. It's kinda disapointing but in the end i think i did ok. The app would have definitely benefit from a few more hours of work but the logic part is fine. For once i think i did something kinda scalable and that's definitely an achievement i can be proud of. Also i learned that styling a table isn't as easy as it seems. I will definitely look into that in a near future. 

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/6999fd0af124fc51d388a5cd0f68c01d5a8b7ad4](Multiple Choice Questions)


### Day 15: April 19, 2023

**Todays Progress:** I started a vanilla JavaScript application taking a date plus time as input and outputting a countdown between the current time and the input time. I read a tutorial plus part of the MDN documentation on the Date object. I wrote the logic to change the user's input into a valid date format then convert this date into days, hours, minutes and seconds between the current time and the date. 

**Thoughts:** For this application, i'm coding along a written tutorial. Initially i was scared that relying on guides/tutorials prevent me from searching/developping my own solutions but i made a point of testing/refactoring what i read and in the end, i find the process rather enjoyable. It's a good opportunity to learn from more experienced developers and hopefully pick up some valuable informations concerning clean code, programming, ...
Since i started this challenge, i did almost all projects on my own so it's really refreshing to see ways of solving problems different than my own. 

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/3249decc97afe613f6a64af13f7aae250770c384](Countdown)


### Day 16: April 20, 2023

**Todays Progress:** Countdown application is almost over. The JS part is finished meaning the countdown is now displayed and updated on screen. There's also the possibility to cancel a countdown before its end or to start another one once a countdown is finished. 

**Thoughts:** Today was really interesting. I learned about the setInterval() function and decided to instantly like it. It's easy to use and open far too many possibilities to count. I also want to try a 'new' method of learning where i basically make pair of projects: the first one in a guided 'safe' environment (throught tutorials) and the second, based on the first's knowledge, where i code alone and must think by myself. It seems like a good method of 'learning then checking if i understood correctly'.  

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/8fa54a56f595d818f2014a28926900f41ec2cbbd](Countdown)


### Day 17: April 21, 2023

**Todays Progress:** Countdown application is finished. I added enough styles to make a decent mobile and desktop responsive design. I also corrected a problem cause by the setInterval() function, more precisely the idInterval value used with clearInterval().

**Thoughts:** This project was really interesting. Following a guide gave me good tips on clean code and let me discovered useful features like the setInterval() function or more generally how to convert milliseconds into seconds, minutes, hours and days. I also learned a good use of the modulo operator!

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/5986005fbd0024bcc1ab5f59ea6fb9c5228bfbfb](Countdown)


### Day 18: April 22, 2023

**Todays Progress:** I started out a Pomodoro application mimicking the one from the website [Pomofocus](https://pomofocus.io/). This time, i tried to do things smartly by writing my process before actually coding anything. I also try to write code more 'spontaneously' alterning between HTML, CSS and JavaScript to gradually 'shape' the app (usually i do the appearance at the end when all is functional). I don't know if it's good or bad but i'll probably have a clue by the end of this project.

**Thoughts:** This project will probably be the biggest one yet. There's a lot of features to test and implement so i'll probably work on it for quite some time. I'm using Pomofocus as a visual reference as i quite like this website and find it well designed. Looking at it more closely, there's a lot of small features / styles i never take notice of before (e.g box-shadow on a button being pressed, a tiny icon indicating a task is now completed, ...). It's kind of cool to rediscover under new lights something you thought you were quite familiar with.

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/16760553f2f3b7b024107fb2ec0d8ea69a3a2b59](Pomodoro)


### Day 19: April 23, 2023

**Todays Progress:** I implemented the Short Break state that is automatically executed at the end of a Pomodoro countdown. I also added a visual update of the page when the user is on short break. I've rewritten the to-do list of the application to make things clearer for the following days.

**Thoughts:** I'm quite satisfied of what i implemented today or more precisely how i implemented it. I listed what i wanted to accomplish and break down each task into smaller steps. Written down my process before actually coding anything made me feel way more in control than usual. Of course, i wasn't always right and sometimes things turned out wrong but at the very least i had a plan to follow which is both reassuring when coding and extremely enjoyable when the coding is done and what was written is actually working correctly. I like coding this way so i'm gonna stick to it from now on.

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/34ee601fd8a5bab63680fec86cd2154fce8291d6](Pomodoro)


### Day 20: April 24, 2023

**Todays Progress:** The application now smoothly transition from 'Pomodoro' state (25 minutes of work) to 'Short Break' state (5 minutes of break) then, every 4 Pomodoro, to 'Long Break' state. Each state has its own visual theme and every time a countdown end, a ring sound can be heard.

**Thoughts:** I keep writing down the tasks i must work on then try to divide these tasks into smaller units. I really want to make this process a habit as i truly think it'll will make things so much easier in the long run (and not only as a developer as this skill can probably be applied to a lot more areas). I'm progressing well on the application but today i copied/pasted a lot of code and i feel that some refactoring will soon be needed. I really need to learn how to use classes and objects in JavaScript, my code always looks like a giant dish of spaghettis and it's getting more and more troublesome as project goes. Next weekend, i will also learn how to use branches in git. My projects becoming bigger, branches will soon be very valuables.

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/5a3eadeb3951b41feffdcca99e0b9e4e20384f3b](Pomodoro)


### Day 21: April 25, 2023

**Todays Progress:** I implemented a new feature to directly choose the 'state' of the application, meaning the type of the next countdown (between Pomodoro, Short Break and Long Break). It's accessible through a set of buttons located at the top of the countdown. Pressing one of the three buttons also update the document's style.

**Thoughts:** I think i'm gonna rewrite several parts of the application. My messy code is one thing but i feel the way i built this project is wrong. Adding the new feature was difficult because i couldn't built on what i previously established. It seems i didn't plan well enough so the best thing i can do is recognize my poor judgement / building skill and try to correct what i can as best as possible.

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/f735fa5fe9cabfbd26b59cd96349a2ab3b429300](Pomodoro)


### Day 22: April 26, 2023

**Todays Progress:** I created a new script and rewrote / refactored most of the logic. Apart from the pause button and its behavior, all features have been reimplemented.

**Thoughts:** While i clearly lack the knowledge to rewrite efficiently my previous code, i'm somewhat satisfied of what i accomplished today. It's far from perfect but still way better than my previous implementation, it's less verbose and more reliant on functions. I also tried to make my code more scalable by writing function that can be use in more than one case. Overall, i found that refactoring is acutally a pleasant experience and  probably a very good exercice for anyone trying to improve its code writing skill. 

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/678ae946d4047b6ac1f21fc5dd13bc6dc282242b](Pomodoro)


### Day 23: April 27, 2023

**Todays Progress:** Refactorization is now complete. The application is functionnal which is more than it was in the previous version. I added the logic/style for the start/pause button plus the logic for the change of mode when a countdown ends.

**Thoughts:** The application is still missing some juicy features (ring sound at the end of a countdown, a task manager,...) but the default functionalities are here and i think it's possible to build on it. Initially i planned to keep working on the app, mainly to add the task manager, but now that i have something working i must confess that i'm eager to work on something else. Maybe something smaller where i can actually work on my basics. If anything, this project made me realize that programming language isn't worth much without proper planning and smart decision making. To acquire that, i need knowledge of my pairs and small projects i can test it out!  

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/46ebc78a40800677d51a9236d467b15e51471857](Pomodoro)


### Day 24: April 28, 2023

**Todays Progress:** I started a new application called Party Games. The end goal is to chain three small scope games (like the Hangman game) so two users can compete together. 

**Thoughts:** I'm not really set on the how and what of this application. I just wanted a project i could use to test out what i'm currently learning on [JavaScript.info](https://javascript.info/). My goal with this project is to focus on writing clean code and developping my problem solving skills. It's the last day of the week (which mean my fatigue is at its peak) but tomorrow i'll have a more concrete idea of the direction i want to go with this application.   

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/3eccf2e6caed8f827cb19c1646bfb95b832adfc6](Party Games)


### Day 25: April 29, 2023

**Todays Progress:** I created a new project dedicated to the proper learning of JavaScript (through the website [javascript.info](https://javascript.info/)). I also started coding the logic for the Hangman game of the Party Games project. For now, a random word is fetched from an API and several divs are created, each containing a letter from the random word. 

**Thoughts:** Lately i realized my learning plan is a mess. More accurately, i don't have an end goal. I wish to get a job as a developper but i didn't really research the kind of skills needed to get it. I think that realization in itself is a progress. Once i figured out the skills needed, i'll research projects that are using theses skills. Projects that can actually help selling myself. For now, i'm learning JavaScript. I created a project where i can test examples and snippets in a small environment. I'm currently revisiting functions and it's really unbelievable how i can use them daily and know so little about them!    

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/f9808fa4e5aa9f4d842a677909f14905bf54d389](Party Games)


### Day 26: April 30, 2023

**Todays Progress:** I refactored some of the code i wrote yesterday to implement the Hangman game of my Party Games project. To draw a proper set of gallows / hangman, i started learning the basics of the Canvas API. I now know how to set up a canvas element and its context, how the canvas coordinates system works and how to use the rectangle functions properly. 

**Thoughts:** Truth be told, the Canvas API is probably not something i should spend a lot of time now. I don't think it's a useful skill to rapidly get a developer job... but it's fun! I had a blast this morning introducing myself to the API using the [MDN Tutorial on the subject](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial) and there seems to be a lot you can actually do with it. Plus, having an interest in game development and animation, i'm quite fond of this kind of technology. My plan for now is to learn the basics of the API, use it on the current project then try more complex things with it in the future. Writing this, i realize i planned a lot of things lately but rarely follows on it!     

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/f6d667c9da2493a6bbfd2b0bca573dd3b4325cf6](Party Games)


### Day 27: May 1, 2023

**Todays Progress:** I learned a bit more about the Canvas API, more specifically how to use paths. I finished the drawing of the gallows / hangman and set up a function to show step by step how the drawing was build. I'll use this function as a foundation to the hangman gameplay loop. 

**Thoughts:** I spend a lot of time on the drawing but i'm actually happy with the result. I now have a basic knowledge of the Canvas API. While reading an article on MDN, i saw a list of libraries for the canvas elements. I'll probably try to use one next time as the process of drawing with the default functions is very time consuming. And i'm saying that when what i drawn was actually very simple shapes!     

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/c8ed0abb62ec5f689521debd101a60bfd09c152c](Party Games)


### Day 28: May 2, 2023

**Todays Progress:** I added a field so users can send their pick plus an input validation to check for user's answer: one character only and it must be a letter.

**Thoughts:** I have a lot of difficulties navigating my code. I said it (and by 'it' i mean my spaguetti code) won't happen again but i guess i didn't act on it. Contrary to what i initially annonced, i will limit that project to the Hangman game. There's already a ton of stuff to do, no need to add more complexity on a code which is barely manageable as it is. For now, i'm going to add a few features and refactor as much code as possible so i can finish this smoothly.     

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/7517254cc5bff96c45a4e56236be7a177b74622c](Party Games)


### Day 29: May 3, 2023

**Todays Progress:** I focused on two things. First, i refactored most of the application's functions. I rearrange them in calling order and i tried to redefine each function to do one task while renaming the ones that didn't seem explicite enough. Second, i added a feature at the start of the application to get the player's names, check their format, store them then transition to the game's core loop. 

**Thoughts:** I refactored as much functions as possible. It's not ideal but it's still a huge improvement compared to yesterday. The code is now clear enough so that i can finish this application without losing too much time. I think i'm slowly getting better at writing 'decent' functions ( by that i mean functions with a clear name and focused on one task). That's the impression i have anyways.     

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/cdf4e1d91d5047ae41c33109810d504516325647](Party Games)


### Day 30: May 4, 2023

**Todays Progress:** I added logic to sort player's answers between valid and unvalid one. Previous answers are also stored in valid/unvalid pools. Finally i integrated a feature to automatically switch turn between players every time an answer is send.

**Thoughts:** The script have now more than 800 lines of code which makes this application the 'bigger' i've done until now. This size is a problem though, i lose a lot of time double checking my code even with dual screen. This morning, i spend 20 minutes on a simple error caused by a function i created twice. Turned out that the one being called in that case is the one being declared last. It's logic but it never happened to me before so i was still surprised. This project is a nest of mistakes. That's good, i'll learn a ton from it!     

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/955fddad27eb3a13285509c2f26d6486fab84878](Party Games)


### Day 31: May 5, 2023

**Todays Progress:** I added a score system which reward good answers and penalise the wrong ones already proposed. When a penalty occurs, a warning is automatically displayed. I also added a color system plus an array of the hangman's images to the game manager object. Every wrong answer is followed by a display of the 'current frame' registered by the game manager. At the end of the round, if the current frame isn't the last one in the array, the next one is loaded for the following round.

**Thoughts:** The end is near! I just noticed that i started this application more than one week ago which makes it the one i've worked on the longest (others will follow!). I did good progress today and, unless there's big complications ahead, i think i can finish this project tomorrow.      

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/3bf810ddeef012202a773c7a3fb3a7a56f600b7f](Party Games)


### Day 32: May 6, 2023

**Todays Progress:** I added a penalties count's feature to break a score tie. I also finished implementing the conditions to end game, either revealed the last letter of the mystery word or displayed the last image of the hangman. When the game ends, part of the document is removed to let some place for a message revealing both victor's name / mystery word and congratulating both players for their participation. 

**Thoughts:** As of now, i considered this project finished. There's a lot more i could do here but it has to end eventually and i'm satisfied with what i built here. This project was supposed to be a chain of three games but in the end i only delivered one. That being said, this game was the hardest i planned out of the three and i think a learned a lot from its development. I now give my functions a proper name reflecting what they do and only that. I also designed them to do one thing and if i need something else i just create another function. I will improve a lot more once i'll have learn to make them more scalable, more reusable depending of the circonstances. I also need to learn classes and modules as soon as possible. My JavaScript file on that project have more than a thousand lines of code and i don't want to work with that again. I need to abstract more, hide complexity so that i can better focus on just implementing each features without causing a ton of problems elsewhere.
I have a three days weekend so i'm going to take the time to think about the projects i have to do. No more random applications, i need to select projects that i can learn the most from. Projects i can actually use in a portfolio to secure a job!       

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/859f33e0f3a1f514a78912cbb4352739089c2214](Party Games)


### Day 33: May 7, 2023

**Todays Progress:** I didn't start any project today and instead focused on learning more about JavaScript objects. Yesterday, i reviewed some basics, how to create them using object litterals (constructors will be tomorrow) and how copying an object merely copy the reference to its address in memory (by opposition to primary data types which are copied in value only). Today, i studied the 'this' keyword. I knew it was primarily used to reference an object inside its own methods but there was a lot i wasn't aware of, the biggest discovery being that 'this' in JavaScript is evaluated at run-time! Which actually explains a lot of things now that i think about it... 

**Thoughts:** I'm trying to use my three days weekend efficiently. The goal is to come up with a well thought learning plan i can follow for the next weeks. To be honest, i'm still on it. Aside from that, i tried to think about a way to find a job in web development as fast as possible. My best friend recommended i build a good CV, motivation's letter and portfolio then send copies to all valid potential employers i can find. I wanted to learn how to use Figma (i think it's a good line on a front end's developer curriculum) so i started building my cv using it. The ideal would be to finish it in the next 24 hours so i can concentrate on the letter but i'm not sure i can do it...      

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/c311cca8dc60e28f88a9e8325805e248357db80d](Learning JavaScript)


### Day 34: May 8, 2023

**Todays Progress:** I learned the basics of the 'new' operator and constructor functions. What is the difference between creating objects through object litteral versus creating them through constructor functions, what happens in a constructor function when one explicitly returns a value,... 

**Thoughts:** Learning more about JavaScript is definitely a good thing, the more i read the more i realize i'm actually using a lot of JavaScript features without really knowing what happens in the back of the store. Best thing is that a part of what i'm currently learning can be applied to other languages (i'm trying to learn Lua, specifically for game development and the two languages have a lot of similarities) which helps a lot. I'm going to spend the rest of the day working on Figma, finding a new JS project i can start tomorrow and, hopefully, starting some real game development / prototyping. There's a lot to do, have to go!      

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/48a4c07959f4cd2bc8208aef74fba09840e2a6c6](Learning JavaScript)


### Day 35: May 9, 2023

**Todays Progress:** I started a Calculator application using vanilla JavaScript. Using HTML & CSS, i created a basic layout based on a mockup i did on Figma yesterday. I also experimented with JavaScript objects to implement the calculator logic.

**Thoughts:** Working with Figma to prototype an application's design early in a project seems like a good idea. Sure it takes some time and research but the design obtained that way works like a roadmap and make the HTML & CSS part way more simple.
I'm trying to use JavaScript objects on that project to apply what i learned this weekend. I'm not sure about the implementation yet but experimenting is a good way to learn so wait and see!    

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/ab98426afec836ab4916f9c59b5237f184b8cc8c](Calculator)


### Day 36: May 10, 2023

**Todays Progress:** I kept experimenting and finally set for a simple system where i keep a trace of the user's last input and base the application's entire logic on what this last input can accomplish combined with the current one. I implemented some basics like updating the calculator's screen with the user's input if it's a digit. I also started setting the social medias features which were added to the calculator's header. 

**Thoughts:** I experimented some more today. Erased as much lines as i created but i very much prefer taking the time to find a decent implementation early in the development. I don't want to spend hours in writing codes to finally hit a wall and realize i have to start on more solid basis. Most on my reflections were actually wrote on paper which makes me realize studying pseudo code or languages like UML may be incredibly worth in the long run.    

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/ab98426afec836ab4916f9c59b5237f184b8cc8c](Calculator)


### Day 37: May 11, 2023

**Todays Progress:** I implemented the logic related to the github and twitter icons using the load() method of the Window interface. I also finished the 'no previous key' use case and set a limit to the number of characters displayed by the Calculator (max 16). I started experimenting with ways to handle the calculator's calculations through three properties: leftOperand, rightOperand and operator.

**Thoughts:** There's too many flaws in my current impementation, i'm gonna start something different based on simple conditions focused on three properties, one for the first value (left operand) another for the second value and a last one for the operator between them.    

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/2a6f3144f205db5b03bd52125844a8d0c7bd86d7](Calculator)


### Day 38: May 12, 2023

**Todays Progress:** I rewrote a big part of the application to make it more manageable and more fit to handle the different use cases. The idea is that every time a calculator's key is pressed, three things are evaluated: is there a left operand? If yes, is there an operator? If yes, is there a right operand? Depending of the results, the same key will display a different result.

**Thoughts:** The way i'm currently coding this application is probably not the best but that's the one i found by myself and if i can finish this project with it i'll be satisfied enough. I kept using pseudo-code to wrote most of the logic i implemented today. I really enjoy this process, i found it useful because i'm someone who's pretty bad at 'thinking logically'. Write on paper helps me see the flaws in my design (not all unfortunately) and partially correct it which is a definite improvement!

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/2dbedfabf3cd880ad38527a39e5bbb839139a71c](Calculator)


### Day 39: May 13, 2023

**Todays Progress:** I wrote all use cases for configurations where the left operand and operator are known as well as when left operand, operator and right operand are known. The JavaScript part is finish and the application is functionnal. What's left is the CSS part.

**Thoughts:** The application seems to work fine. I tested various things manually but it's time consuming and far from being efficient. I'll probaby have to learn how to write and configure proper tests in the long run but it's not a priority yet. I reused lots of code near the end which is not ideal but i was eager to finish the JS part and play with styles. I'm probably gonna review some basics of HTML and CSS in the next days. As of yesterday, i'm unemployed and i wish to use my free time to 1) work on my CV and job research 2) list what i currently know and what fundamental web developer skills do i miss at this point.

**Link to work:**[https://github.com/joanFaseDev/100-days-of-code-projects/commit/c6e3efa71a61ac8aa2b0319e0a8330628eef86cd](Calculator)
