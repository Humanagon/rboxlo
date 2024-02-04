<p align="center">
<img src="https://github.com/orcfoss/Rboxlo/raw/trunk/Branding/Logos/Primary/Big.png" width="60%"><br><i>Project Eclipse 🌙</i>
<br><br>
<a href="https://github.com/orcfoss/Rboxlo/blob/master/LICENSE">
	<img src="https://img.shields.io/github/license/orcfoss/Rboxlo" alt="GitHub License">
</a>
</p>
<hr>

Rboxlo is a **free and open-source** Roblox private server that can be used to relive childhood memories and create new ones. Using Rboxlo, you can set-up your own Roblox private server in minutes with the ability to play Roblox clients dating all the way back to 2007, and as modern as 2017. Rboxlo was created to truly decentralize Roblox, and to eventually eclipse the proprietary closed source Roblox revivals that exist today.

**NOTE:** Rboxlo hasn't had an official release yet, meaning that everything here is still in a "pre-release" stage. However, you can check the current status [here!](https://github.com/orcfoss/Rboxlo/blob/trunk/ROADMAP.md)

## Features

<img src="https://github.com/orcfoss/Rboxlo/raw/trunk/Branding/Artwork/SwordNoob.png" align="right" width="20%">

**Fully open-source and decentralized**

There is no official "Rboxlo hub" or any network where Rboxlo instances connect to and meet up. What you do on your Rboxlo instance remains private forever on your instance. The entirety of Rboxlo's source code is available here, and is released into the public domain, making it so that nobody can claim individual copyright over any part of Rboxlo.

**Multiple client version support**

Rboxlo supports Roblox clients as old as 2007 to Roblox clients as modern as 2017. No matter what Roblox game executable you have, it will work on Rboxlo. Rboxlo also implements all Roblox API endpoints, past or present, to ensure 100% stability with former Roblox clients and (hopefully) older applications designed to work with older APIs.

**Easy to set-up**

Setting up Rboxlo is a process that is very quick. You do not need to be a proficient sysadmin to figure out how to get the ball rolling.

**Modern-day codebase, secure**

Rboxlo does not use archaic technology, and is built using modern-day containerization. Rboxlo also tries to use only the best security practices wherever possible.

**Customizability**

Make Rboxlo yours by customizing every single aspect of the platform. Whether it be the sites theme, the logos, the artwork, or even the color of something as small as the login button, everything is customizable from a single web panel.

## Deployment

**Tech stack:**

- **Node.js** powers the server and everything surrounding it (REST API, matchmaker, etc.)
- **MariaDB** powers the server's database, where all permanent data is stored
- **Docker** containerizes the server and runs it all in a secure fashion
- **.NET** is what the client applications are built on for smooth execution

**Requirements:**

- **Docker** 20.10.0+
- **Visual Studio** 2019+

The requirements are very short and sweet because Docker is used to run the entire server, and Visual Studio is used to build the client applications. Detailed instructions on how to deploy Rboxlo are available in [GUIDE.MD](https://github.com/orcfoss/Rboxlo/blob/trunk/Setup/GUIDE.md).

## Contributing

Rboxlo is licensed with the **MIT License**.

We ask that all potential contributors take a look at the [code of conduct](https://github.com/orcfoss/Rboxlo/blob/trunk/CONTRIBUTING.md) before contributing in order to ensure healthy discourse.

If you find any problem(s) in Rboxlo, feel free to submit an issue. This includes stuff like vulnerabilities, or even the most trivial issues (such as typoes.)

If you would like to suggest a feature or change, submit it as an issue as well; it will be given the appropriate tag once we have seen it.

If you know how to fix an issue, feel free to make a pull request for the issue.

## License
```
Copyright (c) 2021 ORC Free and Open Source Software

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
