# Golden-Sun-Password-Generator
Golden Sun Password Generator for Windows

Not mine, it's from http://home.earthlink.net/~paul3/index.html

Thx Paulygon

===============================================================================

                        Golden Sun Password Generator
                                by Paulygon

                                Version 0.85
                               March 22, 2004

===============================================================================

Table of Contents:

1.  Introduction
2.  About passwords
    a.  Password Types
    b.  Entering Passwords
    c.  Updating Passwords
3.  Using the Program
    a.  Menu Options
        I.   File Menu
        II.  Password Menu
        III. Default Menu
        IV.  About Menu
    b.  Information Tabs
    c.  Inventory Editor
    d.  General Usage (Quick Start)
4.  Details on the password-making procedure
5.  Trouble-shooting
6.  Version History
7.  Contact Information





1.  INTRODUCTION



Welcome to my Golden Sun password maker.  As you know, when you complete this
game, it will allow you to transfer your data to Golden Sun:  The Lost Age.

There are two ways to do this:
1)  Using two GameBoy Advance units and a link cable.
2)  Using passwords generated by the game.

The first option is clearly the easiest way and you won't need this program,
unless you want to tweak your characters or items before transferring.  For
everyone else, it might be difficult to get ahold of 2 GBAs and a link cable,
so the password is the only option left.  This program will also be quite handy
for people who don't have the first game and yet don't want to be locked out of
the extras in the sequel that are available only when transferring data from
the first game.

For those who want or need to use passwords, this program should give you
everything you need to customize your characters and all information that will
be transferred over.

One thing to keep in mind is that this isn't yet a "1.0" release, so there are
still some unknowns and there may yet be some bugs present.  If you find any,
let me know (see contact information at the bottom).



2.  ABOUT PASSWORDS



--  a.  Password Types  --


As you may also know, there are 3 kinds of passwords available.. bronze, silver,
and gold.  Here is a breakdown of what you get with each:

*  Bronze:  The shortest password at 16 characters, but transfers the minimum
     amount of information - Character levels, Djinn, side-quest completion,
     and any of the 8 items that grant the wearer a specific psynergy.
     
*  Silver:  The medium password is 61 characters, but in addition to the bronze
     level data, you also get character stats - HP, PP, Attack, Defense,
     Agility, and Luck.  The stats are the baseline values, before modifiers
     from weapons/armor, djinn, etc. are applied.
     
*  Gold:  The longest password weighs in at a whopping 260 characters!  In
     addition to the bronze and silver data, you also get to carry over coins
     and all items (weapons, armor, healing items, etc.).  Very long, but
     worth it.

Basically it comes down to how much effort you're willing to put forth in
entering the passwords versus how much information you want transferred over.
Just remember you only have to do it once.


--  b.  Entering Passwords  --


The longer a password, the easier it is to make mistakes.  It's important to
make sure you can easily distinguish each character in a password.  You don't
want to be confused later by similar-looking characters.

When you enter your password after starting a new game in The Lost Age or
when choosing to "Update", do it carefully.  When you've finished, if the game
says "Invalid Password", that means one or more mistakes were made when writing
down the password or when entering it.  That's why you want to be careful and
double-check things as you go along.  The game (and hopefully this program ;-)
will never give bad passwords, so if there's a mistake, it was in copying it
down or when entering it.  If you still have problems getting a password to
work, see the trouble-shooting section further down.


--  c.  Updating Passwords  --


If you change your mind after having started a new game with a password, you
can choose "Update" and re-enter a password or re-transfer via link cable to
use newer data from Golden Sun.  The only difference is that you may not be
able to access some of the extras if you have passed certain points in the
story in The Lost Age.  So, Make sure at least all of the side-quest information
is how you want it the first time you make a password.  Note that you can't
update a save once Isaac's party has joined up.  That doesn't happen for quite
a while, you don't need to worry much about it.



3.  USING THE PROGRAM



--  a.  Menu options --


I.  File Menu -- Under the File menu, you have the following choices:


