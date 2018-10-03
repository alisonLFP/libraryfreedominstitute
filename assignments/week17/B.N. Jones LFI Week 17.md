B.N. Jones  
LFI Week 17  
Instructional slides about mobile device privacy

These are taken from lengthiest workshop we ever attempted and we threw in everything but the kitchen sink. We're not sure how successful this was, but thanks to things I've learned in LFI, it will be better the next time we do it in February 2019. The section about phones can be found between [slides 9.0](https://librarianbryan.github.io/privacyworkshopBRRL/#/9) and [slides 9.10](https://librarianbryan.github.io/privacyworkshopBRRL/#/9/10). The slides titles below are also direct links to individual slides. Navigate with up and down arrows, but really the slides are minimal and we just talk. Below I will try to summarize what we cover with asides for things we've learned in the field or during LFI. At this point in the workshop, we would have already covered free/libre/open source software and encryption. We introduce two overarching concepts at the beginning: 1) **more privacy = more work** (because defaults are typically no privacy not that that's a good thing) 2) **consider the source** meaning who do you trust and why. Who is creating this product? Why do they want to you to use it? Who is saying that privacy is dead and who is saying that privacy matters? In general, each section of the workshop goes from conceptually big to small, from functionally difficult to easy.

[**PHONES** 9/0](https://librarianbryan.github.io/privacyworkshopBRRL/#/9)   
Phones track you. Even if you turn your phone off or stick it in a Faraday pouch, when you turn it back on it will ping a cell tower or a wifi network. Each phone has a unique identifier, IMEI. We know now the Google records location if you ask Android not to. An iPhone will leak less data, but not necessarily its apps. We use examples from pop culture to introduce the concept of burner phones. At the end, we'll live demo a Faraday pouch by getting some attendees to put their phones in it and have others try to text them.    

[**Purism Librem5** 9/1](https://librarianbryan.github.io/privacyworkshopBRRL/#/9/1)   
Is there anything we can do? Conceptually *big*, the [Librem5](https://puri.sm/shop/librem-5/). A phone built for privacy from the ground up, all free software. At the time of writing, it's vaporware but the company building it has funding and successfully produces high quality all free software laptops. I make it very clear I am not saying "Preorder this!" but as concept a privacy oriented phone is a thing that exists and you can preorder one from a company that actually makes stuff.

[**Lineage OS** 9/2](https://librarianbryan.github.io/privacyworkshopBRRL/#/9/2)  
Confused metaphor, but like desktop GNU/Linux for your phone. Android but with Google's proprietary bits stripped out. You can add those back in a piece at time if you wish. Has an Android developer feature called Privacy Guard that lets you limit which apps have what permissions to what data. This feature is turned off in commercial versions of Android. I won't work on every phone, and is harder to install than desktop versions GNU/Linux. Probably just one tick upon the average computer user.  

[**F-Droid** 9/3](https://librarianbryan.github.io/privacyworkshopBRRL/#/9/3)  
If you don't have Google Play store, what do you use instead? F-Droid--the free software Android app repository and another example of free software community's tradition of naming things poorly. If an app wants permissions that it does not need, you get a big, clear warning before installing it.

[**Know your settings** 9/4](https://librarianbryan.github.io/privacyworkshopBRRL/#/9/4)  
Imaginary phones and hacking your own phone is hard, so mitigate your risk by configuring the settings the way you want. We give handouts with settings for the latest versions of Android and iOS. This is constantly in flux and Android comes in infinite variations, but we try to teach people where to look.

[**Signal** 9/5](https://librarianbryan.github.io/privacyworkshopBRRL/#/9/5)  
Cross platform, end to end encrypted messaging. Developed by a nonprofit started by cryptographers. It's encryption protocol has been borrowed by many other apps. Free software. Has desktop app, calls, and video chat. If you want to do one immediate, easy thing to do to increase your privacy--install Signal!

[**WhatsApp, etc** 9/6](https://librarianbryan.github.io/privacyworkshopBRRL/#/9/6)  
Other apps also offer end to end encryption. Consider the source. We talk about WhatsApp founders leaving Facebook.   

[**Orbot (Android)** 9/7](https://librarianbryan.github.io/privacyworkshopBRRL/#/9/7)  
Connects your Android phone to the Tor network. We would have previously covered what Tor / Tor Browser was at this point. Can decide which apps you want to route through Tor. I give the example that my podcatcher is not routed through Tor because I have no time for bologna when I'm about to get in the shower and I need a podcast. Works great for every other app though.  

[**Orfox (Android)** 9/8](https://librarianbryan.github.io/privacyworkshopBRRL/#/9/8)   
Like Tor Browser but for Android. Need Orbot for it to work.

[**Onion Browser (iOS)** 9/9](https://librarianbryan.github.io/privacyworkshopBRRL/#/9/9)   
Tor Browser for iOS. Don't need Orbot for it to work. It is always difficult to explain why this is the one you want as opposed to others. The software license requirements of the Apple Appstore are esoteric to those not interested in such things. Consider the source--we're the librarian and we're telling you download this one. Joking. We talk about the credentials of the developer. Onion Browser has a new logo now.

[**Firefox Focus** 9/10](https://librarianbryan.github.io/privacyworkshopBRRL/#/9/10)      
A lightweight version of Firefox preconfigured to block trackers, ads, and not remember history. It is very fast but lacks a lot of features. We don't always include this one as regular mobile Firefox can be configured to do the same thing, the features it lacks are useful, and it does not offer the same anonymity as Orfox or Onion Browser.
