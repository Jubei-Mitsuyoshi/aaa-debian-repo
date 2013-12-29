The Black Debian Repo
======================

A set of debian packages for Kali, jessie, and sid that exist nowhere else


To acess this repo.

cd some/dir

apt-get install git

git clone https://github.com/Jubei-Mitsuyoshi/aaa-debian-repo.git

echo "deb [trusted=yes] file:///path/to/some/dir public distro/distrogit" (ie kali,kaligit or unstable,unstablegit or all of them) >> /etc/apt/sources.list

apt-get update

Then use you favorate package manager system to install the packages

Notes. currently this repo is unsigned due to lazyness but for the paranoid all the
sorces are available in regular debian manner

Package List
============

Kali Packages
=============
Package: arch-devtools
Version: 20131107-aaakali
Architecture: all
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 scripts braught to debian to facilitate
 running a naitive arclinux chroot on a
 debian system

Package: burpsuit
Version: 1.5free-aaakali
Architecture: all
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 performing security testing of web applications.
 Its various tools work seamlessly together to support
 the entire testing process, from initial mapping and
 analysis of an application's attack surface, through
 to finding and exploiting security vulnerabilities.
 This is the free version
 WARNING.... THIS IS A CLOSED SOURCE PACKAGE
 USE AT OWN RISK !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

Package: easy-creds
Version: 3.8+dev-aaakali
Architecture: all
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>

Package: pwnstar
Version: 0.9-aaakali
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 script includes
 Honeypot
 Grab WPA handshake
 Sniffing
 Simple web server with dnsspoof
 Karmetasploit
 Browser_autopwn
 WARNING!!!!!!!!!!!!!!!!!!!!!!!
 THIS PACKAGE CONTAINS BINARIES
 WITHOUT SOURCES AND CONTAINING
 VERY DANGEROUS AND MALICIOUS
 CODE
 USE AT OWN RISK !!!!!!!!!!!!!

Package: winexe
Version: 1.1~20130620kali4-aaa1kali
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 Winexe remotely executes commands on Windows NT/2000/XP/2003 systems from
 GNU/Linux (and possibly also from other Unices capable of building the Samba 4
 software package)The *aaa versions of this package have had modifications to the source code to remedy incompatibilities with nvidia-cuda-toolkit..

Unstable Packages
=================
Package: arch-devtools
Version: 20131107-aaa
Architecture: all
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 scripts braught to debian to facilitate
 running a naitive arclinux chroot on a
 debian system

Package: archlinux-pacman
Version: 4.1.2-aaa
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 archlinux and others package manager
 braught to debian to facilitate running
 an archlinux chroot on a debian host

Package: cinnamon
Version: 2.0.14
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Cinnamon redefines user interactions with the GNOME desktop.
 In particular, it offers new paradigms for launching applications,
 accessing documents, and organizing open windows in GNOME. Later, it
 will introduce a new applets eco-system and offer new solutions for
 other desktop features, such as notifications and contacts
 management. Cinnamon is intended to replace functions handled
 by the GNOME Panel and by the window manager in previous versions of
 GNOME. Cinnamon has rich visual effects enabled by new
 graphical technologies.

Package: cinnamon-bluetooth
Version: 3.8.2
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains a configuration module and an applet compatible with GNOME Bluetooth.

Package: cinnamon-common
Source: cinnamon
Version: 2.0.14
Architecture: all
Maintainer: Linux Mint <root@linuxmint.com>
 Cinnamon redefines user interactions with the GNOME desktop.
 In particular, it offers new paradigms for launching applications,
 accessing documents, and organizing open windows in GNOME. Later, it
 will introduce a new applets eco-system and offer new solutions for
 other desktop features, such as notifications and contacts
 management. Cinnamon is intended to replace functions handled
 by the GNOME Panel and by the window manager in previous versions of
 GNOME. Cinnamon has rich visual effects enabled by new
 graphical technologies.
 .
 This package contains the architecture independent files needed by Cinnamon

Package: cinnamon-control-center
Version: 2.0.9
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains configuration applets for the Cinnamon desktop,
 allowing to set accessibility configuration, desktop fonts, keyboard
 and mouse properties, sound setup, desktop theme and background, user
 interface properties, screen resolution, and other Cinnamon parameters.

Package: cinnamon-control-center-data
Source: cinnamon-control-center
Version: 2.0.9
Architecture: all
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains data files (icons, pixmaps, locales files) needed by
 the configuration applets in the cinnamon-control-center package.

Package: cinnamon-dbg
Source: cinnamon
Version: 2.0.14
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Cinnamon redefines user interactions with the GNOME desktop.
 In particular, it offers new paradigms for launching applications,
 accessing documents, and organizing open windows in GNOME. Later, it
 will introduce a new applets eco-system and offer new solutions for
 other desktop features, such as notifications and contacts
 management. Cinnamon is intended to replace functions handled
 by the GNOME Panel and by the window manager in previous versions of
 GNOME. Cinnamon has rich visual effects enabled by new
 graphical technologies.
 .
 This package contains the debugging symbols.