*  Load data from:
     There are 3 options here -- Golden Sun battery save file, Password data
     file, and Password text in clipboard.
     
     If you have a Golden Sun battery-save file (for example, if you played on
     an emulator or found a save file on the internet), this will allow you to
     load your information directly from it.  That way, you won't have to spend
     time entering everything in from scratch.  Just navigate to where your
     save file is using the dialog and select the appropriate file.  The
     first screen will show you which save slots are available.  If none are,
     then the save file is for the wrong game or doesn't have any valid save
     data in it.  Select one of the save slots (usually one that's marked as
     "Clear", meaning you beat the game with it).
     
     Password data files are created by this program, when you choose to save
     the data you have entered or any changes you have made.  This was included
     so you don't have to re-enter everything if you change your mind after
     having created a password.  Just use the dialog to navigate to the folder
     where you keep these files and select the appropriate one.
     
     The "Password text in clipboard" option is very useful if you want to base
     your passwords on some you have found on the internet.  All you have to do
     is select the password text, and copy it to the clipboard.  It's OK if
     there are blank spaces, blank lines, or dashes, but not if there are other
     words, like "Page 1" (then the program can't tell that that isn't part of
     the password).  The program will let you know if it can't accept the
     text in the clipboard.  If you need to, just paste the password into
     notepad and delete any excess words or characters.  Then, reselect the
     corrected password and copy it.  If there are no mistakes, it should come
     through just fine and you can go from there.
     
*  Save password data...:
     After you enter everything in and have your password, this can be used to
     save everything you entered in case you might want to tweak it again later
     before entering it in (or re-enter a new password using "Update").
     Definitely beats having to re-type everything you used to create a
     password.  ':-)
     
*  Save raw password characters...:
     This option is for those playing on emulators that have a memory-editor
     available that can load data from a file.  It will save you the trouble of
     entering in the passwords yourself.  Pretty nice, no?  ;-)  I will use
     Visual Boy Advance as a reference here.  Here's how it works:
     
     1.  Once you have a password, choose this menu option.  You will be
         presented with a save dialog allowing you to choose what folder you
         will save the file in and to name the raw password memory-dump file.
     
     2.  Next, start up your emulator (or bring it back up), load the game or
         reset it, and get to the password entry screen for the appropriate
         type of password (gold, silver, or bronze).
     
     3.  Once the game is on the right password entry screen, open the
         emulator's memory-editor.  The location of this option will depend on
         the emulator you are using, if it's supported at all.  If not, you
         won't be able to make use of this menu option.  (In Visual Boy Advance,
         look under "Tools | Memory Viewer...")
     
     4.  Choose the "Load" option on the memory editor.  If there isn't one, you
         won't be able to make any use of this menu option.
     
     5.  Use the dialog to navigate to where you saved the raw password data
         file earlier and choose that file.
     
     6.  When you are prompted for an address, type in the hex number
         "0200A74A".  (don't enter the quote marks, of course).  This number
         must be exact, so be sure to enter it correctly (lower case is OK).
     
     7.  Now, close the memory editor and return to the game.  Your password
         should magically appear.  :-)  Just move the cursor to "Finish" and
         press the "A" button (or just press Start).  Not too bad, hmm?  :^D
         
         If the password didn't appear, then you almost certainly made a mistake
         when entering that number in.  If this happens, reset the game and
         get back to the appropriate password entry screen.  Then, go back to
         Step 3.

*  Exit:
     No surprises here.  :-)

     
II.  Password Menu -- under the Password menu, you can do the following:


*  Copy to clipboard:
     Just like in many text editing programs, there is a copy command.  This
     will allow you to copy your passwords into the clipboard.  Then you can
     paste it into a text editor or other word processing program to format it
     in any way you see fit.  Then, you can print it out, add additional
     information (like the stats, items, etc.), save it, or whatever.
     

III.  Default Menu


*  Defaults:
     If you make too many mistakes or just want to start over, you can use this
     to wipe out any changes you made.  Select any of the defaults and the
     data will replace whatever's currently there.

     
