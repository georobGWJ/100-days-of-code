# 100 Days Of Code - Log

### Day 0: January 11, 2017
**Wednesday**

**Today's Progress**: Diagrammed DB schema for CoCo app. Began debugging SAT choice menus.

**Thoughts:** Returned to working on DBC final project app, College Counselor (CoCo). Revisiting this code is bringing back to the DBC people and program which feels good. First goal, figure out why radio selection menus don't allow choosing the last date/location for SATs (it doesn't look like an indexing thing...)

I have some personal project ideas that will be started soon.

**Link to work:** https://github.com/agonzalez0515/Coco-app (I haven't committed what I worked on today.)

### Day 1: January 12, 2017
**Thursday**

**Today's Progress**: Began building Electron based MP3-player app.

**Thoughts:** I want to learn [Electron](http://electron.atom.io/) to create client side apps. So I am. This MP3 app is fairly simple and should be a good base to extend using various techs. (Angular or Ember + Electron? Add a DB backend to track media? Other tech?)

Also, I reindexed my days. Yesterday I was really only doing maintenance, not building and I haven't committed that work yet, so today is the new Day 1.

**Link to work:** https://github.com/georobGWJ/electron-mp3

### Day 2: January 13, 2017
**Friday**

**Today's Progress**: Added play functionality to electron-mp3.

**Thoughts:** HTML5 has built in functions to run audio and video files! I thought I would have to write that myself. I can focus on UX/UI and adding features going forward. :)

**Link to work:** https://github.com/georobGWJ/electron-mp3

### Day 3: January 14, 2017
**Saturday**

**Today's Progress**: Add ability to choose among multiple songs and added volume control.

**Thoughts:** Sooo... Volume control is a lot more challenging than just playing an mp3. I'll do it.

**Link to work:** https://github.com/georobGWJ/electron-mp3

### Day 4: January 15, 2017
**Sunday**

**Today's Progress**: Today I made the volume control actually work and abstracted the song selection menu. The menu is now dynamically created based on a local JSON file.

**Thoughts:** What I learned today. Managing local files using javascript can be tricky. I think that there's an easier way to do it than what I have implemented. Requiring 'fs' instead of writing XML to asynchronously access the file is probably cleaner and easier. I'm really close to MVP now though.

**Link to work:** https://github.com/georobGWJ/electron-mp3

### Day 5: January 16, 2017
**Monday**

**Today's Progress**: Learning day. I built several very small C++ projects to learn Visual Studio. (Hello World needs 110 lines (sans comments) to build as a Windows32 app!) I also figured out that localhost functionality might not reflect deployed functionality.

**Thoughts:** What I learned today: C++ is very fast but can either: require silly amounts of code and/or memory to run. (Hello World can take 110 lines of code or 500Kb for an executable using C++). Also, things might work differently on localhost then they do when deployed.

**Link to work:** https://github.com/agonzalez0515/Coco-app

### Day 6: January 17, 2017
**Tuesday**

**Today's Progress**: I replaced the async XML call to load the JSON play list file with the electron/node 'fs' component. Still having scoping issues.

**Thoughts:** What I learned today. The 'fs' component is a lot cleaner to use for reading and writing files and buffers. It has built in dialogs for creating open or save file widgets. Unfortunately I'm fighting scoping. I know that I'm reading file contents but these aren't being correctly assigned to global variables like they need to be.

Also, github doesn't count markdown file modifications as contributions. That's fair, it's not actual coding, but I'm a little frustrated that I spent 2 hours yesterday debugging. At the end, the issue was with localhost, so I didn't commit anything except for updating a markdown file. I want my effort to be tracked.

**Link to work:** https://github.com/georobGWJ/electron-mp3

### Day 7: January 18, 2017
**Wednesday**

**Today's Progress**: The 'fs' component ad I was using it was still trying to load asynchronously. That's why it wasn't assigning the data to the global variable. I fixed this and added functions to add to the playlist and save the file.

**Thoughts:** Honestly, I was getting genuinely angry at the code and almost said f it. Having solved the issue feels really good though and has energized me to finish up this little app. Next up I think I might start a rogue-like using C++ and the libtcod library.

Also, kind of unrelated, I've decided that I need to become proficient and fast at using Vim. It's a tool that I know I will have on any computer I'll be working on and it's really snappy, even on crap hardware.

**Link to work:** https://github.com/georobGWJ/electron-mp3

### Day 8: January 19, 2017
**Thursday**

