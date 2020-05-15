## IOS-XRv6.1.2 Vagrant Quick Start Guide

You can use the [editor on GitHub](https://github.com/rohitthakur2590/cosmosandcode/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Install vagrant on fedora 30/31/32

```markdown
[rothakur@localhost ~]$ sudo dnf install vagrant
```
### Create a directory

```markdown
[rothakur@localhost ~]$ mkdir ios-xrv9k
```
### Go to the directory

```markdown
[rothakur@localhost ~]$ cd ios-xrv9k
```
### Copy this <iosxrv-fullk9-x64.box> to current location

```markdown
[rothakur@localhost ios-xrv9k]$ mv~/Downloads/iosxrv-fullk9-x64.box .
```
### Initialize VagrantFile

```markdown
 [rothakur@localhost ios-xrv9k]$ vagrant init ios-xrv612
```
### Add the box with command

```markdown
 [rothakur@localhost ios-xrv9k]$ vagrant box add --name ios-xrv612 iosxrv-fullk9-x64.box
```
### Confirm the added box with command

```markdown
 [rothakur@localhost ios-xrv9k]$ vagrant box list
 XRv9k-612          (virtualbox, 0)
```
### Run the vagrant up

```markdown
 [rothakur@localhost ios-xrv9k]$ vagrant up
```
