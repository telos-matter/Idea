# Idea
A bash script for quick note/idea taking

## Usage:
Record a quick note:
<br>
```console
$ idea this is a quick note
```

Record something longer as a project idea:
<br>
```console
$ idea -c project
...
```

See all your todos:
<br>
```console
$ idea -l todo
```

For all possibilities:
<br>
```console
$ idea -h
```

## How-to:
1. Put the **idea** script with your other **bin**aries, or in a separate folder, but then don't forget to include that folder to your **PATH** variable (There are plenty of resources out there if you don't know how to do the latter)
2. Add execution rights to it: ```$ chmod u+x idea```
3. Rehash to use instantly: ```$ rehash``` 

**Note**:
* Not fully input proof, but <i>no input should</i> cause future usage-breaking behavior
* *Obviously* it only works in macOS and Linux distros, or any environment whos file system has '/' as a seperator and can run bash
* When recording an idea:
  * A line is only recorded when enter/return is typed. Finish recording with CTRL+D
  * On macOS CTRL+D is usally mapped as a shortcut, either remove that mapping or use CTRL+C instead to stop a recording
