# Analysis and Recommendations for Providing Anonymous Contact Options and Ensuring Accessibility

## Anonymous Contact Options

The significance of anonymous contact options on websites in the internet is crucial in today's interconnected world. In many situations, individuals seek communication channels that allow them to share their concerns, issues, or questions without revealing their identity. This necessity arises from a variety of reasons, including security concerns, the sensitivity of the topics being discussed, legal or political restrictions, victim protection, and the desire to preserve privacy. This introduction serves as a starting point for examining the various aspects and implications of anonymous communication channels on the internet and their role in supporting and safeguarding the interests and security of users in different life situations. By acknowledging the importance of anonymous contact options, we can take a step towards a more comprehensive provision of support and resources for those in need, while simultaneously ensuring the preservation of their privacy and security.

These communication channels need not be weighed against each other. Strategically, it is most sensible to integrate as many channels as possible. However, all of these must be operated and maintained.

## Creation of a Separate Email Address

A separate email address serves as an initial offering for contact. The recipient's name should reflect trustworthiness, and accompanying text should specify who has access to this mailbox, how these emails are stored, and the deletion deadlines.

Suggestions:

* *secureemail@*
* *trustedcommunication@*
* *safe@*
* *protect@*
* *freedom@*
  
*Only select employees have access to this mailbox, who are committed to confidentiality and immediate deletion of all data after processing.*

## Provision of a PGP Key

Providing a PGP (Pretty Good Privacy) key for contact email addresses is another step towards building trust and is recommended for the following reasons:

* **Encryption of communication:** PGP enables the encryption of emails, ensuring that only the individual with the correct key can decrypt and read the message. This provides an additional layer of security to protect sensitive information from unauthorized access.
* **Protection against surveillance:** Individuals seeking a means of contact may be in countries or situations where governmental surveillance and censorship of communication occur. Using PGP helps protect communication from such surveillance and maintains the privacy of the individuals involved.
* **Authentication:** PGP also allows for the digital signing of emails, verifying messages as authentic and originating from the intended source. This can help ensure the credibility and integrity of communication and persuade recipients that the message comes from the intended person or organization.

