# Reasoning

Jellyfin stopped support for its Qt based desktop client (this package), before the CEF based replacement was ready to ship.  
Consequently, this is the only working desktop client, but it does not recieve fixes anymore.  
In version `1.2.0` the dependency `mpvqt` changed a parameter type from `QVariant` to `QStringList` in [#b3dbc4b](https://github.com/KDE/mpvqt/commit/b3dbc4b1f51121da81865ca051eaa8f8a63e3f15).  
The patch `fix_mpvqt.patch` contains the required changes for `jellyfin-desktop` to support this version.

# Using

`repo.patch` contains the alterations to the AUR-repo required to use this patch.  
`PKGBUILD` already has the patch applied.