Package: cinnamon-desktop-data
Source: cinnamon-desktop
Version: 2.0.4
Architecture: all
Maintainer: Clement Lefebvre <root@linuxmint.com>
 This package includes some files that are shared between several Cinnamon
 apps (internationalization files).

Package: cinnamon-screensaver
Version: 2.0.3
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 cinnamon-screensaver is a screen saver and locker that aims to have simple,
 sane and secure defaults, and be well integrated with the Cinnamon desktop.
 .
 It is designed to support, among other things:
 .
  * the ability to lock down configuration settings
  * translation into other languages
  * user switching
Original-Maintainer: Guilherme de S. Pastore <gpastore@debian.org>

Package: cinnamon-session
Version: 2.0.6
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 The Cinnamon Session Manager is in charge of starting the core components
 of the Cinnamon desktop, and applications that should be launched at
 login time. It also features a way to save and restore currently
 running applications.
 .
 This package contains the binaries for the Cinnamon Session Manager, but
 no startup scripts. It is meant for those willing to start
 cinnamon-session by hand with the components of their choice, and for
 applications such as MDM that use cinnamon-session internally.

Package: cinnamon-session-common
Source: cinnamon-session
Version: 2.0.6
Architecture: all
Maintainer: Linux Mint <root@linuxmint.com>
 The Cinnamon Session Manager is in charge of starting the core components
 of the Cinnamon desktop, and applications that should be launched at
 login time. It also features a way to save and restore currently
 running applications.
 .
 This package contains the translations, data files and startup scripts
 which are common to the Cinnamon and Cinnamon fallback sessions.

Package: cinnamon-settings-daemon
Version: 2.0.8
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains the daemon which is responsible for setting the
 various parameters of a Cinnamon session and the applications that run
 under it. It handles the following kinds of settings:
 .
  * Keyboard: layout, accessibility options, shortcuts, media keys
  * Clipboard management
  * Theming: background, icons, GTK+ applications
  * Cleanup of unused files
  * Mouse: cursors, speed, accessibility options
  * Startup of other daemons: screensaver, sound daemon
  * Typing break
 .
 It also sets various application settings through X resources and
 freedesktop.org XSETTINGS.

Package: cinnamon-settings-daemon-dev
Source: cinnamon-settings-daemon
Version: 2.0.8
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains header files required to build applications that
 communicate with the Cinnamon settings daemon over D-Bus.

Package: cinnamon-translations
Version: 2.0.3
Architecture: all
Maintainer: Clement Lefebvre <root@linuxmint.com>
 Translation files for the Cinnamon desktop.

Package: cjs
Version: 2.0.0
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Makes it possible for applications to use all of GNOME's platform
 libraries using the Javascript language. It's mainly based on the
 Mozilla javascript engine and the GObject introsepection framework.
 .
 This package contains the interactive console application.

Package: compiz
Version: 1:0.9.10+13.10.20131011-aaa1
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 Compiz brings to life a variety of visual effects that make the Linux desktop
 easier to use, more powerful and intuitive, and more accessible for users
 with special needs.
 .
 This metapackage provides the components necessary for running compiz. It
 provides the compiz core, a set of standard plugins, a window decorator using
 the Gtk toolkit and the files necessary to integrate compiz with the GNOME
 desktop environment
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular compiz from ubuntu repositories.

Package: compiz-core
Source: compiz
Version: 1:0.9.10+13.10.20131011-aaa1
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 Compiz brings to life a variety of visual effects that make the Linux desktop
 easier to use, more powerful and intuitive, and more accessible for users
 with special needs.
 .
 Compiz combines together a window manager and a composite manager using
 OpenGL for rendering. A "window manager" allows the manipulation of the
 multiple applications and dialog windows that are presented on the screen. A
 "composite manager" allows windows and other graphics to be combined together
 to create composite images. Compiz achieves its stunning effects by doing
 both of these functions.
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular compiz from ubuntu repositories.

Package: compiz-dev
Source: compiz
Version: 1:0.9.10+13.10.20131011-aaa1
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 Compiz brings to life a variety of visual effects that make the Linux desktop
 easier to use, more powerful and intuitive, and more accessible for users
 with special needs.
 .
 This package contains the headers and libraries needed to compile compiz
 plugins.
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular compiz from ubuntu repositories.

Package: compiz-gnome
Source: compiz
Version: 1:0.9.10+13.10.20131011-aaa1
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 Compiz brings to life a variety of visual effects that make the Linux desktop
 easier to use, more powerful and intuitive, and more accessible for users
 with special needs.
 .
 This package contains files needed to integrate compiz with the GNOME desktop
 environment.
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular compiz from ubuntu repositories.

