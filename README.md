Scrybe
======

HackDuke project for Fall 2015


Quick How-To for using GitHub (for Mac users):


    1 - Open the Terminal.
    
    2 - Navigate to your local directory where you want your GitHub repository files saved.
    
    3 - Type in "git clone https://github.com/MTM616/Scrybe.git"
    
    4 - If this is in your Eclipse workspace (because you like working in Eclipse)...
    
        4.1 - Add a project in Eclipse called "Scrybe".
        
        4.2 - Create project. Everything cloned from GitHub should now show up in Eclipse (may need to "Refresh" folder).
        
        4.3 - This can be useful because Eclipse itself will track content that hasn't been pushed, merge conflicts, etc.
        
    5 - Type in "git status" in the Terminal to see how your local repository matches up with the GitHub repository.
    
    6 - "git add <file>" will add <file> to the GitHub repository.
    
        6.1 - "git add ." will add everything you haven't yet added to the GitHub repository.
        
    7 - "git commit" will confirm your changes. This opens up the vi text editor...
    
        7.1 - Type "i" to edit. Type in your commit message, then ESC to stop editing.
        
        7.2 - Type ":wq" and ENTER to save your changes and quit.
        
        7.3 - As a rarely-used alternative, type ":q!" and ENTER to quit without saving changes.
        
        7.4 - If all this is too much trouble...
        
            7.4.1 - "git commit -m" will confirm changes and allow you to type in a commit message without opening vi.
      
    8 - Type in "git pull" to retrieve any changes pushed to GitHub by other team members.
    
        8.1 - This may cause merge conflicts. Resolve these by editing the files affected.
        
        8.2 - Type in "git commit" again followed by ":wq" and ENTER.
        
    9 - Type in "git push" to finally add all of your committed changes to the GitHub repository.


Google anything that's still confusing.


If you wanna learn how to play around with Git branches, feel free to do so. But be careful what you wish for... http://www.gitguys.com/topics/adding-and-removing-remote-branches/


Purrs and kisses!

MTM616

P.S. Yes, I totally copy-pasted this from last year's hackDuke git repository.
