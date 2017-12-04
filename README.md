# Forewords

This repository contains a list of CLI apps with links and a short description.

This ``README`` file is automatically generated from ``cli-apps.yaml`` using ``cli2md.py`` (it requires the ``yaml`` package to run).
It is commited into the repo for easier access to the content.

Type

```
make
```

to build the latest version of ``README.md``.

# Summary

To date, **188** apps/tools covered, divided in **30** categories; **8** related sites reviewed and listed.

# Index

[Backup](#backup) (3) | [Chat and instant messaging (IM)](#chat) (5) | [Conversion](#conversion) (3) | [Data transfer](#transfer) (11) | [Editors](#editors) (11) | [Email](#email) (6) | [File and file system handling](#file-handling) (14) | [File manager](#file-manager) (5) | [File systems](#file-systems) (2) | [Font management](#font) (2) | [Funny tools](#funny) (6) | [Games](#games) (8) | [Graphics](#graphics) (2) | [Networking](#networking) (5) | [Office tools](#office) (4) | [Organizers and calendars](#organizers) (14) | [Productivity](#productivity) (4) | [Security and encryption](#security) (6) | [Shells](#shells) (3) | [Sound and music](#music) (8) | [System monitoring](#monitor) (14) | [System tools](#system) (7) | [Terminals](#terminals) (5) | [Text processing](#text-processing) (7) | [Text search](#text-search) (4) | [Utilities](#utility) (10) | [Versioning](#versioning) (5) | [Viewers](#viewers) (6) | [Web browser](#browser) (4) | [Web development](#webdev) (4)

Some links to [related resources](#resources).

I'm always interested to new tools, so if you have any suggestion please drop me an email at `toolleeo@gmail.com`.

## <a name="networking"></a>Networking

#### [ipcalc](http://jodies.de/ipcalc)

"ipcalc takes an IP address and netmask and calculates the resulting broadcast, network, Cisco wildcard mask, and host range." 

References
* [How to Calculate Network Addresses with ipcalc](https://www.linux.com/learn/intro-to-linux/2017/8/how-calculate-network-addresses-ipcalc) (rev. 2017-10-07) - The math behind IP addresses is convoluted...



#### [PSSH](https://code.google.com/archive/p/parallel-ssh/)

PSSH provides parallel versions of OpenSSH and related tools. Included are pssh, pscp, prsync, pnuke, and pslurp. The project includes psshlib which can be used within custom applications.

References
* [PSSH - Execute Commands on Multiple Linux Servers in Parallel](http://www.2daygeek.com/pssh-parallel-ssh-run-execute-commands-on-multiple-linux-servers/) (rev. 2017-07-10) - By default everyone prefers openSSH to connect remote Linux servers. openSSH is one of the best tool to connect remote server securely and doing the job perfectly but it doesn’t have the features to execute commands on multiple Linux servers simultaneously, this is where Parallel SSH came to picture.


#### [rtop](http://www.rtop-monitor.org/)

rtop is a simple, agent-less, remote server monitoring tool that works over plain SSH. Written in golang, it does not need any software to be installed on the server that you want to monitor. It works by establishing an SSH session, and running commands on the remote server to collect system metrics.

References
* [rtop - A Nifty Tool to Monitor Remote Server Over SSH](http://www.2daygeek.com/rtop-monitor-remote-linux-server-over-ssh/#) (rev. 2017-07-10) - rtop is a simple, agent-less, remote server monitoring tool that works over SSH. It doesn’t required any other software to be installed on remote machine, except openSSH server package & remote server credentials.


#### [geoiplookup](https://github.com/maxmind/geoip-api-c)

a little application to find geographical and network information of an IP address based no the geoip C API.

References
* [How To Find The Geolocation Of An IP Address From Commandline](https://www.ostechnix.com/find-geolocation-ip-address-commandline/) (rev. 2017-07-10) - geoiplookup is a command line utility that can be used to find the Country that an IP address or hostname originates from. It uses the GeoIP library and database to collect the details of an IP address.


#### [quickserve](https://github.com/charliesome/quickserve)

Quickserve is a very simple HTTP server written in Python that is intended for quickly sharing files on an ad-hoc basis. Aside from opening a port in your firewall if you have one, quickserve requires no set-up and should work with no hassle.

References
* [quickserve](https://xyne.archlinux.ca/projects/quickserve/) (rev. 2017-07-10) - A simple HTTP server for quickly sharing files.


## <a name="utility"></a>Utilities

#### [dasht](http://sunaku.github.io/dasht/man/man0/README.html)

Search API docs offline, in your terminal or browser. 

#### [arch-wiki](https://github.com/deadhead420/arch-wiki)

Search the Arch Wiki anywhere from the command line. 

References
* [How To Search The Arch Wiki Website Right From Terminal](http://www.2daygeek.com/search-arch-wiki-website-command-line-terminal/#) (rev. 2017-08-09) - Whenever you search anything about Arch Linux in web browser, I damn sure the first link would be Arch Wiki. Am i right? Yes, since Arch wiki is an ideal place to get solution for most of the arch Linux issues ...


#### [googler](https://github.com/jarun/googler)

Google Search, Google Site Search, Google News from the terminal. 

References
* [Googler A Command Line Tool To Search Google](http://www.linuxandubuntu.com/home/googler-a-command-line-tool-to-search-google) (rev. 2017-08-09) - Looking for information on the web has become something that we do day in and day out. Whether it is support you are looking for, looking for a product or news about a particular topic, all you have to do is search on the web.


#### [lolcat](https://github.com/busyloop/lolcat)

Ruby Gem to colorize the output of the cat command.

References
* [lolcat : tool to rainbow color linux terminal](http://kerneltalks.com/linux/lolcat-tool-to-rainbow-color-linux-terminal/) (rev. 2017-07-10) - Paint your command outputs with rainbow color! Use lolcat (Ruby gem) tool and add some spice to black putty terminal!


#### [neofetch](https://github.com/dylanaraps/neofetch)

Neofetch is a CLI system information tool written in BASH. Neofetch displays information about your system next to an image, your OS logo, or any ASCII file of your choice. 

References
* [Display Linux Distribution Logo in ASCII Art in Terminal](https://itsfoss.com/display-linux-logo-in-ascii/) (rev. 2017-10-07) - ... You might have seen people sharing such desktop screenshot
with terminal showing the logo of the Linux distribution used in
ASCII art.



#### [pdd](https://github.com/jarun/pdd)

Tiny date, time diff calculator. 

References
* [pdd - Tool to find Date and Time Difference in Linux Command Line](https://linoxide.com/linux-how-to/pdd-tool-date-time-difference-linux-command-line/) (rev. 2017-08-09) - In some occasions where you want to check by how many years someone older than you, how old you are (in days, years or months), the countdown to an event or the next flash sale. There is a python-based command line application ...


#### [powerline](https://github.com/powerline/powerline)

Powerline is a statusline plugin for vim, and provides statuslines and prompts for several other applications, including zsh, bash, tmux, IPython, Awesome and Qtile.

#### [socli](https://github.com/gautamkrishnar/socli)

Stack overflow command line client written in Python. Search and browse stack overflow without leaving the terminal 

References
* [SoCLI - A Tool to Search Stack Overflow from Linux Terminal](https://linoxide.com/linux-how-to/socli-tool-access-stack-overflow-linux-terminal/) (rev. 2017-10-07) - In this article, I am going to show you how
to install Stack Overflow command line interface
(SoCLI) on Linux.  Stack Overflow is a question
and answer website on the topic of computer programming.
We can use command line interface to get any information
from Linux terminal without using the graphical web
interface or terminal browser.



#### [termsaver](http://termsaver.brunobraga.net/)

termsaver to enjoy fancy ASCII screensavers like matrix, clock, starwars, and a couple of not-safe-for-work screens. 

#### [dateutils](http://www.fresse.org/dateutils/)

Dateutils are a bunch of tools that revolve around fiddling with dates and times in the command line with a strong focus on use cases that arise when dealing with large amounts of financial data. 

## <a name="organizers"></a>Organizers and calendars

#### [gcalcli](https://github.com/insanum/gcalcli)

CLI to access Google Calendars; allows to do the main tasks: create, delete, and list events. 

#### [khal](https://github.com/pimutils/khal)

CLI and terminal calendar program, able to synchronize with CalDAV servers through [vdirsyncer](https://github.com/pimutils/vdirsyncer). 

#### [ppl addressbook](http://ppladdressbook.org/)

"``ppl`` is free software made out of other free software. It's built on top of Ruby and Git, and the completely free vcard address book format." 

#### [khard](https://github.com/lucc/khard)

Console carddav client written in Pyhton. 

#### [iKog](https://sites.google.com/site/henspace/ikog/)

A fully-featured task manager incapsulated within a Python script (just carry around the script to retain all the TODOs). When the script is run, a Python shell is opened, where task-related commands can be entered (ADD, LIST, etc.); a pity that commands are uppercase, which requires the annoying use of the Shift key. 

#### [Yokadi](https://yokadi.github.io/)

Project-based todo manager: every task must be specified with a mandatory project indication. Tasks are stored within a SQLlite DB. Written in Python. 

#### [Org mode](http://orgmode.org/)

Super-powerful [Emacs](https://www.gnu.org/software/emacs/) plugin to manage outlines with associated timestamps, priorities, labels, etc.; available views grouped by time (agenda), tags, etc.; plain text storage format. 

#### [pal](http://palcal.sourceforge.net/)

Calendar program for Unix/Linux systems that can keep track of events; custom, plain text storage format; interesting and fully functional. 

#### [Remind](https://www.roaringpenguin.com/products/remind)

Calendar program with possibility to set complex rules to define events; custom, powerful text-based storage format. 

#### [TaskWarrior](https://taskwarrior.org/)

Todo manager with advanced features; dedicated synchronization server available; many plugins and related tools; healthy software project. 

#### [todo.txt](https://ginatrapani.github.io/todo.txt-cli/)

Minimalistic todo manager that uses a simple plain text file to keep track of items; implemented as a shell script. 

#### [todolist](http://todolist.site/)

A minimal clone of [Wunderlist](https://www.wunderlist.com/), with 30% of its features. GTD oriented. It stores the task list in a hidden JSON file in the home directory, making it easy to backup or share them. 

#### [TuDu](https://code.meskio.net/tudu/)

A comand line interface to manage hierarchical todos. Each task has a title, a long text description, a deadline (tudu warns you when the date is close), and a scheduled date. There are categories and priorities. 

#### [Wyrd](http://freecode.com/projects/wyrd/)

Curses front-end for [Remind](https://www.roaringpenguin.com/products/remind) written in OCaml with vertically scrollable time table. 

## <a name="transfer"></a>Data transfer

#### [aria2](https://github.com/aria2/aria2)

Lightweight and easy-to-use download utility; it supports HTTP/HTTPS, FTP, SFTP, BitTorrent, Metalink and multiple sources; cross-platform. 

#### [curl](https://curl.haxx.se/)

A tool and library for transferring data with URL syntax; supports a lot of protocols. 

#### [Deluge](http://deluge-torrent.org/)

A lightweight, Free Software, cross-platform BitTorrent client; a terminal curses interface, web interface and command line client can connect to a running daemon to manage torrent downloads. 

#### [lftp](https://lftp.yar.ru/)

"Sophisticated ftp/http client, and a file transfer program supporting a number of network protocols"; support for bookmarks and mirroring features. 

#### [Magic Wormhole](https://github.com/warner/magic-wormhole)

The program allows transfer arbitrary-sized files and directories (or short pieces of text) from one computer to another The two endpoints are identified by using identical human-readable codes. 

#### [OnionShare](https://onionshare.org/)

"An open source tool that lets you securely and anonymously share a file of any size." 

References
* [OnionShare - A Tool To Share Any Size Of Files Securely And Anonymously](https://www.2daygeek.com/onionshare-secure-way-to-share-files-sharing-tool-linux/) (rev. 2017-12-04) - When we wrote an article about file sharing
utilities such as Magic Womhole & transfer.sh most of the
users asked is it secure? and where the files are stored.
So, we decided to bring one of the best utility that stores
and share files securely over the Internet. When we dig on
that, we came to know about OnionShare which fulfill all
this requirements.



#### [rsync](https://download.samba.org/pub/rsync/rsync.html)

Mirror directories across networked machines; handles diffs/changed files; works across SSH; plenty of parameters. 

#### [sitecopy](http://www.manyfish.co.uk/sitecopy/)

Synchronizes a local copy of a website with a remote copy on a server; does not use SSH/`scp` but FTP for file copy; useful when the remote server does not support secure copy. 

#### [stftp](http://stftp.sourceforge.net/)

(simple terminal FTP) aims to be a "easy-to-use and unbloated client for the UNIX (and UNIX-like) console". 

#### [Woof](http://www.home.unix-ag.org/simon/woof.html)

(Web Offer One File) sets up an HTTP webserver to serve files from a given local directory; all the users connected to the network can see and download the files. 

#### [youtube-dl](http://rg3.github.io/youtube-dl/)

Downloads videos from [YouTube](https://www.youtube.com/) and some other sites; useful for automated bulk downloads. 

## <a name="chat"></a>Chat and instant messaging (IM)

#### [finch](http://www.pidgin.im/)

IM program supporting many protocols, including Yahoo!, AIM, IRC, or WLM; comes with the `Pidgin` project.

#### [irssi](http://www.irssi.org)

The most popular IRC client for the command-line; a flexible program, with many options and supporting many protocols.

#### [RainbowStream](http://www.rainbowstream.org/)

Twitter client for the terminal; allows almost all the operations that can be done from GUI and Web clients.

#### [WeeChat](http://weechat.org/)

A "fast, light and extensible chat client".

#### [ssh-chat](https://github.com/shazow/ssh-chat)

Custom SSH server written in Go. Instead of a shell, you get a chat prompt.

## <a name="email"></a>Email

#### [Newsbeuter](http://newsbeuter.org/)

"The Mutt of RSS Feed Readers": Newsbeuter is an open-source RSS/Atom feed reader for text terminals. It runs on Linux, FreeBSD, Mac OS X and other Unix-like operating systems. Newsbeuter's great configurability and vast number of features make it a perfect choice for people that need a slick and fast feed reader that can be completely controlled via keyboard. 

#### [alpine](http://www.washington.edu/alpine/)

Mail client which aims at being "fast, easy to use email client that is suitable for both the inexperienced email user as well as for the most demanding of power users". 

#### [alot](https://github.com/pazz/alot)

MUA written in Python using the [NotMuch](https://notmuchmail.org/) backend; MailDir format support. 

#### [mbsync](http://isync.sourceforge.net/mbsync.html)

Mailboxes synchronization tool; allows to download email locally; MailDir format supported. 

#### [Mutt](http://www.mutt.org/)

Mail client with tons of features, customization chances, support for IMAP, POP3, multiple storage formats. 

#### [sup](http://sup-heliotrope.github.io/)

MUA written in Ruby; specifically developed for accounts with "a lot of emails"; nice thread-based presentation. 

## <a name="browser"></a>Web browser

#### [Links](http://www.jikos.cz/~mikulas/links//)

A textual Web browser with tables and frames. 

#### [Elinks](http://elinks.cz/)

"Advanced and well-established feature-rich text mode web browser"; started as a fork of `Links`; it supports background download with queueing, some support from CSS, text box editing in external text editor. 

#### [Linx](http://lynx.invisible-island.net/)

A highly configurable text-based web browser; one of the oldest CLI browser I'm aware of. 

#### [w3m](http://w3m.sourceforge.net/)

A text-based web browser as well as a pager like `less`; it can be used as a text formatting tool which typesets HTML into plain text. 

## <a name="webdev"></a>Web development

#### [Metalsmith](http://www.metalsmith.io/)

An extremely simple static site generator; all functionalities are provided by plugins that can be combined and chained; written and extendable in Javascript. 

#### [nanoc](http://nanoc.ws/)

Static site generator written in Ruby; extremely powerful and customizable; support many formats to generate HTML content. 

#### [siege](https://www.joedog.org/siege-home/)

An http load testing and benchmarking utility designed to let web developers stress their code. 

#### [Tsung](http://tsung.erlang-projects.org/)

A multi-protocol distributed load testing tool that can be used to stress HTTP, WebDAV, SOAP, PostgreSQL, MySQL, LDAP and Jabber/XMPP servers. 

## <a name="games"></a>Games

#### [StarWars vision](None)

See Star Wars in ASCII with ``telnet towel.blinkenlights.nl``. 

#### [bastet](http://fph.altervista.org/prog/bastet.html)

(Bastard Tetris) implements the classical Tetris but with a logic to generate the next block which maximizes the difficulty for the player. 

#### [Dwarf fortress](http://www.bay12games.com/dwarves/)

A fantasy game using ASCII art graphical representation of the game environment; it features a rich environment with many options and possibilities. 

#### [freesweep](http://www.upl.cs.wisc.edu/~hartmann/sweep/)

A Minesweeper clone for the terminal which allows you to configure settings such as table rows and columns  up to 1024x1024!), percentage of bombs, colors and also has a highscores table. 

#### [Nethack](http://nethack.org/)

Single player rogue-like dungeon exploration game; I'm currently addicted to [Pixel Dungeon](http://pixeldungeon.watabou.ru/) and its derivatives (Android apps), thus I find nethack a little bit too graphically poor. 

#### [Oldrunner](http://culot.org/public/Code/oldrunner.html)

Character-based remake of Lode Runner; includes all the original 150 levels. 

#### [Slash'EM](http://slashem.sourceforge.net/)

Rogue-like game derived from `nethack` offering extra features, monsters, and items; includes a GUI version. 

#### [Typespeed](http://typespeed.sourceforge.net/)

Type words that are flying by from left to right as fast as you can; features different word sets, e.g., UNIX commands, English words, Non-English words. 

## <a name="funny"></a>Funny tools

#### [asciiacquarium](http://www.robobunny.com/projects/asciiquarium/html/)

Enjoy the mysteries of the sea from the safety of your own terminal! 

#### [cmatrix](http://www.asty.org/cmatrix/)

ncurses program that display the scrolling lines found in the movie `The matrix`. 

#### [cowsay](https://en.wikipedia.org/wiki/Cowsay)

A program that generates a ASCII art of a cow with a bubble containing the specified message (I provide the Wikipedia link since at the moment the link to the author's homepage results to be unreachable). 

#### [cowthink](https://en.wikipedia.org/wiki/Cowsay)

Same as `cowsay`, but uses a "think" bubble instead of a speech bubble. 

#### [fortune](http://software.clapper.org/fortune/)

Generates random messages feched from a quotation database. 

#### [Steam Locomotive](http://www.cyberciti.biz/tips/displays-animations-when-accidentally-you-type-sl-instead-of-ls.html)

A steam locomotive traverses the screen from right to left if `sl` is typed instead of `ls`. 

## <a name="file-handling"></a>File and file system handling

#### [classifier](https://github.com/bhrigu123/classifier)

Organize files in your current directory, by classifying them into folders of music, pdfs, images, etc. 

References
* [Automatically Organize Your Downloads Folder In Linux Using Classifier](http://www.webupd8.org/2017/03/automatically-organize-your-downloads.html?m=1) (rev. 2017-07-10) - My downloads folder is pretty messy but I can't just delete things because I still need most of the stuff I download. To "fix" this, I was looking for an app that can automatically organize my downloads, and I stumbled upon Classifier, an easy to use command line tool that can organize files in any directory.


#### [detox](http://detox.sourceforge.net/)

A utility designed to easily clean up filenames; it replaces characters like spaces with standard equivalents; it also replace UTF-8 or Latin-1 (or CP 1252) characters with more handy ones. 

#### [dtrx](https://brettcsmith.org/2007/dtrx/)

(Do The Right eXtraction) aims at taking "all the hassle out of extracting archives"; allows to use one command to extract archives in different formatsl supports tar, zip, deb, rpm, 7z, rar, gz, bz2, xz; supports recursive extraction (files into file) and extracts files into dedicated directories. 

#### [exa](https://the.exa.website/)

Replacement for 'ls' written in Rust, with colors and several additional "views". 

References
* [exa a modern replacement for ls written in rust for Linux/Unix](https://www.cyberciti.biz/open-source/command-line-hacks/exa-a-modern-replacement-for-ls-written-in-rust-for-linuxunix/) (rev. 2017-08-09) - ls is a command to show files in Linux and Unix-like operating systems. A ls command first appeared in a version of AT&T UNIX as well as in Multics. BSD and GNU Coreutils package provides the ls command with minor syntax changes. There is now third alternative named exa ...
* [Exa – A Modern And Colorful Replacement For LS Command Written In Rust](https://www.2daygeek.com/exa-a-modern-replacement-for-ls-command-linux/) (rev. 2017-10-07) - ls is one of the very basic & essential Linux command for
administrator that can be used in most of the actions (in other
hands, Linux administrator can’t live without ls command). Exa is
a small, fast, portable, modern and colorful replacement for
ls command which was written in rust language.



#### [fasd](https://github.com/clvv/fasd)

A Commandline Tool That Offers Quick Access to Files and Directories. Fasd (pronounced similar to "fast") is a command-line productivity booster. Fasd offers quick access to files and directories for POSIX shells. It is inspired by tools like autojump, z and v. Fasd keeps track of files and directories you have accessed, so that you can quickly reference them in the command line. 

#### [fd](https://github.com/sharkdp/fd)

A simple, fast and user-friendly alternative to find. Written in Rust. 

#### [rename](https://www.kernel.org/pub/linux/utils/util-linux/)

Included in `util-linux`, allows bulk rename of files with regex support. 

#### [renameutils](http://www.nongnu.org/renameutils/)

A set of programs to change file and directory names by editing them inplace; I find `imv` especially useful to edit a filename at the program prompt. 

#### [rmlint](https://github.com/sahib/rmlint/)

A tool to recursively scan a directory tree looking for duplicate and broken files; it outputs statistics and save the list of files in JSON format; it produce a shell script that can be inspected before running it to delete the desire files. 

#### [gcp](https://github.com/petronny/gcp)

`gcp` (Goffi’s cp) is an advanced file copier tool, heavily inspired from the traditional `cp` command utility, but with some additional features: Displays the copy progress indicator, with estimated time, current file speed; logs of all actions; resume of interrupted copy processes. 

#### [nnn](https://github.com/jarun/nnn)

"The missing terminal file browser for X". Provides only diretory traversal and file visualization. No delete/move operations are supported. 

#### [PathPicker](https://facebook.github.io/PathPicker/)

A tool from Facebook that parses the output from a command and presents a UI to select files and directories; can be used to apply a command of a interactively selected files or to move across directories. 

#### [alder](https://github.com/aweary/alder)

"A minimal implementation of the UNIX tree command with colors!" 

#### [tree](http://mama.indstate.edu/users/ice/tree/)

"Recursive directory listing command that produces a depth indented listing of files". 

## <a name="backup"></a>Backup

#### [borg](https://github.com/borgbackup)

Encrypted backups with a clean and simple interface; easy to use and set up; possibility to mount the backup archive with FUSE and inspect it as a regular file system. 

#### [duplicity](http://duplicity.nongnu.org/)

Creates GPG encrypted, compressed backups; client-side encryption allows to upload the backup onto untrusted servers. 

#### [Duply](http://duply.net/)

Simplifies the use of [duplicity](http://duplicity.nongnu.org/) by keeping clean configuration files to automate the backup. 

## <a name="conversion"></a>Conversion

#### [catdoc](http://www.wagner.pp.ru/~vitus/software/catdoc/)

Command line converter from Microsoft Word to plain text; output is sent to the standard output. 

#### [Pandoc](http://pandoc.org/)

Universal document file converter; handles input output from/to a number of formats: HTML, PDF, LaTeX, docx, odt, AsciiDoc, Markdown, Textile, just to mention a few; the quality of conversion strongly depends on the combination of input/output formats. 

#### [xls2csv](http://www.wagner.pp.ru/~vitus/software/catdoc/)

Command line converter from Excel to CSV file format. 

## <a name="file-manager"></a>File manager

#### [lfm](https://inigo.katxi.org/devel/lfm/)

(Last File Manager) is a file manager written in Python; it comes with lots of features, including 1-pane or 2-pane view, files filters and bookmarks, tree view, virtual file-systems to open compressed archives, serch in files, customizable keybindings and themes. 

#### [Midnight Commander](http://www.midnight-commander.org/)

a visual file manager, full-screen text mode application that allows you to copy, move and delete files and whole directory trees and search for files; includes an internal viewer and editor. 

#### [ncursesFM](https://github.com/FedeDP/ncursesFM)

File manager written in C; rather complete in terms of features; especially lightweight and responsive. 

#### [ranger](http://ranger.nongnu.org/)

Console file manager with vi key bindings; curses interface with a view on the directory hierarchy; comes a file launcher that automatically finds out which program to use for a given file type. 

#### [vifm](https://vifm.info/)

"ncurses based file manager with vi like keybindings/modes/options/commands/configuration, which also borrows some useful ideas from mutt" (cit.). 

## <a name="file-systems"></a>File systems

#### [sshfs](https://github.com/libfuse/sshfs)

Locally mount a remote file-system through SSH and access files and directory as they would be on the local machine. 

#### [TMSU](http://tmsu.org/)

A tool for tagging files; it provides a simple command line tool for applying tags and a virtual filesystem so that you can get a tag-based view of your files from within any other program. 

## <a name="versioning"></a>Versioning

#### [git](https://git-scm.com/)

The winner across all the existing file versioning tools; distributed versioning; fully controllable from the command-line; plenty of configuration and usage options; behind a number of related project that leverage git as backend. 

#### [git-annex](https://git-annex.branchable.com/)

Manages files with `git`, without checking the file contents into git; very useful to manage large/binary files. 

#### [git-stats](hhttps://github.com/IonicaBizau/git-stats)

"Local git statistics including GitHub-like contributions calendars." 

#### [Mercurial](https://www.mercurial-scm.org/)

Free, distributed source control management tool. 

#### [tig](https://github.com/jonas/tig)

An ncurses-based text-mode interface for `git` that can act as a repository browser, but can also assist in staging changes for commit at chunk level. 

## <a name="graphics"></a>Graphics

#### [ImageMagick](http://www.imagemagick.org/script/index.php)

Software suite to create, edit, compose, or convert bitmap images; it handles many file formats (including PDF and SVG) and provides processing tools to "resize, flip, mirror, rotate, distort, shear and transform images, adjust image colors, apply various special effects, or draw text, lines, polygons, ellipses and Bézier curves". 

#### [scrot](https://github.com/dreamer/scrot)

A simple CLI tool to capture screenshots. 

## <a name="music"></a>Sound and music

#### [ncmpcpp](https://rybczak.net/ncmpcpp/)

NCurses Music Player Client (Plus Plus) - featureful ncurses based MPD client inspired by ncmpc. Relevant features: tag editor, playlist editor, easy to use search engine, media library, music visualizer, ability to fetch artist info from [last.fm](https://www.last.fm/), new display mode, alternative user interface, ability to browse and add files from outside of MPD music directory. 

#### [espeak](http://espeak.sourceforge.net/)

"a compact open source software speech synthesizer for English and other languages." 

#### [Alsamixer](http://www.alsa-project.org/main/index.php/Main_Page)

ALSA mixer with curses interfaces. 

#### [cmus](https://cmus.github.io/)

A fast and lightweight audio player with configurable keybindings and playlist support. 

#### [MOC](https://moc.daper.net/)

(music on console) is a powerful and easy to use console audio player; user interface a la Midnight Commander; plenty of features; fully controllable from the keyboard. 

#### [mpg123](http://mpg123.org/)

Quick `mp3` sound file player; no visual interface, just a command-line audio file player for `mp3` files. 

#### [mps-youtube](https://github.com/mps-youtube/mps-youtube)

A curses player for music tracks from Youtube; it allows to search for songs and playlists; it downloads the video, extracts the audio track and plays it; handles local playlists and many configuration parameters. 

#### [ogg123](https://www.xiph.org/downloads/)

Quick `ogg` sound file player; no visual interface, just a command-line audio file player for the free and open `ogg` file format. 

## <a name="viewers"></a>Viewers

#### [cacaview](http://caca.zoy.org/wiki/libcaca)

A library and a program to display JPG, PNG, GIF or BMP images in the terminal using ASCII characters. 

#### [feh](https://feh.finalrewind.org/)

"X11 image viewer aimed mostly at console users" (cit.); with no fancy GUI, it is controlled via commandline arguments and configurable key/mouse actions. 

#### [mupdf](http://mupdf.com/)

Lightweight graphical PDF visualizer; strong key-based control; fast and accurate rendering. 

#### [mplayer](http://www.mplayerhq.hu/design7/news.html)

One of the most popular video/audio players around; plays most audio and video formats (using ASCII characters) in the shell; provides a GUI for graphical visualization. 

#### [mpv](https://mpv.io/)

A cross-platform media player with many features such as frame timing, MKV chapters and subtitles. It is a responsive video player with minimal layout customizable with themes. A good alternative media player to VLC since it can handle almost all the media formats as VLC, but using much less resources. 

#### [zathura](https://pwmt.org/projects/zathura/)

Plugin based document file visualizer (PDF, DejaVu, PS); strongly key-based control. 

## <a name="productivity"></a>Productivity

#### [arbtt](http://arbtt.nomeata.de/)

(automatic, rule-based time tracker) runs in background, collecting information regarding open windows, focussed ones, etc.; it can be configured to display statistics on the collected data, e.g., figuring out the time spent on one specific window. 

#### [ledger](http://ledger-cli.org/)

A powerful, double-entry accounting system from the command-line; it uses a simple yet powerful text syntax to specify the items to account. 

#### [Qalculate](https://qalculate.github.io/)

Multi-purpose calculator with customizable functions, units, arbitrary precision, plotting (it includes a GUI). 

#### [Translate Shell](https://www.soimort.org/translate-shell/)

Command-line translator using Google Translate, Bing Translator, Yandex.Translate, etc. 

## <a name="office"></a>Office tools

#### [trino](https://github.com/eneserdogan/trino)

Quick and easy translation of words and phrases entered in the command line.  

#### [Teapot](https://www.syntax-k.de/projekte/teapot/)

Compact ncurses-based spreadsheet with original syntax, 3D-style and built-in functions. 

#### [sc-im](https://github.com/andmarti1424/sc-im)

Spreadsheet Calculator Improvised -- An ncurses spreadsheet program for terminal. It is rich in functionalities, but the syntax of functions and other details are different from the common spreadsheets such as Excel and Calc, making difficult to "re-cycle" existing knowledge on these programs to work proficiently with sc-im. Neverthless, a nice piece of software.

#### [tpp](http://www.ngolde.de/tpp.html)

(text presentation program) a ncurses Ruby program that allows to produce nice text-based presentation with simple markup language. 

## <a name="security"></a>Security and encryption

#### [cipher](https://github.com/ash-shell/cipher)

An Ash module that makes it easy to perform aes-256-cbc encryption for files and directories. 

References
* [Linux-how-to by Alain Francois (posted June 27, 2017)](https://linoxide.com/linux-how-to/cipher-command-line-tool-encrypt-decrypt-files-directories/) (rev. 2017-07-09)

#### [hashcat](https://hashcat.net/hashcat/)

A robust and efficient password cracking tool that can help you recover lost passwords, audit password security, benchmark, or just figure out what data is stored in a hash. 

#### [encfs](http://www.arg0.net/#!encfs/c1awt)

Encrypted filesystem in user-space based on [FUSE](https://it.wikipedia.org/wiki/FUSE); mounts an encrypted directory into a clear one. 

#### [LUKS](https://guardianproject.info/code/luks/)

Hard disk encryption tool; it stores all setup information in the partition header, enabling easy data transport or migration. 

#### [safe.sh](https://github.com/windowsrefund/safe)

Pure Bash script to manage secure archives; simple and clean; uses [gnugpg](https://gnupg.org/) for encryption/decryption, thus can leverage tools like [GPG Agent](https://www.gnupg.org/documentation/manuals/gnupg/Invoking-GPG_002dAGENT.html). 

#### [titan](https://www.byteptr.com/titan/)

Password management belongs to the command line, deep into the Unix heartland, the shell. Titan is written in C and is available under the MIT license. 

References
* [A Command line Password Manager For Linux](https://www.ostechnix.com/titan-command-line-password-manager-linux/) (rev. 2017-07-10) - There are plethora of GUI based password managers. A quick google search will lead you to pick one suitable for you. But the command line password managers are very few. The one today we talk about is Titan. It is written using C programming language. It uses SQlite.


## <a name="system"></a>System tools

#### [conspy](http://conspy.sourceforge.net/)

"Conspy allows a (possibly remote) user to see what is displayed on a Linux virtual console, and send keystrokes to it." 

#### [lshw](http://www.ezix.org/project/wiki/HardwareLiSter)

A small tool to provide detailed information on the hardware configuration of the machine. It can report exact memory configuration, firmware version, mainboard configuration, CPU version and speed, cache configuration, bus speed, etc.  

References
* [LSHW (Hardware Lister) – A Nifty Tool To Get A Hardware Information On Linux](https://www.2daygeek.com/lshw-find-check-system-hardware-information-details-linux/) (rev. 2017-10-07) - lshw (stands for Hardware Lister) is a small nifty
tool that generates detailed reports about various hardware
components on the machine such as memory configuration,
firmware version, mainboard configuration, CPU version
and speed, cache configuration, usb, network card, graphics
cards, multimedia, printers, bus speed, etc.



#### [Ntfy](https://github.com/dschep/ntfy)

Ntfy is a simple yet serviceable cross-platform Python utility that enables you to automatically get desktop notifications on demand or when long running commands complete. It can as well send push notifications to your phone once a particular command completes. 

#### [task-spooler](http://vicerveza.homeunix.net/~viric/soft/ts/)

As the name implies, Task spooler is a Unix batch system  that can be used to add the Linux commands to the queue and execute them one after the other in numerical order (ascending order, to be precise). This can be very useful when you have to run a lots of commands, but you don't want to waste time waiting for one command to finish and run the next command. You can queue it all up and Task Spooler will execute them one by one. In the mean time, you can do other activities. 

#### [ttyload](http://www.daveltd.com/src/util/ttyload/)

ttyload is a lightweight utility which is intended to offer  a color-coded graph of load averages over time on Linux and  other Unix-like systems. It enables a graphical tracking of  system load average in a terminal (“tty“). 

#### [hstr](https://github.com/dvorka/hstr)

A tool for managing the history; powerful visual search and execution of previous commands; history editing capabilities. 

#### [parallel](https://www.gnu.org/software/parallel/)

A shell tool from GNU for executing jobs in parallel using one or more computers; it can split the input and pipe it into commands in parallel. 

## <a name="shells"></a>Shells

#### [Bash](https://www.gnu.org/software/bash/)

(Bourne Again SHell) The most widespread system shell to date. 

#### [Fish](https://fishshell.com/)

"A command line shell for the 90s"; focused on user-friendliness, with powerful autosuggestions, colors, "sane scripting" (w.r.t. to Bash). 

#### [Zsh](http://www.zsh.org/)

Alternative shell designed for interactive use. 

## <a name="monitor"></a>System monitoring

#### [cv](https://github.com/Xfennec/progress)

(Coreutils Progress Viewer) "looks for coreutils basic commands (`cp`, `mv`, `dd`, `tar`, `gzip/gunzip`, `cat`, etc.) currently running on your system and displays the percentage of copied data. It can also show estimated time and throughput". 

#### [glances](https://nicolargo.github.io/glances/)

A comprehensive and detailed system monitoring tool; monitored parameters include: CPU, memory, load, process list, network interfaces, disk I/O, sensors, filesystems, docker, system info, uptime. 

#### [GoTTY](https://github.com/yudai/gotty)

A program to turn CLI tools into web applications; basically, it runs a command and starts a server so that the output can be displayed in a web page. 

#### [inxi](http://smxi.org/docs/inxi.htm)

A comprehensive system information script; provides information about CPU, graphics, audio and network devices, drives and partitions, sensors; implemented as a Bash script. 

#### [iotop](http://guichaz.free.fr/iotop/)

"A Python program with a top like UI used to show of behalf of which process is the I/O going on". 

#### [htop](http://hisham.hm/htop/)

An interactive process viewer for Unix; improves the UI of `top`, by adding real-time meters and colors. 

#### [multitail](https://www.vanheusden.com/multitail/)

A command to open multiple log files in a single terminal window and monitor them in real-time. 

#### [ngrep](http://ngrep.sourceforge.net/)

(Network grep) applies the `grep` logic to the network layer, allowing to match regular expressions against data payloads of packets; it recognizes IPv4/6, TCP, UDP, ICMPv4/6, IGMP and Raw across Ethernet, PPP, SLIP, FDDI, Token Ring and null interfaces. 

#### [progress](https://github.com/Xfennec/progress)

A tool to monitor the progress of common Coreutils command-line tools (`cp`, `mv`, `dd`, `tar`, `rsync`, etc.); it uses an ncurses interface to display the percentage of data copied; it works by reading from system files and retrieving the necessary information for the estimation. 

#### [powertop](https://01.org/powertop)

A `top`-like utility to monitor the sources of power consumption; allows to turn on/off many components; quite useful to track possible power-related issues. 

#### [sysdig](https://www.sysdig.org/)

Sysdig captures system calls and events from the Linux kernel. You can save, filter, and analyze the data with our CLI or our desktop app. Think of sysdig as strace + tcpdump + htop + iftop + lsof + wireshark for your entire system. 

References
* [Sysdig – Linux System Exploration/Diagnostic And Troubleshooting Tool](https://www.2daygeek.com/sysdig-linux-system-diagnostic-monitor-troubleshoot-tool/) (rev. 2017-10-07) - Sysdig is an open source, system exploration/diagnosing
and troubleshooting tool for Linux with native container
support. It is capture system state and activity from a
running Linux instance, then save, filter and analyze.



#### [smem](https://www.selenic.com/smem/)

Python program that reports memory usage; it can report the "proportional set size" (PSS), a meaningful representation of the amount of memory used by libraries and applications in a virtual memory system; it has built-in chart generation. 

#### [top](http://www.unixtop.org/)

The classical Unix utility that provides a rolling display of top cpu using processes. 

#### [watch](http://www.linfo.org/watch.html)

Periodically runs a command in the console while temporarily clearing the screen content; it makes it easy to check differences between the output of two subsequent commands; it provides "diff" functionality to highlight the changing characters between outputs. 

References
* [Watch command to execute script/shell command repeatedly](http://kerneltalks.com/commands/watch-command-to-execute-scriptshell-command-repeatedly/) (rev. 2017-07-10) - “watch” command is small utility using which you can execute shell command or script repetitively and after every n seconds. Its helpful in automation or monitoring.


## <a name="terminals"></a>Terminals

#### [byobu](http://byobu.co/)

A text-based window manager and terminal multiplexer; it features enhanced profiles, convenient keybindings, configuration utilities, and toggle-able system status notifications; compatible with `screen` and `tmux`. 

#### [screen](https://www.gnu.org/software/screen/)

Terminal multiplexer that split a physical terminal between several processes, typically interactive shells. 

#### [Tmate](https://tmate.io/)

A fork of tmux that allows to share the terminal with other users. AFAIK, it connects to a centralized server to establish the connection. Someone may see this inconvenient for privacy issues. 

References
* [Tmate - Share Your Terminal Instantly To Anyone From Anywhere](https://www.ostechnix.com/tmate-share-terminal-instantly-anyone-anywhere/) (rev. 2017-10-07) - There are several popular remote desktop
sharing programs (such as Teamviewer, Guacamole, and
TigerVNC etc) you can use when you need to share your screen
to your coworkers or friends. These programs are used to
share your entire screen to others. But, if it’s only the
Terminal, you can just use Tmate.



#### [tmux](https://tmux.github.io/)

Terminal multiplexer; born to improve `screen`; client-server architecture, `vi` and `emacs` key-bindings, search in window feature and many more. 

#### [warp](https://github.com/spolu/warp)

Secure and simple terminal sharing. 

## <a name="editors"></a>Editors

#### [Emacs](https://www.gnu.org/software/emacs/)

One of the godfathers of text editors; free long-standing software project; tons of extensions and funcionalities; the biggest drawback (my taste): it needs [E-Lisp](https://www.gnu.org/software/emacs/manual/eintr.html) for being programmed.  

#### [jed](http://www.jedsoft.org/jed/index.html)

A text editor with a drop-down menu facility that make it especially user-friendly. 

#### [joe](http://joe-editor.sourceforge.net/)

(Joe's Own Editor) is a compact text editor written in C; a detailed list of features and missing ones is explicitly reported in the website; this editor is mentioned in several web sources for its capability in handling large files. 

#### [nano](https://www.nano-editor.org/)

Easy to use, lightweigth text editor; no complex keybindings to remember. 

#### [micro](https://github.com/zyedidia/micro/)

A terminal-based text editor written in Go that aims to be easy to use and intuitive, while also taking advantage of the full capabilities of modern terminals.  

#### [neovim](https://neovim.io/)

A work in progress attempt to improve [vim](http://www.vim.org/), dropping older/unused OS compatibility, improving the codebase readability, modularity and maintainability; it has chances to become the next choice of vim users. 

#### [slap](https://github.com/slap-editor/slap)

Text editor inspired by [Sublime Text](https://www.sublimetext.com/) written in NodeJS; extedable in Javascript. 

#### [vai](https://github.com/stefanoborini/vai)

A text editor similar to `vim` written in Python; many feature are nicely replicated, some are still missing; however, the advantage of this implementation is its simplicity, maintainability and extensibility, thanks to the Python implementation. 

#### [vim](http://www.vim.org/)

Historically one of the preferred text editors; behavior based on editing modes; plenty of plugins and tips to address every possible editing problem. 

#### [vis](https://github.com/martanne/vis)

"a modern, legacy free, simple yet efficient vim-like editor", and more: "The intention is not to be bug for bug compatible with vim, instead a similar editing experience should be provided. The goal could thus be summarized as 80% of vim's features implemented in roughly 1% of the code"; the editor is scriptable in LUA and supports editing large files. 

#### [WordGrinder](https://cowlark.com/wordgrinder/)

From the website: "WordGrinder is a word processor for processing words. It is not WYSIWYG. It is not point and click. It is not a desktop publisher. It is not a text editor. It does not do fonts and it barely does styles. What it does do is words. It's designed for writing text. It gets out of your way and lets you type." 

References
* [WordGrinder: Distraction-Free Writing From the Command Line](http://fossforce.com/2017/03/wordgrinder-distraction-free-writing-command-line/) (rev. 2017-07-10) - WordGrinder is an old fashioned command line program that doesn’t try to do a lot of things. Its purpose is to get the job done, and stay out of the user’s way while doing it.


## <a name="font"></a>Font management

#### [FIGlet](http://www.figlet.org/)

Not exactly a font manager, but a nice program for making large letters out of ordinary text; an astonishing number of different fonts is available. 

#### [toilet](http://caca.zoy.org/wiki/toilet)

A program that tries to improve `FIGlet`; can load FIGlet fonts; supports Unicode input and output, colour fonts and output, and various output formats, including HTML, IRC and ANSI; uses `libcaca` to produce nice textual effects. 

## <a name="text-processing"></a>Text processing

#### [ccat](https://github.com/jingweno/ccat)

A `cat` command with colorized output. 

#### [fzf](https://github.com/junegunn/fzf)

(FuZzy Finder) is a general-purpose command-line finder with fuzzy search/filter capabilities; good integration with `vim`. 

#### [grc](https://github.com/pengwynn/grc)

(Generic Colouriser) can be configured to parse a given text stream and to colorize it according to regexp written in configuration files; different patterns can be associated to file types. 

#### [jq](https://stedolan.github.io/jq/)

(JSON Query?) is sed-like processor for JSON data; can be used to process JSON files and data streams and perform operations such as those allowed by `cat`, `sed`, `grep` and `awk` on regular text files. 

#### [percol](https://github.com/mooz/percol)

A Python script that "1) receives input lines from  `stdin` or a file, 2) lists the input lines and waits for input that filter/select the line(s), 3) outputs the selected line(s) to `stdout`"; can be used to add interactivity to many regular shell commands. 

#### [pick](https://github.com/calleerlandsson/pick)

Utility that allows users to choose one option from a set of choices using an interface with fuzzy search functionality. 

References
* [Pick - A Commandline Fuzzy Search Tool For Linux](https://www.ostechnix.com/pick-commandline-fuzzy-search-tool-linux/) (rev. 2017-10-07) - The Pick utility can be helpful in certain situations
where you wanted to search for a folder or file that contains
a non-English characters in their name. You don’t have to learn
how to type the non-english characters.



#### [q](http://harelba.github.io/q/)

Executes SQL-like queries on CSVs/TSVs tabular data files; each tabular file is treated as a database table; support to all SQL constructs (`WHERE`, `GROUP BY`, `JOIN`). 

## <a name="text-search"></a>Text search

#### [ack](http://beyondgrep.com/)

A tool like `grep` optimized for programmers; written in Perl, it speeds up searches thanks to skipping non interesting directories, such as `.git`. 

#### [ag](https://github.com/ggreer/the_silver_searcher)

(The silver searcher) is a text search utility targeted to source code; it skips versioning systems data directories; it is inspired by `ack`, but faster. 

References
* [How to supercharge string search through a directory hierarchy on a Linux/Unix](https://www.cyberciti.biz/open-source/command-line-hacks/ag-supercharge-string-search-through-directory-hierarchy/) (rev. 2017-12-04) - Usually, I use the grep command for code
searching on my box. Recently, I come across another
cool tool called ag. It is an attempt to make
something better than ack, which itself is better
than grep command. Let us see how to install and
use the ag tool on Unix-like operating systems.

The ag command can recursively search for PATTERN
in PATH. Like grep or ack, but faster.



#### [paragrep](http://software.clapper.org/paragrep/)

Greps regular expressions in a text file(s) and prints out the paragraphs containing those expressions; a paragraph is defined as a block of text delimited by an empty or blank line; fully customizable via command line parameters. 

#### [sift](https://sift-tool.org/)

Fast and powerful open source alternative to grep; it targets flexibility and performance: can be as fast as "regular" grep and allows to specify complex expressions to find text. 


# <a name="resources"></a>Related resources

A list of some online resoures that contribute interesting links to apps and info.

[The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) - A wonderful summary from Joshua Levy regarding command line (Bash in particular) tools, programs, tips and tricks; contains many pointers to resources and repositories, in the form of "to do this you must know that", which gives great pointers but requires further investigation from different sources; translated in many languages.

[Inconsolation blog](https://inconsolation.wordpress.com/) - "Adventures with lightweight and minimalist software for Linux": reviews of many command-line programs; many programs reviewed (400+, at least), with screenshots and animated GIFs; the style of presentation is ironic and funny, but requires some effort to figure out the real contribution of a program.


[CLIapps blog table](http://www.jaredandcoralee.com/CLIapps.html) - A long list of CLI apps from Jared Bernard; some are quite outdated; pros: some CLI apps are put side-by-side with GUI counterparts; cons: no comments to the apps.


[A little collection of cool unix terminal/console/curses tools](https://kkovacs.eu/cool-but-obscure-unix-tools) - "Some are little-known, some are just too useful to miss, some are pure obscure..." from Kristof Kovacs; nice list with screenshot; mostly oriented to system administration; unfortunately there are no clickable links.


[Caleb Xu shell awesome](https://github.com/alebcay/awesome-shell) - Focused on UNIX shell tools.

[Adam Harris awesome CLI apps](https://github.com/aharris88/awesome-cli-apps) - Nice list of tools; somehow too much Javascript/Node.js-centered for my tastes.

[Marcel Bischoff awesome commandd line apps](https://github.com/herrbischoff/awesome-command-line-apps) - Nice up-to-date list of useful tools.

[CLI-Apps](http://cli-apps.org/) - A site that aims at collecting and organizing CLI apps information from user contributions; considering its social-oriented nature, it misses several mainstream apps.

[Awesome CLI by sintaxi](https://github.com/sintaxi/awesome-cli/blob/master/README.md) - Relatively short list with short descriptions; with some original entries.



