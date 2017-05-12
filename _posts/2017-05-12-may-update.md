---
layout: newsletter
title: "0.9.4 Release announcement"
category: newsletter
permalink: /news/2017/may/
---

## Introduction

OpenCATS is the leading open-source Applicant Tracking System for recruiters and companies. It is the ongoing result of the community's hard work and collaborative development since it was forked from the original base project (which moved into a closed-source SAAS model). This version of OpenCATS provides a number of new features, addresses critical security concerns, and maintains compatibility with current releases of PHP and MySQL.

### ACL system for role-based restrictions

It is now possible to configure granular permissions for users based upon their roles and permit/restrict access to specific sections of the application. This is configured in the global configuration file config.php

### Replacement of TinyMCE with CKEditor
All references to TinyMCE have been removed and it's prelaced in it's entirety throughout the application with the current version of CKEditor. 

### Zipcode lookup via google. 

When adding in new candidate or contact details, the address details will auto-populate using a lookup to google services. Note that some formatting varies per country. Currently this is tested for USA / Europe. 

### Working hard for the future

We're well along the path for the next major version, too - moving to the Symfony framework and with a refreshed GUI based on bootstrap.

### Changelog

The full details of the release (including changelog) are at [https://github.com/opencats/OpenCATS/releases/tag/0.9.4](https://github.com/opencats/OpenCATS/releases/tag/0.9.4)

### Thank you to the developers

The unsung heroes are the developers who have put an immense amount of personal time into maintaining and enhancing this project. You can find them in the release notes.. Every single one of them should be honoured!

### Come and help!
If you want to out with the brand new challenged of OpenCATS as it migrates to Symfony and Bootstrap.. Please view the project on github and lend a hand. We actively monitor github issues, and regularly collaborate on slack.

[http://github.com/opencats/opencats](http://github.com/opencats/opencats)  
[http://opencats.slack.com](http://opencats.slack.com)

### Support queries?
If you've deployed OpenCATS and have a support query, please visit the [User support forums](http://forums.opencat.org) or if you have found an issue with the code - then raise an [issue on github](http://github.com/opencats/opencats/issues)

ALternatively, you can email me night or day - [russh@opencats.org](mailto:russh@opencats.org)
