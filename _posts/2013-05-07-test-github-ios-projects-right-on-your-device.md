---
layout: post
title: "How to run GitHub iOS project on your device in seconds without XCode?"
description: ""
category: 
tags: ["iOS", "without", "xcode", "howto", "build", ".ipa"]
---

Assume you've found some promising iOS library or framework on GitHub, which ideally fits your needs. For example, be [QuickDialogs](https://github.com/escoz/quickdialog). 
But how can you easily examine its possibilities and behavior right on your mobile device? 
Cloning repo, running XCode, codesigning etc. look mess and tedious... You may skip it with [MacBuildServer](http://macbuildserver.com/).

Also, you don't need even desktop/notebook to do that. Just link to GitHub repo and follow few simple steps.

1. Enter GitHub repo URL, like previously mentioned QuickDialogs ```git://github.com/escoz/QuickDialog.git``` on the [MacBuildServer Try Page](http://macbuildserver.com/try/)
![Enter GitHub Repo]({{ site.url }}/images/try_form/enter_github_repo.PNG)

2. Choose correct project and build configuration (for QuickDialogs, you may leave default settings)
![Build Setup]({{ site.url }}/images/try_form/setup_build.PNG)

3. Press "Next". Also, you may specify any additional signing options, like in normal workflow. (If you've got all prerequisites on your iDevice)
![Signing Options]({{ site.url }}/images/try_form/signing_options.PNG)

4. Click 'Install app via OTA' button.
![Install app via OTA]({{ site.url }}/images/try_form/install_ipa_ota.PNG)

5. Enjoy it! :-)

I hope it will help you and you'll love [MacBuildServer](http://macbuildserver.com/) for really simple projects building workflow.

{% include JB/setup %}

