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