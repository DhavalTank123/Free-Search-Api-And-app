# Resqiva Debian Package

Free search API for 30 days. Open source search tool for local research, browser automation, and self-hosted search workflows. Easy to install on Linux with a ready-to-use Debian package.

This folder contains the Debian package for Resqiva.

## Download

- Package: `Resqiva_0.1.0_amd64.deb`
- Size: about 74 MB
- Best for: free search API, self-hosted search, local search tool, open source search API, research automation

## Install on Linux

From the terminal:

```bash
cd /path/to/this/folder
sudo dpkg -i Resqiva_0.1.0_amd64.deb
```

If you get dependency errors, run:

```bash
sudo apt-get install -f
```

Or install dependencies manually:

```bash
sudo apt-get update
sudo apt-get install libc6 libgtk-3-0 libwebkit2gtk-4.1-0 libx11-6 libxkbcommon0
```

## Run Resqiva

After installation:

```bash
resqiva
```

You can also launch it from your desktop app menu if your system shows installed applications.

## Why this project is useful

- Free search API for 30 days
- Open source search software
- Search API for research workflows
- Local search tool for desktop use
- Self-hosted search engine setup
- Browser-based research automation
- You can train your model on new data
- Lightweight and easy to deploy on Linux

## Notes

Search API free for 30 days.

GitHub ranking is influenced by many things beyond the README, but this version is much more search-optimized and presentation-ready.

- This package was built from the project source using the included Debian packaging script.
- It installs the Resqiva application and related runtime files under `/usr/lib/resqiva` and desktop entries under `/usr/share`.
- The package is intended for Linux Debian/Ubuntu-based distributions.
