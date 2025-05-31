

# Footprinting and Reconnaissance

## What is Footprinting?

Footprinting is the process of collecting as much information as possible about a target network to identify ways to intrude into an organization's network system.

## Why Footprinting?

- Ensures all relevant information about the target is identified systematically and methodically.

- Critical for understanding the security posture of the target.

- Must be performed accurately and in a controlled manner to avoid missing key data.

## Uses of Footprinting

- **Know Security Posture:** Understand the complete security setup of the organization.

- **Reduce Attack Area:** Narrow down the attack scope to specific IP ranges, networks, domains, remote access points, etc.

- **Build Information Database:** Compile a database of the target’s security weaknesses.

- **Draw Network Map:** Outline the target’s network infrastructure to understand the environment.

## What is Done in Footprinting?

- Collect basic information about the target and its network.

- Determine **operating systems, platforms, web server versions.**

- Use techniques like **Whois, DNS queries, organizational queries**.

- Identify vulnerabilities and exploits for launching attacks.

## Terminology

- **Open Source or Passive Information Gathering:** Collecting data from publicly accessible sources.

- **Active Information Gathering:** Gathering information via social engineering, on-site visits, interviews, questionnaires.

## Information to Collect

## Network Information

                                

- Domain names

- Network blocks

- Reachable system IP addresses

- Rogue/private websites

- TCP/UDP services running

- Intrusion Detection Systems (IDS)

## System Information

- User and group names

- System banners

- Routing tables

- System architecture

- Remote system types

- System names

## Organization Information

- Employee details

- Organization website

- Location details

- Address and phone numbers

- Comments in HTML source code

- Security policies

- Background information

## How to Perform Footprinting?

- Through search engines

- Social networking sites

- Official websites

- Direct communication with the target

- Job portals

## Importance of Footprinting

Skipping footprinting can lead to failure in attacks due to lack of critical information, such as:

- Missing authentication details (e.g., victim’s date of birth).

- Incorrect assumptions about the target (e.g., wrong bank for phishing).





## Footprinting Using Search Engines

- Search engines are primary sources for extracting technology platforms, employee data, login pages, intranet portals, and contact information.

- Results include web pages, videos, images, and files classified by relevance.

## Advanced Google Hacking Techniques

Common Google search operators used for footprinting:

- `[intitle:]` — Search term in the title.

- `[allinurl:]` — All keywords in URL.

- `[inurl:]` — Keywords in URL.

- `[location:]` — Search by location.

- `[info:]` — Information Google has about a webpage.

- `[site:]` — Restrict to specific domain.

- `[allintitle:]` — All search terms in title.

## Other Reconnaissance Techniques

- Google Advanced Search and Image Search for detailed information.

- Reverse image search tools: Google Image Search, TinEye, Yahoo Image Search.

- Video search engines (YouTube, Google Videos) to extract hidden info from videos.

- Video analysis tools: YouTube DataViewer, EZGif.

## Harvesting Email Lists

- Email addresses are crucial for social engineering and brute force attacks.

- Tools like **theHarvester** and **Email Spider** extract email addresses using search engines.

- Example command: `theharvester -d example.com -l 200 -b baidu`

<img src="file:///C:/Users/nihar/AppData/Roaming/marktext/images/2025-05-31-12-49-53-image.png" title="" alt="" width="524">-53-image.png" title="" alt="" width="524">



## Deep and Dark Web Footprinting

- Use Tor Browser, ExoneraTor, OnionLand Search engine to gather sensitive personal information.

- **Deep Web:** Hidden and unindexed web pages accessed via special browsers.

- **Darknet:** Subset of deep web allowing anonymous browsing.

- Tools for access: TOR Browser, Freenet, GNUnet, I2P.

## Extracting Website Information

- Use Internet Archive Wayback Machine (archive.org) to explore archived versions of websites.

- Retrieve deleted or old content useful for phishing and web application attacks.

## Traceroute

- Finds the path packets take to reach the target host.

- Useful to analyze network routes and identify potential man-in-the-middle attack points.

- Tools: Path Analyzer Pro, VisualRoute, Traceroute NG, PingPlotter.

- Installation example: `sudo apt-get install traceroute`

![](C:\Users\nihar\AppData\Roaming\marktext\images\2025-05-31-12-51-11-image.png)

***Useful Commands :***

 theharvester -d floorcafe.com -l 200 -b baidu          - search the mail ids available in baidu search engine

sudo apt-get install traceroute
