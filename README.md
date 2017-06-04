# LoveCraft
A place for scripts that can speak to your loved ones.


*** Edit the script ***
Right click the hp-start script and choose Open With > Script Editor

![](images/editTheScript.png?raw=true)  

*** Change the defaults ***
1. Change the time  

This line causes the application to terminate at 6pm.  
```
set endTime to 18 * 60 * 60 -- 6pm
```

2. Change the phone number.  

Insert the desired phone number in place of '15555555555'

```
set phone_number to "15555555555"
```

3. Add your own messages!  

The script already has a few example messages.  
```
set messageList to {"😍", "😘", "Hey, Just wanted to say I love you!", "Hope you're having a good day!", "Can't wait to see you tonight!"}
```

4. Checkout out the random message modifiers  

Look for the following function  
```
on modifyMessage(message)
```

*** Create the application ***

Choose File > Export...

![](images/export.png?raw=true)  

Change the File Format to "Application"  
Choose 'Stay open after run handler"  

![](images/save.png?raw=true)

An "hp-start" Application will appear in the same directory.  
You can either double click this or run it from the command line.  
