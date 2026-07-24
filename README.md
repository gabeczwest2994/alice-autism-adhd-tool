# ALICE - screening tool 2026

> **ALICE is a lightweight browser-based screening application for ADHD and autism. It is implemented in HTML and distributed as a focused, versioned release.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/gabeczwest2994/alice-autism-adhd-tool?style=flat-square)](https://github.com/gabeczwest2994/alice-autism-adhd-tool)

---

<p align="center">
  <a href="https://gabeczwest2994.github.io/alice-autism-adhd-tool/">
    <img src="https://img.shields.io/badge/Download-ALICE%20Latest-brightgreen?style=for-the-badge" alt="Download ALICE">
  </a>
</p>

> **[Download ALICE v](https://gabeczwest2994.github.io/alice-autism-adhd-tool/)**

---

[Download Latest Build](https://gabeczwest2994.github.io/alice-autism-adhd-tool/)

---

## What is ALICE?

ALICE provides a small, browser-ready interface for ADHD and autism screening. Its HTML-first design keeps the experience direct and uncomplicated: the project can be hosted as static files, opened locally, and viewed in a standard browser.

The tool is intended for neurodiversity-focused screening scenarios where a simple informational or early-stage assessment workflow is useful. Because the project has a compact structure, it can also be deployed and inspected without a complex application stack.

---

## Highlights

- Minimal interface for presenting screening material
- Screening flows for ADHD
- Screening flows for autism
- HTML implementation that runs in a web browser
- Suitable for static web hosting
- Designed around neurodiversity-related screening contexts
- Small, straightforward project structure for deployment and review

---

## Installation and setup

Download or clone the repository, move into the project directory, and open the main HTML file in a browser:

    git clone https://github.com/gabeczwest2994/alice-autism-adhd-tool.git
    cd alice
    open index.html

To publish ALICE through a web server, copy its HTML files into the server's public directory and open the primary page in a browser.

---

## Using ALICE

1. Launch the main HTML file in a modern browser.
2. Work through the prompts or other screening content shown by the interface.
3. Follow the result flow provided by the repository author.

A basic local server can be used when testing the project:

    python -m http.server 8000

Open the resulting local address:

    http://localhost:8000

---

## Configuration

There is no separate runtime configuration system for this HTML-based tool. Changes are generally made directly in the project source.

When settings, prompts, text, or other options are defined in the markup or scripts, edit the applicable HTML file before deploying the updated version. Static hosting normally only requires selecting the correct entry file.

---

## Requirements

- A current web browser
- Support for HTML
- Access to a local or hosted web environment
- Basic static file hosting for online publication

---

## Frequently asked questions

**Must ALICE be installed?**  
No. In normal use, ALICE can be opened directly as a static page or served from a web server.

**How are project updates applied?**  
Update the HTML and related web files in the repository, then replace the deployed files or open the revised files locally.

**Where is the screening material stored?**  
Review the repository's HTML source. The prompts, wording, and layout are expected to be defined in those files.

**What can I check if the page fails to display?**  
Verify that the main HTML entry file exists, confirm that referenced paths are correct, and make sure the browser supports the content used by the project.

---

## License

ALICE is released under the GNU GPL v3.0. See [LICENSE](LICENSE) for the full license text.
