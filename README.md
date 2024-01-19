# VSCodium - Windows 7, 8 & 8.1 backport

This isn't really a fancy readme but I don't give a shit,
also shoutout to cozmo (https://www.github.com/CozmoDev). Also if you hate Alex313031, this is a great replacement for his VSCodium fork

### Anyways, this port uses electron 22 as a base, if you wanna do this yourself, here are the 2 only methods u can port VSCode (or any electron app in general to windows 7):

- completely compile this yourself (which is a pain in the ass from personal experience BUT it is possible and it will work, please reffer to actual vscode documentation tho)

- or you can just compile the default electron 22 app, then copy everything except for the "resources" (like in the image bellow)

<p align="center">
  <img alt="a" src="https://media.discordapp.net/attachments/721626533290180730/1198017044470321253/image.png">
</p>

now that you copied the electron files that WILL work on windows 7, copy them over to the directory of your desired VSCode (which should look something like this)
<p align="center">
  <img alt="a" src="https://media.discordapp.net/attachments/721626533290180730/1198017573514657852/image.png">
</p>

after that, delete Code.exe (cuz it wont work) and rename electron.exe to "Code.exe" (its the replacement executable pretty much)

<p align="center">
  <img alt="a" src="https://media.discordapp.net/attachments/721626533290180730/1198021416164003851/image.png">
</p>


and boom, youre done! just make sure you get the right electron build, ill update this readme if this method ever stops working for the people that cant code to be able to reproduce, or u can be an actual programmer and just manually compile with electron28 and then add supermium-electron (quick shoutout to win32)

here is a screenshot of the finished product

<p align="center">
  <img alt="a" src="https://media.discordapp.net/attachments/721626533290180730/1198021932960989346/image.png">
</p>

if this documentation is too shitty for you to understand just dm me on discord and ill help you (discord tag: aiek.)
