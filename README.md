# Wreeper's Beginner Resources
Hello! Before we are getting started, I'd like to introduce myself. I'm most commonly online known as Wreeper, having a site at https://wreeper.com/, and at the moment of writing this I'm currently a student having information technology as both a study objective and a hobby. After writing personalized advice for a classmate who later decided that gaming is better than trying to learn something, I thought that maybe instead of trying to continue to help a single person, I should improve my list a bit and put it on GitHub so that eventually someone may find it useful too.

This is not exactly a tutorial, but rather a list of tools and/or projects I compiled together that may already or may not already be well-known so you get to have a starting point. I have been working on this list when I found time and motivation to do so, and I recommend that you experiment getting stuff done alone after getting examples and documenting yourself well enough so you get actual hands-on experience.

This list of resources and explanations will assume that you already know basic terminology. I recommend using the internet within your best interest to find out what a thing means if you're having trouble understanding it. Please note that multiple things on this list may have a dedicated Wiki site for them that you can search and further document yourself on.
## Table of contents
- [Getting experience with servers and systems](#getting-experience-with-servers-and-systems)
  - [Linux distros you can get started with](#linux-distros-you-can-get-started-with)
  - [Booting an operating system up](#booting-an-operating-system-up)
  - [Connecting to a server via SSH](#connecting-to-a-server-via-ssh)
  - [Programming languages and environments](#programming-languages-and-environments)
- [Service providers](#service-providers)
  - [Servers](#servers)
  - [Domains](#domains)
  - [Tunneling](#tunneling)
- [Having issues](#having-issues)
## Getting experience with servers and systems
This is the most important aspect in my opinion, so I'm starting with it. Whether you want to develop software, websites, games, eventually you'll hit the need for a server designed to serve a purpose.
### Linux distros you can get started with
Most servers are running on Linux distributions. A server is essentially a computer, just like your PC. Naturally, having some Linux experience will not hurt.
| Name | Description | Link |
| ---- | ------- | ---- |
| **Debian** | Minimal resource usage and very adopted with much support, updates designed for stability | [debian.org](https://debian.org/) |
| **Ubuntu** | Debian fork focused on ease of use and latest updates | [ubuntu.com](https://ubuntu.com/) |
| **Linux Mint** | Ubuntu fork with ease of use appealing to desktop users | [linuxmint.com](https://linuxmint.com/) |
| **Arch Linux** | The origin of the meme *"i use arch btw"*, will give you a challenge | [archlinux.org](https://archlinux.org/) |
| **Kali Linux** | Distribution containing tools for pentesting and digital forensic science | [kali.org](https://www.kali.org/) |
| **Termux** | Terminal emulator and Linux environment app for Android devices | [termux.dev](https://termux.dev/en/) |
### Booting an operating system up
Depending on how you want to use an OS and what you want to do with it, these tools definitely came handy to me at one point or another. Experience with some will likely make you have a better understanding and confidence in yourself.
| Name | Description | Link |
| ---- | ------- | ---- |
| **VirtualBox** | Tool to run virtual machines on your computer | [virtualbox.org](https://www.virtualbox.org/) |
| **Docker** | The standard way to create isolated, ready-to-use containers | [docker.com](https://www.docker.com/) |
| **Rufus** | WINDOWS-based utility to create bootable drives | [rufus.ie](https://rufus.ie/en/) |
| **netboot.xyz** | iPXE bootloader allowing you to install operating systems over network | [netboot.xyz](https://netboot.xyz/) |
| **Ventoy** | Tool to create a USB drive with multiple bootable operating systems | [ventoy.net](https://www.ventoy.net/en/index.html) |
| **Proxmox VE** | Virtualization platform (OS) that lets you make multiple virtual machines | [proxmox.com](https://www.proxmox.com/en/products/proxmox-virtual-environment/overview) |
| **WSL** | Windows Subsystem for Linux is an alternative running a Linux VM from inside Windows | [learn.microsoft.com](https://learn.microsoft.com/en-us/windows/wsl/) |
### Connecting to a server via SSH
You will likely not use and carry around a keyboard to connect to a personal server at home for management, so you'll likely need to manage it remotely. Here's some tools that allow you to do just that.
| Name | Description | Link |
| ---- | ------- | ---- |
| **OpenSSH** | By far the standard tool for remote login with the SSH protocol | [openssh.org](https://www.openssh.org/) |
| **MobaXterm** | AIO terminal for Windows featuring dancing penguins when idle | [mobaxterm.mobatek.net](https://mobaxterm.mobatek.net/) |
| **Termius** | Cross-platform SSH client with syncing features | [termius.com](https://termius.com/) |
| **Termux** | Terminal emulator and Linux environment app for Android devices | [termux.dev](https://termux.dev/en/) |
## Programming languages and environments
It helps you to know how to code! Depending on what you are willing to do, learning some of these may help. Getting yourself familiar with most of them will be great to understand complex things later on.
| Name | Description |
| ---- | ------- |
| **C++** | Very useful programming language used for game development, system software, and resource critical applications |
| **Python** | Beginner friendly, readable language, widely used for automation, robotics, scripting, data analysis and backend development |
| **PHP** | A general-purpose scripting language being used primarily for creation of website backends |
| **Java** | High-level, general-purpose, memory-safe, object-oriented programming language (not to confuse with JavaScript) |
| **JavaScript** | You know, the core language of the web that runs inside browsers to make websites interactive (not to confuse with Java) |
| **C#** | C-Sharp, Microsoft's programming language designed to run on the .NET framework, considered to be a descendant of C++ and Java |
| **Bash** | Bourne Again SHell, scripting language useable in Linux shells to automate various terminal tasks and system administration |
| **HTML** | Hypertext Markup language for documents to be displayed in a web browser |
| **CSS** | Cascading Style Sheets, style sheet language used for specifying the presentation and styling of a document written in a markup language |
| **NodeJS** | Cross-platform, open-source widely used JavaScript runtime environment that lets you run JavaScript code on the serverside |
## Service providers
Eventually, you might need a domain for your project, or a server, or something like that. This list may help you get to the right place.
### Servers
| Name | Description | Link |
| ---- | ------- | ---- |
| **LowEndBox** | Newer starting hosting providers can offer servers at attractive prices | [lowendbox.com](https://lowendbox.com/) |
| **Hetzner Online** | Despite the price increases regarding RAM, it remains a solid competitor | [hetzner.com](https://www.hetzner.com/) |
| **OVHcloud** | Well-known European hosting provider operating for a long time | [ovhcloud.com](https://www.ovhcloud.com/) |
| **Contabo** | Historically known as cheap, but the RAM crisis affected everyone | [contabo.com](https://contabo.com/en/) |
| **Netcup** | Notorious for calling you to ask you about near gas stations, but known for good prices | [netcup.com](https://www.netcup.com/en) |
### Domains
Where to find domains? There are countless of places where you could get a domain from or document yourself about domains on, but what I can recommend you is avoiding the classic $1 traps registrars will set up.
| Name | Description | Link |
| ---- | ------- | ---- |
| **Porkbun** | Often has good prices and supports many TLD's | [porkbun.com](https://porkbun.com/) |
| **Cloudflare Registrar** | Registers domains at registrar cost prices (WARNING! IT REQUIRES USAGE OF CLOUDFLARE DNS) | [cloudflare.com](https://www.cloudflare.com/domains/) |
| **TLD-List.net** | List of register and renewal prices of multiple TLD's across many registrars (not a registrar itself) | [tld-list.com](https://tld-list.com/) |
### Tunnelling
Tunnelling is very important, especially if you plan to host services from your own home or you want a secure way to access your local servers remotely. Whatever may be your use case, these will come in handy!
| Name | Description | Link |
| ---- | ------- | ---- |
| **WireGuard** | General purpose VPN technology and tunnel to setup yourself | [wireguard.com](https://www.wireguard.com/) |
| **Cloudflare Tunnel** | Tunnel designed to connect origin servers to Cloudflare without opening the ports up to the Internet | [developers.cloudflare.com](https://developers.cloudflare.com/tunnel/) |
## Having issues
You're looking for something? Perhaps a fix to your issue? Below are some places that helped me get around.
| Name | Description | Link |
| ---- | ------- | ---- |
| **Reddit** | The IT-related Reddits may be a good source of information | [reddit.com](https://reddit.com/) |
| **StackOverflow** | Forum based on questions and answers about programming | [stackoverflow.com](https://stackoverflow.com/questions) |
| **AskUbuntu** | If you have issues with Ubuntu/Debian, someone probably asked it here | [askubuntu.com](https://askubuntu.com/) |
| **SuperUser** | Forum about computer hardware, software, and general desktop usage |[superuser.com](https://superuser.com/) |
| **Unix & Linux Stack Exchange** | Forum based on questions and answers for users of Linux, FreeBSD and other Un*x-like operating systems | [unix.stackexchange.com](https://unix.stackexchange.com/) |
