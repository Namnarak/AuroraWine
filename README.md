# AuroraWine

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
