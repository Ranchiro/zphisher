Certainly! Here's a customized version of the Zphisher README tailored for your GitHub profile, with your name and repository link:

---

<!-- Zphisher -->

<p align="center">
  <img src=".github/misc/logo.png">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.3.5-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/Ranchiro/zphisher?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/Ranchiro/zphisher?style=for-the-badge">
  <img src="https://img.shields.io/github/issues/Ranchiro/zphisher?color=red&style=for-the-badge">
  <img src="https://img.shields.io/github/forks/Ranchiro/zphisher?color=teal&style=for-the-badge">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Author-Ranchiro-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Open%20Source-Yes-darkgreen?style=flat-square">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-lightblue?style=flat-square">
  <img src="https://img.shields.io/badge/Written%20In-Bash-darkcyan?style=flat-square">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FRanchiro%2Fzphisher&title=Visitors&edge_flat=false"/>
</p>

<p align="center"><b>A beginner-friendly, automated phishing tool with 30+ templates.</b></p>

##

### Disclaimer

<i>Any actions and activities related to <b>Zphisher</b> are solely your responsibility. The misuse of this toolkit can result in <b>criminal charges</b> against the persons involved. <b>The contributors will not be held responsible</b> for any misuse of this toolkit.

<b>This toolkit contains materials that can be potentially damaging or dangerous for social media.</b> Refer to the laws in your province/country before accessing or using this in any unauthorized way.

<b>This tool is made for educational purposes only.</b> Do not attempt to violate the law with anything contained here. <b>If this is your intention, then exit immediately!</b>

It only demonstrates "how phishing works". <b>You shall not misuse the information to gain unauthorized access to someone's social media.</b> Use at your own risk.</i>

##

### Features

* Latest and updated login pages.
* Beginner-friendly interface.
* Multiple tunneling options:

  * Localhost
  * Cloudflared
  * LocalXpose
* URL masking support.
* Docker support.

##

### Installation

* Clone this repository:

  ```
  git clone --depth=1 https://github.com/Ranchiro/zphisher.git
  ```

* Navigate to the cloned directory and run `zphisher.sh`:

  ```
  cd zphisher
  bash zphisher.sh
  ```

* On the first launch, it will install the necessary dependencies. After that, ***Zphisher*** is ready to use.

##

### Installation (Termux)

You can easily install Zphisher in Termux using tur-repo:

```
pkg install tur-repo
pkg install zphisher
zphisher
```

### Note:

***Termux discourages hacking.*** Avoid discussing anything related to *Zphisher* in Termux discussion groups. For more information, check the [Termux Wiki](https://wiki.termux.com/wiki/Hacking).

##

### Installation via ".deb" file

* Download `.deb` files from the [**Latest Release**](https://github.com/Ranchiro/zphisher/releases/latest).

* If you are using ***Termux***, download the `*_termux.deb` file.

* Install the `.deb` file by executing:

  ```
  apt install <your path to deb file>
  ```

  Or:

  ```
  dpkg -i <your path to deb file>
  apt install -f
  ```

##

### Run on Docker

* Docker Image Mirror:

  * **DockerHub**:

    ```
    docker pull ranchiro/zphisher
    ```
  * **GHCR**:

    ```
    docker pull ghcr.io/ranchiro/zphisher:latest
    ```

* Using the wrapper script [**run-docker.sh**](https://raw.githubusercontent.com/Ranchiro/zphisher/master/run-docker.sh):

  ```
  curl -LO https://raw.githubusercontent.com/Ranchiro/zphisher/master/run-docker.sh
  bash run-docker.sh
  ```

* Temporary Container:

  ```
  docker run --rm -ti ranchiro/zphisher
  ```

  * Remember to mount the `auth` directory.

##

<details>
  <summary><h3>Dependencies</h3></summary>

<b>Zphisher</b> requires the following programs to run properly:

* `git`
* `curl`
* `php`

> All dependencies will be installed automatically when you run **Zphisher** for the first time.

</details>

<details>
  <summary><h3>Tested on</h3></summary>

* **Ubuntu**
* **Debian**
* **Arch**
* **Manjaro**
* **Fedora**
* **Termux**

</details>

##

<h3 align="center"><i>:: Workflow ::</i></h3>
<p align="center">
<img src=".github/misc/workflow.gif"/>
</p>

##

### Find Me on:

<p align="left">
  <a href="https://github.com/Ranchiro" target="_blank"><img src="https://img.shields.io/badge/Github-blue?style=for-the-badge&logo=github"></a>
</p>

---

**Note:** This tool is intended for educational purposes only. Unauthorized use is prohibited.

---
