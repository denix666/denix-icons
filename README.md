denix-icons
===========

denix-icons - is a set of icons for DeniX-OS.


Installation
============

**From yum repository:**

Fedora `16,17` - install the denix-x repo:

```vim
#rpm -ivh http://fedora.os.vc/yum/base/x1/i386/denix-repo-1.1-2.x1.noarch.rpm
```
and then install the package as regular:

```vim
#yum install denix-icons
```


**Manual RPM installation:**

If you want to install this package manualy, download the latest version from one of my mirrors:

http://mirror.os.vc/denix-repo/yum/base/x1

and install it by using this command as root:

```vim
#rpm -ivh denix-icons.xx.x-xx.x1.noarch.rpm
```


**Howto build RPM from source:**

Clone my git repository and run the build script:

```vim
$mkdir git-repos
$cd git-repos
$git clone https://github.com/denix666/denix-icons.git
$cd denix-icons
$./build_denix-icons.sh
```
