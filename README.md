> [!IMPORTANT]
> **⚠️ ACTIVE DEVELOPMENT HAS MOVED TO CHOREOPS**
>
> `KidsChores` has officially evolved into a new, expanded integration called **[ChoreOps](https://github.com/ccpk1/choreops)**.
> 
> Based on incredible feedback from this community, the backend has been completely re-architected to Home Assistant Platinum standards to support *everyone* in the household (not just kids!), along with an entirely new "Over-The-Air" dashboard system.
> 
> **Please migrate to ChoreOps to access all new features and continued support.**
> Upgrading is safe and easy: ChoreOps includes a built-in migration tool and runs safely in parallel with KidsChores. You can set it up, migrate your data, and ensure you are completely happy before removing your old configuration.
> 
> 👉 **[Get started with ChoreOps here!](https://github.com/ccpk1/choreops)**

---

[![HACS Custom](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/custom-components/hacs)
![GitHub Release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/ad-ha/kidschores-ha?include_prereleases)
![GitHub Downloads (all assets, latest release)](https://img.shields.io/github/downloads/ad-ha/kidschores-ha/latest/total)

[![GitHub Actions](https://github.com/ad-ha/kidschores-ha/actions/workflows/validate.yaml/badge.svg)](https://github.com/ad-ha/kidschores-ha/actions/workflows/validate.yaml)
[![Hassfest](https://github.com/ad-ha/kidschores-ha/actions/workflows/hassfest.yaml/badge.svg)](https://github.com/ad-ha/kidschores-ha/actions/workflows/hassfest.yaml)

<h1>KidsChores</h1>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e95bdb54-2c4c-4a84-96b4-f47a46a1228a" alt="KidsChores logo" width="300">
</p>
<p align="center">
  <a href="https://buymeacoffee.com/varetas3d" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174">
  </a>
</p>
<p>
  <br>
  <br>
</p>

# 🏆 KidsChores: The Ultimate Home Assistant Chore & Reward System

**The easiest-to-use and most feature-rich chore management system for Home Assistant.**
Get up and running in **10 minutes or less**, with **unmatched capabilities** to gamify the process and keep kids engaged!

✅ **Track chores effortlessly** – Assign chores, set due dates, and track completions.

✅ **Gamify the experience** – **Badges, Achievements, and Challenges** keep kids motivated.

✅ **Bonuses & Penalties** – Reward extra effort and enforce accountability.

✅ **Customizable Rewards** – Give coins, stars, points, or any currency system you choose.

✅ **Built-in User Access Control** – Restricts actions based on roles (kids, parents, admins).

✅ **Smart Notifications** – Notify kids and parents; parents can approve chores & rewards from their phone or watch.

✅ **Calendar Integration & Custom Scheduling** – Automatically manage recurring chores and sync with Home Assistant’s calendar.

✅ **Works Offline & Keeps Data Local** – Everything is processed locally for **privacy & security**.
<br><br>
**"Designed for kids, but flexible for the whole family—assign chores to anyone, from toddlers to teens to adults!"**

📖 **[System Overviews, FAQ's, Tips & Tricks, and Usage Examples in the Wiki →](https://github.com/ad-ha/kidschores-ha/wiki)**

---

## ⚡ Quick Installation

📌 **Via HACS (Recommended)**

1. Ensure **HACS** is installed. ([HACS Setup Guide](https://hacs.xyz/docs/installation/manual))
2. In Home Assistant, go to **HACS > Custom Repositories**.
3. Add `https://github.com/ad-ha/kidschores-ha` as an **Integration**.
4. Search for **KidsChores**, install, and **restart Home Assistant**.

📖 **[Full Setup & Configuration Guide →](https://github.com/ad-ha/kidschores-ha/wiki/Installation-&-Setup)**

---

## 🌟 Key Features

### 👧👦 Multi-User Management

- **Profile Creation & Customization:**

  - Create and manage individual profiles for multiple kids and parents.
  - Track each child’s progress, achievements, and performance with ease.

- **Effortless Management:**
  - Handle multiple kids with a single integration while monitoring individual statistics and trends.
  - **Built-in Access Control** (Restrict actions based on user roles to prevent unauthorized changes). **[Learn More →](https://github.com/ad-ha/kidschores-ha/wiki/Access-Control:-Overview-&-Best-Practices)**
 
  ---

### ⭐ **Customizable Points System**

- Personalize the points system by choosing your own name and icon (e.g., Stars, Bucks, Coins) to better resonate with your family.

  ---

### 🧹 **Chore Management**

- **Assign & Track Chores:**

  - Easily define chores with descriptions, icons, due dates, and customizable recurring schedules.  **[Learn More →](https://github.com/ad-ha/kidschores-ha/wiki/Chore-Status-and-Recurrence-Handling)**
  - Supports **individual chores** (assigned to a single kid) and **shared chores** (requiring participation from multiple kids).
  - **Labels** can be used to **group chores** by type, location, or difficulty—or to **exclude specific chores** based on your family's needs.

- **Smart Notifications & Workflow Approvals:**

  - Parents and kids receive **dynamic notifications** for **chore claims, approvals, and overdue tasks**.
  - Notifications are **actionable** on **phones, tablets, and smartwatches**, allowing parents to **approve or reject** tasks with a single tap.
  - **Customizable reminders** help ensure chores stay on track and are completed on time.

- **Dynamic Chore States & Actions:**
  - Leverage dynamic buttons to claim, approve, or disapprove chores—completion with built-in authorization and contextual notifications.
  - Monitor progress with sensors that update on a per-kid and global level.
 
  ---

### 🎁 **Reward System**

- Rewards help **motivate kids** by offering incentives they want while reinforcing responsibility. Parents can **create a list of rewards**, assign a **point cost**, and let kids claim them when they have enough points.

- **Customizable & Goal-Oriented:**

  - Add rewards tailored to your kid’s interests (e.g., extra screen time, a special outing).
  - Assign point values to **encourage saving** and **set goals**.

- **Seamless Claim & Workflow Approval Process:**
  - Kids can **claim rewards** when they meet the point requirement.
  - Parents receive an **approval notification**; once approved, **points are automatically deducted**, and the parent is responsible for delivering the reward.
 
  ---

### 🏅 **Badge System**

- Badges reward **milestone achievements** and encourage consistency by tracking progress over time.  **[Learn More →](https://github.com/ad-ha/kidschores-ha/wiki/Badges:-Overview-&-Examples)**

- **Earned Through Chores & Points:**

  - Kids can unlock badges by **completing chores** or **earning points** (e.g., 100 chores or 100 points).
  - Badge progress is **tracked from the start**, so kids receive credit for past achievements.

- **Multipliers & Tracking:**
  - Badges can apply a **points multiplier** to boost future earnings (e.g., 1.5x points per chore).
  - Tracks each kid’s **highest badge earned** and **full badge history**.
 
  ---

### ⚖️ **Bonuses & Penalties**

- Bonuses and penalties allow parents to **reinforce positive behavior** and **correct missteps** by adjusting points dynamically.  **[Learn More →](https://github.com/ad-ha/kidschores-ha/wiki/Bonuses-&-Penalties:-Overview-&-Examples)**

- **Bonuses: Reward Extra Effort**

  - Award **extra points** for exceptional behavior, teamwork, or going above expectations.
  - Can be applied manually or automatically through the system, with **custom labels and tracking**.

- **Penalties: Encourage Accountability**
  - Deduct points for missed chores or rule-breaking to **reinforce responsibility**.
  - Easily track applied penalties and ensure fair, transparent adjustments.
 
  ---

### 🏆 **Challenges & Achievements**

- Challenges and achievements **motivate kids with structured goals**, rewarding consistency beyond daily chore completions.  **[Learn More →](https://github.com/ad-ha/kidschores-ha/wiki/Challenges-&-Achievements:-Overview-&-Functionality)**

- **Achievements: Personal Milestones**

  - Earned by **completing a set number of chores** or **maintaining streaks** over time (e.g., 100 total chores, 30-day streak).
  - Tracks individual progress and provides **long-term motivation**.

- **Challenges: Time-Bound Goals**
  - Require kids to **complete specific tasks within a set timeframe** (e.g., 50 chores in a month).
  - Can be **individual or shared**, encouraging teamwork toward a common goal.

  ---

### 📅 **Calendar Integration**

- KidsChores integrates with **Home Assistant’s calendar**, allowing chores and challenges to displayed alongside other household events.

- **Sync Chores to Calendar:**

  - View **due dates** for individual and shared chores directly in the Home Assistant calendar.
  - Helps parents and kids **plan ahead** and stay organized.

- **Track Challenges & Time-Sensitive Goals:**
  - Challenges with set timeframes (e.g., "Complete 50 chores in a month") appear in the calendar for **easy progress tracking**.
  - Provides a **visual timeline** of ongoing and upcoming challenges.

  ---

### 📊 **Detailed Statistics & Advanced Controls**

- KidsChores provides **comprehensive tracking** through **real-time sensors and interactive buttons**, giving parents full insight into chore activity and progress.

- **Comprehensive Sensors & Data Tracking:**

  - Monitor **daily, weekly, and monthly stats** on chore completions, points earned, rewards redeemed, badges awarded, and penalties applied.
  - Analyze **historical trends** to celebrate progress, adjust incentives, and identify areas for improvement.

- **Interactive Controls & Automation:**

  - Use dynamic buttons for **claiming chores, approving rewards, and applying bonuses or penalties** directly from the UI.
  - Seamlessly integrate with Home Assistant automations for **custom alerts, reports, and dashboard insights**.

- 📖 **[View the Full List of Sensors & Actions →](https://github.com/ad-ha/kidschores-ha/wiki/Sensors-&-Buttons)**

  ---

### 🛠 Customization & User-Friendly Interface

- **🛠 Dynamic Buttons & Actions:**

  - Manage chores and points directly from the Home Assistant UI with buttons for claiming, approving, redeeming, and adjusting points.

- **🌐 Multilingual Support:**

  - Currently available in English and Spanish to cater to a diverse user base.

- **🔧 Easy Setup & Maintenance:**

  - KidsChores offers a **fully interactive Options Flow** with a **user-friendly setup wizard** and **comprehensive configuration menus**, allowing you to manage everything **directly from the Home Assistant UI**—**no YAML or coding required**. With an intuitive frontend interface, you can effortlessly configure:
    - **Points**
    - **Kids & Parents**
    - **Chores**
    - **Rewards**
    - **Badges**
    - **Penalties & Bonuses**
    - **Achievements & Challenges**

- **Organize with Home Assistant Labels:**
  - Use **labels** to categorize and manage chores, rewards, penalties, badges, and challenges—making it easier to filter, group, or exclude specific tasks based on your needs.
 
---

### ⚙️ Make KidsChores Your Own

---

- If that's still not enough for you—**this is Home Assistant!** With a little customization, you can make KidsChores work exactly how you want.  

  📅 **Want to set schedules from your Google Calendar?**  
  📲 **Want to claim chores using NFC tags?**  
  ✅ **Want to automatically approve specific chores?**  
  ⏳ **Want to automatically apply a penalty or a custom alert when a chore goes overdue?**  
  
  The **[Tips & Tricks](https://github.com/ad-ha/kidschores-ha/wiki/Tips-&-Tricks)** section of the Wiki is packed with ideas to help you **customize, automate, and extend** KidsChores to fit your family's needs.  

---

## 🔐 **Security & Privacy**

🔹 **100% Local & Private** – Your data stays on your Home Assistant instance, ensuring complete privacy.

🔹 **No External Data Sharing** – No cloud services, no third-party access—everything runs securely on your local network.

🔹 **Built-in User Access Control** – Restrict actions based on roles to prevent unauthorized changes.

With **KidsChores**, your family’s information remains private, secure, and fully under your control.

---

## 🤝 Join the Community & Contribute

🚀 **Get Help & Share Ideas**

- 💬 **Join Community Discussions** → [Home Assistant Forum](https://community.home-assistant.io/t/kidschores-family-chore-management-integration)
- 🛠️ **Report Issues & Request Features** → [GitHub Issues](https://github.com/ad-ha/kidschores-ha/issues)

👨‍💻 **Want to contribute?**

- Submit a **pull request**: [GitHub Contributions](https://github.com/ad-ha/kidschores-ha/pulls).
- Help with **translations** and **documentation updates**.

---

KidsChores makes managing chores effortless, engaging, and rewarding for the whole family. With built-in gamification, smart automation, and flexible tracking, it turns daily routines into a fun and structured experience.

Whether you want to **encourage responsibility**, **motivate with rewards**, or simply **streamline household tasks**, KidsChores has you covered.

**Get started today and transform how your family manages chores, rewards, and accountability!**

---

## LICENSE

This project is licensed under the [GPL-3.0 license](LICENSE). See the LICENSE file for details.

---

## DISCLAIMER

THIS PROJECT IS NOT AFFILIATED WITH OR ENDORSED BY ANY OFFICIAL ENTITY. The information provided is for educational purposes only, and the developers assume no legal responsibility for the functionality or security of your devices.