Package: compiz-plugins
Source: compiz
Version: 1:0.9.10+13.10.20131011-aaa1
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 Compiz brings to life a variety of visual effects that make the Linux desktop
 easier to use, more powerful and intuitive, and more accessible for users
 with special needs.
 .
 This package contains the plugins that come with compiz but not officially
 supported.
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular compiz from ubuntu repositories.

Package: compiz-plugins-default
Source: compiz
Version: 1:0.9.10+13.10.20131011-aaa1
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 Compiz brings to life a variety of visual effects that make the Linux desktop
 easier to use, more powerful and intuitive, and more accessible for users
 with special needs.
 .
 This package contains the default compiz plugins we activate in ubuntu coming
 with core compiz.
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular compiz from ubuntu repositories.

Package: compizconfig-settings-manager
Source: compiz
Version: 1:0.9.10+13.10.20131011-aaa1
Architecture: all
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 The OpenCompositing Project brings 3D desktop visual effects that improve
 usability of the X Window System and provide increased productivity.
 .
 This package contains the compizconfig settings manager.
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular compiz from ubuntu repositories.
Python-Version: 2.7

Package: cpyrit-cuda
Version: 0.4.0+git20131223-aaa
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 gpu acceleration to the existing *aaa pyrit packages.

Package: emerald
Version: 0.9.5-aaa
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 This package provides a decorator for compiz-fusion and a themer application
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular emerald from ubuntu repositories.
Original-Maintainer: Nicholas Thomas <lupine@beryl-project.org>

Package: fontconfig-infinality
Version: 1-aaa
Architecture: all
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 This package include FreeType2 configuration files for modifying settings
 provided by the infinality patches.

Package: freetype-infinality
Version: 2.4.9-aaa
Architecture: all
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 The purpose of these patches is to provide the nicest font rendering of any
 operating system. The second goal is to provide customization so that the
 end user is able to adjust the settings to his or her taste.

Package: galternatives
Version: 0.13.5-aaa
Architecture: all
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 A GUI to help the system administrator to choose what program
 should provide a given service.
 .
 This is a graphical front-end to the update-alternatives
 program shipped with dpkg.

Package: gdebi
Version: 0.9.2-aaa0
Architecture: all
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 gdebi lets you install local deb packages resolving and installing
 its dependencies. apt does the same, but only for remote (http, ftp)
 located packages.
 .
 This package contains the graphical user interface.
 .
 The *aaa versions of this package have gsku refs and dependencies
 removed to increase speed and stability, if not running under root
 privelages please use the regular debian package

Package: gdebi-core
Source: gdebi
Version: 0.9.2-aaa0
Architecture: all
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 gdebi lets you install local deb packages resolving and installing
 its dependencies. apt does the same, but only for remote (http, ftp)
 located packages.
 .
 This package contains the libraries and command-line utility.
 .
 The *aaa versions of this package have gsku refs and dependencies
 removed to increase speed and stability, if not running under root
 privelages please use the regular debian package

Package: gdebi-kde
Source: gdebi
Version: 0.9.2-aaa0
Architecture: all
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 gdebi lets you install local deb packages resolving and installing
 its dependencies. apt does the same, but only for remote (http, ftp)
 located packages.
 .
 This package contains the KDE user interface.
 .
 The *aaa versions of this package have gsku refs and dependencies
 removed to increase speed and stability, if not running under root
 privelages please use the regular debian package

Package: gir1.2-cinnamondesktop-3.0
Source: cinnamon-desktop
Version: 2.0.4
Architecture: amd64
Maintainer: Clement Lefebvre <root@linuxmint.com>
 This package provides the include files and static library for the Cinnamon
 desktop library functions.
 .
 This package contains the introspection data for CinnamonDesktop

Package: gir1.2-muffin-3.0
Source: muffin
Version: 2.0.5
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Muffin is the window manager used by Cinnamon.
 .
 This package contains the GObject introspection data which may be
 used to generate dynamic bindings.

Package: gir1.2-nemo-3.0
Source: nemo
Version: 2.0.8
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Nemo is the official file manager and graphical shell for the
 Cinnamon desktop.
 .
 This package can be used by other packages using the GIRepository format to
 generate dynamic bindings.

Package: libcinnamon-control-center-dev
Source: cinnamon-control-center
Version: 2.0.9
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains the files needed to build Control Center panels

Package: libcinnamon-control-center1
Source: cinnamon-control-center
Version: 2.0.9
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains the library used by Control Center panels

Package: libcinnamon-desktop-dev
Source: cinnamon-desktop
Version: 2.0.4
Architecture: amd64
Maintainer: Clement Lefebvre <root@linuxmint.com>
 This package provides the include files and static library for the Cinnamon
 desktop library functions.

