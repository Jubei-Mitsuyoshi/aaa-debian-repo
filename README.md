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

Package: compiz
Version: 1:0.9.10+13.10.20131011-aaa
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
Version: 1:0.9.10+13.10.20131011-aaa
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
Version: 1:0.9.10+13.10.20131011-aaa
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
Version: 1:0.9.10+13.10.20131011-aaa
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
Version: 1:0.9.10+13.10.20131011-aaa
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
Version: 1:0.9.10+13.10.20131011-aaa
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
Version: 1:0.9.10+13.10.20131011-aaa
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
Version: 0.9.1-aaa
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
Version: 0.9.1-aaa
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
Version: 0.9.1-aaa
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

Package: libcompizconfig0
Source: compiz
Version: 1:0.9.10+13.10.20131011-aaa
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
Version: 1:0.9.10+13.10.20131011-aaa
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
Version: 1:0.9.10+13.10.20131011-aaa
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
Version: 1:0.9.10+13.10.20131011-aaa
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

Package: libfreetype-infinality6
Source: freetype-infinality
Version: 2.4.9-aaa
Architecture: amd64
Maintainer: Jubei Mitsuyoshi <jubei.house.of.five.masters@gmail.com>
 The purpose of these patches is to provide the nicest font rendering of any
 operating system. The second goal is to provide customization so that the
 end user is able to adjust the settings to his or her taste.

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
Version: 1:0.9.10+13.10.20131011-aaa
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

