# About Me
...
# Works In Progress
No specific due date on these; Just things I'm working on or planning to make


LinuxFromScratch (ALFS) scripts

-   working OpenRC init system ontop of sysvinit
-   working RPM package manager, with a few test binaries (sudo, musl, busybox, etc...)
-   working networking (dhcpcd, wpa_supplicant, Links browser, etc...)

----

Small busybox/linux with Musl-libc install scripts

-   Musl with musl-gcc
-   Busybox with symlinks in /bin, statically built
-   Pre-installed firmware (to a reasonable extent)
-   Both BIOS and UEFI boot capability

Custom tarball-based package manager (intended for LinuxFromScratch)

-   Package installs and removal
    *   Ability to specify a static or dynamically-linked binary - musl AND glibc
-   Updates (from remote OR local [user-specified] repository - using wget)
    *   Repository not included
-   Upgrades (Uninstalling old, installing new versions)
    *   Rebuild other packages ontop of new versions of others
-   Documentation on how to package a program
    *   Included example packages, as well as the scripts used to build them
    *   Suggestions for other packages, and additional resources
