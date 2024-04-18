# Windows-activator

An guide how to activate Windows 10 AND 11 Pro for free

# Getting started

What you first need to do is open CMD (Command Prompt) as Administrator using this keyboard key:

![687474703a2f2f692e737461636b2e696d6775722e636f6d2f42385a69742e706e67](https://github.com/vandamme0/windows-activator/assets/108348838/22d6afd0-55b8-49a6-b55a-d0e7a04e4702)+ ```R```


And now type in ```cmd.exe``` in the box

It should now look as something like this:

![134801377-b9769c34-8a9d-4d4f-ba8e-6c073f1ce4a2](https://github.com/vandamme0/windows-activator/assets/108348838/922e9559-5364-4282-82e4-431753aea47e)

Now press this keys on your keyboard:

```Ctrl``` + ```Shift ```+ ```Enter```

Now you have something like this:

![134801445-9b90e121-350b-42ea-afec-b499f1fbfae9](https://github.com/vandamme0/windows-activator/assets/108348838/2f2060e8-0cf0-47e1-9e7a-c6c18aa196d3)

Now, click on ```Yes```

Now you have something like this:


![134807479-53ccdaf9-feb0-49a3-9843-5bb4db016128](https://github.com/vandamme0/windows-activator/assets/108348838/3a4be7f7-a3b5-4f74-8f84-d78fc3757df0)

# The commands

Now, type the following command: ```slmgr.vbs /upk```

Note: this will remove your current activation key! Now it will give an message, click on ```OK```

And now this command: ```slmgr.vbs /cpky``` It will give an message once again, and click on ```OK``` again

And now type this command: ```slmgr.vbs /ckms``` Once again click on OK when you get an message       

# Edition upgradable check command

Now we are gonna check of your edition is supported to upgrade to Pro, run the following command to check this: ```DISM /online /Get-TargetEditions``` If you see ```Professional``` in the list, then you can upgrade your Windows edition to Pro for free!

# Running Windows Pro installer

Now, copy and paste this complete command:

```sc config LicenseManager start= auto & net start LicenseManager```

```sc config wuauserv start= auto & net start wuauserv```

```changepk.exe /productkey VK7JG-NPHTM-C97JM-9MPGT-3V66T```

```exit```

It will run an installer and you will see an message: ```% complete```

Now wait until it's 100% and then you get an error (This is normal, this needs to happen.)

When you get the error, just click Exit and then reboot your pc.

You will now see an message that he is running updates and is installing features, just wait until its done and check``` info``` in settings, You will see that Windows 10/11 Pro is installed! (May show Windows Enterprise, but will be Windows Pro!!)

But we are not done, You will see that it isn't activated and that you can't change some settings, now we are gonna fix that!
