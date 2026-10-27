# ReVanced Magisk Module
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/rvc_magisk)
[![CI](https://github.com/j-hc/revanced-magisk-module/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/j-hc/revanced-magisk-module/actions/workflows/ci.yml)

Extensive ReVanced builder  

Get the [latest CI release](https://github.com/j-hc/revanced-magisk-module/releases).

Use [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from Play Store if you are using magisk modules. 

<details><summary><big>Features</big></summary>
<ul>
 <li> Supports all present and future ReVanced apps (including projects implementing the same interface like Morphe)</li>
 <li> Receives in-app updates</li>
 <li> Can build modules and non-root APKs</li>
 <li> Updated daily with the latest versions of apps and patches</li>
 <li> Optimizes APKs and modules for size</li>
 <li> Modules</li>
    <ul>
     <li> handle installation of the correct version of the stock app and all that</li>
     <li> do not trigger root detections</li>
     <li> receive updates from Magisk/KernelSU app</li>
     <li> recompile invalidated odex for faster usage</li>
    </ul>
</ul>
</details>

## To include/exclude patches or patch other apps

 * Star the repo :eyes:
 * Use the repo as a [template](https://github.com/new?template_name=revanced-magisk-module&template_owner=j-hc)
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

also see here [`CONFIG.md`](./CONFIG.md)

## If you are having trouble with the classic mount method of the modules
such as,
- **"Reflash needed"** error after reboots
- **"Suspicious mount detected"** warnings from root detector apps

You can consider using [rvmm-zygisk-mount](https://github.com/j-hc/rvmm-zygisk-mount)
## Install
[![Get YT & YT Music on Obtainium](https://raw.githubusercontent.com/ImranR98/Obtainium/main/assets/graphics/badge_obtainium.png)](https://apps.obtainium.imranr.dev/redirect?r=obtainium://apps/%5B%7B%22id%22%3A%22app.morphe.android.youtube%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2F0xRafay%2Frevanced-magisk-module%22%2C%22author%22%3A%220xRafay%22%2C%22name%22%3A%22YouTube%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22verifyLatestTag%5C%22%3Afalse%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22githubBuildVerificationMode%5C%22%3A%5C%22off%5C%22%2C%5C%22sortMethodChoice%5C%22%3A%5C%22date%5C%22%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22onDemandOnly%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22versionStringSource%5C%22%3A%5C%22default%5C%22%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%5C%22%2C%5C%22versionDetection%5C%22%3A%5C%22auto%5C%22%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22youtube-morphe.*-all%5C%5C%5C%5C.apk%24%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Atrue%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22refreshBeforeDownload%5C%22%3Afalse%2C%5C%22enableVirusTotalScan%5C%22%3Atrue%2C%5C%22includeZips%5C%22%3Afalse%2C%5C%22zippedApkFilterRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22includeTarballs%5C%22%3Afalse%2C%5C%22tarballedApkFilterRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22appId%5C%22%3A%5C%22app.morphe.android.youtube%5C%22%2C%5C%22enforceGitHubAttestations%5C%22%3Afalse%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Afalse%2C%5C%22extractVersionFromAssetName%5C%22%3Afalse%2C%5C%22releaseCommitShaAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22appName%5C%22%3A%5C%22Youtube%20Morphe%5C%22%2C%5C%22appAuthor%5C%22%3A%5C%220xRafay%5C%22%2C%5C%22observedPackageId%5C%22%3A%5C%22app.morphe.android.youtube%5C%22%2C%5C%22observedVersionName%5C%22%3A%5C%2221.20.405%5C%22%2C%5C%22observedVersionCode%5C%22%3A1561173354%2C%5C%22confirmedInstallRelease%5C%22%3A%7B%5C%22appId%5C%22%3A%5C%22app.morphe.android.youtube%5C%22%2C%5C%22sourceUrl%5C%22%3A%5C%22https%3A%2F%2Fgithub.com%2F0xRafay%2Frevanced-magisk-module%5C%22%2C%5C%22overrideSource%5C%22%3Anull%2C%5C%22version%5C%22%3A%5C%222%5C%22%2C%5C%22assetName%5C%22%3A%5C%22youtube-morphe-v21.20.405-all.apk%5C%22%2C%5C%22assetUrl%5C%22%3A%5C%22https%3A%2F%2Fapi.github.com%2Frepos%2F0xRafay%2Frevanced-magisk-module%2Freleases%2Fassets%2F681839125%5C%22%2C%5C%22versionName%5C%22%3A%5C%2221.20.405%5C%22%2C%5C%22versionCode%5C%22%3A1561173354%2C%5C%22versionSettings%5C%22%3A%5C%22%5B%5C%5C%5C%22default%5C%5C%5C%22%2C%5C%5C%5C%22%5C%5C%5C%22%2C%5C%5C%5C%220%5C%5C%5C%22%2Cfalse%5D%5C%22%7D%2C%5C%22lastInstalledTime%5C%22%3A1793113687860%7D%22%2C%22overrideSource%22%3Anull%7D%2C%7B%22id%22%3A%22app.morphe.android.apps.youtube.music%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2F0xRafay%2Frevanced-magisk-module%22%2C%22author%22%3A%220xRafay%22%2C%22name%22%3A%22YouTube%20Music%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22verifyLatestTag%5C%22%3Atrue%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22githubBuildVerificationMode%5C%22%3A%5C%22off%5C%22%2C%5C%22sortMethodChoice%5C%22%3A%5C%22date%5C%22%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22onDemandOnly%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22versionStringSource%5C%22%3A%5C%22default%5C%22%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%5C%22%2C%5C%22versionDetection%5C%22%3A%5C%22auto%5C%22%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22music-morphe.*arm64-v8a%5C%5C%5C%5C.apk%24%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Atrue%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22refreshBeforeDownload%5C%22%3Afalse%2C%5C%22enableVirusTotalScan%5C%22%3Atrue%2C%5C%22includeZips%5C%22%3Afalse%2C%5C%22zippedApkFilterRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22includeTarballs%5C%22%3Afalse%2C%5C%22tarballedApkFilterRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22enforceGitHubAttestations%5C%22%3Afalse%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Afalse%2C%5C%22extractVersionFromAssetName%5C%22%3Afalse%2C%5C%22releaseCommitShaAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22appName%5C%22%3A%5C%22YT%20Music%20Morphe%5C%22%2C%5C%22appAuthor%5C%22%3A%5C%220xRafay%5C%22%2C%5C%22observedPackageId%5C%22%3A%5C%22app.morphe.android.apps.youtube.music%5C%22%2C%5C%22observedVersionName%5C%22%3A%5C%229.20.53%5C%22%2C%5C%22observedVersionCode%5C%22%3A92053240%2C%5C%22confirmedInstallRelease%5C%22%3A%7B%5C%22appId%5C%22%3A%5C%22app.morphe.android.apps.youtube.music%5C%22%2C%5C%22sourceUrl%5C%22%3A%5C%22https%3A%2F%2Fgithub.com%2F0xRafay%2Frevanced-magisk-module%5C%22%2C%5C%22overrideSource%5C%22%3Anull%2C%5C%22version%5C%22%3A%5C%222%5C%22%2C%5C%22assetName%5C%22%3A%5C%22music-morphe-v9.20.53-arm64-v8a.apk%5C%22%2C%5C%22assetUrl%5C%22%3A%5C%22https%3A%2F%2Fapi.github.com%2Frepos%2F0xRafay%2Frevanced-magisk-module%2Freleases%2Fassets%2F681838909%5C%22%2C%5C%22versionName%5C%22%3A%5C%229.20.53%5C%22%2C%5C%22versionCode%5C%22%3A92053240%2C%5C%22versionSettings%5C%22%3A%5C%22%5B%5C%5C%5C%22default%5C%5C%5C%22%2C%5C%5C%5C%22%5C%5C%5C%22%2C%5C%5C%5C%220%5C%5C%5C%22%2Cfalse%5D%5C%22%7D%2C%5C%22lastInstalledTime%5C%22%3A1793112777782%2C%5C%22appId%5C%22%3A%5C%22app.morphe.android.apps.youtube.music%5C%22%7D%22%2C%22overrideSource%22%3Anull%7D%5D
)

## Building Locally
### On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/j-hc/revanced-magisk-module/main/build-termux.sh)
```

### On Linux
```console
$ git clone https://github.com/j-hc/revanced-magisk-module --depth 1
$ cd revanced-magisk-module
$ ./build.sh
```
