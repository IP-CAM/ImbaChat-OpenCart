# ImbaChat-OpenCart

[![ImbaChat](http://imbachat.com/themes/imbachat/assets/img/logo.svg "ImbaChat")](http://imbachat.com "ImbaChat")

# Chat widget for OpenCart CMS

This is free plugin for integration OpenCart CMS с chat service imbachat.com 
It allows to add chat widget between users on your website for free. 

# Links:

[Demo site](http://wordpress.imbachat.com/)

[Plugin for WordPress CMS](https://github.com/imbasynergy/ImbaChat-WordPressCMS)

[Source code of the demo site](https://github.com/imbasynergy/ImbaChat-WordPressCMS-demo)

[Technical support](http://imbachat.com/help)

# Features:

* Full integration with the user base of your website
* Single authorisation mechanism in a chat and on a website (users need not sign up in a chat)
* Chatting between users mano a mano
* Sending pictures
* Sending geolocation
* Sending smiles
* Real time message delivery
* It does not load your server (The chat widget uses project servers imbachat.com)
* You can use it on shared hosting
* It continues correct working even without the Internet (Your messages will be sent as soon the Internet appears)

[![Chat demo](http://imbachat.com/storage/app/uploads/public/docs/demo.gif "Chat demo")](https://imbachat.com "Chat demo")


## Steps to install a chat widget:
- Download the plugin from [plugin repository](https://github.com/imbasynergy/ImbaChat-OpenCart)
- Move the contents of the repository to the root folder of your site
- Open the admin panel of your site, then open `Design`>` Theme Editor`> `common`>` footer` and paste at the end body ```{{ include( 'default/template/extension/module/imbachat.twig' ) }}```
    ![install](https://i.ibb.co/XyP8Zds/2020-02-12-12-20-22.png "install")
- Register on the site [imbachat.com](https://github.com/imbasynergy/ImbaChat-OpenCart)
- Go to the widget page, and create yourself a widget
- In the process of creating a widget, you will need to select "Integration with OpenCart CMS" and follow the instructions
