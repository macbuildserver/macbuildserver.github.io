---
layout: post
title: "How to test any open source ios project from github right on your device?"
description: ""
category: 
tags: []
---

Assume you've found some promising iOS library or framework which by description ideally fits your needs. For example, [QuickDialogs](https://github.com/escoz/quickdialog). 
But how can you quickly examine its possibilities and behavior right on your mobile device? You need clone repo, change code signing options(bundle id, provide own provision profile and certificate and so on), then build .ipa file and install on mobile device through iTunes. Looks tedios, doesn't it?

But with our service you can do all stuff right on your iOS compatible device. 

1. Follow the link to [our trial page](http://macbuildserver.com/try/);
2. Enter github repo url, like previous mentioned QuickDialogs git://github.com/escoz/QuickDialog.git;
![Enter GitHub Repo]({{ site.url }}/images/try_form/enter_github_repo.PNG)
3. Choose correct project and build configuration(for QuickDialogs leave default settings);
![Build Setup]({{ site.url }}/images/try_form/setup_build.PNG)
4. Press Next;
![Signing Options]({{ site.url }}/images/try_form/signing_options.PNG)
5. Click 'Install app via OTA' button.
![Install app via OTA]({{ site.url }}/images/try_form/signing_options.PNG)
6. Enjoy it! :-)


{% include JB/setup %}

