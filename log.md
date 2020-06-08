# 100 Days Of Code - Log

### Day 32: 8. June 2020
**Progress**: fixed bug: wrong movement after second kill, getLairSpot in progress
**Thoughts:** Learned to respect timers when put in a setTimeout loop - startGhostMovement was just continuing with next setTimeout call normally even after clearTimeout because it was in the middle of a loop
**Link:** [Pacman JS](https://github.com/nahero/pacman_js)

### Day 31: 6. June 2020
**Progress**: fixing bugs: skipping between getOutOfLair and initializing normal movement, wrong movement after second kill - still in progress
**Thoughts:** Debugging is always time-consuming, consol.log everything...
**Link:** [Pacman JS](https://github.com/nahero/pacman_js)

### Day 30: 5. June 2020
**Progress**: sequenced animations and functions with Promises, added avatar to ghost class
**Thoughts:** Promises and nested Promises open up easier sequencing and other possibilities, I was actually calling a .then in a wrong way all along!
**Link:** [Pacman JS](https://github.com/nahero/pacman_js)

### Day 29: 4. June 2020
**Progress**: WAAPI ghost flying back to lair with speed relative to distance, respawn blinking animation
**Thoughts:** Transform properties cannot be separated giving me headaches. Considered GSAP but that would be diving down the rabbit hole. I will work with limitations as there are many things to accomplish to call this a finished app.
**Link:** [Pacman JS](https://github.com/nahero/pacman_js)

### Day 28: 3. June 2020
**Progress**: Implemented web animation API (WAAPI) instead of css animations and transitions.
**Thoughts:** WAAPI gives much better controls over animations and is smoother overall
**Link:** [Pacman JS](https://github.com/nahero/pacman_js)

### Day 27: 2. June 2020
**Progress**: Properly init and re-init ghost on start and eaten: move out of lair then triggering normal movement.
**Thoughts:** A lot of thinking today, and trying to incorporate Promises but ended not using them
**Link:** [Pacman JS](https://github.com/nahero/pacman_js)

### Day 25 and 26: 30. May and 1. June 2020
**Progress**: ghost return to lair on eaten, getOutOfLair, moveTowardTarget, isCoordsCloser, ghost eaten animation.
**Thoughts:** Everything is coming together to make a much more complex and enjoyable game. Morning fitness and mynoise.net for the win!
**Link:** [Pacman JS](https://github.com/nahero/pacman_js)

### Day 24: 29. May 2020
**Progress**: Ghosts movement rate slow/speed-up using setTimeout, pacdot animation
**Thoughts:** Have to find out why pacdot animation slows the game so much
**Link:** [Pacman JS](https://github.com/nahero/pacman_js)

### Day 23: 28. May 2020
**Progress**: Ghosts advanced movement: fluid movement, intersections, avoiding moving backwards, getting out of lair
**Thoughts:** Solving the problem on paper and/or comments first - then coding - is the way to go.
**Link:** [Pacman JS](https://github.com/nahero/pacman_js)

### Day 22: 27. May 2020
**Progress**: Preparing ghosts advanced movement, more reworked functions for reusability
**Thoughts:** Should have done different setup from the start, but that's always the issue :)
**Link:** [Pacman JS](https://github.com/nahero/pacman_js/commit/643057a6100f4d31800e492662eabae3cf428731)

### Day 21: 23. May 2020
**Progress**: Ghosts fluid movement rework, reworked functions for reusability, introduced ghosts avatars just like pacman
**Thoughts:** A lot of thought and bughunting goes into reusability, but it's worth it
**Link:** [Pacman JS](https://github.com/nahero/pacman_js/commit/fa30e44a180a3aec4ce4e0787f4c0d03c511ed8a)

### Day 20: 21. May 2020
**Progress**: Pacman continuous automatic movement rework, planned the end goal
**Thoughts:** Digging deeper, I want to build something polished, but not an exact clone of Pacman.
**Link:** [Pacman JS](https://github.com/nahero/pacman_js/commit/677c6efb49d97de32915bcb9adf90b074da1cad0)

### Day 19: 20. May 2020
**Progress**: Pacman JS bug fixes, more code optimization, started on 3d perspective
**Thoughts:** Wasted a lot of time on continuous movement on keyboard, didn't work
**Link:** [Pacman JS](https://github.com/nahero/pacman_js/commit/b42a55d894f648dcce6a851f44f6ace476d25c6f)

### Day 18: 19. May 2020
**Progress**: More Pacman JS, different movement calculations, breaking up into functions
**Thoughts:** Overthinking...
**Link:** [Pacman JS](https://github.com/nahero/pacman_js/commit/b42a55d894f648dcce6a851f44f6ace476d25c6f)

### Day 17: 18. May 2020
**Progress**: Pacman in vanilla JS, based on Ania Kubow tutorial
**Thoughts:** Been a long time since I worked in plain javascript! Direct DOM manipulation, wow... :)
**Link:** [Pacman JS](https://github.com/nahero/pacman_js/commit/b42a55d894f648dcce6a851f44f6ace476d25c6f)

### Day 16: 15. May 2020
**Progress**: Arduino code for DC load
**Thoughts:** Yup, lost my momentum because of the scope of Angular tutorial. I need to start building, not just learning.

### Day 15: 11. May 2020
**Progress**: Auto-logout, auth-guard, authentication wrap-up
**Thoughts:** Finally a full circle with authentication
**Link:** [Angular9 - 2020 edition](https://github.com/nahero/Angular9-2020-edition/commit/dcf47a873f0f5fa0197c5b5442f20d0938c196ae)

### Day 14: 9. May 2020
**Progress**: Storing user data to localStorage, auto-login
**Thoughts:** None whatsoever.
**Link:** [Angular9 - 2020 edition](https://github.com/nahero/Angular9-2020-edition/commit/57094671bb6ecf43d5b3f0c40ff33549922e1f38)

### Day 13: 8. May 2020
**Progress**: Auth interceptor
**Thoughts:** Took a small piece today and went throught it without tutorial to get a better grasp on details and errors.
**Link:** [Angular9 - 2020 edition](https://github.com/nahero/Angular9-2020-edition/commit/85bb596443640b925d85b6a4993ad6494ac9fefd)

### Day 12: 7. May 2020
**Progress**: User login, storing user data, adding auth token to HTTP request
**Thoughts:** Starting to feel that Angular steep learning curve, everything seems clear but there are so many details and variants that you really need to pay attention in class.
**Link:** [Angular9 - 2020 edition](https://github.com/nahero/Angular9-2020-edition/commit/f4ac74b8b9a89a672b878c7e186187748c83606e)

### Day 11: 6. May 2020
**Progress**: Auth service error handling + loading spinner
**Thoughts:** Max Schwarzmuller is really getting on my nerves already, so therefore, I turned off the sound and turned on the subtitles. Nothing personal Max :)
**Link:** [Angular9 - 2020 edition](https://github.com/nahero/Angular9-2020-edition/commit/8839f5664d7a2528ebc7bfff3277ccfa3888120c)

### Day 10: 5. May 2020
**Progress**: Angular route resolver (if no data loaded from database), Firebase user authentication"
**Thoughts:** Finally got to the user authentication
**Link:** [Angular9 - 2020 edition](https://github.com/nahero/Angular9-2020-edition)

### Day 9: 4. May 2020
**Progress**: Angular HTTP saving and fetching data from Firebase - back to main app
**Thoughts:** getting a good hold of GET/PUT/POST with Firebase
**Link:** [Angular9 - 2020 edition](https://github.com/nahero/Angular9-2020-edition)

### Day 8: 2. May 2020
**Progress**: Angular HTTP headers and HTTP interceptors
**Thoughts:** not much practical use from this part of tutorial, have to go back to main app and apply this properly
**Link:** [Angular9 - HTTP](https://github.com/nahero/angular9-http)

### Day 7: 1. May 2020
**Progress**: Angular HTTP requests + Firebase - error handling and get post attempt - CORS block
**Thoughts:** hello again CORS old friend...
**Link:** [Angular9 - HTTP](https://github.com/nahero/angular9-http)

### Day 6: 30. April 2020
**Progress**: Angular HTTP requests + Firebase - adding types and moving requests to a service
**Thoughts:** Just a follow-up on HTTP requests today
**Link:** [Angular9 - HTTP](https://github.com/nahero/angular9-http)

### Day 5: 29. April 2020
**Progress**: Angular HTTP requests + Firebase
**Thoughts:** Firebase does all the job on creating database and providing back-end and main API endpoint, but setting up the requests with proper types and using pipe/operators to modify the data received can be a PITA
**Link:** [Angular9 - HTTP](https://github.com/nahero/angular9-http)

### Day 4: 28. April 2020
**Progress**: Angular Pipes - built-in and creating custom pipes
**Thoughts:** Already know pipes from angularjs but went in deeper this time, and creating custom pipes with AngularCLI is a breeze
**Link:** [Angular9 - Pipes](https://github.com/nahero/angular9-pipes)

### Day 3: 27. April 2020
**Progress**: Reactive forms and CRUD using reactive forms
**Thoughts:** Will investigate how to use existing Interface to setup reactive form, whose value should obviously be identical to the Interface (at least in this course)
**Link:** [Angular9 - 2020 edition](https://github.com/nahero/Angular9-2020-edition)

### Day 2: 25. April 2020
**Progress**: Forms - template driven and reactive forms
**Thoughts:** Rolling along :)
**Link:** [Angular9 - 2020 edition](https://github.com/nahero/Angular9-2020-edition)

### Day 1: 24. April 2020
**Progress**: Angular observables and Subject + setting up a git repo from local project
**Thoughts:** Re-acquanting with Angular quirks and using new features
**Link:** [Angular9-observables](https://github.com/nahero/angular9-Observables)

### Day 0: 23. April 2020
**Progress**: Back to the big Angular 9 tutorial on Udemy - observables and custom observables
**Thoughts:** Good to be back on Angular after few months developing Wordpress sites :)
**Link:** [Udemy - Angular, the complete guide (2020 edition)](https://www.udemy.com/course/the-complete-guide-to-angular-2/)

<!--
### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link to work:** [Calculator App](http://www.example.com)

### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link(s) to work**: [Calculator App](http://www.example.com)


### Day 1: June 27, Monday

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence)
-->
