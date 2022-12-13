# Idea
A bash script for quick note/idea taking

## Usage:
Record a quick idea:
<br>
```console
$ idea this is a quick note
```


Record something longer:
<br>
```console
$ idea
```
<i>Note: A line is only recorded when enter/return is typed. Finish recording with CTRL+C/D</i>
<br>


See your ideas:
<br>
```console
$ idea -l
```


For full possibilities:
<br>
```console
$ idea -h
```

## How-to:
1. Put the **idea** script with your other **bin**aries, or in a separate folder, but then don't forget to include that folder to your **PATH** variable (There are plenty of resources out there if you don't know how to do the latter)
2. Add execution rights to it: ```$ chmod u+x idea```
3. Rehash to use instantly: ```$ rehash``` 

## Note:
* It's currently not fully input proof, but <i>no input should</i> cause usage-breaking behavior
* *Obviously* it only works in macOS and Linux distros, or any environment whos file system has '/' as a seperator and can run bash
