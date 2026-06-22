<a name="readme-top"></a>

<div align="center">

<img src="./docs/media/usb-wordmark-light.png#gh-light-mode-only" style="max-width: 320px; width: 100%;" alt="USB - University Schedule Builder">
<img src="./docs/media/usb-wordmark-dark.png#gh-dark-mode-only" style="max-width: 320px; width: 100%;" alt="USB - University Schedule Builder">

### 🛠️ Build Your Academic Schedule with Absolute Ease!

[![Stars](https://img.shields.io/github/stars/University-Schedule-Builder/USB-Extension?style=for-the-badge&labelColor=1a1a1a&color=3B82F6)](https://github.com/University-Schedule-Builder/USB-Extension/stargazers)
[![Issues](https://img.shields.io/github/issues/University-Schedule-Builder/USB-Extension?style=for-the-badge&labelColor=1a1a1a&color=3B82F6)](https://github.com/University-Schedule-Builder/USB-Extension/issues)
[![Firefox Add-on](https://img.shields.io/amo/v/usb-university-schedulebuilder?style=for-the-badge&labelColor=1a1a1a&color=3B82F6&label=firefox)](https://addons.mozilla.org/en-US/firefox/addon/usb-university-schedulebuilder/)
[![Telegram](https://img.shields.io/badge/Telegram-Join-26A5E4?style=for-the-badge&logo=telegram&logoColor=white&labelColor=1a1a1a)](https://t.me/addlist/f0wphxX8nG43MWM0)

<br/>

[Why USB?](#why-usb) &middot; [Key Features](#key-features) &middot; [Screenshots](#screenshots) &middot; [Privacy & Security](#privacy--security) &middot; [Installation Guide](#installation-guide) &middot; [FAQ](#faq) &middot; [Support & Contact](#support--contact) &middot; [العربية](./README.md)

</div>

<br/>

> [!IMPORTANT]
> **Digital Transparency Statement:** The USB project is a 100% independent and unofficial student initiative. Developed by a student from Al-Mustaqbal University in the Al-Qassim region, the system aims to streamline academic processes and enhance the schedule registration experience for both male and female students. The system **is not** affiliated with nor supervised by Al-Mustaqbal University. This repository is strictly for documentation and guides; the extension's source code is currently private. Builds are distributed through official browser stores, and signed `.zip` releases will be published on the [Releases page][releases] once available.

> [!WARNING]
> **Critical Security Warning:** The USB project does not host any official channels on Discord. The **only** officially approved platforms are the Telegram community and the [GitHub Issues][issues] section. If you encounter any entity or account requesting money or your academic portal (Self-Service) passwords under the name of USB, please ignore and report them immediately. We never request such sensitive data.

<details>
<summary><kbd>Table of Contents (Navigation)</kbd></summary>

<br/>

- [Why USB?](#why-usb)
- [Key Features](#key-features)
- [Screenshots](#screenshots)
- [Privacy & Security](#privacy--security)
- [Installation Guide](#installation-guide)
- [FAQ](#faq)
- [Support & Contact](#support--contact)
- [Contributing](#contributing)
- [Disclaimer](#disclaimer)
- [License](#license)

</details>

<br/>

## Why USB?

The **USB (University Schedule Builder)** browser extension functions as a smart solution powered by flexible automation. The system directly processes your academic study plan alongside the course sections offered for the current term, transforming them into a comprehensive, interactive weekly calendar. This allows you to construct your schedule, test for time conflicts, and arrange your preferences beforehand.

* **Flexible Dual-Mode Access:** 
    * *Sync Mode:* Securely logs in through your browser to seamlessly scrape your active study plan and live offered sections.
    * *Free Mode:* Requires absolutely no login! Simply select your major (Engineering, Computer Science, Software Engineering... etc.) and start building your schedule immediately.
* **Early Conflict Detection Algorithm:** Instantly detects overlapping times between chosen sections before you even attempt to register on the university website.
* **Smart Prerequisite Analyzer:** Automatically turns a course card red if it requires a prerequisite that you haven't passed yet, alerting you with the exact name of the missing course.
* **Automated Elective Management:** Elective slots within the plan are uniquely structured to be interactive and clickable; opening a curated list of courses mapped to the correct elective group without any confusion.
* **Secure Local Storage Environment:** The system operates entirely within your own local browser. Your data is never uploaded, and we do not host intermediate servers—your configuration stays completely on your device.
* **Comprehensive Presets System:** Save multiple drafts and variants of your schedule (e.g., Morning Schedule, No-Thursday Schedule) to compare setups and select your ideal layout.
* **Full Bilingual & Layout Support:** A highly optimized user interface that natively supports Arabic and English (RTL / LTR) with fluid performance, free of layout shifts during loading.

<p align="right"><a href="#readme-top">&#9650; back to top</a></p>

## Key Features

<table>
<tr>
<td width="33%" valign="top">

**🗂️ Study Plan Structuring**

Sync Mode fetches your official study plan directly from the portal. Free Mode allows you to build schedules account-free; just pick your major and department to begin.

</td>
<td width="33%" valign="top">

**⚡ Early Issue Catching**

An intelligent validation layer prevents and flags overlapping class times, alongside real-time prerequisite checks to verify registration eligibility.

</td>
<td width="33%" valign="top">

**🎨 Flexible Personalization**

Tailor your viewing experience, save multiple named drafts, and export your final layout as a high-quality PNG image or a formatted text summary for sharing.

</td>
</tr>
</table>

| Component / Feature | Technical & Functional Description |
|---|---|
| **Sync Mode** | Integrates with the student academic portal to retrieve the user's specific plan (passed/remaining courses) and live term sections, storing them securely on your local device. |
| **Free Mode** | Account-free execution. The system parses your major's plan from an embedded database while sourcing section timings from the university's public guest timetable. |
| **Interactive Weekly Calendar** | An advanced view rendering flexible time blocks: Morning Shift (08:00–15:00), Evening Shift (16:00–22:00), or Full Day. |
| **Toolbar Mini-Week (Popup)** | A quick, compact weekly strip accessible directly from the browser extension popup, displaying your current layout at a glance. |
| **Time-Conflict Prevention** | A timing safeguard that flashes an immediate alert if you attempt to add a section that overlaps with a previously selected course. |
| **Academic Prerequisite Monitor** | Highlights course cards in red when prerequisites are missing, offering an info button that breaks down pass/fail statuses per requirement. |
| **Elective Course Processor** | Automatically maps placeholder elective slots into interactive buttons, showing only the courses available to you within the proper department group. |
| **Level Completion Indicator** | Allows you in Free Mode to mark specific courses or entire academic tiers (e.g., Preparatory Year, Level 3) as completed to accurately update the plan. |
| **Draft Management (Presets)** | Saves various scheduling scenarios. The system automatically suggests smart names based on total credit hours, course count, and the current month. |
| **Backup System (Snapshot)** | Takes a static snapshot of active offered sections, ensuring your custom schedule survives even if the university portal encounters downtime. |
| **Automated Background Sync** | Triggers silent data syncs when opening the popup while on an active portal tab (throttled to once every 5 minutes to mitigate server stress). |
| **Silent Plan Versioning** | Periodically checks for study plan structural updates pushed by developers, with fallback mechanics for offline use. |
| **Persistent Design Ecosystem** | Fully localized interface supporting RTL standards with on-the-fly toggling to English, persisting your chosen theme and language preferences. |
| **Export & Share Toolset** | Extract your completed weekly schedule with a single click as a high-definition PNG image or a beautifully structured text string. |

<p align="right"><a href="#readme-top">&#9650; back to top</a></p>

## Screenshots

<table>
<tr>
<td width="50%" align="center">
<img src="./docs/media/calendar-sync.png" height="100%" width="100%"><br/>
<sub><b>Main Calendar View (Sync Mode)</b> &middot; Full schedule view after data ingestion, with integrated period toggles (Morning/Evening).</sub>
</td>
<td width="50%" align="center">
<img src="./docs/media/popup-week.png" height="75%" width="75%"><br/>
<sub><b>Extension Popup View</b> &middot; A quick and compact look at your academic week directly from the browser toolbar.</sub>
</td>
</tr>
<tr>
<td width="50%" align="center">
<img src="./docs/media/free-mode-setup.png" width="100%"><br/>
<sub><b>Free Mode Quick Configuration</b> &middot; Selection screen for majors and departments to generate the plan framework without authenticating.</sub>
</td>
<td width="50%" align="center">
<img src="./docs/media/conflict-warning.png" width="100%"><br/>
<sub><b>Time Conflict Flagging</b> &middot; A critical alert UI designed to block overlapping lecture hours and section schedules.</sub>
</td>
</tr>
<tr>
<td width="50%" align="center">
<img src="./docs/media/prereq-dialog.png" width="100%"><br/>
<sub><b>Prerequisite Analysis Overlay</b> &middot; Visually flags restricted courses in red with a breakdown of unfulfilled academic requirements.</sub>
</td>
<td width="50%" align="center">
<img src="./docs/media/elective-picker.png" width="100%"><br/>
<sub><b>Elective and General Course Picker</b> &middot; A smart popover interface built to ease choosing elective classes from approved university buckets.</sub>
</td>
</tr>
<tr>
<td width="50%" align="center">
<img src="./docs/media/presets-panel.png" width="100%"><br/>
<sub><b>Draft Panel Control (Presets)</b> &middot; Interface to save, retrieve, and automatically catalog multiple schedule drafts based on total credits.</sub>
</td>
<td width="50%" align="center">
<img src="./docs/media/settings-rtl.png" width="100%"><br/>
<sub><b>Global Settings Panel</b> &middot; Controls for language selection, visual themes, and forcing remote checks for study plan revisions.</sub>
</td>
</tr>
</table>

<p align="right"><a href="#readme-top">&#9650; back to top</a></p>

## Privacy & Security

* **Zero Telemetry or Analytics:** The USB extension does not track, collect, log, or transmit any analytical data regarding your academic choices or application usage to any external server.
* **Localized Session Integration:** In Sync Mode, communication with the university's official portal occurs exclusively through your active browser session. No data is proxied through an external backend, as the project does not utilize a centralized server.
* **Local Storage Principle:** Your academic plans, selected sections, draft variations, and interface preferences reside solely inside your browser's client-side Local Storage.
* **Anonymous Free Mode Routing:** Utilizing Free Mode ensures total anonymity. The utility functions flawlessly without needing your name, student ID, or any active university session tokens.
* **Credential Safety:** Please remember that protecting your authentication credentials remains your strict personal responsibility; our system architecture is programmatically built to never read or store your passwords.

<p align="right"><a href="#readme-top">&#9650; back to top</a></p>

## Installation Guide

| Target Web Browser | Availability & Download Status |
|---|---|
| **Mozilla Firefox** | Officially live on [addons.mozilla.org][firefox-amo] - search for the verified extension title or use the direct link. |
| **Google Chrome** | Currently undergoing standard technical and security review cycles on the Chrome Web Store. Live status notifications will be broadcasted on the [Telegram channel][telegram]. |
| **Standalone Manual Builds** | Cryptographically signed `.zip` archive packages for manual deployment will be supplied on the [Releases page][releases] upon stable builds. |

<p align="right"><a href="#readme-top">&#9650; back to top</a></p>

## FAQ

**Q: Does the USB system store or log my university portal password anywhere?**  
A: Absolutely not. Sync Mode operates entirely inside your own local browser environment using your existing active session. Your credentials are never transmitted to any destination, as USB is designed serverless.

**Q: Am I required to log in to my official portal to use USB?**  
A: No, it is not mandatory. You can use "Free Mode" out of the box. Just select your major and academic track to start structuring your classes. Note that Free Mode relies on the university's latest major plans and guest timetables; if your plan is older, use Sync Mode to pull your exact catalog from the portal.

**Q: Is the USB project officially endorsed by Al-Mustaqbal University?**  
A: No. This is an independent student-led open development created to help fellow peers navigate class registration easily. It is not an official branch of the university administration.

**Q: Why isn't the Google Chrome variant live yet?**  
A: The extension is currently pending approval from the official Chrome Web Store validation team. Keep an eye on the [Telegram channel][telegram] for instantaneous launch updates.

**Q: Where can I look at the source code codebase?**  
A: The core application logic is private and hosted outside this repository. This specific tracker is explicitly allocated for asset management, distribution documentation, technical support, and tracking issues.

<p align="right"><a href="#readme-top">&#9650; back to top</a></p>

## Support & Contact

* **[Telegram Channel & Community][telegram]** - Our primary verified platform for distribution announcements, system patches, and peer-to-peer troubleshooting among students using USB.
* **[GitHub Issues Tracking][issues]** - Allocated exclusively for submitting technical bug reports and structuring feature requests. When detailing a bug, please outline your browser engine, access mode (Sync/Free), and step-by-step reproduction instructions.

</div>

<br/>

> [!WARNING]
> We do not operate any servers or channels on Discord. Our development team will never reach out to you privately to ask for monetary fees or sensitive academic portal credentials. Beware of copycat or phishing accounts.

<p align="right"><a href="#readme-top">&#9650; back to top</a></p>

## Contributing

Because the application source files are private, direct codebase contributions are not accepted in this repository. However, you can significantly support the project's ecosystem by:

* **Analyzing & Isolating Bugs:** Logging technical anomalies you encounter by opening a ticket in the [GitHub Issues][issues] pipeline.
* **Architecting Feature Requests:** Pitching structural ideas and automation suggestions inside our [Telegram channel][telegram].
* **Community Guidance:** Assisting incoming freshmen and incoming students with configuring their calendar layouts inside the Telegram group.

<p align="right"><a href="#readme-top">&#9650; back to top</a></p>

## Disclaimer

</div>

<br/>

> [!IMPORTANT]
> **Legal Disclaimer:** The USB project is a completely independent, unofficial student initiative. It holds no corporate affiliation with, endorsement from, or operation by Al-Mustaqbal University. Sync Mode reads portal metrics purely within your local browser ecosystem under your own active session permissions; USB does not maintain backend servers capable of caching or transmitting credential keys or roster setups. Users retain full liability for using this tool in accordance with university data policies and for validating the accuracy of their academic registration decisions. Always audit and verify your definitive schedule inside the university's official portal.

<p align="right"><a href="#readme-top">&#9650; back to top</a></p>

## License

</div>

<br/>

> [!NOTE]
> **License Status:** The definitive open-source or distribution license for this codebase has not been formally finalized. A standard `LICENSE` file will be initialized here as soon as a legal framework is chosen.

<br/>

<div align="center">

<img src="./docs/media/usb-mark.svg" width="48" alt="">
<br/><br/>
<sub>Built with love ☕ to help every student navigate the semester registration rush. <a href="#readme-top">&#9650; back to top</a></sub>

</div>

<!-- Hyperlinks References -->
[releases]: https://github.com/University-Schedule-Builder/USB-Extension/releases
[issues]: https://github.com/University-Schedule-Builder/USB-Extension/issues
[telegram]: https://t.me/addlist/f0wphxX8nG43MWM0
[firefox-amo]: https://addons.mozilla.org/en-US/firefox/addon/usb-university-schedulebuilder/