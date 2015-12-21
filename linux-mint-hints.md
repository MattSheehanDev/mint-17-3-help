## Linux Mint ##


###### Repeat the previous command ######
```
$> !!
```
Ex.<br/>
$> apt-get install package *Error, need root permission*<br/>
$> sudo !! *Success*


###### Adds program to environment path ######
```
$> sudo ln -s /path/to/program
```
Ex.<br/>
$> sudo ln -s /usr/bin/nodejs /usr/bin/node


#### Packages ####

###### Install package ######
```
$> sudo apt-get install <package>
```

###### Removes package and all configuration files (--purge) ######
```
$> sudo apt-get --purge remove <package>
```

###### Update package ######
```
$> sudo apt-get update
$> sudo apt-get upgrade <package-name>
```
Ex. <br/>
$> sudo apt-get upgrade firefox

###### Returns available packages related to search term ######
```
$> apt-cache search <search term>
```

###### List all installed packages ######
```
$> dpkg --list
```

###### Make directory ######
```
$> sudo mkdir <directory path>
```

#### Mount Drives ####
###### Mount drive to directory ######
```
$> sudo mount <path of mount drive> <directory path>
```

###### Mount drive to directory as read only ######
```
$> sudo mount -o ro <path of mount drive> <directory path>
```

###### Show process id's ######
```
$> ps [-u|-C|-A|-N|x]
```
[user name|command name|All processes|negate selection|processes without controlling ttys]


#### Utilities ####
###### Parse with regex ######
```
$> grep <regex>
```

###### Print exit code ######
```
echo $?
```
Returns previous command's exit code. An exit code of 0 indicates successful execution.
Ex. <br />
$> rm unknown-file.txt *Error file does not exist* <br />
$> echo $? *Returns 1*

###### Switch workspace ######
```
Ctl + Alt + [arrow-key]
```
