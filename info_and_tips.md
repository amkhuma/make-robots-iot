### Below are some tips and instructions that might help on Make Day :)

-----

#### Working on the Pi

* We've installed the Pi-compatible version of VS-Code. You can open it from the Programming section on the Taskbar, or you can open the directory you're in from the command line with the following command:
`$ code-oss .`

* If you want to install a different editor or extra extensions then go ahead! Remember that not everything you're used to has an ARM-compatible version.


#### Control the Pi with VNC

You might want to code on your own machine and not on the Pi itself. In that case, you can control the Pi from your own machine with VNC. Here's how to do it:

* Click on the VNC icon on the top-right of the control panel

* Not the IP address of your Pi

* Use VNC-Viewer on your own device and connect to the IP Address of your Pi

* You will be asked for a username and password: Enter "pi" and "raspberry" for these

* That´s it!


#### Version Control and Github

Sharing is good, so contribute to the community by pushing your code to Github! Also, you probably want to have the code you write on your own Github profile. We've established a convention for version control, so please note the following:

* In any of the activity repos, make a branch named after the team members' names or with the the members' Github handles. E.g. if your team consists of members Sally, Mark and Thando (with Github handles Sal88, markymark and Tmann), then name the branch "sally-mark-thando" or "Sal88-markymark-Tmann. Please prefix the branch with "groups", So:

    `$ git checkout -b groups/sally-mark-thando`, or

    `$ git checkout -b groups/Sal88-markymark-Tmann`
<br>
* Push this branch to the repository:
    `$ git push origin groups/sally-mark-thando`
<br>
* Since you have been added as a collaborator to the OfferZen-Make team, you have access to the repo and branch from your own account. Therefore go ahead and fork that branch on Github so that you ¨own¨ the code.

NOTE: If you have any comments/suggestions about the process above then please send a message to @dan and/or @nuclearnic on Slack :)


#### Additional Info and Resources

* Check out the Sphero CLI we´ve created here: https://github.com/OfferZen-Make/sphero-cli
<br>
* If you want to play around with Gobot, it is already installed. Check out `/home/pi/go/src/gobot.io/x/gobot` and ask the Make Masters for help. Golang is tricky if you haven´t used it before! ;)
