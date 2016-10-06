
# Chapter 9: Making Empty Files (Touch)

## Do More

### Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.

```
Evans-MacBook-Pro:do_more_chapter_9 Evan$ mkdir temp
Evans-MacBook-Pro:do_more_chapter_9 Evan$ cd temp
Evans-MacBook-Pro:temp Evan$ mkdir temp2
Evans-MacBook-Pro:temp Evan$ cd ../
Evans-MacBook-Pro:do_more_chapter_9 Evan$ rmdir temp2
rmdir: temp2: No such file or directory
```

I cannot remove the temp2 directory because I am not in temp.  The temp2
directory is in temp, not do_more_chapter_9


