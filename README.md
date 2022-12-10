# Idea
A bash script for quick note/idea taking

## Usage:
Record a quick idea:
<br>
```> idea this is a quick note```


Record something longer:
<br>
```> idea```
<br>
<i>A line is only recorded when enter/return is typed. Finish recording with CTRL+C/D</i>


See your ideas:
<br>
```> idea -l```


For full possibilities:
<br>
```> idea -h```

## How-to:
1. Put the **idea** script with your other **bin**aries, or in a separate folder, but then don't forget to include that folder to your **PATH** variable (There are plenty of resources out there if you don't know how to do the latter)
2. Add execution rights to it: ```> chmod u+x idea```
3. Rehash to use instantly: ```> rehash``` 

## Note:
* It's currently not fully input proof, but <i>no input should</i> cause usage-breaking behavior
* *Obviously* it only works in macOS and Linux distros, or any environment that can run bash. Read that as of windows 10, windows can run bash too, idk haven't tried it yet, try it and let me know! 😄
