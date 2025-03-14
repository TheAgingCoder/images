# [universal](https://github.com/devcontainers/images/tree/main/src/universal)
This document describes the base contents of the Universal image. Note that this image also includes detection logic to dynamically install additional language / runtime versions based on your repository's contents. Dynamically installed content can be found in sub-folders under `/opt`.

**Image version:** dev

**Source release/branch:** [main](https://github.com/devcontainers/images/tree/main/src/universal)

**Digest:** sha256:77296e6f937a114e60426af8ebcbe4a64232837b164af0351aaf3701918de3fc

**Tags:**
```
mcr.microsoft.com/devcontainers/universal:dev-focal
mcr.microsoft.com/devcontainers/universal:dev-linux
mcr.microsoft.com/devcontainers/universal:dev
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Ubuntu 20.04.5 LTS (debian-like distro)

**Architectures:** linux/amd64

**Available (non-root) user:** codespace

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Node.js](https://nodejs.org/en/) | 14.21.2<br />16.19.0 | /usr/local/share/nvm/versions/node/&lt;version&gt; |
| [Python](https://www.python.org/) | 3.10.4<br />3.9.7 | /usr/local/python/&lt;version&gt; |
| [Java](https://adoptopenjdk.net/) | 11.0.17<br />17.0.5 | /usr/local/sdkman/candidates/java/&lt;version&gt; |
| [.NET](https://dotnet.microsoft.com/) | 6<br />0<br />4<br />0<br />5<br />7<br />0<br />1<br />0<br />2 | /usr/local/dotnet |
| [Ruby](https://www.ruby-lang.org/en/) | 3.0.5<br />3.1.3 | /usr/local/rvm/rubies/&lt;version&gt; |
| [PHP](https://xdebug.org/) | 8.0.16<br />8.1.4 | /usr/local/php/&lt;version&gt; |
| GCC | 9.4.0-1ubuntu1~20.04.1 | 
| Clang | 10.0.0-4ubuntu1 | 
| [Go](https://golang.org/dl) | 1.19.5 | /usr/local/go |
| [Jekyll](https://jekyllrb.com/) | 4.3.1 | 
| [Jupyter Lab](https://jupyter.org/) | 3.5.2 | /home/codespace/.local/bin/jupyter-lab |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 4181e8a2cc936bc7b7a89d674bf261023159ed35 | /home/codespace/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 0ccd099bff8e384043883c4ae01b589794b13d72 | /usr/local/share/nvm |
| [nvs](https://github.com/jasongin/nvs) | 4fc93c60fb3341a56984ae2b50553561acff33ea | /usr/local/nvs |
| [rbenv](https://github.com/rbenv/rbenv.git) | 61747c06d42a4ef094fcc498eefcd93d5d9d7016 | /usr/local/share/rbenv |
| [ruby-build](https://github.com/rbenv/ruby-build.git) | 697bcff8b50e9673036cf54200bd82eb689fe3db | /usr/local/share/ruby-build |

**Pip / pipx installed tools and packages**

| Tool / package | Version |
|----------------|---------|
| numpy | 1.24.1 |
| pandas | 1.5.2 |
| scipy | 1.10.0 |
| matplotlib | 3.6.2 |
| seaborn | 0.12.2 |
| scikit-learn | 1.2.0 |
| torch | 1.13.1 |
| requests | 2.28.1 |
| plotly | 5.11.0 |
| jupyterlab-git | 0.41.0 |
| certifi | 2022.12.7 |
| pylint | 2.15.10 |
| flake8 | 6.0.0 |
| autopep8 | 2.0.1 |
| black | 22.12.0 |
| yapf | 0.32.0 |
| mypy | 0.991 |
| pydocstyle | 6.2.3 |
| pycodestyle | 2.10.0 |
| bandit | 1.7.4 |
| virtualenv | 20.17.1 |
| pipx | 1.1.0 |

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

**Ruby gems and tools**

| Tool / gem | Version |
|------------|---------|
| rake | 13.0.6 |
| ruby-debug-ide | 0.7.3 |
| debase | 0.2.5.beta2 |
| jekyll | 4.3.1 |

**Other tools and utilities**

| Tool | Version | Path |
|------|---------|------|
| [git](https://github.com/git/git) | 2.25.1 | /usr/bin |
| [Xdebug](https://xdebug.org/) | 3.2.0 | /usr/local/php/current |
| [Composer](https://getcomposer.org/) | 2.5.1 | /usr/local/php/current/bin |
| [kubectl](https://github.com/kubernetes/kubectl) | v1.26.0 | /usr/local/bin |
| [Helm](https://github.com/helm/helm) | 3.10.3 | /usr/local/bin |
| [Docker Compose](https://github.com/docker/compose) | 1.29.2 | /usr/local/bin |
| [SDKMAN!](https://github.com/sdkman/sdkman-cli) | 5.16.0 | /usr/local/sdkman |
| [rvm](https://github.com/rvm/rvm) | 1.29.12 | /usr/local/rvm |
| [GitHub CLI](https://github.com/cli/cli) | 2.21.2 | 
| [yarn](https://yarnpkg.com/) | 1.22.19 | /usr/bin |
| [Maven](https://maven.apache.org/) | 3.8.7 | /usr/local/sdkman/candidates/maven/current/bin |
| [Gradle](https://gradle.org/) | 7.6 | /usr/local/sdkman/candidates/gradle/current/bin |
| Docker (Moby) CLI &amp; Engine | 20.10.22+azure | 
| [conda](https://github.com/conda/conda) | 4.12.0 | /opt/conda/bin |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.0.9 |
| apt-utils | 2.0.9 |
| build-essential | 12.8ubuntu1.1 |
| ca-certificates | 20211016ubuntu0.20.04.1 |
| clang | 1:10.0-50~exp1 |
| cmake | 3.16.3-1ubuntu1.20.04.1 |
| cppcheck | 1.90-4build1 |
| curl | 7.68.0-1ubuntu2.15 |
| dialog | 1.3-20190808-1 |
| g++ | 4:9.3.0-1ubuntu2 |
| gcc | 4:9.3.0-1ubuntu2 |
| gdb | 9.2-0ubuntu1~20.04.1 |
| git | 1:2.25.1-1ubuntu3.6 |
| git-lfs (Git Large File Support) | 3.3.0 |
| gnupg2 | 2.2.19-3ubuntu2.2 |
| htop | 2.2.0-2build1 |
| iproute2 | 5.5.0-1ubuntu1 |
| iptables | 1.8.4-3ubuntu2 |
| jq | 1.6-1ubuntu0.20.04.1 |
| less | 551-1ubuntu0.1 |
| libatk-bridge2.0-0 | 2.34.2-0ubuntu2~20.04.1 |
| libatk1.0-0 | 2.35.1-1ubuntu2 |
| libc6 | 2.31-0ubuntu9.9 |
| libc6-dev | 2.31-0ubuntu9.9 |
| libcups2 | 2.3.1-9ubuntu1.2 |
| libgbm1 | 21.2.6-0ubuntu0.1~20.04.2 |
| libgcc1 | 1:10.3.0-1ubuntu1~20.04 |
| libgssapi-krb5-2 | 1.17-6ubuntu4.1 |
| libgtk-3-0 | 3.24.20-0ubuntu1.1 |
| libicu66 | 66.1-2ubuntu2.1 |
| libkrb5-3 | 1.17-6ubuntu4.1 |
| liblttng-ust0 | 2.11.0-1 |
| libnspr4 | 2:4.25-1 |
| libnss3 | 2:3.49.1-1ubuntu1.8 |
| libpango-1.0-0 | 1.44.7-2ubuntu4 |
| libpangocairo-1.0-0 | 1.44.7-2ubuntu4 |
| libsecret-1-dev | 0.20.4-0ubuntu1 |
| libssl1.1 | 1.1.1f-1ubuntu2.16 |
| libstdc++6 | 10.3.0-1ubuntu1~20.04 |
| libx11-6 | 2:1.6.9-2ubuntu1.2 |
| libx11-xcb1 | 2:1.6.9-2ubuntu1.2 |
| libxcomposite1 | 1:0.4.5-1 |
| libxdamage1 | 1:1.1.5-2 |
| libxfixes3 | 1:5.0.3-2 |
| lldb | 1:10.0-50~exp1 |
| llvm | 1:10.0-50~exp1 |
| locales | 2.31-0ubuntu9.9 |
| lsb-release | 11.1.0ubuntu2 |
| lsof | 4.93.2+dfsg-1ubuntu0.20.04.1 |
| make | 4.2.1-1.2 |
| man-db | 2.9.1-1 |
| manpages | 5.05-1 |
| manpages-dev | 5.05-1 |
| moby-cli (Docker CLI) | 20.10.22+azure-ubuntu20.04u1 |
| moby-engine (Docker Engine) | 20.10.22+azure-ubuntu20.04u1 |
| nano | 4.8-1ubuntu1 |
| ncdu | 1.14.1-1 |
| net-tools | 1.60+git20180626.aebd88e-1ubuntu1 |
| openssh-client | 1:8.2p1-4ubuntu0.5 |
| openssh-server | 1:8.2p1-4ubuntu0.5 |
| pigz | 2.4-1 |
| pkg-config | 0.29.1-0ubuntu4 |
| procps | 2:3.3.16-1ubuntu2.3 |
| psmisc | 23.3-1 |
| python3-dev | 3.8.2-0ubuntu2 |
| python3-minimal | 3.8.2-0ubuntu2 |
| rsync | 3.1.3-8ubuntu0.4 |
| sed | 4.7-1 |
| software-properties-common | 0.99.9.8 |
| strace | 5.5-3ubuntu1 |
| sudo | 1.8.31-1ubuntu1.2 |
| tar | 1.30+dfsg-7ubuntu0.20.04.2 |
| unzip | 6.0-25ubuntu1.1 |
| valgrind | 1:3.15.0-1ubuntu9.1 |
| vim | 2:8.1.2269-1ubuntu5.9 |
| vim-doc | 2:8.1.2269-1ubuntu5.9 |
| vim-tiny | 2:8.1.2269-1ubuntu5.9 |
| wget | 1.20.3-1ubuntu2 |
| xtail | 2.1-6 |
| zip | 3.0-11build1 |
| zlib1g | 1:1.2.11.dfsg-2ubuntu1.5 |
| zsh | 5.8-3ubuntu1.1 |