Package: libcinnamon-desktop0
Source: cinnamon-desktop
Version: 2.0.4
Architecture: amd64
Maintainer: Clement Lefebvre <root@linuxmint.com>
 This library is used by Cinnamon to load the .desktop files.

Package: libcjs-dev
Source: cjs
Version: 2.0.0
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Makes it possible for applications to use all of GNOME's platform
 libraries using the Javascript language. It's mainly based on the
 Mozilla javascript engine and the GObject introspection framework.
 .
 This package contains the development files applications need to
 build against.

Package: libcjs0c
Source: cjs
Version: 2.0.0
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Makes it possible for applications to use all of GNOME's platform
 libraries using the Javascript language. It's mainly based on the
 Mozilla javascript engine and the GObject introspection framework.
 .
 This is the shared library applications link to.

Package: libcompizconfig0
Source: compiz
Version: 1:0.9.10+13.10.20131011-aaa1
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 The OpenCompositing Project brings 3D desktop visual effects that improve
 usability of the X Window System and provide increased productivity
 through plugins and themes contributed by the community giving a
 rich desktop experience.
 .
 This package contains the library for plugins to configure settings.
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular compiz from ubuntu repositories.

Package: libcompizconfig0-dev
Source: compiz
Version: 1:0.9.10+13.10.20131011-aaa1
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 The OpenCompositing Project brings 3D desktop visual effects that improve
 usability of the X Window System and provide increased productivity
 through plugins and themes contributed by the community giving a
 rich desktop experience.
 .
 This package contains the headers and development files needed to
 build plugins with settings support.
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular compiz from ubuntu repositories.

Package: libdecoration0
Source: compiz
Version: 1:0.9.10+13.10.20131011-aaa1
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 The window decoration library is responsible for drawing the window borders
 and title bar of windows managed by Compiz. It is used by window decorators
 like gtk-window-decorator.
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular compiz from ubuntu repositories.

Package: libdecoration0-dev
Source: compiz
Version: 1:0.9.10+13.10.20131011-aaa1
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 The window decoration library is responsible for drawing the window borders
 and title bar of windows managed by Compiz. It is used by window decorators
 like gtk-window-decorator.
 .
 This package contains files required for developing window decorators
 compatible with Compiz.
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular compiz from ubuntu repositories.

Package: libemeraldengine-dev
Source: emerald
Version: 0.9.5-aaa
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 This package contains the headers and development files needed to
 build engines for emerald.
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular emerald from ubuntu repositories.
Original-Maintainer: Nicholas Thomas <lupine@beryl-project.org>

Package: libemeraldengine0
Source: emerald
Version: 0.9.5-aaa
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 This package provides some engines for drawing decoration on compiz-fusion
Original-Maintainer: Nicholas Thomas <lupine@beryl-project.org>

Package: libfreetype-infinality6
Source: freetype-infinality
Version: 2.4.9-aaa
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 The purpose of these patches is to provide the nicest font rendering of any
 operating system. The second goal is to provide customization so that the
 end user is able to adjust the settings to his or her taste.

Package: libmuffin-dev
Source: muffin
Version: 2.0.5
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Muffin is the window manager used by Cinnamon.
 .
 This package contains the development files.

Package: libmuffin0
Source: muffin
Version: 2.0.5
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Muffin is the window manager used by Cinnamon.
 .
 This package contains the window manager shared library.

Package: libnemo-extension-dev
Source: nemo
Version: 2.0.8
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Nemo is the official file manager and graphical shell for the
 Cinnamon desktop.
 .
 This package provides the necessary development libraries and include
 files to develop and compile Nemo extensions.

Package: libnemo-extension1
Source: nemo
Version: 2.0.8
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Nemo is the official file manager and graphical shell for the
 Cinnamon desktop.
 .
 This package contains a few runtime libraries needed by nemo' extensions.

Package: libthunarx-2-0
Source: thunar
Version: 1.6.3-1aaa0
Architecture: amd64
Maintainer: Debian Xfce Maintainers <pkg-xfce-devel@lists.alioth.debian.org>
 This package contains the Thunar extension library which permits adding new
 features to the Thunar file manager.

Package: libthunarx-2-dev
Source: thunar
Version: 1.6.3-1aaa0
Architecture: amd64
Maintainer: Debian Xfce Maintainers <pkg-xfce-devel@lists.alioth.debian.org>
 This package contains the headers and the static library for libthunarx,
 the extension library used by thunar

Package: muffin
Version: 2.0.5
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Muffin is the window manager used by Cinnamon.
 .
 This package contains the core binaries.

