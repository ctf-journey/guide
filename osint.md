---
Title: OSINT
Tags: ["guide"]
Image : ""
Description: "guess the flag"
Draft: 
---

## Introduction

## Related Tools
- Social Media
  - Sherlock [GitHub](https://github.com/sherlock-project/sherlock)
    - `python3 sherlock [username]`
  - OSINT telegram bot <https://t.me/UniversalSearchBot> 
    - to search by: Email, Image, Phone, Location, Telegram ID, Domain, VK ID, IP Address
    - To find: GAIA ID, Activity on google services (map reviews, calendar, google+, etc.), Instagram, Myspace, Leaks
- Reverse Search
  - Search engines (Using dorks) [Google](https://www.google.com) [Bing](https://www.bing.com/)
    - you can use any search engines of your choice
  - tineye, a reverse image search engine ([Website](https://tineye.com/))
  - [Google Images](https://images.google.com), [Google Lens](https://lens.google.com)
  - [The Wayback Machine](https://archive.org/)
- Personal Details
  - epieos, osint tool for email and phone number ([Website](https://epieos.com/))
  - theHarvester ([Kali docs](https://www.kali.org/tools/theharvester/)) ([github](https://github.com/laramies/theHarvester))
  - Guerillamail (create throwaway emails to send & recieve) <www.guerrillamail.com> (as of 4 Jan, the website is unsecure)
- Framework
  - [OSINT framework](https://osintframework.com/)
  - [Shodan](https://shodan.io)

## Key Concepts
- when given USERNAME, run through sherlock/google to find websites where the username turns up. consider `inurl:`
- when given EMAIL
  - consider sending an email to the address (with throwaway email) because there might be an automated reply (thanks josh)
  - consider running it through a reverse email checker (I haven't found one that works) or obtaining the GAIA ID to check for google activity

## .