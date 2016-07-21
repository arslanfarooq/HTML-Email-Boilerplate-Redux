HTML Email Boilerplate Redux
==============================================

A HTML Email Boilerplate is designed to create a solid foundation for any email campaign by fixing various email client quirks from the beginning (saving headaches later!), as well as providing a good starting point for building your own email campaigns/templates.

There are various email boilerplate templates around, however Central College Nottingham has adapted its own boilerplate template based on a variety of sources as well our own additions based on our own research and development. We regularly review changes in email client behaviour and aim to keep our boilerplate constantly up to date with the latest developments and changes in the email world.

We refer to our email boilerplate as a redux of the [original HTML Email Boilerplate](http://htmlemailboilerplate.com/)

## What does our redux version of the HTML email boilerplate include?

As well as creating a solid foundation for any email campaign, our boilerplate also focuses on the following areas:

* Forcing the document mode (edge) for Internet Explorer based clients
* CSS3 support in the native mail client on Windows Phone 8 and above (POP3/IMAP)
* Scaling images correctly in Outlook 2010 and 2013 when using DPI scaling factors greater than 96 DPI (100%)
* Improved Windows Phone 7/8/8.1 compatibility
* Improved Office 365 (OWA) compatibility (Microsoft have since improved the rendering standards of OWA [in the October 2014 update](http://blogs.office.com/2014/10/14/improving-outlook-web-app-options-settings-2/))
* Android 4.4 centring fix

As well as fixing other email client quirks that have been discovered.

## Usage:

Our boilerplate is split into two versions, stable and experimental. Previously this was managed by creating different HTML document versions, however since [
1bc2b35](https://github.com/centralcollegenottingham/HTML-Email-Boilerplate-Redux/commit/1bc2b35d4e4730eb4aea203f2d8fded1a93ec0d9) this is now done via branches in the Git repo.

### Develop branch

This is the latest/bleeding edge version of the email boilerplate, experimental code that needs testing will appear here first, it provides a branch for testers/curious users to check out the very latest developments of the email boilerplate, but be warned, email client compatibility is not guaranteed on develop.

**It is strongly recommended that you NEVER use the develop version of the boilerplate in a live email campaign. The develop version may not have been tested thoroughly and hence its cross email client compatibility is not guaranteed. Always use the master branch!**

### Master branch (default branch)

This is the stable version of the boilerplate which should be used in email campaigns. 

**Note:** Always use the "without guidelines" version in any email campaign.

### Guidelines

Two versions of the email boilerplate exist, one version is full of HTML/CSS comments that details every aspect of the code, the other is the same code but with all the comments stripped out.

**Never use the guidelines version in a live email campaign, as HTML/CSS comments play havoc with spam filters and even cause emails to appear blank in a few clients! You will also be adding unnecessary bloat to your HTML as well **


## License:

The MIT License (MIT)

Copyright (c) 2014 - 2016 Central College Nottingham

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

## Credits:

This boilerplate is originally based on two very popular boilerplates by:

* Sean Powell - http://htmlemailboilerplate.com
* Email on Acid - http://www.emailonacid.com/blog/details/C13/html_boilerplate

Further additions and adaptations have been made Central College Nottingham either from our own research or cited from sources. Where sources have been cited in the guidelines version of the stable boilerplate, credit is given to the original author of the referenced information.



