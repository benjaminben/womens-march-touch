## THIS IS OUR PROCESS:

### Pushing Changes
```
git checkout [your branch] //work from your personal branch, if you aren't already

//BLAHBLAHBLAH make your changes in Touch
//Make sure to reexport your .tox files / containers that you've edited

git status //see list of altered files
git diff //see changes made (probably moot since binary data but yea...)
git add [list] [of] [changed] [files] [space] [separated]
git commit -m "[message describing what is changed]"
git push origin [your branch]
```

### Receiving Updates
```
git checkout [your branch] //work from your personal branch, if you aren't already
git pull origin [other branch] //pull changes from other teammate
git merge [other branch] //merge changes from other teammate's branch into into yours
```

🍻