Package: muffin-common
Source: muffin
Version: 2.0.5
Architecture: all
Maintainer: Linux Mint <root@linuxmint.com>
 Muffin is the window manager used by Cinnamon.
 .
 This package contains the shared files.

Package: muffin-dbg
Source: muffin
Version: 2.0.5
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Muffin is the window manager used by Cinnamon.
 .
 This package contains the debugging symbols.

Package: nemo
Version: 2.0.8
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Nemo is the official file manager for the Cinnamon desktop. It allows
 to browse directories, preview files and launch applications associated
 with them. It is also responsible for handling the icons on the Cinnamon
 desktop. It works on local and remote filesystems.
 .
 Several icon themes and components for viewing different kinds of files
 are available in separate packages.

Package: nemo-data
Source: nemo
Version: 2.0.8
Architecture: all
Maintainer: Linux Mint <root@linuxmint.com>
 Nemo is the official file manager and graphical shell for the
 Cinnamon desktop.
 .
 This package contains pictures, localization files and other data
 needed by nemo.

Package: nemo-dbg
Source: nemo
Version: 2.0.8
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Nemo is the official file manager for the Cinnamon desktop. It allows
 to browse directories, preview files and launch applications associated
 with them. It is also responsible for handling the icons on the Cinnamon
 desktop. It works on local and remote filesystems.
 .
 Several icon themes and components for viewing different kinds of files
 are available in separate packages.
 .
 This development package contains unstripped binaries compiled with
 debugging symbols needed by gdb.

Package: pup-volume-monitor
Version: 0.1.15-aaa
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 a udisks replacement, unlike udevil and cousins
 it should work with gnome file managers

Package: pyrit
Version: 0.4.0+git20131223-aaa
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 Pyrit allows one to create massive databases, pre-computing part of the
 WPA/WPA2-PSK authentication phase in a space-time-tradeoff. Exploiting the
 computational power of many-core- and other platforms through ATI-Stream,
 Nvidia CUDA, OpenCL and VIA Padlock, it is currently by far the most powerful
 attack against one of the world's most used security-protocols.
 .
 This package contains the basic version of Pyrit, with support for MMX, SSE2
 and VIA PADLOCK detected at run-time. Support for non-free technologies such
 as Nvidia CUDA can be added through extensions, of which cpython-cuda is
 available
 .
 This is the git version of this package, repackaged from debian to aaa standards
 it now works with the aaa* cpyrit-cuda package to enable gpu accelerated cracking

Package: python-compizconfig
Source: compiz
Version: 1:0.9.10+13.10.20131011-aaa1
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 Compiz Fusion is the result of the re-unification of the Beryl-project
 and the community around the Compiz Window Manager. It seeks to provide
 an easy and fun-to-use windowing environment, allowing use of the
 graphics hardware to provide impressive effects, amazing speed and
 unrivalled usefulness
 .
 This package provides python bindings for the compizconfig system.
 .
 The *aaa versions of this package are specially modified for debian and aaa
 if running a ubuntu box please use the regular compiz from ubuntu repositories.

Package: thunar
Version: 1.6.3-1aaa0
Architecture: amd64
Maintainer: Debian Xfce Maintainers <pkg-xfce-devel@lists.alioth.debian.org>
 Thunar is the file manager designed to be the default file manager of Xfce 4.6
 It has been designed to be fast and easy to use.
 .
 An Xfce plugin can manages the trash, if xfce4-panel is installed as well.
 Please read README.Debian for volume management stuff.

Package: thunar-data
Source: thunar
Version: 1.6.3-1aaa0
Architecture: all
Maintainer: Debian Xfce Maintainers <pkg-xfce-devel@lists.alioth.debian.org>
 This package contains architecture-independent files for thunar.

Package: thunar-dbg
Source: thunar
Version: 1.6.3-1aaa0
Architecture: amd64
Maintainer: Debian Xfce Maintainers <pkg-xfce-devel@lists.alioth.debian.org>
 This package contains debugging symbols for thunar and libthunarx, the file
 manager and file management libraries for Xfce Desktop Environment.

Package: timeshift
Version: 1.2.7-aaa
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 TimeShift is a system restore utility which takes snapshots
 of the system at regular intervals. These snapshots can be restored
 at a later date to undo all changes that were made after the snapshot
 was taken.
 .
 The *aaa versions of this package are specially modified to remove gksu
 dependencies and repackaged for debian.

Package: xarchiver
Version: 1:0.5.2+20130119-aaa
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 Xarchiver is a lightweight desktop independent GTK+ frontend for manipulating
 7z, arj, bzip2, gzip, rar, tar, zip, rpm and deb files. It allows you to
 create archives and add, extract, and delete files from them. Password
 protected archives in the arj, 7z, rar and zip formats are supported.
 .
 The *aaa versions of this pakage are heavily patched to add features ( xz support
 for one ) and improve stability

