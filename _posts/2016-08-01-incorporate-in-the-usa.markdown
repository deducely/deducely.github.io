---
layout: post
title:  "How we incorporated Deducely, Inc in the USA using Stripe Atlas"
date:   2016-08-02 12:12:12 +0530
permalink: /blog/how-to-incorporate-in-the-us-from-oustside-the-usa-v3
excerpt_separator: <!--more-->
---

> In our first blogpost, I'd like to talk about how we incorporated in US from outside the USA.

<!--more-->

>This is a version 3.0 post that is inspired from [ V 1.0 by my former boss Girish Mathrubootham](http://blog.freshdesk.com/how-to-incorporate-a-us-corporation-from-outs/) and [V 2.0 by Suresh Sambandam, CEO of KiSSFLOW. ](https://www.chargebee.com/blog/how-to-incorporate-in-the-us-v2/)

<!--break-->
>This article can not be considered Legal advise, please consult a lawyer and/or accountant before incorporating.

![US Incorporation 101](http://i.imgur.com/cUx4iEn.png)



The US has one of the most mature banking and financial systems in the world. Owing to this  many internet businesses prefer to incorporate in the US. In India the reserve bank of India does **not** allow businesses to automatically charge user's credit/debit card's; explicit user consent is expected via a second factor authentication like an OTP or a password. This hampers the smooth functioning of subscription businesses that charge users every month.

However **A US based company can store its user's credit cards and charge them automatically** in a recurring fashion seamlessly. For the convenience of auto-charging credit cards many 'Subscription As A Service' (SaaS) companies based out of India have their headquartered in the US.

Deducely being a SaaS product, we wanted the ability to charge our user's cards every month automatically without asking them to input their card number every month. Since we operate from India our options were very limited

#### We had 3 options in hand, but we had apprehensions too:
1. Incorporate in a foreign country - Too costly, close to $2000
2. Use 2Checkout or FastSpring - About 10% to be paid as commissions
3. Use Paypal subscriptions - Developer un-friendly, average customer support

**Enter The Atlas Program**
![Stripe Atlas](http://i.imgur.com/KxuqDHx.png)

Stripe atlas is a bento box  for businesses to get up and running. Stripe Atlas grants the following for a flat fee of $500:

1. US company registration (A Delaware C corp).
2. Registering with the IRS for taxation purposes.
3. A Zero balance US bank account in Silicon valley bank.
4. Access to Legal and Tax consultation from PwC, Orrick and UpCounsel.
5. **$15,000 in Amazon Web Services Credits.**
6. A Stripe account ready to accept payments.


We were skeptical about this program, We even felt it was too good to be true but when we approached  [Avinash Raghava](https://twitter.com/avinashraghava) of [iSpirit](http://www.ispirt.in)  and [Suresh Sambandam](https://twitter.com/sureshsambandam) of [KiSSFLOW](https://kissflow.com) for expert opinion, we were advised to go ahead and incorporate via Stripe Atlas. It was totally worthwhile.

### How to incorporate a Delaware C Corp in the USA through the Stripe Atlas program?

#### Step 1: Get an invite to the Atlas program

This is the most difficult part, as of now the stripe atlas program is invite only, you could try requesting an invite on the website or via their [twitter account](https://twitter.com/atlas). Once you are successfully invited you'd get an email with a link that can be used to register an account at [Stripe Atlas](https://atlas.stripe.com/). Now You'd be required to create a new Stripe account.

#### Step 2: Enter detailed information about your business

Once you have signed up for the Stripe account you would be presented with the following overview screen :

![stripe starting page](http://i.imgur.com/SWtcNjI.png?1)

When we click on get started we are presented with a screen that asks a few details about the product and the business:

![business details page](http://i.imgur.com/Mmtnk1d.png)

#### Step 3: Enter how you'd like to structure your company

There are two ways to structure your company when your business is not physically present in the US. This is a very crucial decision and should be taken after thorough deliberation.

1. Setting up a US headquartered company with an Indian (or other non US country) subsidiary: [Freshdesk's model](http://blog.freshdesk.com/how-to-incorporate-a-us-corporation-from-outs/)
2. Setting up a US subsidiary for a non US parent company: [KiSSFLOW's model](https://www.chargebee.com/blog/how-to-incorporate-in-the-us-v2/)

![Company incorporation screen](http://i.imgur.com/f6BOVoY.png)

We had not incorporated anywhere yet and we went ahead with Freshdesk's model , so we were asked to enter our company's desired name, while entering the desired name please ensure that the name is not registered by any other entity, a simple google search could help you out.

Although we could have enter our local non US address, we went ahead and purchased a physical address in the US through [virtual post mail](http://www.virtualpostmail.com) for $10/month; virtualpostmail.com scan the physical mail that we get and email it to us. We received our ETPS(Electronic tax payment system) credentials through our physical address. Though the US address wouldn't be of any other use in the immediate future, we wanted Deducely to be global and hence we invested in a US physical address.

We got a US phone number for free through Google Voice and entered that as our phone number, to get a Google voice number you need to know someone with a US phone number from a major carrier like Verizon, AT&T or Sprint. Once the google voice setup is done you will be able to make and receive calls from your US google voice number through the [Hangouts dialer app](https://play.google.com/store/apps/details?id=com.google.android.apps.hangoutsdialer&hl=en) . You could enter your local number here as well.
> If you choose to set up a US subsidiary with a Non US company as the parent you would be asked to present the Non US company's tax ID and registration certificate. Please consult your local lawyer and accountant for any regulatory compliances that need to be met.

#### Step 4: Enter the details about the people in the company

In this page you'd be prompted to enter the personal details of all the people who would have more than 25% stakes in the company. Please have a scanned copy of your passport or any other government issued IDs.

![Personal details about the founders](https://i.imgur.com/pH9RR8A.png)

Now,  in the same page, you will also be asked to select the company's president, secretary, incorporator and directors.

![Board of directors](http://i.imgur.com/5wthqZG.png?1)  

#### Step 5: Enter the bank account administrator details and pay:

 Getting a US bank account is the most difficult part for any non US entrepreneur , You either have to be physically present in the US or know someone in the US who could introduce you to the bank. These banks tend to have high maintenance fees and high minimum balances associated with them. However stripe atlas has partnered with [Silicon Valley Bank(SVB)](svb.com). SVB provides a zero balance account with no maintenance fee for 2 years. In the following screen you will get an option to select the administrator for the SVB account

 ![SVB administrator](http://i.imgur.com/2RY9V80.png)

#### Step 6: Enter your credit/debit card details:

 You will be presented with a stripe checkout popup where you can enter your card details. You will we charged $500 USD only after the successful incorporation of your company. After the payment you'd get a prompt saying that your incorporation would be complete in one week.

<center>
<img src="http://i.imgur.com/SX3fOBL.png?1">
</center>
<br>

 **Since Deducely was one of the initial pilot companies to be incorporated via the Stripe Atlas program we did not have to spend a dime to get up and running with a US company and bank account! Thanks a tonne [Patrick](https://twitter.com/patrickc), we owe you one!**

#### Step 7: The application review process:

I am not sure if this is step would be applicable for everyone. A couple of days after we had submitted our application we received an email from stripe requesting us to furnish details like our estimated timeline, screenshots, Terms of service etc... and we showed them our screenshots and git account; after a few anxious days our application was accepted. I feel this is necessary steps to prevent abuse of this program.

#### Step 9: Digitally sign the incorporation documents:

After the review process is done and dusted, all the associated people in step 4 would receive an email with a link to a [Docusign](http://docusign.com) document. You can read the documents and sign. We would be able to proceed to the next step only when all the associated people have completed signing the documents.

#### Step 10: The AWS activate account:

After signing all the documents you'd get an email with a link to activate your AWS goodies. You'd get:

* $15,00 in AWS credits valid for 2 years.
* Access to AWS web based training (worth $600).
* Access to AWS business support (worth $5000).
* Access to AWS solution architects.

#### Step 11: Receive your incorporation documents:

After you digitally sign all the incorporation documents , wait for around 5-7 days to get your Delaware C corp incorporation certificate and your Tax ID(Employer Identification Number) from the IRS.

#### Step 12: Opening the SVB account:

Since we had given a PO box address in the US we were asked to give the physical address where our business is present. We emailed this to SVB and after 1 week we were granted access to SVB online banking.

 **This is the end of the incorporation procedure, here a few things to be done next**

#### Next Steps:

1) Signing the stock plans:
Stripe would email you a draft of a Stock agreements, get it signed by your board of directors. Stripe would also schedule a free 30 minute call with upcounsel - a law firm for clarifying any queries.

2) Sending funds to the SVB account:
Ideally you can wire funds into your SVB account, but this is a tedious process involving a lot of waiting. We found (square cash)[https://cash.me] to be a convenient way to send cash into our SVB account. It takes 2 working days for the cash to show up in your bank account.

3) Getting a credit / debit card :
You have funds in your SVB account and you want to pay for your hosting and other subscriptions, there are two options that I am aware of, the first method would be to apply get a business credit/debit card from SVB and get it delivered to your address. The second method is signing up at [privacy.com](hhtps://privacy.com). Privacy.com is a new age fin tech company that links with your bank account, through this service you can generate virtual VISA cards with fixed spending limits and close them whenever you want. We use privacy.com to generate virtual credit cards and track our spending. This service is free!

4) The Unofficial Stripe entrepreneurs Facebook group:
If you are not based in the US and have a US based company , we have created an [unofficial stripe atlas entrepreneurs group in Facebook](https://www.facebook.com/groups/1751531058421877/) . You are not alone here, if you run into any issues or need help you can ask other fellow atlas entrepreneurs for help.

Overall our experience with Stripe atlas was exemplary. Their support team always had our back; I'd like to give a huge shoutout to Anita from the Stripe atlas team, she was very not only knowledgeable but also very patient in replying to the barrage of queries that we raised every day! Ideally a service like this would cost you at least 800$ without the bank account and $15,000 in AWS credits. Stripe Atlas = A happy meal for company incorporation!

>If you need any help or have any queries related to this post please reach out to me at aswin &lt;at&gt; deducely &lt;dot&gt; com  

<meta property="og:title" content="How we incorporated Deducely, Inc In the USA using Stripe Atlas" />
<meta property="og:image" content="http://i.imgur.com/cUx4iEn.png?1" />
<meta property="og:locale" content="en_US" />
<meta property="og:type" content="article" />
<meta property="og:description" content="How we incorporated Deducely, Inc in the US spending $0*" />
<meta property="og:site_name" content="Deducely.com" />
<meta property="article:publisher" content="https://facebook.com/deducely" />
<meta property="article:author" content="https://www.facebook.com/aswinvayiravan" />