**Today's Progress**: I added functionality to go to the next song in the playlist once a song ended and partially implemented the ability to delete songs from the playlist.

**Thoughts:** Not many today. It's satisfying to add functionality and to continue learning JS UI. I want to get this app shiny sooner rather than later so that I can move on.

**Link to work:** https://github.com/georobGWJ/electron-mp3

### Day nil: January 20, 2017
**Friday**

**Today's Progress**: I went to a friend's graduation celebration and party today. I got home too late and tired to code.

**Thoughts:** Right now, I think that the languages that I want to focus on learning and practicing the most are C++, Python, Javascript and Clojure. That covers a broad range of programming styles and levels.

**Link to work:**

### Day 9: January 21, 2017
**Saturday**

**Today's Progress**: Worked on extending the functionality of the message boards of College Counselor by adding new tables.

**Thoughts:** It's amazing how quickly info leaves your mind when you don't practice. I'm working in Rails again and needing to look up a lot more than I thought I would need to.

**Link to work:** https://github.com/agonzalez0515/Coco-app

### Day 10: January 22, 2017
**Sunday**

**Today's Progress**: Styling! And adding subforums.

**Thoughts:** Today I added the logic and structure to define individual forums to the CoCo message board. Coding on a Southwest flight is like being a T-REX, there is NO arm space.

**Link to work:** https://github.com/agonzalez0515/Coco-app

### Day 11: January 23, 2017
**Monday**

**Today's Progress**: Continuing implementation of Forums and styling improvements.

**Thoughts:** Fuck trump (From here on I will refer to him as Donny, as in "Shut the fuck up Donny!").

**Link to work:** https://github.com/agonzalez0515/Coco-app

### Day 12: January 24, 2017
**Tuesday**

**Today's Progress**: Implemented message board tags.

**Thoughts:** There were two ways to implement Tags for messages. An easy way and an efficient way. Today I waffled between the two and didn't get all of the logic done.

**Link to work:** https://github.com/agonzalez0515/Coco-app

### Day nil: January 25, 2017
**Wednesday**

**Today's Progress**: Nada.

**Thoughts:** I couldn't muster motivation today.

**Link to work:**

### Day 13: January 26, 2017
**Thursday**

**Today's Progress**: Finished implementing almost all Tag logic, using the more efficient way.

**Thoughts:** Good day. High motivation and follow-through to finish the Tag logic. I still want to add some AJAX to make things cleaner but am close to merging this branch. :)

**Link to work:** https://github.com/agonzalez0515/Coco-app

### Day 14: January 27, 2017
**Friday**

**Today's Progress**: Worked on adding AJAX to the tag buttons so that they can be upvoted.

**Thoughts:** It's a little surprising how quickly you forget things. It's been a while since I used AJAX with RAILS and I coded a little slower than I would have liked to. In my defense, I'm working with new tech at work (Fortran) and have a lot on my mind.

**Link to work:** https://github.com/agonzalez0515/Coco-app

### Day nil: January 28, 2017
**Saturday**

**Today's Progress**: Nada.

**Thoughts:** Traveled back home to Oakland from Aurora. Got engrossed with reading about how Trump is destroying our country.

**Link to work:**

### Day 15: January 29, 2017
**Sunday**

**Today's Progress**: Finished implementing Tag AJAX and improved styling.

**Thoughts:** I had to do some old fashioned AJAX, not just using RAILS helpers. It was fun logic-ing out how to do it.

**Link to work:** https://github.com/agonzalez0515/Coco-app

### Day nil: January 30, 2017
**Monday**

**Today's Progress**: Today I worked on some debugging but didn't build anything new.

**Thoughts:** Not a lot. I'm done adding the features I absolutely wanted. There are a few more I may add. Meeting on Friday with the team.

**Link to work:** https://github.com/agonzalez0515/Coco-app

### Day nil: January 31, 2017
**Tuesday**

**Today's Progress**: Nada.

**Thoughts:** Stressful, long day at work.

**Link to work:**

### Day 16: February 1, 2017
**Wednesday**

**Today's Progress**: Returned to electron-mp3 project. Improved Play and Pause functionality. Partially implemented Delete function.

**Thoughts:** It's good to take a break from a project. I can see several ways to refactor what I had done before. It might be better to try to use a sqlite3 DB instead of JSON. That would be a bit heavier resource wise but would be more flexible.

**Link to work:** https://github.com/georobGWJ/electron-mp3