Package: xarchiver-dbg
Source: xarchiver
Version: 1:0.5.2+20130119-aaa
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 Xarchiver is a lightweight desktop independent GTK+ frontend for manipulating
 7z, arj, bzip2, gzip, rar, tar, zip, rpm and deb files. It allows you to
 create archives and add, extract, and delete files from them. Password
 protected archives in the arj, 7z, rar and zip formats are supported.
 .
 This package contains detached debugging symbols.

Package: cinnamon
Version: 2.0.14+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Cinnamon redefines user interactions with the GNOME desktop.
 In particular, it offers new paradigms for launching applications,
 accessing documents, and organizing open windows in GNOME. Later, it
 will introduce a new applets eco-system and offer new solutions for
 other desktop features, such as notifications and contacts
 management. Cinnamon is intended to replace functions handled
 by the GNOME Panel and by the window manager in previous versions of
 GNOME. Cinnamon has rich visual effects enabled by new
 graphical technologies.

Package: cinnamon-bluetooth
Version: 3.8.2+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains a configuration module and an applet compatible with GNOME Bluetooth.

Package: cinnamon-common
Source: cinnamon
Version: 2.0.14+git20131218aaa
Architecture: all
Maintainer: Linux Mint <root@linuxmint.com>
 Cinnamon redefines user interactions with the GNOME desktop.
 In particular, it offers new paradigms for launching applications,
 accessing documents, and organizing open windows in GNOME. Later, it
 will introduce a new applets eco-system and offer new solutions for
 other desktop features, such as notifications and contacts
 management. Cinnamon is intended to replace functions handled
 by the GNOME Panel and by the window manager in previous versions of
 GNOME. Cinnamon has rich visual effects enabled by new
 graphical technologies.
 .
 This package contains the architecture independent files needed by Cinnamon

Package: cinnamon-control-center
Version: 2.0.9+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains configuration applets for the Cinnamon desktop,
 allowing to set accessibility configuration, desktop fonts, keyboard
 and mouse properties, sound setup, desktop theme and background, user
 interface properties, screen resolution, and other Cinnamon parameters.

Package: cinnamon-control-center-data
Source: cinnamon-control-center
Version: 2.0.9+git20131218aaa
Architecture: all
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains data files (icons, pixmaps, locales files) needed by
 the configuration applets in the cinnamon-control-center package.

Package: cinnamon-dbg
Source: cinnamon
Version: 2.0.14+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Cinnamon redefines user interactions with the GNOME desktop.
 In particular, it offers new paradigms for launching applications,
 accessing documents, and organizing open windows in GNOME. Later, it
 will introduce a new applets eco-system and offer new solutions for
 other desktop features, such as notifications and contacts
 management. Cinnamon is intended to replace functions handled
 by the GNOME Panel and by the window manager in previous versions of
 GNOME. Cinnamon has rich visual effects enabled by new
 graphical technologies.
 .
 This package contains the debugging symbols.

Package: cinnamon-desktop-data
Source: cinnamon-desktop
Version: 2.0.4+git20131218aaa
Architecture: all
Maintainer: Clement Lefebvre <root@linuxmint.com>
 This package includes some files that are shared between several Cinnamon
 apps (internationalization files).

Package: cinnamon-screensaver
Version: 2.0.3+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 cinnamon-screensaver is a screen saver and locker that aims to have simple,
 sane and secure defaults, and be well integrated with the Cinnamon desktop.
 .
 It is designed to support, among other things:
 .
  * the ability to lock down configuration settings
  * translation into other languages
  * user switching
Original-Maintainer: Guilherme de S. Pastore <gpastore@debian.org>

Package: cinnamon-session
Version: 2.0.6+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 The Cinnamon Session Manager is in charge of starting the core components
 of the Cinnamon desktop, and applications that should be launched at
 login time. It also features a way to save and restore currently
 running applications.
 .
 This package contains the binaries for the Cinnamon Session Manager, but
 no startup scripts. It is meant for those willing to start
 cinnamon-session by hand with the components of their choice, and for
 applications such as MDM that use cinnamon-session internally.

Package: cinnamon-session-common
Source: cinnamon-session
Version: 2.0.6+git20131218aaa
Architecture: all
Maintainer: Linux Mint <root@linuxmint.com>
 The Cinnamon Session Manager is in charge of starting the core components
 of the Cinnamon desktop, and applications that should be launched at
 login time. It also features a way to save and restore currently
 running applications.
 .
 This package contains the translations, data files and startup scripts
 which are common to the Cinnamon and Cinnamon fallback sessions.

