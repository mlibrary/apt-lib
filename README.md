<p align="center">
 <h1 align="center"> - MLibrary Public DEB-repo - </h1>
</p>

<p align="center">
  <a href="https://github.com/CodeCrafter912/GitHubPagesTest/actions/workflows/build-and-deploy.yml"><img src="https://github.com/CodeCrafter912/GitHubPagesTest/actions/workflows/build-and-deploy.yml/badge.svg" /></a>
  <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" />
  <a href="https://www.gnu.org/licenses/agpl-3.0" ><img src="https://img.shields.io/badge/License-AGPL%20v3-blue.svg" /></a>
</p>

<p align="center">
MLibrary Public Packages (Bullseye)
</p>

# Setup
To use the repository, please follow these steps:
1. Import key:
```bash
wget -qO - "https://apt.lib.umich.edu/github-pages-dep-repo/pub.gpg" | sudo apt-key add -
```
2. Add repo:
```bash
echo "deb https://apt.lib.umich.edu/github-pages-dep-repo bullseye main" > /etc/apt/sources.list.d/github-pages-dep-repo.list
```
3. Apt update
```bash
apt update
```
