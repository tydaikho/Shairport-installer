Shairport-installer
===================
The 'shairport-installer.sh' script installs an Airport-like server on your Debian machine called 'Shairport' developed by 'abrasive' (Github). This means that Airplay-supported devices can airplay music through the speakers connected to your Linux machine. Examples of airplay supported devices: IOS-devices and rooted Android with e.g Airaudio app installed. The devices must be connected to the same network as the Linux machine to get access. Shairport solely allows for playing music. There is a video equivalent from another repository that I currently haven't tried it out.<br/>
The Shairport system should work for Fedora users as well but they need to check if the packages in the script suits their distro and find its equivalent if not.<br/>
First time you run the 'shairport-installer' script the shairport server will start automatically but when you want to start it next time you should run the 'run_shairport' script created on your desktop. 

<h3>Guide:</h3>
<ol>
<li>Download 'shairport-installer.sh' to any location on your Linux machine - the desktop for instance</li>
<li>Use the terminal to get directed to the file location; <code>cd Desktop</code></li>
<li>Install shairport, create run_shairport.sh on desktop and run shairport first time: <code>sudo sh shairport-installer.sh</code></li>
<li>Now the shairport server should run in your terminal:<br/>
<code>Listening for connections.<br/>
11758</code> (new number each run)<br/>
Look for 'Shairport' on your Airplay device and play music. If it works, you can then remove the 'shairport-installer.sh' file.</li>
</ol>

src: https://github.com/abrasive/shairport

