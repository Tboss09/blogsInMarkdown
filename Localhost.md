## How to view a Website (Create-React-App) hosted on port 3000 in your phone's browser😲😨🥶.

---

### Almost every developers want to have a feel on how some animations, positioning of some element or the whole website would look on Mobile devices,Tablets and so on.Luckily for us, we have _DevTools_ _(`Ctrl` + `Shift` + `i` or `F12` to activate)_ built in on all browsers in which we could view our websites in different resolutions..

### The thing is _DevTools_ isn't always 100% accurate and sometimes a website perfectly built and tested with `Chrome` _DevTools_ could look way worse on `Firefox` not to go close to the almighty `Internet Explorer`. I once faced this and it left me depressed for days..

### That was when i made some research and found about Chrome Remote Debugging and trust me its been fun ever since.

---

### **So for this project we will need :**

1. A USB Cord
1. [Chrome Canary](https://google-chrome-canary.en.softonic.com/ 'Install Chrome Canary from Softonic')
   installed on your desktop
1. [Chrome Beta](https://play.google.com/store/apps/details?id=com.chrome.beta 'Install Chrome Beta on YOur Laptop')
   installed on your phone <br> <br>

#### First off we need to configure our Phone( by enabling it for USB debugging)

- Step 1 :

#### Search for `build number` in your settings. You can find it if you go to :

```
 Settings > About Phone > Build Number
```

and click on the `Build number` 7 times or infinitely till you see the
notification

> You are now a developer

to make the `Developer Options` accessible on your mobile device

![alt text](img/FotoJet.png 'Steps to getting  developer options accessible on your phone')

- Step 2:

####

Go to:

```
Settings > System > advanced > Developer Options
```

Or alternative;y Search for `Developer Options`, Turn it on, Scroll to
`USB Debugging` and switch it on...

![alt text](img/devOptions1.png 'Switching on Developer Options')

<div align="center">
  <small> NOW WE ARE DONE WITH THE PHONE CONFIGURATION 
  </small>
</div>

<br>

<div align="center">
  <h2>
Lets Move to Desktop Configuration:
  </h2>
</div>
<br>

- Step 1 :

```
Connect Your USB Cord to the Desktop then to your mobile Device
```

<p>
Make Sure you have Chrome Beta opened on your mobile device

</p>

- Step 2

Open Chrome Canary then type in address bar, type in:

```
chrome://inspect
```

<br>
<br>
<h3 align ="center">
You would receive a Notification
on your mobile device
</h3>

<br>

![alt text](img/Capture3.png 'Accept USb Debugging Options')

---

<br>

<br>
<h4 align ="center">You should see something like this on Chrome Canary</h4>

![alt text](img/Capture4.png 'Chrome Canary View')

#### Now your phone Browser _(Chrome Beta)_ is connected to _Chrome Canary_, Any tab you open on your phone's Browser (Chrome Beta) would show automatically on this page

<br>

![alt text](img/snapshot.png 'Snapshot of your screen on Chrome Canary')

<p style ="color:gray; text-align:center; font-size:14px; width:80%; margin:auto;">
 A cool feature i like about this is the
 <code>inspect</code> option which takes a snapshot
of your phone and syncs every activity you do on Chrome Beta with Chrome Canary
</p>
<br>
<br>
<h2 align ="center">
Here is where the fun begins</h2>

![alt text](img/PortGrid.jpg 'Snapshot of your screen on Chrome Canary')

#### You would see a button with the word `Port Forwading`,

<br>

Click on it Then a dialog pops up with heading

```
Port Forwading Settings
```

Then you see two input fields

The First has a placeholder of `Port`, Type

```
 3000
```

The Second has a placeholder of `IP ADDRESS AND PORT`, type in

```
localhost:3000
```

Then click on _`Enable Port forwarding button at the End of the dialog`_

After that click _Done_

Wait don't tell me thats all😨, But yes, That is all 😜.

## Now type in

```
http://localhost:3000/
```

in your Phone's Browser (_Chrome Canary_)

![alt text](img/screen.gif 'Snapshot Of Localhost on browser')