IV.  About Menu:  Here, you can check out a little bit about the program, which
       will mostly be redundant if you've managed to read all of this.  ;-)


       Note:
       
         DON'T EMAIL ME ABOUT PROBLEMS WITH PASSWORDS UNLESS YOU'VE DOUBLE- OR
         TRIPLE-CHECKED EVERYTHING.  THIS IS ESPECIALLY IMPORTANT, BECAUSE THE
         LENGTH OF THE PASSWORDS MAKES THE WHOLE ENTRY PROCESS MORE ERROR-PRONE.

         Thanks.  :-)


--  b.  Information Tabs --


Here are the different tabs where you will enter or customize the information
necessary to make your passwords.  A general note:  If any controls appear
grayed out, it's because that information isn't used for the type of password
you've selected and so editing it isn't necessary.

*  Password:  This is where you select which kind of password you want and
     where to go when you're ready to make your passwords.  You can also see a
     preview of the current password, based on the type selected and the game
     data.  Just be sure to click the button to refresh the password if you've
     made changes to any of the game data.

     If you loaded data from a Golden Sun battery save file, a list of save
     slots with valid data will be shown.  Clear-data saves will be marked for
     your convenience.  In this case, a warning applies:
     
     ** Just be careful... Selecting a different slot here will cause all other
        tabs to change values to reflect the different save data.  Be sure to
        look at all of them first, by selecting them in turn and then visiting
        the different tabs to see what all data is in that slot.  Then, you can
        select the one you want for your passwords and start making changes. **

*  Djinn:  Check which Djinn you want to transfer or click the button to
     select all of them.  Simple enough.  :-)
     
*  Characters:  Here, you can customize character data.  Only the character
     levels are available with bronze passwords.  For silver or gold passwords,
     everything will be editable.  Note the limits on these values as stated at
     the bottom of the tab.
     
*  Items:  This shows what items your characters have.  Again, the notes at the
     bottom are helpful to understand what is transferred.  For bronze and
     silver passwords, the password will only keep track of 1 instance of each
     kind of blue item, so adding multiples of those is just a waste of space.
     They will all end up in Isaac's inventory, despite what is shown here.

     Notes:
     
     *  The edit button will allow you to edit the contents of each character's
        inventory.  Note that adding non-blue items for bronze and silver
        passwords is a waste of time because they are not encoded into these
        types of passwords... that is, unless you will also be making a gold
        password eventually.
        
     *  For gold passwords, the entire inventory will be encoded into the
        password.  This is why it's important to make sure you have both the
        Mars Star and the Black Orb in there somewhere.  They are shown in red
        for convenience.  The program will attempt to add them if missing but
        if all spaces are already filled up, it can't... then it will be up to
        you to make room for them and to be sure that they get included.
        
     *  If these 2 items (see above) aren't included, you may not be able to
        finish the game.  This is because they are important to the story.  I
        haven't tested this, so I don't know what will really happen.  I just
        don't want to hear any complaints if this turns out to be the case...
        there's plenty of warning and it's not my fault if nobody bothers to
        read it.  ;-)
        
