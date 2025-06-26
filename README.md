
<p align="center">
<img src="https://github.com/user-attachments/assets/96fdabb8-ce48-47bc-9d26-0534e26ba918", width="350", height="350">
</p>

<h1 align="center">DEDSEC_CLICKFIX</h1>
<h4 align="center">CLICKFIX is a Linux-based social engineering tool that delivers payloads using a ClickFix</h4>

### DESCRIPTION

CLICKFIX is a social engineering tool designed to deploy malware using a deceptive technique known as the ClickFix attack. The tool creates a fake CAPTCHA verification page to trick the victim into thinking they need to verify themselves to access the website.

Behind the scenes, when the victim interacts with the fake CAPTCHA, a hidden payload is silently copied to their clipboard. The page then displays a message instructing the user to press Win + R (opening the Windows Run dialog) and paste the copied content. If the victim follows the instructions, the payload is executed, granting the attacker control or executing malicious code on the target system.

### Features:

  * Custom Links: Create your own malicious payload links and make them appear legitimate using a flexible link builder.
  * Templates: Choose from a list of pre-made, realistic-looking URLs (e.g., popular websites, social media pages, file-sharing links) to mask your payload.
  * Link Masker: Apply the DEDSEC-style masking technique to cloak your real link behind a convincing front, increasing the chances of the victim clicking and following through.
  * Clipboard Payload Injection: Automatically copies malicious commands to the victim’s clipboard through browser interaction.
  * Run Dialog Exploit: The payload is crafted specifically to be executed via the Windows Run command, reducing detection by security tools.
  * Tunnel Integration: Quickly expose your local page to the internet using built-in Cloudflare tunneling.
    
### SCREENSHOT 
<p align="center">
<img src="https://github.com/user-attachments/assets/e61fdf4d-abfb-4b98-a15b-5861e488e6c9", width="500", height="500">
<img src="https://github.com/user-attachments/assets/4a3d1200-10b5-41d9-8e63-74e3c23c8859", width="500", height="500">
</p>

### Create an API Key
1. Create Temporary Email [Tempmail](https://www.emailnator.com/) (Optional)
1. Register a [T.LY Account](https://t.ly/register)
2. Create an [API Token](https://t.ly/settings#/api)
   
### INSTALLATION
    * git clone https://github.com/0xbitx/DEDSEC_CLICKFIX.git
    * cd DEDSEC_CLICKFIX
    * pip install requests tqdm tabulate
    * sudo apt intall zip
    * chmod +x dedsec-clickfix
    * ./dedsec-clickfix

### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS 
* Ubuntu

## Support

If you find my work helpful and want to support me, consider making a donation. Your contribution will help me continue working on open-source projects.

**Bitcoin Address: `36ALguYpTgFF3RztL4h2uFb3cRMzQALAcm`**

<h1 align="center"> DISCLAIMER </h1>

<h4 align="center">I'm not responsible for anything you do with this program, so please only use it for good and educational purposes. </h4>




