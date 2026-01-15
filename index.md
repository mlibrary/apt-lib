<p align="center">
 <h1 align="center"> - MLibrary Public Debian Repository - </h1>
</p>

<p align="center">
  <a href="https://github.com/mlibrary/apt-lib/actions/workflows/build-and-deploy.yml"><img src="https://github.com/mlibrary/apt-lib/actions/workflows/build-and-deploy.yml/badge.svg" /></a>
  <a href="https://www.gnu.org/licenses/agpl-3.0" ><img src="https://img.shields.io/badge/License-AGPL%20v3-blue.svg" /></a>
</p>

<p align="center">
MLibrary Public Packages (Bullseye)
</p>

# Setup
To use the repository, please follow these steps:
1. Import key (as root or with sudo):
```bash
mkdir -p /etc/apt/keyrings
curl -fsSL https://apt.lib.umich.edu/mlibrary-archive-keyring.gpg -o /etc/apt/keyrings/mlibrary-archive-keyring.gpg
```
2. Add repo:
```bash
echo "deb [signed-by=/etc/apt/keyrings/mlibrary-archive-keyring.gpg] https://apt.lib.umich.edu bullseye main" > /etc/apt/sources.list.d/mlibrary.list
```
3. Apt update
```bash
apt update
```

# Index of /
Files in this directory:
- 📁 [dists/](dists)
- 🗒 [mlibrary-archive-keyring.asc](mlibrary-archive-keyring.asc)
- 🗒 [mlibrary-archive-keyring.gpg](mlibrary-archive-keyring.gpg)
- 📁 [pool/](pool)