*  Miscellaneous:  Here you can set the remaining information like the number
     of coins and the side-quest completion flags.  The coins are only
     available for gold passwords, while the side-quest flags are available for
     all password types.  Check any boxes that take your fancy, but to get the
     most of the The Lost Age experience, check them all.
     
     Notes:
     
     * The side-quest flags should be set how you want them in the first
       password (the one used to start the game).  Otherwise, you risk passing
       up points in the story line where these flags are checked, before you
       can update with a new password (if you're planning on doing that).
     
     * As stated in the program, I do not currently know which flag represents
       which side quest.  If anyone helps me figure any of these out and verify
       them, I would appreciate it very much and will give credit in future
       releases of this program.


--  c.  Inventory Editor --


Here is where you can modify the contents of a character's inventory.  Although
it's easy enough to figure out what everything does by experimentation, here's
a short breakdown:

*  Add button:  Select an item in the Items list and click "Add" to add the
     the item to the first empty slot in your character's inventory.  Clicking
     this button additional times will add extra copies of this item, except
     for green items, because only one of each kind is allowed in a character's
     inventory.. to add more, just change the quantity or use another character.
     
*  Replace button:  This will replace the selected item in your character's
     inventory with whatever is selected in the main items list.  If it's a
     green item, the amount (quantity) of the item will be preserved.  Use this
     to change an item instead of using "Remove" and then "Add" (because it's
     easier :-).

*  Remove button:  This will remove the selected item from a character's
     inventory.

*  Quantity button:  This will change the amount of the item that's selected in
     the character's inventory.  This only works for the green items... other
     kinds can only have one per slot.  Choose a number from 1 to 30.
     
*  Up / Down buttons:  These buttons will move the selected item up or down in
     the list.  They're useful for organizing the inventory.  Such organization
     is only for appearances, as the game will sort them in a different order
     once you put your password in.
     
*  Top / Bottom buttons:  These buttons will move the selected item to the top
     or bottom of the list.  Again, used for organization and just for the sake
     of appearance in this program.

*  OK button:  Use this to accept the changes you've made.

*  Cancel button:  This will reject any changes made since the dialog appeared.

  Note:  The items marked as "?" represent unused item values in Golden Sun.
    They will be encoded into the gold password, but will likely appear as
    unknown items in The Lost Age, as well.  Their effects are unpredictable, so
    be careful about them.  You probably don't want any of them if you need the
    space, but the possibility to have them is provided for those that want to
    experiment.


--  d.  General Usage (Quick Start) --


When making a password, you will typically do the following:

*  Choose one of the defaults from the Defaults menu, load data from one of
   the load options in the menu, or just start filling in all values.  Be sure
   to save password data if you think you might want to tweak this data some
   more later on.
   
*  Select the password type and fill out all necessary fields or make any
   desired adjustments.
   
*  When everything is ready, click the "Refresh Password" button to make sure
   the password displayed is based on the latest information.  You may also
   want to save again at this point if you plan to keep your data.
   
*  Write down the password by viewing the box down in the right corner
   and using the list next to it to select different pages of the password.
   
   - or -

   Copy the password to the clipboard all at once (from the Password menu, or
   by pressing the shortcut key Ctrl+C).  From there, you can paste it into
   your favorite text editor.  Then you can format it, add other information or
   whatever, and then print it out.  You can save it to a text file for future
   reference, e-mail it, etc...  it's all up to you.



4.  DETAILS ON THE PASSWORD-MAKING PROCEDURE



This section is for those interested in the password-making process.  I'll try
not to get too heavily into details, but rather touch on the general processes
involved.  If you don't understand, don't worry about it.  Don't ask me to
explain what all of the words mean... that's what the internet and search
engines are for.  Besides, I don't have time to explain it everyone who asks.
Nothing personal.  ;-)  Anyway, the process goes a little something like this:

*  Information validation:
     The first thing done is to make sure that certain data, like stats, are
     capped to certain limits.  1999 for HP and PP; 999 for Attack, Defense,
     and Agility; 99 for Luck.  Character class or other factors may limit what
     is shown during the game to a lower number.

     You may note that in the program, you can't use 999 for attack, defense,
     or agility.  The reason for this is that although the password can store
     this information, The Lost Age doesn't seem to acknowledge anything higher
     than 511.  For those more technically inclined, this means that the highest
     bit is ignored and treated as 0.  Rather surprising, but oh well... :-}
     
*  Packing:
     The next step is the packing of the data.  This means that the binary bits
     representing the information going into the password are placed next to
     each other, across byte boundaries and into predetermined spots.  Not
     every piece of data is packed together, just related pieces.. like all
     levels, djinn, stats, items, etc.  Data that will not be stored into a
     password is not included at all.
     
