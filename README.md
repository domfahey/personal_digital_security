# personal_digital_security

# Personal Digital Security Guide
**Rev 20240208**  
**Dominic Fahey**  
[@domfahey](https://twitter.com/domfahey)

---

## "Risk Prevention - Not much in life is 100%"

### Executive Summary: Risk Prevention for the Average Apple User

In an era where digital security is paramount, the "Risk Prevention - Not much in life is 100%" guide serves as an essential roadmap for average Apple users who seek to fortify their digital life without being overwhelmed by complex cybersecurity jargon or measures. Acknowledging that no security measure is foolproof, this guide pragmatically focuses on significantly reducing risk through accessible and effective strategies. It is tailored for individuals who may not be high-value targets like journalists or politicians but still recognize the importance of safeguarding their digital presence against common threats.

The cornerstone of the guide's advice is the strong endorsement of Two-Factor Authentication (2FA), with a clear hierarchy of preference that begins with hardware keys, followed by push-based and TOTP/token-based methods, and advises against the use of SMS-based 2FA due to its vulnerabilities. This is particularly emphasized for critical accounts such as email and financial services, where the risks of SIM-swap scams and related frauds are highlighted.

To complement 2FA, the guide advises on several other key security measures:
- **Device Security**: Recommendations include the purchase of hardware security tokens, the activation of Apple's Stolen Device Protection, and the use of unique, long, random passphrases managed via reputable password managers.
- **Communication Security**: The guide suggests securing cell phone accounts by setting up strong PINs/passcodes, requesting port freezes, and employing unique passcodes on mobile devices.
- **Financial Security**: A preference for credit over debit cards is advised to mitigate fraud risks, alongside the practice of shredding sensitive documents and implementing credit freezes to protect against identity theft.
- **Privacy and Online Security**: Strategies include using reputable DNS providers, monitoring for data breaches, opting out of unsolicited marketing, and employing tools like HTTPS Everywhere and VPNs to enhance online privacy and security.

The guide encapsulates a holistic approach to digital security, balancing the ease of implementation with the effectiveness of each measure. By adopting these practices, users can significantly enhance their digital security posture, protecting themselves against a wide array of common threats without needing to be cybersecurity experts.

This comprehensive set of recommendations underscores the importance of proactive measures in today's digital landscape. It is a testament to the achievable balance between accessibility for the average user and the implementation of robust security practices that can thwart the efforts of opportunistic attackers.

### Recommendations

- Use Two-factor Authentication (2FA) for all accounts with a preference for non-SMS solutions. I recommend (in order) hardware key, push-based, and TOTP/token-based. Only use SMS if there is no other option.
  - [Two-factor Authentication](https://twofactorauth.org/)
  - [So Hey You Should Stop Using Texts for Two-Factor Authentication | WIRED](https://www.wired.com/)
- Especially do not use SMS 2FA for your email or financial accounts.
- Disable SMS / cell phone password recovery for your email and financial accounts.
  - Why? If you become a victim of a SIM-swap or port-out scam, a fraudster can take over your email and then use it to take over other accounts.
- If you use a TOTP like Google Authenticator or Authy, never give anyone your one-time code if you didn’t request it.
  - [How Google Authenticator made one company’s network breach much, much worse | Ars Technica](https://arstechnica.com/)
  - [How Authy 2FA Backups Work](https://authy.com/)
- Consider purchasing two or more hardware tokens / security keys.
  - [What is Security Keys for Apple ID and why does it matter? | ZDNET](https://www.zdnet.com/)
- Activate Apple Stolen Device Protection.
  - [About Stolen Device Protection for iPhone - Apple Support](https://support.apple.com/)
- Consider activating Apple end-to-end encryption.
  - [How to Enable Advanced Data Protection on iOS, and Why You Should | Electronic Frontier Foundation](https://www.eff.org/)
- Ditch complex passwords; use unique, long, random passphrases for all accounts.
  - [Forget Tough Passwords: New Guidelines Make It Simple : All Tech Considered : NPR](https://www.npr.org/)
- Use a password manager to manage your unique, long passwords.
  - [The Best Password Managers for 2024 | PCMag](https://www.pcmag.com/)
- Secure your cell phone: Make sure the password, pin, and security codes are long, secure, and unique.
  - [Your mobile phone account could be hijacked by an identity thief](https://www.ftc.gov/news-events/blogs/techftc/2016/06/your-mobile-phone-account-could-be-hijacked-identity-thief)
- Call your cell phone provider and ask for a port freeze and ask to lock your account to your current SIM. Not all providers will do all of those things. If yours won’t, consider changing to one that will.
  - [On phone numbers and identity](https://www.coinbase.com/blog/on-phone-numbers-and-identity)
- Use a unique passcode on your mobile devices.
  - [Use a passcode with your iPhone, iPad, or iPod touch - Apple Support](https://support.apple.com/)
- Don't use debit cards, instead use ATM or credit cards.
  - [Why You Should Never Use a Debit Card To Pay for Anything](https://www.thebalance.com/shred-mail-identity-theft-1947644)
- Shred documents.
- Add security/credit freezes.
  - [Equifax Security Freeze](https://www.equifax.com/personal/credit-report-services/credit-freeze/)
  - [TransUnion Freeze My Credit](https://www.transunion.com/credit-freeze)
  - [Experian Freeze or Unfreeze Your Credit File for Free](https://www.experian.com/freeze/center.html)
- Use a reputable DNS provider.
- Register your email to monitor if it has been compromised in a data breach.
  - [Have I Been Pwned](https://haveibeenpwned.com/)
- Don’t reuse passwords!
- Don’t answer unknown numbers on your personal phone. If they need you, they will leave a message.
- Register for the National Do Not Call Registry.
  - [National Do Not Call Registry](https://www.donotcall.gov/)
- Opt Out of prescreened credit card and insurance offers via USPS.
  - [OptOutPrescreen.com](https://www.optoutprescreen.com/)
- Opt out of direct marketing via USPS on DMA Choice.
  - [DMAchoice](https://www.dmachoice.org/)
- Use HTTPS Everywhere on your web browsers.
  - [HTTPS Everywhere | Electronic Frontier Foundation](https://www.eff.org/https-everywhere)
- Don’t Use public Wi-Fi and if you must, use a VPN.
  - [Why You Really Need to Stop Using Public Wi-Fi](https://www.vpn.com/)
- Use a reputable VPN provider.
  - [The 10 Best VPN Services for 2024 | PCMag](https://www.pcmag.com/)

Credit to Bryan VonCannon for seeding this list
