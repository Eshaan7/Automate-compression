# Automate-compression
## What the script does: 
  1. goes into a directory(user inputs the directory path)
  2. Archive all files recursively to .tar and pipe them through gzip -9 to get
     best compression creating <>.tar.gz
  3. Appends all of these individual <>.tar.gz files into another tarball.
  4. Finally .tar #{compress ffs please} > .tar.gz  
   
## Why python as well as shell script ?
  Wrote it in python first because python makes everything easier, but the code got messy and there were alot of system calls so it hit me that shell script will be a better option and it was..Win-win or lose-lose, that you decide.

## Notes
 The script works best with text files. Even so much that a friend of mine converted 40 gigs to 100mb. 
 <p align="center"><img src="https://image.slidesharecdn.com/codingsuperpowersupershort-140924145900-phpapp02/95/coding-superpower-1-638.jpg?cb=1411571210" height="150" width="150" align="center"></p>
 P.S. This is actually my first repo with python and bash code. Enjoy!
    
