# How I lost €4k in a Facebook scam

**TLDR**: don't click ads if you don't trust them 100%

This is a cautionary tale of how I lost close to €4,000 in a sophisticated Facebook scam. I still find it hard to believe I fell for a scam like this. I have 2FA on all my accounts, use a password manager, and I'm generally very cautious with account security.

![TikTok Ads Business page](tiktok-fb-logo.png)

Two days ago, I spotted an ad while browsing Facebook promoted by [Tiktok Ads Business](https://www.facebook.com/Tiktok-Ads-Business-101239798393070/). Unfortunately I don't have a screenshot of the ad in question, but it promised a $3000 credit for new businesses that signed up for the TikTok Ads program. As someone being 15+ years in ad tech, I am used to the idea of businesses giving away ad credits to new advertisers. $3000 is a very high amount, but it didn't raise any red flags since I've heard of the generous [TikTok Back to Business Program](https://www.tiktok.com/business/en/back-to-business-program) before.

![TikTok Ads Business app listing](tiktok-app-page.png)

The ad click took me to the [TikTok Ads Business](https://play.google.com/store/apps/details?id=com.acazira.tforbusiness) Android app on the Google Play Store. 10k+ downloads, 1000+ reviews and a 4.6 rating on average - again, this didn't raise any immediate red flags. Sure, the developer name "Develop App" sounds strange and should I have looked better, the developgameonline@gmail.com developer email and com.acazira.tforbusiness package name would have definitely raised some concerns.

![App screen 1](app-screen-1.jpg)

After installing the app, it opened a clone of the [TikTok Back to Business Program](https://www.tiktok.com/business/en/back-to-business-program) page. After entering my phone number and email, the app asked me to log in with Facebook to get the credits.

![App screen 2](app-screen-2.jpg)

After logging in with my Facebook, a voucher code was displayed under the balance with the explanation that it would take up to 48 hours before TikTok would contact me:

![App screen 3](app-screen-3.jpg)

Two days went by and I was getting curious when I would get that promised email. Then, a transaction email from PayPal arrived:

![PayPal email](paypal-email.png)

Facebook charged €3,990.17 from my linked business PayPal account. I was surprised - I didn't recognize the ad spend so I tried to log in to my Facebook Ad account. Unfortunately it was nowhere to be found - the scammer used my Facebook auth token to remove me from the Facebook Business entity. Strangely enough this is possible without getting any emails from Facebook. I had no way to check my Business entity or Ad account on Facebook to see what's going on.

Contacting Facebook about such scams/hacks is a challenge on its own: there is a [support page](https://www.facebook.com/business/help/support) but in all my attempts I was unable to click the "email" icon. The "chat" icon always says "chat unavailable":

![Facebook support](facebook-support.gif)

Fortunately I found the [Facebook Business Support](https://www.messenger.com/t/facebookadsupport) messenger account, and they replied quickly by confirming the issue:

![Facebook chat](facebook-chat.png)

It's been 12 hours later now and I haven't received an email from Facebook yet. This is a very frustrating experience so far. Will I get my ad account and business account (including all pages that belong to it) back? Will I get the money refunded? What kind of ads did these scammer run with my ad account? I will update this document if I find out more.

What I have done so far:
* Changed my Facebook and PayPal passwords
* Invalidated all signed in devices/tokens
* Reported the fake TikTok Ads Business page to Facebook (no reponse yet)
* Reported the fake TikTok Ads Business app to Google (no response yet)
* Initiated a PayPal chargeback process