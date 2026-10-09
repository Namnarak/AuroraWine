<!-- CYTECH_README_REFRESH:START -->
<div align="center">
<a href="https://github.com/Namnarak/AuroraWine"><img width="100%" alt="AuroraWine banner" src="https://capsule-render.vercel.app/api?type=waving&color=0:181224,100:A855F7&height=210&section=header&text=AuroraWine&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=Aurora-maintained%20Wine%20runtime%20for%20Aurora%20Studio&descAlignY=59&descSize=16"></a>

<img alt="Project: Runtime Fork" src="https://img.shields.io/badge/PROJECT-Runtime%20Fork-A855F7?style=flat-square&labelColor=181224"> <img alt="Stack: Wine · Linux" src="https://img.shields.io/badge/STACK-Wine%20%C2%B7%20Linux-A855F7?style=flat-square&labelColor=181224">

<a href="https://github.com/Namnarak/AuroraWine">Source</a> · <a href="https://github.com/Namnarak/AuroraWine/issues">Issues</a> · <a href="https://github.com/Namnarak/AuroraWine/releases">Releases</a>

</div>
<!-- CYTECH_README_REFRESH:END -->

---

> [!NOTE]
> Based on [vinegarhq/kombucha](https://github.com/vinegarhq/kombucha); upstream license and patch attribution remain in place.

AuroraWine is the Aurora-maintained Wine runtime fork of [vinegarhq/kombucha](https://github.com/vinegarhq/kombucha), used as the managed Wine runtime for Aurora Studio.

It preserves the upstream LGPL-2.1 license and patch history. Aurora Studio downloads stable runtime releases from this fork so it does not depend on a Vinegar installation.

Upstream Kombucha serves as the place to fetch customized Wine builds for Vinegar.

These Wine builds are patched to fix numerous issues with Roblox Studio that are
otherwise non-existent on Windows. Some of these issues are caused by Wine itself,
while others are bugs specific to a desktop environment or display server.

At the time of writing this, Kombucha comes in four different flavors:
* stable
* unstable
* proton-unstable

"stable" builds of Kombucha are based on stable/development releases of Wine. These
builds are intended for use in production.

"unstable" builds of Kombucha are based on the latest commit of Wine and are updated
more frequently. They may also include experimental patches, so caution is advised
when using in production.

Builds of Kombucha labeled under "proton-unstable" are only meant as a stop-gap solution
for issues that are present in the aforementioned flavors but aren't in the Wine fork
included in Proton. Fixes from said fork are expected to the ported over to "unstable"
and later "stable". Do not expect this flavor to be maintained in the long term.

---

<!-- CYTECH_STAR_HISTORY:START -->

## Star History

<a href="https://star-history.dera.page/#Namnarak/AuroraWine&type=date&legend=top-left">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://star-history.dera.page/svg?repos=Namnarak/AuroraWine&type=date&legend=top-left&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://star-history.dera.page/svg?repos=Namnarak/AuroraWine&type=date&legend=top-left" />
    <img alt="GitHub star history for Namnarak/AuroraWine" src="https://star-history.dera.page/svg?repos=Namnarak/AuroraWine&type=date&legend=top-left" width="800" />
  </picture>
</a>

<!-- CYTECH_STAR_HISTORY:END -->
