# [go](https://github.com/devcontainers/images/tree/main/src/go)

**Image version:** dev

**Source release/branch:** [main](https://github.com/devcontainers/images/tree/main/src/go)

**Image variations:**
- [1.19-bullseye](#variant-119-bullseye)
- [1.19-buster](#variant-119-buster)
- [1.18-bullseye](#variant-118-bullseye)
- [1.18-buster](#variant-118-buster)

## Variant: 1.19-bullseye

**Digest:** sha256:c43ffd53f342473b4e6691e2a202f84b2eace14e8b84ceca597430f8cb013b77

**Tags:**
```
mcr.microsoft.com/devcontainers/go:dev-1.19-bullseye
mcr.microsoft.com/devcontainers/go:dev-1.19
mcr.microsoft.com/devcontainers/go:dev-1
mcr.microsoft.com/devcontainers/go:dev-1-bullseye
mcr.microsoft.com/devcontainers/go:dev-bullseye
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 11 (bullseye)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Go](https://golang.org/dl) | 1.19.4 | /usr/local/go |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 4181e8a2cc936bc7b7a89d674bf261023159ed35 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 0ccd099bff8e384043883c4ae01b589794b13d72 | /usr/local/share/nvm |

**Go tools and modules**

| Tool / module | Version |
|---------------|---------|
| golang.org/x/tools/gopls | 0.11.0 |
| honnef.co/go/tools | 0.3.3 |
| golang.org/x/lint | 0.0.0-20210508222113-6edffad5e616 |
| github.com/mgechev/revive | 1.2.4 |
| github.com/uudashr/gopkgs | 2.0.1+incompatible |
| github.com/ramya-rao-a/go-outline | 0.0.0-20210608161538-9736a4bde949 |
| github.com/go-delve/delve | 1.20.1 |
| github.com/golangci/golangci-lint | latest |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.2.4 |
| apt-utils | 2.2.4 |
| ca-certificates | 20210119 |
| curl | 7.74.0-1.3+deb11u3 |
| dialog | 1.3-20201126-1 |
| g++ | 4:10.2.1-1 |
| gcc | 4:10.2.1-1 |
| git | 1:2.30.2-1 |
| gnupg2 | 2.2.27-2+deb11u2 |
| htop | 3.0.5-7 |
| iproute2 | 5.10.0-4 |
| jq | 1.6-2.1 |
| less | 551-2 |
| libc6 | 2.31-13+deb11u5 |
| libc6-dev | 2.31-13+deb11u5 |
| libgssapi-krb5-2 | 1.18.3-6+deb11u3 |
| libicu67 | 67.1-7 |
| libkrb5-3 | 1.18.3-6+deb11u3 |
| liblttng-ust0 | 2.12.1-1 |
| libssl1.1 | 1.1.1n-0+deb11u3 |
| libstdc++6 | 10.2.1-6 |
| locales | 2.31-13+deb11u5 |
| lsb-release | 11.1.0 |
| lsof | 4.93.2+dfsg-1.1 |
| make | 4.3-4.1 |
| man-db | 2.9.4-2 |
| manpages | 5.10-1 |
| manpages-dev | 5.10-1 |
| nano | 5.4-2+deb11u2 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1 |
| openssh-client | 1:8.4p1-5+deb11u1 |
| pkg-config | 0.29.2-1 |
| procps | 2:3.3.17-5 |
| psmisc | 23.4-2 |
| rsync | 3.2.3-4+deb11u1 |
| strace | 5.10-1 |
| sudo | 1.9.5p2-3 |
| unzip | 6.0-26+deb11u1 |
| vim-tiny | 2:8.2.2434-3+deb11u1 |
| wget | 1.21-1+deb11u1 |
| yarn | 1.22.19-1 |
| zip | 3.0-12 |
| zlib1g | 1:1.2.11.dfsg-2+deb11u2 |
| zsh | 5.8-6+deb11u1 |

## Variant: 1.19-buster

**Digest:** sha256:2b4cc3b3fc8b08640b089db4276b0c7566e4d1c9eb15420023681ef67e90e3bb

**Tags:**
```
mcr.microsoft.com/devcontainers/go:dev-1.19-buster
mcr.microsoft.com/devcontainers/go:dev-1-buster
mcr.microsoft.com/devcontainers/go:dev-buster
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 10 (buster)

**Architectures:** linux/amd64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Go](https://golang.org/dl) | 1.19.4 | /usr/local/go |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 4181e8a2cc936bc7b7a89d674bf261023159ed35 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 0ccd099bff8e384043883c4ae01b589794b13d72 | /usr/local/share/nvm |

**Go tools and modules**

| Tool / module | Version |
|---------------|---------|
| golang.org/x/tools/gopls | 0.11.0 |
| honnef.co/go/tools | 0.3.3 |
| golang.org/x/lint | 0.0.0-20210508222113-6edffad5e616 |
| github.com/mgechev/revive | 1.2.4 |
| github.com/uudashr/gopkgs | 2.0.1+incompatible |
| github.com/ramya-rao-a/go-outline | 0.0.0-20210608161538-9736a4bde949 |
| github.com/go-delve/delve | 1.20.1 |
| github.com/golangci/golangci-lint | latest |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 1.8.2.3 |
| apt-utils | 1.8.2.3 |
| ca-certificates | 20200601~deb10u2 |
| curl | 7.64.0-4+deb10u3 |
| dialog | 1.3-20190211-1 |
| g++ | 4:8.3.0-1 |
| gcc | 4:8.3.0-1 |
| git | 1:2.20.1-2+deb10u6 |
| gnupg2 | 2.2.12-1+deb10u2 |
| htop | 2.2.0-1+b1 |
| iproute2 | 4.20.0-2+deb10u1 |
| jq | 1.5+dfsg-2+b1 |
| less | 487-0.1+b1 |
| libc6 | 2.28-10+deb10u2 |
| libc6-dev | 2.28-10+deb10u2 |
| libgcc1 | 1:8.3.0-6 |
| libgssapi-krb5-2 | 1.17-3+deb10u5 |
| libicu63 | 63.1-6+deb10u3 |
| libkrb5-3 | 1.17-3+deb10u5 |
| liblttng-ust0 | 2.10.3-1 |
| libssl1.1 | 1.1.1n-0+deb10u3 |
| libstdc++6 | 8.3.0-6 |
| locales | 2.28-10+deb10u2 |
| lsb-release | 10.2019051400 |
| lsof | 4.91+dfsg-1 |
| make | 4.2.1-1.2 |
| man-db | 2.8.5-2 |
| manpages | 4.16-2 |
| manpages-dev | 4.16-2 |
| nano | 3.2-3 |
| ncdu | 1.13-1+b1 |
| net-tools | 1.60+git20180626.aebd88e-1 |
| openssh-client | 1:7.9p1-10+deb10u2 |
| pkg-config | 0.29-6 |
| procps | 2:3.3.15-2 |
| psmisc | 23.2-1+deb10u1 |
| rsync | 3.1.3-6 |
| strace | 4.26-0.2 |
| sudo | 1.8.27-1+deb10u4 |
| unzip | 6.0-23+deb10u3 |
| vim-tiny | 2:8.1.0875-5+deb10u4 |
| wget | 1.20.1-1.1 |
| yarn | 1.22.19-1 |
| zip | 3.0-11+b1 |
| zlib1g | 1:1.2.11.dfsg-1+deb10u2 |
| zsh | 5.7.1-1+deb10u1 |

## Variant: 1.18-bullseye

**Digest:** sha256:f10ef38a2b5451249d60463fd9309afbdfd9e90f07b5fa95873ee0b1b995825f

**Tags:**
```
mcr.microsoft.com/devcontainers/go:dev-1.18-bullseye
mcr.microsoft.com/devcontainers/go:dev-1.18
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 11 (bullseye)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Go](https://golang.org/dl) | 1.18.9 | /usr/local/go |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 4181e8a2cc936bc7b7a89d674bf261023159ed35 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 0ccd099bff8e384043883c4ae01b589794b13d72 | /usr/local/share/nvm |

**Go tools and modules**

| Tool / module | Version |
|---------------|---------|
| golang.org/x/tools/gopls | 0.11.0 |
| honnef.co/go/tools | 0.3.3 |
| golang.org/x/lint | 0.0.0-20210508222113-6edffad5e616 |
| github.com/mgechev/revive | 1.2.4 |
| github.com/uudashr/gopkgs | 2.0.1+incompatible |
| github.com/ramya-rao-a/go-outline | 0.0.0-20210608161538-9736a4bde949 |
| github.com/go-delve/delve | 1.20.1 |
| github.com/golangci/golangci-lint | latest |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.2.4 |
| apt-utils | 2.2.4 |
| ca-certificates | 20210119 |
| curl | 7.74.0-1.3+deb11u3 |
| dialog | 1.3-20201126-1 |
| g++ | 4:10.2.1-1 |
| gcc | 4:10.2.1-1 |
| git | 1:2.30.2-1 |
| gnupg2 | 2.2.27-2+deb11u2 |
| htop | 3.0.5-7 |
| iproute2 | 5.10.0-4 |
| jq | 1.6-2.1 |
| less | 551-2 |
| libc6 | 2.31-13+deb11u5 |
| libc6-dev | 2.31-13+deb11u5 |
| libgssapi-krb5-2 | 1.18.3-6+deb11u3 |
| libicu67 | 67.1-7 |
| libkrb5-3 | 1.18.3-6+deb11u3 |
| liblttng-ust0 | 2.12.1-1 |
| libssl1.1 | 1.1.1n-0+deb11u3 |
| libstdc++6 | 10.2.1-6 |
| locales | 2.31-13+deb11u5 |
| lsb-release | 11.1.0 |
| lsof | 4.93.2+dfsg-1.1 |
| make | 4.3-4.1 |
| man-db | 2.9.4-2 |
| manpages | 5.10-1 |
| manpages-dev | 5.10-1 |
| nano | 5.4-2+deb11u2 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1 |
| openssh-client | 1:8.4p1-5+deb11u1 |
| pkg-config | 0.29.2-1 |
| procps | 2:3.3.17-5 |
| psmisc | 23.4-2 |
| rsync | 3.2.3-4+deb11u1 |
| strace | 5.10-1 |
| sudo | 1.9.5p2-3 |
| unzip | 6.0-26+deb11u1 |
| vim-tiny | 2:8.2.2434-3+deb11u1 |
| wget | 1.21-1+deb11u1 |
| yarn | 1.22.19-1 |
| zip | 3.0-12 |
| zlib1g | 1:1.2.11.dfsg-2+deb11u2 |
| zsh | 5.8-6+deb11u1 |

## Variant: 1.18-buster

**Digest:** sha256:12227eb4f91d2a0b24b5fac5d527d4a947652496940c0da4df54fe0b6ba9c863

**Tags:**
```
mcr.microsoft.com/devcontainers/go:dev-1.18-buster
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 10 (buster)

**Architectures:** linux/amd64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Go](https://golang.org/dl) | 1.18.9 | /usr/local/go |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 4181e8a2cc936bc7b7a89d674bf261023159ed35 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 0ccd099bff8e384043883c4ae01b589794b13d72 | /usr/local/share/nvm |

**Go tools and modules**

| Tool / module | Version |
|---------------|---------|
| golang.org/x/tools/gopls | 0.11.0 |
| honnef.co/go/tools | 0.3.3 |
| golang.org/x/lint | 0.0.0-20210508222113-6edffad5e616 |
| github.com/mgechev/revive | 1.2.4 |
| github.com/uudashr/gopkgs | 2.0.1+incompatible |
| github.com/ramya-rao-a/go-outline | 0.0.0-20210608161538-9736a4bde949 |
| github.com/go-delve/delve | 1.20.1 |
| github.com/golangci/golangci-lint | latest |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 1.8.2.3 |
| apt-utils | 1.8.2.3 |
| ca-certificates | 20200601~deb10u2 |
| curl | 7.64.0-4+deb10u3 |
| dialog | 1.3-20190211-1 |
| g++ | 4:8.3.0-1 |
| gcc | 4:8.3.0-1 |
| git | 1:2.20.1-2+deb10u6 |
| gnupg2 | 2.2.12-1+deb10u2 |
| htop | 2.2.0-1+b1 |
| iproute2 | 4.20.0-2+deb10u1 |
| jq | 1.5+dfsg-2+b1 |
| less | 487-0.1+b1 |
| libc6 | 2.28-10+deb10u2 |
| libc6-dev | 2.28-10+deb10u2 |
| libgcc1 | 1:8.3.0-6 |
| libgssapi-krb5-2 | 1.17-3+deb10u5 |
| libicu63 | 63.1-6+deb10u3 |
| libkrb5-3 | 1.17-3+deb10u5 |
| liblttng-ust0 | 2.10.3-1 |
| libssl1.1 | 1.1.1n-0+deb10u3 |
| libstdc++6 | 8.3.0-6 |
| locales | 2.28-10+deb10u2 |
| lsb-release | 10.2019051400 |
| lsof | 4.91+dfsg-1 |
| make | 4.2.1-1.2 |
| man-db | 2.8.5-2 |
| manpages | 4.16-2 |
| manpages-dev | 4.16-2 |
| nano | 3.2-3 |
| ncdu | 1.13-1+b1 |
| net-tools | 1.60+git20180626.aebd88e-1 |
| openssh-client | 1:7.9p1-10+deb10u2 |
| pkg-config | 0.29-6 |
| procps | 2:3.3.15-2 |
| psmisc | 23.2-1+deb10u1 |
| rsync | 3.1.3-6 |
| strace | 4.26-0.2 |
| sudo | 1.8.27-1+deb10u4 |
| unzip | 6.0-23+deb10u3 |
| vim-tiny | 2:8.1.0875-5+deb10u4 |
| wget | 1.20.1-1.1 |
| yarn | 1.22.19-1 |
| zip | 3.0-11+b1 |
| zlib1g | 1:1.2.11.dfsg-1+deb10u2 |
| zsh | 5.7.1-1+deb10u1 |

