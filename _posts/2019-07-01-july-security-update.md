---
layout: newsletter
title: "0.9.4 Security update"
category: newsletter
permalink: /news/2019/july/
---

## Urgent Security release

In response to an XML External Entity (XXE) Injection vulnerability we have released OpenCats v0.9.4-3.

### Overview
OpenCats suffers from an unauthenticated xml external entity injection that allows remote users to read files on the underlying operating system.

Date Reported: 28 Jun 2019

### More information:
OpenCats XML External Entity (XXE) Injection

Remote users (job applicants) can upload docx or odt files to read files on the underlying operating system. A docx file will be used here, but odt files can be used as well since the same vulnerable functions in DocumentTotext.php are used to parse the files.

### Remediation
This problem has been fixed in version 0.9.4-3

We recommend that you upgrade your opencats instance asap.

If you wish to apply a fix instead, please [view the changes](https://github.com/opencats/OpenCATS/pull/440) which requries you to add a single line to /lib/DocumentToText.php

### Thanks
We are extremely grateful to Reginald Dodd for finding this vulnerability and notifying the OpenCATS project. 

### Support queries?
If you have any questions regarding this security fix, please visit the [User support forums](http://forums.opencat.org) or if you have found an issue with the code - then raise an [issue on github](http://github.com/opencats/opencats/issues)
