# ARMoredScraper
Stealthy pentesting and web scraping toolkit built on ARM64 Ubuntu. Custom Playwright setup, automation, troubleshooting, and real estate data collection
````markdown name=README.md
# Zach - Beginner Pentesting & Web Scraping Enthusiast

A few months ago I got into automation, so I made a Stripe app that automatically documents every swipe into an Excel format. But for me, I got bored of trying to better it, so after going down a few rabbit holes I fell in love with pentesting and web scraping. I became so obsessed that I spent hours trying to download RustDesk on my computer while running Windows 11, just so I could work on these things from my phone whenever I was at work on break, a passenger in the car, and so on. Eventually, I found out that, with my passion, it would be better to download Ubuntu.

I love what I'm doing so much that no matter how hard it got to download offensive penetration tools on my Lenovo ThinkPad X13s with ARM64 Snapdragon processor, I was able to find workarounds to get the tools I need. For example, I’m running Ubuntu 24.04 and tried to download Playwright, but it didn’t work at first because it only supports the libicu74 library, while my system has version 76. There were no tutorials or clear guides on how to fix this, and even with perfect AI prompts, it wasn’t straightforward. So I had to deep dive, do a lot of research, and eventually figured out that creating symbolic links from the version 76 libraries to the expected version 74 filenames would solve the problem. That’s how I got it working perfectly.

---

## About Me

**Current Focus:** Penetration Testing (Pentesting) & Web Scraping  
**Experience Level:** Beginner / Self-Learner  
**Interests:** Cybersecurity, Automation, Data Collection, Stealth Techniques  
**Learning Goals:**
- Master advanced web scraping frameworks (Playwright, Puppeteer)
- Build stealthy, scalable scrapers with proxy and fingerprint rotation
- Develop hands-on penetration testing skills using Kali Linux and other tools
- Understand anti-bot evasion and CAPTCHAs
- Contribute to open-source security and scraping projects

---

## Technical Skills

| Skill                  | Level         |
|------------------------|--------------|
| Python                 | Beginner     |
| JavaScript / Node.js   | Beginner     |
| Playwright / Puppeteer | Beginner     |
| Linux Command Line     | Intermediate |
| Proxy Management       | Learning     |
| CAPTCHAs & Stealth     | Learning     |
| VS Code                | Comfortable  |

---

## Projects

### ARM64 Playwright Web Scraping Setup
- Built a fully working Playwright environment on an ARM64 Lenovo ThinkPad running Ubuntu 24.04.
- Solved complex library dependency issues (`libicu` symlinks) to enable browser automation.
- Integrated `playwright-extra` with stealth plugins for anti-bot evasion.
- Developed scripts simulating human-like browsing behavior (random mouse movement, keyboard input, delays).
- Configured Node.js and Python environments side-by-side for flexible development.

### Penetration Testing Exploration
- Setting up Kali Linux and related pentesting tools on ARM64 architecture.
- Learning network scanning, vulnerability assessment, and ethical hacking.

---

## Lessons Learned

I've learned that the more I know, the more I realize what I don't know. Working in this field has shown me how important it is to really dive deep into everything I'm downloading and to understand what every little command does. Creating bots that act like humans is a necessity—being in this field requires constant learning and adaptation.

I've discovered the importance of documenting every failure and always finding the root cause of an issue. Sometimes, I have to physically write things down on paper and really dive into things I don't understand to truly grasp them. This process of note-taking and hands-on exploration has been essential to my progress.

---

## Screenshots: Today's Troubleshooting & Progress

Below are screenshots documenting my workflow and the issues I overcame:

**1. Diagnostic Python Script for Troubleshooting Playwright/Dependencies**  
![image1](image1)

**2. Playwright Stealth Scraper Script & Project Organization**  
![image2](image2)

**3. Module Path Error While Running Scraper (Troubleshooting in Action)**  
![image3](image3)

**4. Minimal Playwright Test Script for Isolating/Fixing Setup**  
![image4](image4)

These images show the real process of diagnosing, debugging, and validating my Playwright and scraping setups on ARM64 Ubuntu, as described above.

---

## Next Project: Stealth Real Estate Data Collection System

One thing I’ve learned on this journey: **there are no tutorials for doing what I did with my ARM64 setup, Playwright, and stealth automation tools.** Every step required hands-on experimentation, deep research, and custom solutions.

### Project Objectives

- **Discover Underserved or High-Margin Local Real Estate Opportunities**
    - Identify properties or markets that are overlooked or have strong profit potential.

- **Build Valuable Datasets for Resale or Clients**
    - Collect and structure data such as price trends, “second chance” property seeker signals, and other actionable market indicators.

- **Feed Downstream Tools and Services**
    - Integrate the data pipeline with:
        - Real-time alerts for market changes
        - Competitor monitoring dashboards
        - Localized scraping services for clients and internal use

### Why This Project?

- Tutorials simply don’t exist for building a stealth, scalable real estate data collection system on ARM64/Ubuntu with advanced anti-bot evasion.
- Real estate is rich with hidden opportunities that can be uncovered through creative automation and data analysis.
- Building a robust, stealthy system will push my skills further and open up real opportunities for offering valuable data services.

---


- Feedback and mentorship from experienced pentesters and web scraping devs.
- Collaborative opportunities to build real-world automation and security projects.
- Resources and tutorials focused on stealth scraping and advanced pentesting on ARM64 platforms.
````
