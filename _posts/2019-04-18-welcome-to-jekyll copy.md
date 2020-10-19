---
title: "HP Client Management Script Library"
date: 2019-04-18T17:34:30-04:00
categories:
  - blog
tags:
  - Powershell
  - update
  - HP
---

HP released the HP Client Management Script Library modules, which provide easier access to maintain Firmware, Bios and Driver updates for end points from the command line.

You can install the HPCMSL module from the PSGallery as shown below:
```
Install-Module -Name HPCMSL -Force -AcceptLicense
```
{: .language-powershell}

In specific, we will have a look at the Softpaq Repository Module.

![Softpaq Repository Diagram]({{ site.url }}{{ site.baseurl }}/assets/images/hpssm.jpg)


HP released the HP Client Management Script Library modules, which provide easier access to maintain Firmware, Bios and Driver updates for end points from the command line.

You can install the HPCMSL module from the PSGallery as shown below: