# KC7-CloutHaus (rough work from Notepad)

#### Important Info to note
```
{
  "hire_date": "2024-10-10 00:00:00+00:00",
  "name": "Afomiya Storm",
  "user_agent": "Mozilla/5.0 (Windows NT 10.0; rv:51.0) Gecko/20100101 Firefox/51.0",
  "ip_addr": "10.10.0.3",
  "email_addr": "afomiya_storm@clouthaus.com",
  "username": "afstorm",
  "role": "Influencer Partner",
  "hostname": "OQPA-DESKTOP",
  "mfa_enabled": "False",
  "company_domain": "clouthaus.com"
}
```
```
{
  "timestamp": "2025-04-03 11:20:02+00:00",
  "method": "GET",
  "src_ip": "10.10.0.3",
  "user_agent": "Mozilla/5.0 (Windows NT 10.0; rv:51.0) Gecko/20100101 Firefox/51.0",
  "url": "https://super-brand-offer.com/login?username=afstorm&password=**********"
}
```

#### Questions
#### Q: Based on Afomiya’s Instagram profile, what is the email address she uses for brand deals?

**Ans : afomiya.storm@gmail.com**

#### Q: Which of the following signs should Afomiya look for to determine if an email offering a brand deal is a phishing attempt?

**Ans : E**

*Afomiya is engaging with her followers on Instagram and decides to do a Q&A session on her Instagram Stories. During the session, she answers some seemingly harmless questions.*

*However, a few of the questions posed by a follower are actually security questions used for her email and social media accounts.*

#### Q: What technique is the threat actor using to manipulate her into revealing personal information that could compromise her email or Instagram account?

**Ans : social Engineering**

*Security questions might seem like a good second layer of protection, but for attackers, they’re often easy pickings, especially in the age of social media*
*Answers to “What’s your pet’s name?” 🐶 or “What city were you born in?” 🌆 are often shared publicly or inadvertently revealed in Q&A posts 🙋, birthday shoutouts 🎂, or tagged photos 📸. That’s exactly how the attacker tried to exploit Afomiya.*
*This is called Open Source Intelligence (OSINT), using publicly available info to gather intel on a target*
*Examine the screenshot of the authentication log and identify the answers the attacker submitted for the security questions.*

#### Q: What answer did the attacker enter to try and bypass the security questions? Enter one of the answers the attacker submitted.

**Ans : Kidus**

#### Q: The threat actor is all geared up, thinking they’ve got Afomiya’s accounts in the bag 🎒 But when they try to reset her password, they hit a roadblock.

*Even though they’ve got all the right answers, they can’t get past one tiny hurdle: the code sent to Afomiya’s phone 📱*

*No code, no access. The attacker’s frustration levels rise faster than Afomiya’s follower count, and they’re left staring at a screen, unable to break through that last layer of security 🤔*

#### Q: What security measure saved Afomiya's email account from being hacked, despite the threat actor having access to her security question answers?

**Ans : 2FA/MFA**

#### Q: According to CloutHaus internal employee logs, what is Afomiya’s designated professional email?

```
Employees
| where username contains "storm"
```

**Ans : afromiya.storm@clouthaus.com**

#### Q: What is Afomiya’s role with CloutHaus?

**Ans : influencer partner**

#### Q: Based on the CloutHaus employee table, what is the status of Multi-Factor Authentication (MFA) for Afomiya’s account?

```
Employees
| where username contains "storm"
|distinct mfa_enabled
```
**Ans : false**

#### Q: What is the sender’s email address in the email Afomiya received from "Dior"?

**Ans : collabs@dior-partners.com**

#### Q: What is the subject line of the email Afomiya received from "Dior"?

**Ans : [EXTERNAL] Exclusive Partnership Opportunity with Dior**

#### Q: What is the link provided in the email?

**Ans : https://super-brand-offer.com/login**

#### Q: When did Afomiya click on the link? Paste the entire timestamp.

**Ans : 2025-04-03 11:20:00**

#### Q: What username did she enter?

**Ans : afstorm**

#### Q:What is the IP address associated with the domain?

**Ans : 198.51.100.12**

#### Q: How many distinct domains are linked to the suspicious IP address?

**Ans : 3**

*Afomiya’s Insta game was on point 💅from smoothie bowls to sunrise selfies, she shared it all. Her followers? Obsessed. The attacker? Even more obsessed… but for very different reasons*

*Turns out, every cute post and “just woke up like this” story was giving the attacker breadcrumbs to follow.*

*Because of her habit of reusing passwords (seriously, it’s been through more accounts than her favorite pair of sneakers), the attacker waltzed right into her Instagram.*

*Just like that, her carefully curated grid became ground zero for a cyber drama she definitely didn’t sign up for.*

Enter: I have MFA setup for my Instagram!

*Afomiya’s Instagram account is hijacked, and the attacker immediately starts messaging her followers, asking for money and offering “exclusive investment opportunities,” because who wouldn’t want to invest in a micro-influencer, right?*

*Yeah, it goes down in the DMs, and her fans, trying to be supportive, happily send funds, thinking they’re helping their favorite influencer.*

#### Q: What are the followers really investing in: a great deal or a phishing scam?

**Ans : phishing scam**

#### Q: Based on the images showing the apartment view and amenities from Afomiya’s Instagram post, use a reverse image search to identify the name of the apartment building.

 **Ans : The Apartments at CityCenter**

*And just to add salt to the wound, the attacker even got into her mailbox.*

*Why? Afomiya’s photo dump of her new place included a close-up of her keys. Oops!*

*This is a textbook case of information leakage, oversharing online in ways that hand attackers clues to bypass security.*

ENTER: Unlocking trouble with a photo!

*Afomiya started spotting suspicious login attempts in her email 👀📧 — then noticed her Instagram acting strange too. Tough to catch when her DMs are a non-stop scrollathon , but something was definitely off.*

*She jumped into action:*

*Changed her Insta password faster than an outfit change in a GRWM video*
*Updated passwords across all her accounts (goodbye reused passwords )*
*Activated multi-factor authentication to level up her security*
*This wasn’t just a reaction — it was resilience.*

#### Q: ❓ What should you never reuse across different sites to protect your accounts?

**Ans : passwords**

*Afomiya sprang into action like a digital ninja 🥷 securing her accounts, changing passwords faster than you can say “phishing,” and letting her followers and brand partners know what went down. She learned that cyber villains don’t wait, so neither should she!*

*With her cybersecurity glow-up, Afomiya ditched bad habits (goodbye password reuse) and embraced the mighty powers of MFA and digital awareness*

*As she spread the word like a cyber fairy godmother she realized that staying safe online isn’t just a one-time fix, it’s a lifestyle. Now, she’s her own threat hunter, dodging red flags like a pro and keeping the cyber baddies at bay*

ENTER: Be the hunter, not the hunted!

#### Q: what ip address was used to gain access 

**Ans : 182.45.67.89**

#### Q: what domains are associated with this ip (enter one)

**Ans : influence-deals.net**

#### Q: What part of the User-Agent string indicates the suspicious browser and operating system? (Submit either the browser name/version or the operating system name/version.)

**Ans : Windows NT 5.2**

#### Q: What country did the login originate from?

**Ans : Jinan, Shandong, China**

#### Q: According to the attacker's web search history on the site, what were they trying to hack?
*read all the searches made **Trigger warning: it is creepy and stalker-ed***

**Ans : location**


#### Q: According to another search log, what kind of personal info were they sneakily trying to uncover (and pretending to ask “for a friend”)?

**Ans : home address**

#### Q: What kind of account or app does that log suggest they were targeting?

**Ans : Venmo**

#### Q: Based on another search, what shady and fake event were they pretending to plan as a way to lure Afomiya?

**Ans : birthday party**

#### Q: Which forwarded email contained Afomiya’s payment details or direct deposit form?
(Submit the exact subject line.)

[EXTERNAL] [FORWARD] Afomiya's payment details – direct deposit form

#### Q: What forwarded email subject included a passport scan?
(Submit the exact subject line.)

Pro tip
 [EXTERNAL] [FORWARD] Afomiya's passport scan – confidential


 #### Q: Which forwarded email subject contained either Afomiya’s bank statement or year-end tax documents?
(Submit the exact subject line.)


 [EXTERNAL] [FORWARD] Re: Re: Re: Afomiya's bank statement – confidential; [EXTERNAL] [FORWARD] Re: Tax documents – year-end summary


Based on everything you’ve discovered, what do you think the attacker’s true objective was?

**Ans : all**
