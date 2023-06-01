# Hi, I'm Vili

I'm an amateur programmer, artist, and musician

I primarily program in <b>C</b>, and also know (varying amounts of) <b>HTML</b>, <b>Python</b>, <b>C#</b>, <b>Java</b>, and a <i>tiny</i> bit of <b>JS</b> and <b>Lua</b>

Most of my work revolves around Linux and other UNIX-based OSes (personal fan of OpenBSD, Minix, etc...)

Programs I write will be intended for Linux, as it is what I use daily, however I will attempt to port them to Windows, and potentially BSD and MacOS

# Works In Progress

<details>
  <summary> ALFS Scripts </summary>
  <b>STATUS: WIP - getting OpenRC to work, info soon</b>
  
  A script to install a heavily customised LinuxFromScratch (+BLFS) build
  
  Fully desktop-capable, however with no DE/WM preinstalled (Xorg & dependencies are included)
  
  -    OpenRC init system ontop of sysvinit
  -    RPM package manager (with a guide for building packages)
  -    UEFI boot capable
  
  
</details>

<details>
  <summary> Tiny Linux Distribution </summary>
  <b>STATUS: WIP - working on getting Musl to work properly as the main C library</b>
  
  -    Busybox as init and the core utilities - static build against Musl, with symlinks to /bin for individual programs
  -    Glibc alongside Musl-libc
    -    GCC, Musl-gcc, and Clang/LLVM
  -    Accounts & account/auth management (PAM, passwd, select coreutils, OpenDoas)
  -    Grub, installed for both i386-pc (bios) and x86_64-efi
  -    Less than 100MB installed size

</details>

<details>
  <summary> Tar-based Package Manager </summary>
  <b>STATUS: concept</b>
  
  Intended for LinuxFromScratch and other independent Linux distributions
  
  Made to have as few dependencies as possible, to be simple to build
  
  Details soon...
  
</details>

<details>
  <summary> A game </summary>
  <b>STATUS: Animation, music, and sound work first.</b>
  
  Keeping this mostly secret for now, I'll give details when it's presentable.
  
  Working on everything myself in the Godot game engine (C#, using C for some basic data handling)
</details>
