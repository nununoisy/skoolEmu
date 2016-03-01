                                                                         
                                                                         
           E                          s  olEm                            
           m                          k o                                
  musk     u   ol  uskool   skoolE    o l          uskoolEmu  o      k   
  u        s ool  u      m s      u   o E         u    l    k o      o   
   koolE   koo    s      u k      s   l muskoolE  s    E    o l      o   
        u  oolE   k      s o      k   E u         k    m    o E      l   
        s  o  mu  o      k o      o   m s         o    u    l m      E   
  olEmus   l    ko lEmusk   Emusko    u  oolEmus  o    s    E  skoolE    
                                                                         

                           version 1 by nununoisy


Readme and Guide

skoolEmu is my solution to boredom at school. Put it on a flash drive and you have a large collection of web-based emulators at your disposal.

DISCLAIMER - NO ROMS ARE INCLUDED (besides homebrew). YOU MUST OBTAIN THESE ROMS YOURSELF. PLEASE BE RESPONSIBLE AND DO SO LEGALLY. I AM NOT RESPONSIBLE FOR ANYTHING THAT HAPPENS AS A RESULT OF AN ILLEGAL ROM DOWNLOAD.

Contents
-----------------------
1 -- setup
2 -- usage
3 -- emulators
4 +- emulator specific usage/tips
  |
  +---- JSNES by bfirsh			(Nintendo Entertainment System/Famicom)
  |
  +---- XNES by tjwei			(Super NES/Super Famicom)
  |
  +---- mupen64plus-js by jquesnelle	(Nintendo 64)
  |
  +---- Gameboy-Online by taisel	(Gameboy/Gameboy Color)
5 -- credits


1: setup
---------------------
Extract the zip to a folder somewhere. Remember where this is.
Optionally, you can copy index.html and paste a shortcut to the desktop.

2: usage
---------------------
Launch index.html in your favorite browser (Firefox or Chrome recommended), then select the emulator you wish to use.

3: emulators
---------------------
The following emulators are included:

JSNES by Ben Firshman (NES), XNES by tjwei (SNES), mupen64plus-js by jquesnelle (N64), and Gameboy-Online by taisel (GB/GBC). All of these are open source and can be found on GitHub.
More emulators are coming soon. I may also make a version of skoolEmu with native Windows executables, we'll see.

If you want, you can add an emulator by simply adding it to your index.html file. Requests for emulators are accepted at nununoisy@gmail.com.

Frederic Cambus wrote a great article with downloads for javascript emulators at http://www.cambus.net/emulators-written-in-javascript/.

4: emulator specific usage/tips
---------------------

4a - JSNES: to use JSNES, find the rom you want to play and place it into <skoolEmu folder>/emulators/jsnes-master/local-roms. Name it custnes.nes. Then start JSNES and select Custom Rom from the dropdown.
No roms are included besides homebrew because it would be illegal for me to include them. You must add them yourself inside the local-roms folder using the correct filename as described below.
Filenames for roms in the dropdown (all homebrew roms are already present and named correctly):

Bubble Bobble: 'Bubble Bobble (U).nes'
Contra: 'Contra (U) [!].nes'
Custom Rom: 'custrom.nes'
Donkey Kong: 'Donkey Kong (JU).nes'
Dr. Mario: 'Dr. Mario (JU).nes'
Golf: 'Golf (JU).nes'
The Legend of Zelda: 'Legend of Zelda, The (U) (PRG1).nes'
Lemmings: 'Lemmings (U).nes'
Lifeforce: 'Lifeforce (U).nes'               
Mario Bros.: 'Mario Bros. (JU) [!].nes'
Mega Man: 'Mega Man (U).nes'
Pac-Man: 'Pac-Man (U) [!].nes'
Super Mario Bros.: 'Super Mario Bros. (JU) (PRG0) [!].nes'
Tennis: 'Tennis (JU) [!].nes'
Tetris: 'Tetris (U) [!].nes'
Tetris 2: 'Tetris 2 (U) [!].nes'
Zelda II - The Adventure of Link: 'Zelda II - The Adventure of Link (U).nes'
Duck Hunt: 'Duck Hunt (JUE) [!].nes'
Super Mario Bros. 3: 'Super Mario Bros. 3 (U) (PRG1) [!].nes'

If you're comfortable with editing javascript, a JSON-formatted rom list can be found and edited in index.html.

Also, (and this bothers me too) the sound is very desynchronized. I can't fix that. Sorry.

4b - XNES: XNES is much simpler. Load it up and browse for your rom (must be headered [must have .smc extension]) and click start to play.

4c - mupen64plus-js: This emulator works only in Firefox. It crashes or has minor to severe errors in Chrome. It is in a very early stage, so don't expect it to play your games perfectly.
Sadly, there is not yet support for different plugins of config editing. Otherwise, it worked fairly well with the two games I tested, Super Mario 64 and Paper Mario.

4d - Gameboy-Online: Another simple emulator, it runs very well. Select Open from the File menu to load a rom.
This emulator is quite advanced, it has support for saves among other things. Try everything out, see what it can do.

5: credits
---------------------

nununoisy (obviously) - for finding the emulators, creating this package, making minor tweaks, and writing this guide
Ben Firshman - for creating JSNES
tjwei - for creating XNES
jquesnelle - for creating mupen64plus-js
taisel - for creating Gameboy-Online