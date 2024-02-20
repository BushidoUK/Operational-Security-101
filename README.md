![image](https://github.com/BushidoUK/Operational-Security-101/assets/59974887/dfdb74dc-3e4c-4d4f-99cf-85e70baaf914)

# Operational Security 101
- A repository of advice and guides to share with friends and family who are concerned about their safety during online activities and the security of their devices.
- This repository is based on a [blog](https://blog.bushidotoken.net/2020/12/operational-security-tips-and-tricks.html) I wrote back in 2020, but I wanted a way to update the advice, while preserving the original.

## Social Media:

Social media is difficult to avoid in this day and age. While many guides recommend deleting your accounts and uninstalling your apps, that is not practical for non-technical users trying to live their life.

- Set social media accounts like Twitter, Facebook, Instagram, Threads, TikTok, SnapChat to private (and I recommend your family to do this as well)
- Avoid using your real name when creating accounts to make it harder for people to find you, it is even possible have a [Single Name Only](https://www.wikihow.com/Make-a-Single-Name-Account-on-Facebook) account 
- Avoid using identifiable personal pictures with your face in your profile pictures and/or cover pictures.
- Leave the bio details of social media accounts blank too and avoid sharing identifiable information, such as your car with its number plate or your house front door with its number
- As tempting as it is, avoid checking-in to locations or tagging the specific location of your pictures in social media posts.
- Avoid accepting friend requests or follows from random people, make it so only a list of your actual real life family, friends or colleagues are permitted to view your social media content.
- Finally, have a conversation about the risks of social media with your friends and family and ask them not share pictures of you and prevent them from tagging you.
- As time consuming as it is, go back through your social media timeline and the timeline or your friends and family to make sure that no compromising images or posts were shared historically.

## Personal Security (PERSEC) for Your Accounts:

The types of things most people are afriad of online is if their social media, email, online shopping or bank accounts get hacked. In many cases, these types of security risks come from attacks that are automated by cybercriminals. If people implemented basic cyber hygiene, then they would be immune to 99% of these generic scams as well as some more targeted attacks too due to low-skilled scammers not being able to circumvent basic controls.

- Avoid reusing your passwords and avoid using the most common passwords! Follow the rule of 'Three Random Words' then add some numbers and special characters. That is the [official guidance](https://www.ncsc.gov.uk/collection/top-tips-for-staying-secure-online/three-random-words) from the UK NCSC.
- Use more than one email account! Ideally you should keep one email address for confidential high-value services like finance or business or government related admin stuff and another more internet-facing one for activities like online shopping, tickets, receipts or social media, and potentially even a third backup email for conversations and other sensitive communication.
- For things like marketing paywalls and other sites that require an email (and you known they just want to spam you), use a [temproary email service](https://10minutemail.com/) just to get the link they email you.
- For as many accounts as possible, use Multi-Factor Authentication codes to secure access to your account. This includes One-Time Passcode (OTPs) generated by an authenticator mobile app. It is okay to use SMS-based two-factor authentication (2FA), but do realize that this is less secure than the MFA mobile app due to SMS messages being spoofable.
- **Have I been Pwned** is a VERY useful service to check if your email address has appeared in any data breaches/leaks. If you email appears in a breach you should immediately update your passwords. Have I Been Pwned will also notify you if your email address is present in a new breach as well!
- Password managers are one of the most useful programmes to organise accounts in an encrypted database, these can only be accessed locally with one master password and physical access to your system with the password manager software on it.
- Alway backup data! Protect yourself from corrupted drives, broken devices, or ransomware by backing up your files. This can be done in multiple ways such as removable media (USBs and external drives), and cloud services such as Google Drive, OneDrive, iCloud, Dropbox or Proton Drive.


## Personal Security (PERSEC) for Your Devices:

The goal of these tips to secure your devices so that you become a harder target for cybercriminals. The following steps will help you avoid being a victim to 99% of automated threats and, for targeted attacks, the more time, effort, skills or resources it takes a cybercriminal to compromise you, the more likely and faster it will be that they give up and move on.

- Keep your system updated with the latest security patches, apply them as soon as possible and set systems to update automatically!
- Do not turn off default security settings, especially built-in antivirus software like Windows Defender!
- Check the enabled permissions of mobile apps so that you do not unwittingly share your contact details, SMS log, notifications, and other sensitive information with marketing companies, adware, and malware. 
- Many unpleasant applications come from third-party unverified/unmoderated sites. Only download applications from official sources, such as the Google Play Store for Android, the AppStore for Apple or the Microsoft Store for Windows.
- In general, I recommended completely avoiding pirating sites and using cracked software due to the enermous amounts of malware the push that can do the most nasty stuff like steal the credentials to your email accounts and others that are stored in your browsers or launch ransomware on your system, plus your [IP is leaked to the world](https://iknowwhatyoudownload.com/en/contacts/) when you torrent stuff!
- If you see any suspicious URLs or Websites, you can these two services - **Browserling** & **URLscan** - to visit the site and check it before entering
- If you see any suspicious files on your computer, you can use **VirusTotal** to scan the file and check for malware or even adware

## More Advanced PERSEC

Along with the above, those who are `public-facing personalities` may not get the luxury to conceal their real names from the world. For this group of people they are forced to up their OPSEC game
due to the increased threat level and the higher number of attacks. The recommendations below are for types of users that take their security seriously.

- Firstly, if you require a proper security review, it will be worth it to ask a professional to check your OPSEC using OSINT and other other types of audits.
- Credit monitoring to check for fraudulent transactions.
- Setting up alert emails to check if you are mentioned on Twitter or in news articles can be done via Google Alerts.
- Secure email services such as ProtonMail can be used to send encrypted email addresses to others with similar ‘@protonmail.com’ accounts.
- Any applications, software or services should be reviewed before use with their privacy policies reviewed.
- Before you interact with someone online whether you know them or not, they should be vetted via a quick background research.
- Virtual Private Network (VPN) appliances are recommended for when surfing the web and in public WiFi to encrypt your traffic on networks you do not own and from websites.
- It may also be worth investigating the use of a Virtual Machine (VM) to run a Linux or Windows operating system (OS) inside your primary OS.
- End-to-end encrypted (E2EE) chatting applications for mobile and desktop are recommended such as Signal or Keybase for secure communications and file sharing.
- A final interesting tool that many security engineers use are known as CanaryTokens - these are laid like traps that set off an alert if an intruder triggers them.

## Resources

A list of sites and services mentioned throughout the guide above:

1. Multi-Factor Authenticator (MFA) mobile app: https://www.microsoft.com/en-us/account/authenticator
2. Visit a Site from a Virtual Computer's Browser: https://www.browserling.com/
3. Scan any URL to see if it is malicious: https://urlscan.io/
4. Scan any File to see if it is malicious: https://www.virustotal.com/
5. Check if you email and/or password has been exposed in a data breach: https://haveibeenpwned.com/
6. Temproary Email Service: https://10minutemail.com/
7. Free and Safe Password Manager: https://keepass.info/download.html
8. Setup alerts to monitor for your mentions in articles found by Google: https://www.google.co.uk/alerts
9. Privacy-focused Email Accounts: https://protonmail.com/
10. Reputable VPN software: https://protonvpn.com/
11. Free Virtual Machine Software: https://www.virtualbox.org/
12. Free E2EE Chatting Apps: https://keybase.io | https://signal.org
14. Place Trackers in files on your Desktop/Laptop or Removable Media Devices: http://canarytokens.org/generate
