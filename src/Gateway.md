
# Gateway

Cloudflare Gateway is a modern next generation firewall between your user, device or network and the public Internet. Once you setup Cloudflare Gateway, Gateway’s DNS filtering service will inspect all Internet bound DNS queries, log them and apply corresponding policies.

## WARP client
Cloudflare Zero Trust customers can use the Cloudflare WARP application to connect corporate desktops to Cloudflare Gateway for advanced web filtering. The Gateway features rely on the same performance and security benefits of the underlying WARP technology, with security filtering available to the connection.

>
A secure path to the Internet.
- Secure your global users without network complexity and latency
- Get complete visibility into Internet traffic
- Data stays internal across every environment
- Protects users as they connect to the rest of the Internet. Instead of back hauling traffic to a centralized location, users connect to a nearby Cloudflare data center where we apply one or more layers of security, filtering, and logging, before accelerating their traffic to its final destination.

## What is a secure web gateway (SWG)
A secure web gateway (SWG) is a cyber security product that protects company data and enforces security policies. SWGs operate in between company employees and the Internet. Like a water filter, which removes dangerous impurities from water so that it is safe to drink, SWGs filter unsafe content from web traffic to stop cyber threats and data breaches. They also block risky or unauthorized user behavior.
All SWG products contain these technologies:

- URL filtering
- Anti-malware detection and blocking
- Application control
- What is URL filtering

### URL Filtering

URL filtering restricts what web content users can access. It does this by blocking certain URLs from loading. Companies implement URL filtering to help prevent employees from using company resources — devices, network bandwidth, etc. — in a way that negatively impacts the company. URL filtering also helps mitigate malware and phishing attacks by blocking malicious webpages. Secure web gateways often include a URL filtering feature.

URL filtering bases its filtering policies on a database that classifies URLs by topic and by "blocked" or "allowed" status. Typically a company will not develop this database internally, relying instead on the vendor providing the filtering service. However, most vendors enable companies to customize which URLs are blocked or allowed.

URL filtering can block individual URLs or categories of URLs. By blocking individual URLs, companies can block specific webpages that are known to be dangerous or inappropriate. Meanwhile blocking URL categories allows companies to more efficiently restrict the type of content accessed over their networks by blocking large groups of URLs at once instead of having to list hundreds of individual URLs.

Typically the URL filtering vendor will create the categories and fill them out with groups of URLs that are all related to the same topic or are considered objectionable for similar reasons. For instance, all known URLs used for phishing attacks could be tracked in one "phishing" category, and a company could block all these webpages by using that category. Categorization can be an automatic process: some URL filtering services can use machine learning to identify websites that fit a particular category.

URL filtering takes place at the application layer of the Internet (see What is the OSI model?). The web protocols most frequently used at this layer are HTTP, FTP, and SMTP. The URL filter examines requests that use these protocols, and if they are directed at a blocked URL, it filters out the request and directs the device that the request originated from to a block page.

How does URL filtering help block malware and phishing attacks?
Several types of cyber attacks require users to load one or more webpages in order to be successful. Some cyber attackers aim to trick users into loading a malicious webpage that initiates a malware download. If these malicious webpages are identified as dangerous, URL filtering can block them, preventing this type of attack.

Other cyber attackers attempt to steal user accounts via phishing attacks: tricking users into giving away their login credentials or active session. Many phishing attacks ask users to load fake websites that appear legitimate, where the users then are prompted to enter their credentials, thus giving them to the attacker. Known phishing websites can be filtered out using URL filtering, thwarting these types of attacks.

Cloudflare Gateway offers fast and highly effective DNS filtering, along with other technologies to keep internal employees secure. Cloudflare Gateway is part of the Cloudflare for Teams product suite, which provides internal company security.