*  Integrity checking:
     Next, a numerical operation is performed on all of the packed information.
     For the technically inclined, it is rather like a CRC, but not exactly as
     far as I can tell (I'm no expert, though).  The resulting number is put at
     the end of the packed information and is used by The Lost Age as a final
     check on the validity of all passwords.  This CRC-like result is very
     sensitive to changes, meaning that slight changes in the packed data will
     produce a wildly different result.  This makes error detection very
     accurate.
     
*  Transformation:
     The packed information (including the CRC-like checksum) is encrypted
     via an exclusive-or operation to further enhance error detection.
     
*  Integrity checking, part 2, and unpacking:
     Following this, the packed and encrypted information is split up into a
     series of characters with 64 possible values.  This means that each
     character is 6 bits in length and is unpacked 6 bits at a time from our
     transformed data.  As this data is being transformed into characters, a
     checksum is calculated for every row of password data.  This covers the
     first 9 characters in each row of a password.  The checksum is then
     included as the 10th character on each row.  This is not done for the
     final row of bronze and silver passwords, since those do not have 10
     characters in them.

     The Lost Age will compute the checksums separately and compare it to what's
     in each row of the password.  This is the first line of defense against
     password-entry errors (and hacking :-).  For those whom I corrected a few
     passwords on the GameFAQs message board, this is how I was able to find
     out where the passwords were incorrect.  Finding out what was wrong from
     there was mostly guesswork, though.  :-}

*  Final transformation to character values:
     Lastly, an arithmetic operation is performed on each character to produce
     the final characters that will be displayed by Golden Sun.
     
So, if this wasn't too confusing, you can see that the password system is
highly resistant to password-hacking or errors in entry.  Pretty nice, I must
say, if producing results that are a bit long.  But, then again, this is an RPG
and there's lots of info to be encoded, so it's not really unexpected.
All of this is definitely worth it, but it also made this program tougher for
me to make.  ;-)



5.  TROUBLE-SHOOTING



*  Alright, so you entered a password and it didn't work.  What now?  Well, if
you were careful in writing down and/or entering the password, then you
shouldn't be needing to read this.  ;-)  The password-making process imitates
the game's own password-making process very closely, so it should never produce
bad passwords.  If you're sure that it did, make sure you saved the information
you entered, zip up that file, and e-mail it to me.  Make sure that the
information you saved will reproduce the bad password.  If you didn't make a
save file of it, then you probably shouldn't bother sending me anything... yes,
I'm so sure of it that I will need real proof of it malfunctioning.  Nothing
personal.  :-)


*  What the heck, the program crashed when I tried to run it!  Not another
"Illegal operation"!  >:-\  Honestly, this should be very rare..  it's likely
to be a result of some operating system files not being quite up-to-date,
version conflicts with older system libraries, etc.  It's such an unpredictable
thing, that the exact cause is practically impossible to pinpoint.  All I can
suggest if you were unfortunate enough to have this happen is to try updating
your operating system, drivers for your hardware, etc.

If the program worked before, but not later, then you might want to try rolling
back other program installations or driver updates, if possible, for those that
might have caused it to stop working.  Sometimes install programs will overwrite
system files with older (and incompatible versions) and cause other programs
that rely on them to behave strangely.  You can also try re-downloading the
program.  If after all of this, it still crashes like that, then I'm not sure
what to tell you... sorry.  :-(

If the program crashes after successfully starting, I would very much like to
hear about it.  Try to give as much information about what you were doing as
possible... the more, the better.  Otherwise, there's not much chance I will be
able to figure out what's going on.  Include the information you used to make
the password, if you think it's related to that, by saving it to a file, zipping
it up, and then attaching it in an e-mail.  My contact information is below.



6.  VERSION HISTORY



Details the history of changes.  Those reporting genuine bugs are listed in
parenthesis after the description.


  Version 0.85 -- March 22, 2004.
    * Fixed a crashing bug when trying to save the raw password characters to
      disk (FirenEX).
  Version 0.81 -- March 5, 2004.
    * Fixed a bug in saving password data where old data would be saved if the
      update button wasn't clicked first (Gamer at Random).

  Version 0.8  -- February 25, 2004.  Initial release.



7.  CONTACT INFORMATION



If you find any problems, have any comments, or can fill me in on any missing
or unknown information, you can reach me here:

  paulygon65@yahoo.com
  
Updated versions will appear first at my website:

  http://home.earthlink.net/~paul3/
  

Again, if you think you found a glitch or a bad password, please try to verify
the information before letting me know.  Investigating everything takes time,
which will be much longer if I get many error reports that turn out to be
mistakes in password entry or something like that.  If you do report a problem,
make sure to include any necessary files and give as much information as
possible.  Thanks.