Package: cinnamon-settings-daemon
Version: 2.0.8+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains the daemon which is responsible for setting the
 various parameters of a Cinnamon session and the applications that run
 under it. It handles the following kinds of settings:
 .
  * Keyboard: layout, accessibility options, shortcuts, media keys
  * Clipboard management
  * Theming: background, icons, GTK+ applications
  * Cleanup of unused files
  * Mouse: cursors, speed, accessibility options
  * Startup of other daemons: screensaver, sound daemon
  * Typing break
 .
 It also sets various application settings through X resources and
 freedesktop.org XSETTINGS.

Package: cinnamon-settings-daemon-dev
Source: cinnamon-settings-daemon
Version: 2.0.8+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains header files required to build applications that
 communicate with the Cinnamon settings daemon over D-Bus.

Package: cinnamon-themes
Version: 2013.11.25+git20131218aaa
Architecture: all
Maintainer: Clement Lefebvre <root@linuxmint.com>
 A collection of the best themes available for Cinnamon.

Package: cinnamon-translations
Version: 2.0.3+git20131218aaa
Architecture: all
Maintainer: Clement Lefebvre <root@linuxmint.com>
 Translation files for the Cinnamon desktop.

Package: cjs
Version: 2.0.0+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Makes it possible for applications to use all of GNOME's platform
 libraries using the Javascript language. It's mainly based on the
 Mozilla javascript engine and the GObject introsepection framework.
 .
 This package contains the interactive console application.

Package: gir1.2-cinnamondesktop-3.0
Source: cinnamon-desktop
Version: 2.0.4+git20131218aaa
Architecture: amd64
Maintainer: Clement Lefebvre <root@linuxmint.com>
 This package provides the include files and static library for the Cinnamon
 desktop library functions.
 .
 This package contains the introspection data for CinnamonDesktop

Package: gir1.2-muffin-3.0
Source: muffin
Version: 2.0.5+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Muffin is the window manager used by Cinnamon.
 .
 This package contains the GObject introspection data which may be
 used to generate dynamic bindings.

Package: gir1.2-nemo-3.0
Source: nemo
Version: 2.0.8+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Nemo is the official file manager and graphical shell for the
 Cinnamon desktop.
 .
 This package can be used by other packages using the GIRepository format to
 generate dynamic bindings.

Package: libcinnamon-control-center-dev
Source: cinnamon-control-center
Version: 2.0.9+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains the files needed to build Control Center panels

Package: libcinnamon-control-center1
Source: cinnamon-control-center
Version: 2.0.9+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 This package contains the library used by Control Center panels

Package: libcinnamon-desktop-dev
Source: cinnamon-desktop
Version: 2.0.4+git20131218aaa
Architecture: amd64
Maintainer: Clement Lefebvre <root@linuxmint.com>
 This package provides the include files and static library for the Cinnamon
 desktop library functions.

Package: libcinnamon-desktop0
Source: cinnamon-desktop
Version: 2.0.4+git20131218aaa
Architecture: amd64
Maintainer: Clement Lefebvre <root@linuxmint.com>
 This library is used by Cinnamon to load the .desktop files.

Package: libcjs-dev
Source: cjs
Version: 2.0.0+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Makes it possible for applications to use all of GNOME's platform
 libraries using the Javascript language. It's mainly based on the
 Mozilla javascript engine and the GObject introspection framework.
 .
 This package contains the development files applications need to
 build against.

Package: libcjs0c
Source: cjs
Version: 2.0.0+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Makes it possible for applications to use all of GNOME's platform
 libraries using the Javascript language. It's mainly based on the
 Mozilla javascript engine and the GObject introspection framework.
 .
 This is the shared library applications link to.

Package: libmuffin-dev
Source: muffin
Version: 2.0.5+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Muffin is the window manager used by Cinnamon.
 .
 This package contains the development files.

Package: libmuffin0
Source: muffin
Version: 2.0.5+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Muffin is the window manager used by Cinnamon.
 .
 This package contains the window manager shared library.

Package: libnemo-extension-dev
Source: nemo
Version: 2.0.8+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Nemo is the official file manager and graphical shell for the
 Cinnamon desktop.
 .
 This package provides the necessary development libraries and include
 files to develop and compile Nemo extensions.

Package: libnemo-extension1
Source: nemo
Version: 2.0.8+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Nemo is the official file manager and graphical shell for the
 Cinnamon desktop.
 .
 This package contains a few runtime libraries needed by nemo' extensions.

Package: muffin
Version: 2.0.5+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Muffin is the window manager used by Cinnamon.
 .
 This package contains the core binaries.

Package: muffin-common
Source: muffin
Version: 2.0.5+git20131218aaa
Architecture: all
Maintainer: Linux Mint <root@linuxmint.com>
 Muffin is the window manager used by Cinnamon.
 .
 This package contains the shared files.

Package: muffin-dbg
Source: muffin
Version: 2.0.5+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Muffin is the window manager used by Cinnamon.
 .
 This package contains the debugging symbols.

