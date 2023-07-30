<div id="container">
    <div id="sidebar">
        <fieldset>
            <legend>Table Of Contents</legend>
            <ul>
                <li><a href="#Setup&Start"><b>- Setup & Start</b></a>
                    <ul>
                        <li><a href="#Setup&Start#Requirements">Requirements</a></li>
                        <li><a href="#Setup&Start#Guide">Basic Guide</a></li>
                    </ul>
                </li>
                <li><a href="#Config"><b>- Configuration</b></a>
                </li>
                <li><a href="#Plugins"><b>- Plugins</b></a>
                    <ul>
                        <li><a href="#Plugins#Download">Downloading Plugins</a></li>
                        <li><a href="#Plugins#InstalationAndUpdate">Installing/updating a plugin</a></li>
                        <li><a href="#Plugins#Dev">Writing your own plugins</a></li>
                    </ul>
                </li>
            </ul>
        </fieldset>
    </div>
    <div class="articles">
        <article>
          <h1 id="Setup&Start" class="title">PieMC Documentation - Setup & Start</h1>
            <p>
                <b id="Setup&Start#Requirements">A computer or device with the following is required:</b><br>
                 - Python 3.10 or newer Installed <br>
            </p>
            <h3 id="Setup&Start#Guide">Installing, Updating and Running:</h3>
            <p>
                1. Download the latest stable version of PieMC on github. <br>
                2. Unzip the file <br>
                3. Double click on start.cmd (For windows) or start.sh (For Linux).<br>
                4. If there is any update available, it will update automatically.
            </p>
        </article>
        <article>
            <h1 id="Config" class="title">Configuration</h1>
            <p>
                Let's take a look to the configuration file: <code>config.py</code>. This file is used to store various settings for PieMC. It can be found in piemc folder.
            </p>
            <pre>
HOST = 0.0.0.0
PORT = 19132
MAX_PLAYERS = 20
GAMEMODE = Survival
LANG = en
MOTD1 = PieMC Server
MOTD2 = Powered by PieMC
DEBUG = True  ; Only For Development
            </pre>
            <p>
                In the<code>config.py</code> file, we have defined settings for the PieMC server.
            </p>
            <p>
                For example, the <code>HOST</code> setting is set to <code>0.0.0.0</code>, indicating that the server will listen on localhost. The <code>PORT</code> setting is set to <code>19132</code> (Default), specifying the port number the server will use for communication with the client. <br/>
                Other settings such as <code>MAX_PLAYERS</code>, <code>GAMEMODE</code>, <code>LANG</code>, <code>MOTD1</code>, <code>MOTD2</code>, and <code>DEBUG</code> are also defined.
            </p>
        </article>
        <article>
            <h1 id="Plugins" class="title">Plugins</h1>
            <p>
                PieMC can be extended and customized with plugins.<br/>
                A plugin is an external module which can be “plugged in” to your server to add custom features, change default behaviours and more.
            </p>
            <h3 id="Plugins#Download">Downloading Plugins</h3>
            <p>
                Discover a diverse array of pre-made plugins on our plugin Marketplace, <a href="/plugins">PieMC Marketplace</a>.
            </p>
            <h3 id="Plugins#InstalationAndUpdate">Installing/updating a plugin</h3>
            <p>
                Installing the desired plugin will be a breeze with a simple command execution. <br> 
                You can find the specific installation command in the <a href="/plugins">PieMC Marketplace</a> (Under Development).
            </p>
            
            </p>
            <h3 id="Plugins#Dev">Creating your own plugin</h3>
            <p>
                Creating your own plugin will be a seamless task, thanks to our robust and powerful development library.
            </p>
            <pre class="language-markup">// Coming Soon</pre>
        </article>
        </div>
</div>