However, it is important to note that using PGP requires some technical expertise, both from the organization and the users. Therefore, appropriate training and support should be provided in the form of instructions and links to ensure effective use of PGP. The public key should also be published on key servers such as [https://keys.openpgp.org/](https://de.wikipedia.org/ "https://keys.openpgp.org/")  or [https://keyserver.pgp.com/vkd/GetWelcomeScreen.event](https://keyserver.pgp.com/vkd/GetWelcomeScreen.event "https://keyserver.pgp.com/vkd/GetWelcomeScreen.event") . See also Appendix "Generating Key Pair".

## Provision of a Simple Contact Form

Not all internet users are technically savvy or familiar with encryption technologies such as PGP. A contact form is a user-friendly option that allows even those without specific technical skills to easily make contact, ensuring the needs of a broad target audience are met. Accompanying text should clarify deletion deadlines and specify to whom the message is directed. Additionally, an optional field for providing an email address should be offered, with the note that this field is optional but necessary for the website operators to respond to the contact request.

## Provision of a Securedrop

Setting up a Securedrop system on the website is an additional and particularly secure way to receive confidential information. Securedrop is an open-source platform used by media organizations and other institutions to securely receive anonymous information from whistleblowers, activists, and other sources. In addition to anonymous communication (Securedrop allows users to send messages and files anonymously without disclosing their identity or email address), it offers a range of security features, including encryption and the ability to securely upload files. This ensures the protection of sensitive information from unauthorized access and the disclosure of their identity, which could have serious consequences. A Securedrop system can also be useful for individuals who wish to report misconduct or wrongdoing within their own organization or community to uncover issues and bring about positive change without revealing the identity of the whistleblower. However, it is important to note that implementing and maintaining a Securedrop system may pose a small technical challenge and require training of staff. It is also important to ensure that users are adequately informed about how to use the system effectively.

## Provision of Encrypted Messenger Services

In addition, contact can be offered via various messenger services. To do this, the respective service must be installed on a mobile phone, and depending on the service, certain data must be provided on the website. With Telegram, for example, a link can be created so that the user's own phone number is not displayed. An interesting option would be a Matrix/Element set up (https://www.heise.de/news/Element-Eigene-Messaging-Infrstruktur-statt-oeffentlicher-Matrix-Server-5069142.html). This can be completely self-operated and provides high security. However, this also requires maintenance efforts.

## Accessibility of the Arts Rights Justice Library on the Tor Network

Using the Tor Browser (https://www.torproject.org/de/) already enables anonymous use of websites.

The Tor Browser works by routing the user's traffic through a series of encrypted servers before reaching the internet. This means that the user's IP address, which is normally used to track location and identity, is obscured. Thus, websites and services visited on the Clearnet ("normal" internet) only see the address of a Tor exit server and not that of the user.

## Advantages of Offering a .onion Service

### Maximum Security

In addition to the anonymity already provided by the user with the Tor Browser or a VPN on the Clearnet pages of the Library, a .onion service offers maximum security. The user remains in the Tor network and does not use an exit node, eliminating the non-tracking of the request up to the exit node.

### No Censorship Restrictions

Censorship restrictions vary by country and politics. When using the Tor Browser, the restrictions of the exit node are applied, as these are implemented on a network basis. Thus, if an exit node in Vietnam is randomly used for the route through the Tor network, the Clearnet offer of Taz in Germany, for example, could not be reached, but the .onion service would not be affected as no exit node is used here.

### Reputation

The decision to host a website on the darknet also underscores the commitment to security and privacy. This can strengthen the trust of users who are aware that their personal information and activities are respected and protected. It emphasizes the commitment to creating a safe space.

### Ideological Support for the Tor Network

In addition, an offering in the darknet can significantly enrich the diversity and creativity of this part of the internet. By creating a creative space in the darknet, unconventional ideas and art forms can be promoted that might otherwise not find a place in the mainstream internet. This contributes to the diversification and enrichment of the cultural landscape of the darknet.

## Disadvantages of Offering a .onion Service

### Effort

Depending on the implementation, additional efforts will be required of the operators. In the lightweight implementation, a .onion address is added in the server configuration. Accessibility is thus easily extended to the darknet, and there is no double content management (see Appendix "Server Configuration"). In addition, public relations efforts are required. Making this special offer known and maintaining attention to it, in specialist media and social media.

### Low Target Audience (Cost/Benefit)

The limited number of users in the darknet is indeed a challenge for special offers. The darknet is significantly less accessible compared to the Clearnet, the public internet. Therefore, it may be more difficult to reach a broad and diverse target audience. It is important to recognize that the darknet represents a niche that addresses specific interests and needs. To be successful with a library in the darknet, it is important to have realistic expectations and focus on a dedicated and perhaps smaller target audience. This requires targeted and audience-oriented advertising through publications of specialist articles, contacting existing link lists requesting inclusion, as well as announcements in social media including Reddit and Lemmy.

## Conclusion

In today's digital landscape, the provision of anonymous contact options on websites is paramount for ensuring the accessibility and security of individuals seeking assistance or support. By offering a range of communication channels such as separate email addresses, PGP encryption, contact forms, Securedrop systems, and encrypted messenger services, organizations can cater to diverse user needs while safeguarding their privacy. Furthermore, extending accessibility to the darknet through .onion services enhances security and offers an additional layer of anonymity. However, it is essential to acknowledge the technical challenges and limited audience reach associated with darknet offerings. Overall, by implementing these recommendations, organizations can foster trust, promote transparency, and provide a safe environment for individuals to seek assistance and share sensitive information without fear of repercussions.


## Appendix
### Generating Key Pair

Install Software: Ensure you have PGP software installed on your computer. GnuPG (GPG) is widely used open-source software available on many platforms. You can download and install it from the official website: https://gnupg.org/download/index.html

Open the Command Line (Terminal): On most operating systems, you can open the command line (terminal). This is where you will enter the PGP commands.

Generate Your PGP Key Pair: Enter the following command and press "Enter". This command generates your PGP key pair and guides you through the process:
gpg --gen-key

You will be prompted for various information, including your name, email address, and a password for the key. Please follow the instructions and enter the appropriate information.

Select Key Type and Key Length: You will be prompted to select the key type and key length. In most cases, RSA as the key type is sufficient. The recommended key length is currently at least 2048 bits. However, you can also choose a longer key length to increase security.

Generate Random Entropy: The generator will prompt you to perform random actions on your computer to generate entropy. This can be mouse movements, keyboard inputs, or other activities. The more entropy you generate, the more secure your key will be.

Key Pair Generated: Once the process is complete, your PGP key pair is generated. You will find the public key ID and fingerprints in the output. This information is important for sharing your public key and ensuring that others can verify it.

Export Your Public Key (Optional): You can export your public key to share it with others. Use the following command to export your public key to a file:
gpg --export -a "Your Name" > publickey.asc

Replace "Your Name" with your actual name. The file "publickey.asc" contains your public key.

It is also recommended to use the Windows software: https://www.gpg4win.de/. Further recommended instructions: https://riseup.net/de/security/message-security/openpgp/gpg-keys.

### Server Configuration

To make a website accessible under a .onion address, you must use the Tor network to create an onion service address for your website. Here are the steps you need to follow:

Install Tor: Make sure you have the Tor Browser or Tor Server installed on your web server. Information on installation can be found on the official Tor website (https://www.torproject.org/de/).

Configure Web Server: You need to configure your web server to respond to requests from Tor Hidden Services. In most cases, this is achieved with the Apache or Nginx web server.

Apache Configuration: In the Apache configuration file (usually under /etc/apache2/sites-available/ on Debian-based systems), you need to create a separate virtual host configuration for your .onion address. This could look something like this:
    <VirtualHost *:80>
      ServerName youronionaddress.onion
      DocumentRoot /var/www/yourwebsite
    </VirtualHost>

Nginx Configuration: With Nginx, you can create a similar configuration:
    server {
      listen 80;
      server_name youronionaddress.onion;
      root /var/www/yourwebsite;
    }

Tor Configuration: Configure Tor to provide your website as a Hidden Service. You need to create or edit a torrc configuration file, usually under /etc/tor/.
Add the following lines:
    HiddenServiceDir /var/lib/tor/youronionaddress/
    HiddenServicePort 80 127.0.0.1:80

Replace youronionaddress with the desired name for your .onion address.

Restart Tor: Restart the Tor service to apply the configuration.
    sudo service tor restart

Retrieve Hidden Service Address: After restarting Tor, you can find the .onion address in the file /var/lib/tor/youronionaddress/hostname. This address is your .onion address, under which your website is accessible.

Testing: Verify that your website is accessible via the .onion address by accessing the address in the Tor Browser or via the Tor network.