Package: nemo
Version: 2.0.8+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Nemo is the official file manager for the Cinnamon desktop. It allows
 to browse directories, preview files and launch applications associated
 with them. It is also responsible for handling the icons on the Cinnamon
 desktop. It works on local and remote filesystems.
 .
 Several icon themes and components for viewing different kinds of files
 are available in separate packages.

Package: nemo-compare
Version: 2.0.0+git20131218aaa
Architecture: all
Maintainer: Clement Lefebvre <root@linuxmint.com>
 Simple context menu file comparison extension for Nemo 3 and above,
 inspired by the discontinued 'diff-ext' extension. By default it uses
 'meld' to do the comparison and provides "Compare", "Compare to ~/foo/bar"
 and "Compare Later" in Nemo context menu. Using the configurator tool
 you can choose your favourite compare tool for one-on-one, three-way and
 multi-compare situations.

Package: nemo-data
Source: nemo
Version: 2.0.8+git20131218aaa
Architecture: all
Maintainer: Linux Mint <root@linuxmint.com>
 Nemo is the official file manager and graphical shell for the
 Cinnamon desktop.
 .
 This package contains pictures, localization files and other data
 needed by nemo.

Package: nemo-dbg
Source: nemo
Version: 2.0.8+git20131218aaa
Architecture: amd64
Maintainer: Linux Mint <root@linuxmint.com>
 Nemo is the official file manager for the Cinnamon desktop. It allows
 to browse directories, preview files and launch applications associated
 with them. It is also responsible for handling the icons on the Cinnamon
 desktop. It works on local and remote filesystems.
 .
 Several icon themes and components for viewing different kinds of files
 are available in separate packages.
 .
 This development package contains unstripped binaries compiled with
 debugging symbols needed by gdb.

Package: nemo-dropbox
Version: 2.0.1+git20131218aaa
Architecture: amd64
Maintainer: Clement Lefebvre <root@linuxmint.com>
 Nemo Dropbox is an extension that integrates the Dropbox web service with
 your Cinnamon Desktop.
 .
 Installing this package will download the proprietary dropbox binary
 from dropbox.com.

Package: nemo-fileroller
Version: 2.0.0+git20131218aaa
Architecture: amd64
Maintainer: Clement Lefebvre <root@linuxmint.com>
 Nemo File Roller is an extension that integrates the File Roller service with
 your Cinnamon Desktop.

Package: nemo-gtkhash
Version: 0.7.0~1+git20131218aaa
Architecture: amd64
Maintainer: Mònica Ramírez Arceda <monica@debian.org>
 The GtkHash extension for nemo which allows users to compute
 message digests or checksums using the mhash library.
 Currently supported hash functions include MD5, MD6, SHA1,
 SHA256, SHA512, RIPEMD, TIGER and WHIRLPOOL.

Package: nemo-media-columns
Version: 2.0.0+git20131218aaa
Architecture: all
Maintainer: Clement Lefebvre <root@linuxmint.com>
 A Nemo extension to display music/EXIF and PDF metadata info in the Nemo List View.

Package: nemo-pastebin
Version: 2.0.0+git20131218aaa
Architecture: all
Maintainer: Clement Lefebvre <root@linuxmint.com>
 nemo-pastebin is a Nemo extension written in Python, which
 allows users to upload text-only files to a pastebin service just
 by right-clicking on them.
 .
 After sending the files, a notification will be shown and the paste
 URL copied into the clipboard.
 .
 Users can also customize the extension's behaviour just by using
 nemo-pastebin-configurator, an easy-to-use configuration tool.

Package: nemo-rabbitvcs
Version: 2.0.0+git20131218aaa
Architecture: all
Maintainer: Clement Lefebvre <root@linuxmint.com>
 RabbitVCS is a set of graphical tools written to provide simple and
 straightforward access to the version control systems SVN (Subversion) and Git.
 This is the extension for the Nemo file manager (v1.1.2 or greater).

Package: nemo-share
Version: 2.0.0+git20131218aaa
Architecture: amd64
Maintainer: Clement Lefebvre <root@linuxmint.com>
 Nemo Share allows you to quickly share a folder from
 the GNOME Nemo file manager without requiring root access.

Package: nemo-terminal
Version: 1.0.1+git20131218aaa
Architecture: amd64
Maintainer: Clement Lefebvre <root@linuxmint.com>
 Nemo Terminal is an embedded terminal for Nemo, the Cinnamon file manager.
 It embeds a terminal pane into Nemo that is accessible by hotkey (default F4)
 and automatically follows the currently active directory in Nemo.

Package: python-nemo
Source: nemo-python
Version: 2.0.0+git20131218aaa
Architecture: amd64
Maintainer: Clement Lefebvre <root@linuxmint.com>
 Python binding for Nemo, to allow Nemo property page and menu item
 extensions to be written in Python.

