# Be Keeper – More Than Just Another Parental Control System

**Empowering parents and children to manage screen time effectively while ensuring online safety.**

Be Keeper was created out of a need for a reliable parental control system that prioritizes children's safety and promotes healthy internet usage **without** resorting to intrusive surveillance. It provides parents with the tools to guide their children's digital habits while respecting their privacy.

![hmi_screen](https://github.com/user-attachments/assets/c41c3b39-443a-402a-b03e-d7de2b639a31)

## Main Features:

* **Intuitive Hardware:** An external touchscreen interface built with an Android based ESP32 HMI, Arduino, and C#, ensuring a user friendly experience.
* **Seamless Connectivity:** Connects to the computer via USB, with automatic port detection and simplified setup.
* **Activity Based Time Management:** Kids shall select from predefined categories such as "Educational," "Homework," or "Playing," each with time limits set by parents.
* **Advanced Monitoring:** The application continuously tracks running apps, active windows, and browsing history, using the Google API to analyze YouTube content for age appropriateness.
* **Proactive Alerts:** Parents receive Telegram notifications for inappropriate usage or when daily time limits are reached.
* **AI Powered Insights:** Uses the OpenAI API to analyze real time usage and logs, preventing inappropriate content while efficiently summarizing links, app names, chats, and searches reducing false alarms and saving parents time.
* **Comprehensive Reporting:** A detailed daily report provides an overview of the child's online activity.
* **Child Friendly Reminders:** A two minute warning before time limits expire allows kids to save their work and transition smoothly.
* **Tamper Proof Design:** Regular data backups and immediate computer lockdown with parental alerts if the HMI is disconnected. 
* **Privacy Focused:** Be Keeper is AV friendly and does not log keystrokes, ensuring privacy while providing essential parental controls.

This comprehensive solution integrates intuitive hardware with powerful software to foster healthy digital habits while giving children a sense of agency in a safe and secure online environment.

## Future Enhancements:

Exciting new features are already in development for the next version of Be Keeper! Here's a preview:

* **AI Powered Content Filtering:** The current version sends parents only unique website and video names. In the next version, AI will analyze YouTube and browsing history, flagging only inappropriate content to minimize unnecessary notifications.
* **Daily Summary & Statistics:** Receive a concise daily overview of your child's computer usage, including time spent on different activities, websites visited, and apps used. This will provide valuable insights into their digital habits and help parents make informed screen time decisions.
* **Blacklist/Whitelist Functionality:** Create custom lists of allowed or blocked applications, YouTube videos, and websites for greater control over your child's online experience.

I encourage all followers to share their ideas and suggestions. Your feedback is invaluable in shaping the future of Be Keeper!

---

## Special Thanks:

* To my wonderful kids, your increased computer activity during the long holiday motivated me to design and implement this system quickly. Extended breaks can make it especially challenging to balance screen time with other activities. You not only inspired this solution but also helped me understand the importance of creating a tool that promotes responsible technology use while providing peace of mind. 😊

---

## Software & Development Tools:

* **Programming Languages:** C#, Arduino IDE, Visual Studio (VisualMicro)
* **GUI Design:** SquareLine Studio
* **Hardware:** ESP32-S3 Elecrow 5" touchscreen
* **Software Frameworks/Libraries:** Android (for the HMI)
* **Data Format:** JSON
* **External APIs:** Google API (YouTube analysis), OpenAI API (data analysis & real time usage monitoring), Telegram API (notifications & remote control)
