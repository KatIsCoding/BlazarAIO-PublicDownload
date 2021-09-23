# Blazar V3 Public Download
> Current Version 3.3.0b

#### Hello everyone!! Dev here! After some time of working on this great project, we finally have a stable version which we decided to launch, we totally acknowledge that this version is far from being perfect, however, we will continue to work on this amazing project and continue making it even better.

## Debugging

#### During alpha testing we didn't find any important bug, however, if you happen to find one, here is a quick guide on how to report it:
- Open a Ticket in our Discord Group
- Give a small description of what you were doing before the bug happened
- Open the app files
- We need you to send us the following files: "buildFile", "debug.txt", "log.txt"
- Sometimes you won't be able to find the "log.txt" file, don't worry about it! Just send the others.


After this, we will do all the hard work and try to diagnose your bug, if we happen to find it as a really problematic bug, we will be updating the app with a hotfix for that.

## Next features

- AutoUpdater
> We know how frustrating is to always be downloading this really big file every time we want to get the newest version, that's why our first priority is to make an AutoUpdater and AutoInstaller that will do all this boring work for you in the most efficient way.

- More Sites!!
> For now we have a kinda small list of available services compared to past versions, this is because we have been rebuilding all our modules so we can have that extra speed we know you like, however, this task happens to be really complex and slow (especially for those difficult sites), the idea we had to start implementing more modules is to make polls where you can participate to help us decide which module should be added next time, this way we can know for sure we are in the right direction.

- Make Dashboard useful
> Our current app dashboard looks really great and everything and we know it would be even cooler if it had any functionality, however, we considered this to not be a big concern for now and that's why we decided to leave this for later and focus on other aspects such as the improvement of our current modules.

- ???
> We will be making some public polls for all of you so we can know what is the next thing you would like to see in our next versions!!

## Acknowledgments 

- There is a bug affecting Nike's genner that slows down the account generation, we are working on this and the next immediate patch will be a hotfix for this problem.
- Currently our app is using a big chunk of disk usage, we are working on a solution for this and we are sure once we have the AutoUpdater feature this will get better.

## How to use
> We considered the information above this section as really important, please read it if you haven't

### Installation
##### Since v3.1.0b the AutoUpdates were introduced, that's why we will need you to do some extra steps in order to be able to use that feature
- Download [this file](https://cdn.discordapp.com/attachments/637141086334222369/890399171197145118/install.ps1) and move it to the folder were you want to install BlazarAIO
- Right click the file named "install.ps1" and then left click the option `Run with PowerShell`
- A blue window like the following should appear: (Ignore the contents of the following image since it may vary in your case)
- ![img](https://media.discordapp.net/attachments/858836866823094272/887919689647407144/unknown.png)
- In the best case scenario, no user input will be needed, however in some cases you will need to input "Y" when it prompts it **Be sure to always use capital letters(Y) for those**
- After that, an admin rights window might appear, which you just need to click Yes
- Once it finishes it should say: "Press Enter to continue..."

**Notes:**

- In case you skipped a step (For example, didn't use capital letters) please create a ticket with the message `AutoUpdates#551` and the dev directly will come to you in order to help with your problem
- In case you already had git installed or want to install it by your own, you can skip this step, however we encourage you to install `Chocolatey` since it can be used in future updates
- In case an error pop up shows once you open the app, please open a ticket with a screenshot of the error and the message `AutoUpdates#1` and the dev directly will come to you in order to help with your problem

### Usage
- Inside the unzipped folder you'll find a BlazarAIO.exe file, execute and you are good to go
- We consider our GUI really user friendly, that's why we invite you to explore everything the app has to offer, however, if you are not sure of how something works, let us know ;)



### Changelog
## v3.0.1b
- Fixed "Only Nike" Bug
> Next version features include AutoUpdater and Nike SMS mode

## v3.1.0b
- Added AutoUpdater
- Started the development of Nike SMS module

## v3.1.1b
- Added Head toggle option

## v3.2.2b
- Fixed False Positives in Nike Module
- Implemented the ability to add proxies using breaklines

## v3.3.0b
- Invite only beta started!!
