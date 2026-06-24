# Real Open Source Software (ROSS) Manifesto

## What is ROSS?

**Real Open Source Software (ROSS)** is a classification used to distinguish software that completely adheres to the true philosophy of digital freedom, community autonomy, and transparency from projects that merely use "open source" as a marketing buzzword (open-washing). 

For a project to be considered **ROSS**, it must not only expose its source code but also actively respect and defend the **Four Essential Freedoms** of software:
* **Freedom 0:** The freedom to run the program for any purpose.
* **Freedom 1:** The freedom to study how the program works, and change it.
* **Freedom 2:** The freedom to redistribute copies.
* **Freedom 3:** The freedom to distribute copies of your modified versions to others.

---

## The Nuance of Corporate Ownership: When is it ROSS?

There is a common misconception that if a mega-corporation or a commercial entity owns a project, it cannot be "Real Open Source." This is not true. Corporate backed or corporate owned software **can absolutely be ROSS**, provided they maintain a strict line between corporate stewardship and user subjugation.

Consider these high-profile examples and where they stand:

### 1. Proxmox VE & Ubuntu (The True ROSS Tier)
* **Proxmox VE** is owned by Proxmox Server Solutions GmbH. While they sell enterprise support subscriptions and repository access for stable production environments, the entire core OS is completely open source under the GNU Affero General Public License (AGPLv3). Anyone can download it, strip out the subscription notification, and run it at enterprise scale for free without breaking the license.
* **Ubuntu** is backed by Canonical. Canonical drives the development, but the base OS remains completely open and freely redistributable. If a user dislikes Canonical's corporate choices (such as forcing Snap packages), the ROSS nature of the code allows the community to freely fork it—which is exactly how massive ecosystems like Linux Mint and Pop!_OS exist.

### 2. AOSP (The Guarded ROSS Tier)
* **Android Open Source Project (AOSP)** is maintained primarily by Google. AOSP itself is released under permissive open-source licenses (mostly Apache 2.0). Because it is ROSS, independent developers can take AOSP and build entirely de-Googled, privacy-focused operating systems like GrapheneOS or LineageOS. However, Google pushes the boundaries of open-washing by keeping its vital ecosystem features (Google Play Services) closed-source, creating a stark divide between pure AOSP and the commercial "Android" experience found on retail phones.

### 3. VirtualBox (The Divided Tier)
* **VirtualBox** (maintained by Oracle) highlights the "Open-Core" dilemma. The VirtualBox base package is released under the GNU General Public License (GPL) v3 and is fully ROSS. However, Oracle gates crucial features—like USB 2.0/3.0 support, VirtualBox RDP, and disk encryption—behind the proprietary **VirtualBox Extension Pack**, which carries a highly restrictive, non-free commercial license. The base is ROSS; the complete ecosystem is not.

---

## ROSS vs. The "Open-Washed" Traps

To truly understand ROSS, it must be contrasted against modern licensing traps used by corporations to trick developers:

| Feature / Trait | The Illusion ("Open-Washed") | The Reality (**ROSS**) |
| :--- | :--- | :--- |
| **Licensing** | **Source-Available (BSL / SSPL / Elastic)**<br>You can view the code, but you cannot host it as a service, compete with the vendor, or use it past a certain scale. | **OSI-Approved (GPL, AGPL, MIT, Apache 2.0)**<br>No arbitrary restrictions on who can use it, how they use it, or how they make a living with it. |
| **Monetization** | **Feature Gatekeeping (Open-Core)**<br>Vital functionalities (security, clustering, multi-tenancy) are locked behind an enterprise paywall. | **Value-Add Services**<br>The software is 100% complete. Monetization comes from optional official hosting, technical support, or managed services. |
| **Governance** | **Corporate Monarchy**<br>Outside contributions are ignored or heavily restricted unless you sign a predatory Contributor License Agreement (CLA) giving up your rights. | **Community-Driven**<br>The code can be freely extended, and the community has the ultimate power to fork the project if corporate leadership turns malicious. |

## Why ROSS Matters

When software is **ROSS**, the power dynamic balances back toward the user. It guarantees that even if the corporate owner goes bankrupt, gets bought out by a predatory private equity firm, or changes their business model overnight, the software cannot be taken away from the world. 

ROSS is code insurance for the digital age. It ensures that the software you rely on belongs to humanity, not just a boardroom.
