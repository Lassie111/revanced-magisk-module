#### ⚠️ Do not download modules from 3rd party sources like random websites you found on Google. There are many that uses these modules and impersonates ReVanced.

# ReVanced Magisk Module
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/rvc_magisk)
[![CI](https://github.com/Lassie111/revanced-magisk-module/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/Lassie111/revanced-magisk-module/actions/workflows/ci.yml)

Extensive ReVanced builder  

Get the [latest CI release](https://github.com/Lassie111/revanced-magisk-module/releases).

Use [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from Play Store if you are using magisk modules. 

## Features
<ul>
 <li>Support all present and future <a href="https://github.com/revanced/revanced-patches">ReVanced</a> and <a href="https://github.com/inotia00/revanced-patches">ReVanced Extended</a> apps</li>
 <li> Can build Magisk modules and non-root APKs</li>
 <li> Updated daily with the latest versions of apps and patches</li>
 <li> Optimize APKs and modules for size</li>
 <li> Modules</li>
    <ul>
     <li> recompile invalidated odex for faster usage</li>
     <li> receive updates from Magisk app</li>
     <li> do not break safetynet or trigger root detections</li>
     <li> handle installation of the correct version of the stock app</li>
     <li> support Magisk and KernelSU</li>
    </ul>
</ul>
Note that the <a href="../../actions/workflows/ci.yml">CI workflow</a> is scheduled to build the modules and APKs everyday using GitHub Actions if there is a change in ReVanced patches. You may want to disable it.

## To include/exclude patches or patch other apps
[**See the list of patches**](https://j-hc.github.io/rvmm-config-gen/)

 * Star the repo :eyes:
 * [Fork the repo](https://github.com/Lassie111/revanced-magisk-module/fork) or use it as a template
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

also see here [`CONFIG.md`](./CONFIG.md)

## Building Locally
### On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/Lassie111/revanced-magisk-module/main/build-termux.sh)
```

### On Desktop
```console
$ git clone https://github.com/Lassie111/revanced-magisk-module
$ cd revanced-magisk-module
$ ./build.sh
```
