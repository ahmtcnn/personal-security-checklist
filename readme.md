

# Personal Security Checklist


## Passwords

Ideally you should use a different, and secure password to access each service you use. To securely manage all of these, a password manager is usually the best option.

Most reported data breaches [this Verizon report](http://www.verizonenterprise.com/resources/reports/rp_dbir-2016-executive-summary_xg_en.pdf) are caused by involved weak, default or stolen passwords. Massive amounts of private data was stolen because of this.

For everything you could ever want to know about passwords, check out [this guide](https://heimdalsecurity.com/blog/password-security-guide/).

| **Security**                                                               | **Priority** | **Details and Hints**                                                                                                                                                                                                                                                                                                                                                                                                                                              | **Done** |
| -------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- |
| **Use a strong password**                                                  | Recommended  | Check how strong your password is at: [HowSecureIsMyPassword.net](https://howsecureismypassword.net). Try to get a got mixture of upper and lower-case letters, numbers and symbols. Avoid names, places and dictionary words where possible, and aim to get a decent length. Have a look at [How Long will it take to Crack my Password](https://www.betterbuys.com/estimating-password-cracking-times/).                                                         | [ ]      |
| **Don’t save your password in browsers**                                   | Recommended  | Most modern browsers offer to save your credentials when you log into a site. Don’t allow this! As they are not encrypted, hence can allow easy access into your accounts. Also do not store passwords in a .txt file or any other unencrypted means. Ideally use a password manager.                                                                                                                                                                              |          |
| **Use different passwords for each account you have**                      | Recommended  | If one password gets compromised, it can give hackers access to your other online sites, so it is highly recommended not to reuse the same passwords. In order to manage having hundreds of different passwords, use a [password manager](https://en.wikipedia.org/wiki/Password_manager). Have a look at [LastPass](https://www.lastpass.com), [DashLane](https://www.dashlane.com), [KeePass](https://keepass.info) or [Robo Forms 8](https://www.roboform.com). | [ ]      |
| **Be cautious when logging in on someone else’s device**                   | Recommended  | Ideally you wouldn’t ever log into any of your services on someone else’s device, since you can’t be sure that they don’t have any malware. If you do, ensure that your in a private session (like Incognito mode) so that nothing gets saved                                                                                                                                                                                                                      | [ ]      |
| **Avoid password hints**                                                   | Optional     | It is likely that there is a lot of information about you online, so it can be an easy task for a hacker to find out which high school you went to, or what your Mums name is.                                                                                                                                                                                                                                                                                     | [ ]      |
| **Never answer online security questions truthaly**                        | Optional     | Instead, create a password inside your password manager to store your fictitious answer. This will stop people guessing your place of birth or mothers mainen name.                                                                                                                                                                                                                                                                                                | [ ]      |
| **Don’t use a 4-digit pin to access your phone**                           | Optional     | Don’t use a short pin to access your smartphone or computer. Instead use a text password.                                                                                                                                                                                                                                                                                                                                                                          | [ ]      |
| **Use an offline password manager**                                        | Advanced     | Consider an offline password manager, encrypted by a strong password. If you work across two or more computers, this could be stored on an encrypted USB. [KeePass](http://keepass.info/) is a strong choice                                                                                                                                                                                                                                                       |          |
| **If possible, try to avoid bio-metric and hardware-based authentication** | Advanced     | Fingerprint sensors, face-detection and voice-recognition are all easily hackable. Where possible replace these with traditional passwords.                                                                                                                                                                                                                                                                                                                        | [ ]      |
| P**assword protect your BIOS and drives**                                  | Advanced     | A BIOS or UEFI password helps to make an inexperienced hackers life a bit harder if they get hold of your PC or hard drive, [here is a guide on how to do it](https://www.howtogeek.com/186235/how-to-secure-your-computer-with-a-bios-or-uefi-password/).                                                                                                                                                                                                         | [ ]      |


**2-Factor Authentication**

This is a secure method of logging in, where you supply not just your password, but also an additional code usually from a device that only you’d have access to.

| **Security**              | **Priority** | **Details and Hints**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | **Done** |
| ------------------------- | ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| **Use an authenticator.** | Recommended  | Use [Google Authenticator](https://support.google.com/accounts/answer/1066447) where sites offer 2-FA. Alternative authenticators include: [Authy](https://authy.com),  [FreeOTP](https://freeotp.github.io), [LastPassAuthenticator](https://lastpass.com/auth/) and [AuthenticatorPlus](https://www.authenticatorplus.com). SMS codes are ubiquitous, but easy to break so although better than nothing, not ideal. Another option is a hardware-based 2FA, such as [Yubico](https://www.yubico.com/security-keys-authentication/), although with limited compatibility and of  course a physical cost. Check out [this list of apps/ sites which provide the option of 2FA](https://twofactorauth.org/). | [ ]      |


**Browser and Search**

Most modern web browsers allow for addons and extensions, these can access anything that you do online, avoid installing anything that may not be legitimate and check permissions first. Be aware that ever website that you interact with, including search engines will likely be keeping records of all your activity. Last year Kaspersky reported [over a million data exploits caused by malicious sites](https://securelist.com/it-threat-evolution-q1-2017-statistics/78475/).

For more browser security pointers, check out: [Here’s How To Get Solid Browser Security](https://heimdalsecurity.com/blog/ultimate-guide-secure-online-browsing/) 

| **Security**                                       | **Priority** | **Details and Hints**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| -------------------------------------------------- | ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Deactivate ActiveX**                             | Recommended  | [ActiveX](https://en.wikipedia.org/wiki/ActiveX) is barley used nowadays, but Microsoft  browsers have it enabled by default. It acts as a middleware between Java and Flash applications and your PC. But it is commonly used for malicious sites to run scripts directly on your PC. See [this article](https://www.howtogeek.com/162282/what-activex-controls-are-and-why-theyre-dangerous/) for more details.                                                                                                                                                                   |
| **Disable Flash**                                  | Recommended  | Adobe Flash has been around since the dawn of the internet, however it has been falling in popularity for a while. It brings with it many unpatched vulnerabilities (a few of which you can [read about here](https://www.comparitech.com/blog/information-security/flash-vulnerabilities-security/)). See [this guide](https://www.howtogeek.com/222275/how-to-uninstall-and-disable-flash-in-every-web-browser/), on how to disable Flash player, or [this guide for more details on how dangerous it can be](https://www.tomsguide.com/us/disable-flash-how-to,news-21335.html). |
| **Block Trackers**                                 | Recommended  | Consider installing a browser extension, such as [Privacy Badger](https://www.eff.org/privacybadger), to stop advertisers from secretly tracking you                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Block scripts from bad origin**                  | Recommended  | Use an extension such as [uBlock Origin](https://github.com/gorhill/uBlock), to block anything being loaded from an external or unverified origin.                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Force HTTPS only traffic**                       | Recommended  | Ensure that you only use websites through https. It’s recomended to use an extension such as [HTTPS Everywhere](https://www.eff.org/https-everywhere), to force all sites to load securely.                                                                                                                                                                                                                                                                                                                                                                                         |
| **Only use trusted browser addons and extensions** | Recommended  | Both Firefox and Chrome webstore allow you to check what permissions access rights an extension requires before you install it. Check the reviews. Only install extensions you really need.                                                                                                                                                                                                                                                                                                                                                                                         |
| **Always keep your browser up-to-date**            | Recommended  | Browser vulnerabilities are constantly being discovered and patched, so it’s important to keep it up to date, to avoid a zero-day exploit.                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Use a private search engine**                    | Optional     | Take a look at [DuckDuckGo](https://duckduckgo.com) or [StartPage](https://www.startpage.com). Neither store cookies or cache anything.                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Consider a privacy browser**                     | Optional     | Google openly collects usage data on Chrome usage. There are several privacy browsers out there which minimise the amount of data collected. Have a look at [Brave Browser](https://brave.com), [Yandex](https://browser.yandex.com), or [Comodo](https://www.comodo.com/home/browsers-toolbars/browser.php). As a more extreme choice, consider [Tor](https://www.torproject.org/).                                                                                                                                                                                                |
| **Disable JavaScript**                             | Advanced     | Many modern web apps, are JavaScript based, so disabling it will greatly reduce your browsing experience. But if you really want to go all out, then it will reduce your attack surface. Read more about the growing [risk of JavaScript malware](https://heimdalsecurity.com/blog/javascript-malware-explained/).                                                                                                                                                                                                                                                                  |


**VPN**

A Virtual Private Network (VPN) allows you to securely connect to the internet, when you visit a site, your visiting it through the secure VPN connection and not broadcasting your own IP address. A VPN will hide your identity on the websites you visit, to your internet service provider, and to anyone else trying to track you, they can also encrypt your traffic so you can browse more securely on public networks. They’re really easy to setup.

| **Done** | **Security**  | **Details and Hints**                                                                                                                                                                                                                                                                           |
| -------- | ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| []       | **Use a VPN** | Ideally use a paid-for VPN, as they’re considerably better quality so won’t affect your speeds, nor show adds. Take a look at [VyprVPN](https://www.goldenfrog.com/vyprvpn), [NordVPN](https://nordvpn.com), [IPVanish](https://www.ipvanish.com) and [TunnelBear](https://www.tunnelbear.com). |

 
**Social Media**


| **Done** | **Security**                                                          | **Details and Hints**                                                                                                                                                                                                                                                                                                                                                      |
| -------- | --------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| []       | **Check your privacy settings**                                       | Most social networks allow you to control your privacy settings. Ensure that your profile can only be viewed by people who you are in your friends list, and you know personally.                                                                                                                                                                                          |
| []       | **Only put info on social media that you wouldn’t mind being public** | Even with tightened security settings, don’t put anything online that you wouldn’t want to be seen by anyone other than your friends. Don’t reply soley on the social networks security.                                                                                                                                                                                   |
| []       | **Don’t give social networking apps permissions they don’t need**     | By default many of the popular social networking apps, will ask for permission to access your contacts, your call log, your location, your messaging history etc.. If they don’t need this access- don’t grant it.                                                                                                                                                         |
| []       | **Remove meta data before uploading media**                           | Most smartphones and some cameras automatically attach a comprehensive set of additional data to each photograph., This usually includes things like time, date, location, camera model, user etc. Remove this data before uploading. See [this guide](https://www.makeuseof.com/tag/3-ways-to-remove-exif-metadata-from-photos-and-why-you-might-want-to/) for more info. |


**Your Devices**


| **Done** | **Security**                                            | **Details and Hints**                                                                                                                                                          |
| -------- | ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| []       | **Turn of connectivity features that arn’t being used** | When your not using WiFi, Bluetooth, NFC or anything else- turn those features off. These are commonly used to easily hack individuals.                                        |
| []       | **Uninstall apps that you don’t need**                  | Don’t have apps that your not using on your phone, as they can be collecting data in the background. Don’t install apps from non-legitimate sources, or apps with few reviews. |
| []       | **Don’t grant apps permissions that they don’t need.**  | If an app doesn’t need access to your camera- don’t grant it access. Same with any features of your phone, be wary about what each app has access to.                          |



**Phone Number**


| **Done** | **Security**                       | **Details and Hints**                                                                                                                                                                                                                                                                                                                                                                                                  |
| -------- | ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| []       | Avoid using your real phone number | Where possible, avoid giving out your real phone number while creating accounts online. You can create phone numbers using services such as [Google Voice](https://voice.google.com) or [Skype](https://www.skype.com/en/features/online-number/). For temporary usage you can use a service like [iNumbr](https://www.inumbr.com) that generates a phone number that forwards messages and calls to your main number. |

 
**Communication**

SMS texting is not secure.

| **Done** | **Security**                                     | **Details and Hints**                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| -------- | ------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ ]      | Don’t use SMS - Use E2E encrypted messaging apps | [iMessage is secure](https://techcrunch.com/2014/02/27/apple-explains-exactly-how-secure-imessage-really-is/). For non-Apple users [Signal](https://signal.org) is the most secure option. As of late 2016 [WhatsApp](https://www.whatsapp.com) is also [end-to-end-encrypted using the Signal protocol](https://signal.org/blog/whatsapp-complete/). Signal can also protect your phone calls.                                                                                                    |
| [ ]      | Use a secure email provider                      | Most email providers completely invade your privacy intercepting both messages sent and received. [ProtonMail](https://protonmail.com) is a secure email provider, that is open source and offers end-to-end encryption. There are alternative secure mail providers (such as [CounterMail](https://countermail.com), [HushMail](https://www.hushmail.com) and [MailFence](https://mailfence.com))- but [ProtonMail](https://protonmail.com) has both a clear interface and strong security record |


**Your Router**


| **Done** | **Security**                     | **Details and Hints**                                                                                                                                                                                                                                                                                                             |
| -------- | -------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| []       | **Don’t use a default password** | Change your router password- [here is a guide as to how](https://www.lifewire.com/how-to-change-your-wireless-routers-admin-password-2487652).                                                                                                                                                                                    |
| []       | **Ideally hide your SSID**       | An SSID (or Service Set Identifier) is simply your network name. If it is not visible, it is much less likely to be targeted. You can usually hide it after logging into your router admin panel, [see here for more details](https://www.lifewire.com/hide-your-wireless-network-from-your-internet-leeching-neighbors-2487655). |


**Operating Systems**

Although Windows and OS X are easy and convient, they both are far from secure. The ideal option would be to install a security-based OS. Where this often isn’t possible, using a VM or dual-booting with a consumer-focused Linux distro is still preferable to primarily using a either of Microsoft’s, Apple’s or Google’s services.

| **Done** | **Security**                                             | **Details and Hints**                                                                                                                                                                                                                                                                     |
| -------- | -------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| []       | **Consider Switching to Linux**                          | Linux is considerably [more secure](https://www.pcworld.com/article/202452/why_linux_is_more_secure_than_windows.html) than both OSX and Windows. Some distros are still more secure than others, so it’s worth choosing the right one to get a balance between security and convenience. |
| []       | **Consider running a custom ROM on your Android device** | Your default OS tracks information about your usage, and app data, constantly. Consider a security-focused custom ROM, such as [Lineage](https://lineageos.org) or [CopperheadOS](https://copperhead.co/android/).                                                                        |

**Shopping**


| **Done** | **Security**                                                  | **Details and Hints**                                                                                                                                                                                                        |
| -------- | ------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| []       | **Consider using a pre-paid debit card, topped up with cash** | There are a lot of options out there, some are free, some are only available in certain locations, some do require identity checks, whereas others don’t- so it’s worth shopping round to find the one that’s right for you. |
| []       | **Consider paying with a Crypto currency**                    | This is the most secure method of payment, although unfortunately not currently widley supported.                                                                                                                            |
| []       | **Consider not getting goods delivered to your home address** | Use a pickup service, such as Doddle, Amazon Click + Collect, eBay Argos collect etc.                                                                                                                                        |


