# Plesk Promo Box Remover

Plesk Extension that removes the big blue Promo Box on the home screen in Service Provider view.

Here's what it looks like:


![Plesk Promo Box Remover](https://github.com/versluis/plesk-promo-box-remover/raw/master/before.png)
BEFORE (without this extension): the big blue box shows Plesk related stuff at the top


![Plesk Promo Box Remover](https://github.com/versluis/plesk-promo-box-remover/raw/master/after.png)
AFTER (with this extension enabled): the clutter free "zen-at-large" experience lets you focus on your server 


### Supported Plesk Versions

The extension has been tested with 
* Plesk 12
* Plesk 12.5
* Plesk Onyx (17 and 17.5)


### Installation and Usage

* download the ZIP file from this repo (promoboxremover.zip)
* in your Plesk installation, head over to the Extensions tab on the left hand side
* under "My Extensions", upload the ZIP file
* ignore the warning about "untrusted sources"
* enjoy an ad-free Home Screen in Plesk


### Source

The only source file is global.css. It simply targets the promo box class and suppresses the its output.
To find out more about how to get started writing your own Plesk Extensions, have a look at my article from 2014: https://wpguru.co.uk/2014/02/how-to-create-an-extension-in-plesk/
