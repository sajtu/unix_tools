# unix_tools

A collection of Unix, Unix-like, and Linux command-line utilities, helper scripts, and system administration tools developed by Sean Tu.

This repository primarily exists to make my life easier as a Unix user and system administrator. Over time, I add new scripts that simplify repetitive tasks, provide wrappers around common commands, or improve the readability of command output.

Many of these tools are also influenced by the fact that I am dyslexic. Where practical, I prefer command output that is easier and faster to scan, with consistent formatting and reduced visual clutter. Some utilities intentionally present information differently than traditional Unix tools in order to improve readability.

As I create or discover additional tools that I find useful, they will be added to this repository.

---

## Features

Depending on the script, you may find functionality such as:

- Simplified wrappers around common Unix/Linux commands
- System administration helper scripts
- Improved and more readable command output
- Reduced command-line steps for common administrative tasks
- Small utilities developed to solve day-to-day problems
- Opinionated tools designed for practical use rather than strict compatibility with traditional Unix tools

---

## Installation

Clone the repository using HTTPS:

```bash
git clone https://github.com/sajtu/unix_tools.git
cd unix_tools
./INSTALL_TOOLS
```

Or clone using SSH (requires a GitHub account with a configured SSH key):

```bash
git clone git@github.com:sajtu/unix_tools.git
cd unix_tools
./INSTALL_TOOLS
```

---

## Requirements

Most scripts are intended to run on Unix-like operating systems, including:

- Linux
- BSD
- macOS
- Other POSIX-compatible systems

Some scripts may require additional software or packages. Refer to comments or documentation within each script for any specific dependencies.

Some scripts may be specific to Linux (and specific Linux distributions), MacOS/Darwin, FreeBSD, Solaris, etc. They will produce error if they are executed on other O/S'es or distributions.

---

## Project Philosophy

These utilities are written with practicality in mind.

Many scripts intentionally differ from traditional Unix tools if doing so results in output that is easier to read, requires fewer commands, or improves day-to-day system administration. Strict compatibility with existing utilities is not always the primary goal.

Several tools were designed specifically to make command-line output easier for people with dyslexia, including myself. If a tool chooses readability over convention, that is usually intentional.

This repository is a living collection. As I develop new tools or discover useful scripts, they will be added here over time.

---

## Disclaimer

This repository is provided **AS IS**, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement.

These scripts were developed primarily for my own personal use. While they may be useful to others, they have not been tested in every operating system, distribution, configuration, or environment.

**You are solely responsible for reviewing, understanding, testing, and validating every script before using it on your own systems.**

By downloading, copying, modifying, or using any software, script, example, or documentation contained in this repository, you acknowledge and accept all risks associated with its use, including but not limited to:

- Data loss
- Service interruption or downtime
- Corrupted files or data
- Security issues
- Configuration errors
- Hardware or software damage
- Financial loss
- Any direct, indirect, incidental, consequential, special, or exemplary damages

The author shall not be liable for any claim, damage, loss, liability, or expense arising from the use of, misuse of, or inability to use any material contained in this repository.

Always test scripts in a non-production environment before using them on systems containing important data or providing critical services.

---

## Contributing

Although this repository was created primarily for my own personal use, anyone is welcome to use the scripts.

If you discover a bug, improve a script, or fix an issue, please consider opening an Issue or submitting a Pull Request so the improvements can benefit everyone.

Feel free to fork this repository and adapt it to your own needs.

---

## Author

Sean Tu

GitHub: https://github.com/sajtu
