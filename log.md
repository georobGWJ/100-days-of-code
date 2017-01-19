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

### Day 2: January 14, 2017
**Saturday**

**Today's Progress**: Add ability to choose among multiple songs and added volume control.

**Thoughts:** Sooo... Volume control is a lot more challenging than just playing an mp3. I'll do it.

**Link to work:** https://github.com/georobGWJ/electron-mp3

### Day 3: January 15, 2017
**Sunday**

**Today's Progress**: Today I made the volume control actually work and abstracted the song selection menu. The menu is now dynamically created based on a local JSON file.

**Thoughts:** What I learned today. Managing local files using javascript can be tricky. I think that there's an easier way to do it than what I have implemented. Requiring 'fs' instead of writing XML to asynchronously access the file is probably cleaner and easier. I'm really close to MVP now though.

**Link to work:** https://github.com/georobGWJ/electron-mp3

### Day 4: January 16, 2017
**Monday**

**Today's Progress**: Learning day. I built several very small C++ projects to learn Visual Studio. (Hello World needs 110 lines (sans comments) to build as a Windows32 app!) I also figured out that localhost functionality might not reflect deployed functionality.

**Thoughts:** What I learned today: C++ is very fast but can either: require silly amounts of code and/or memory to run. (Hello World can take 110 lines of code or 500Kb for an executable using C++). Also, things might work differently on localhost then they do when deployed.

**Link to work:** https://github.com/agonzalez0515/Coco-app

### Day 5: January 16, 2017
**Tuesday**

**Today's Progress**: I replaced the async XML call to load the JSON play list file with the electron/node 'fs' component. Still having scoping issues.

**Thoughts:** What I learned today. The 'fs' component is a lot cleaner to use for reading and writing files and buffers. It has built in dialogs for creating open or save file widgets. Unfortunately I'm fighting scoping. I know that I'm reading file contents but these aren't being correctly assigned to global variables like they need to be.

Also, github doesn't count markdown file modifications as contributions. That's fair, it's not actual coding, but I'm a little frustrated that I spent 2 hours yesterday debugging. At the end, the issue was with localhost, so I didn't commit anything except for updating a markdown file. I want my effort to be tracked.

**Link to work:** https://github.com/georobGWJ/electron-mp3

### Day 5: January 17, 2017
**Wednesday**

**Today's Progress**: The 'fs' component ad I was using it was still trying to load asynchronously. That's why it wasn't assigning the data to the global variable. I fixed this and added functions to add to the playlist and save the file.

**Thoughts:** Honestly, I was getting genuinely angry at the code and almost said f it. Having solved the issue feels really good though and has energized me to finish up this little app. Next up I think I might start a rogue-like using C++ and the libtcod library.

Also, kind of unrelated, I've decided that I need to become proficient and fast at using Vim. It's a tool that I know I will have on any computer I'll be working on and it's really snappy, even on crap hardware.

**Link to work:** https://github.com/georobGWJ/electron-mp3
