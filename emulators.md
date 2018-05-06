<hr size="10">

| [ Home ](index.html) | [ Media ID Guide ](media_ID.html) | [ Operating Systems ](operating_systems.html) | [ Emulation ](emulators.html) | [ Resources ](resources.html) |
<hr size="10">

# What is emulation?
Emulation is essentially a way of tricking a **host** computer into running a **guest** [operating system](operating_systems.html) that it was not "meant" to run. This could mean running Mac OS 7 on a 2016 iMac that natively runs MacOS Sierra, running MS-DOS on a Dell laptop natively running Windows 10, running Windows 95 on a modern day Mac or PC, etc.

The idea here is that if you're trying to render old files (e.g. photos, documents, programs, videos, etc.) that you retrieved from obsolete removable media :
&nbsp; &nbsp; &nbsp; &nbsp; **a)** they may not render (or render correctly) on your modern computing system, and if that's the case then
&nbsp; &nbsp; &nbsp; &nbsp; **b)** you probably don't have access to the legacy computing environment (hardware and operating system)
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;for which the files were intended.

The solution is to **EMULATE** the required operating system (and the hardware it ran on) on the computer that you have now.

**NOTE:** _**emulation**_ is different than _**virtualization**_. There are many types of <a href="https://en.wikipedia.org/wiki/Virtualization" target="_blank">virtualization</a>, but in the context of obsolete removable media, the term typically refers to creating a "virtual machine" on your current hardware to run software that is **still compatible** with the hardware it's running on. An example of this is using a guest <a href="https://bitcurator.net/BitCurator" target="_blank">BitCurator</a> Linux distribution on your present-day Mac or PC. **Emulation**, on the other hand, simulates a **complete computing environment:** an operating system and the original hardware architecture on which it ran. [I'm iffy on this explanation in all contexts.]

#####  A note about BitCurator:
<a href="https://bitcurator.net/BitCurator" target="_blank">BitCurator</a> is not an emulator like those listed below, but it should be considered here. The <a href="https://confluence.educopia.org/display/BC/BitCurator+Environment" target="_blank">BitCurator environment </a> is a suite of open-source tools, designed by librarians and archivists, to process born-digital materials in a forensic manner. BitCurator can be used to safely mount, disk image, and analyze obsolete removable media. It is extremely well-documented.



### Selecting an emulator:
There are different emulating applications for different operating systems/hardware architectures. These applications come with varying levels of pre-configuration and compilation. There are MANY emulators out there, but here are some well-documented ones to get you started:


* #### Mac OS
 * <a href="http://sheepshaver.cebix.net/" target="_blank">SheepShaver</a> – emulates a <a href="https://en.wikipedia.org/wiki/Power_Macintosh" target="_blank">PowerPC Mac</a> (MacOS 7.5.2 through 9.0.4)
   * can be hosted on the following systems:
     * Mac OS X (PowerPC and Intel)
     * Windows NT/2000/XP
     * Unix with X11 (Linux i386/x86_64/ppc, NetBSD 2.x, FreeBSD 3.x)
     * BeOS R4/R5 (PowerPC)
 * <a href="https://basilisk.cebix.net/" target="_blank">Basillisk II</a> – emulates a <a href="https://en.wikipedia.org/wiki/Macintosh_Classic" target="_blank">Mac Classic</a> (MacOS 0.x thru 7.5) or a <a href="https://en.wikipedia.org/wiki/Macintosh_II_family" target="_blank">Mac II</a> (MacOS 7.x, 8.0, 8.1)
   * can be hosted on the following systems:
     * Mac OS X (PowerPC and Intel)
     * Windows NT/2000/XP
     * Unix with X11 (Linux i386/x86_64, Solaris 2.5, FreeBSD 3.x, IRIX 6.5)
     * BeOS R4/R5 (PowerPC)
     * AmigaOS 3.x
 * <a href="http://www.gryphel.com/c/minivmac/index.html" target ="_blank">Mini vMac</a> variations for
<a href="https://en.wikipedia.org/wiki/Macintosh_128K" target = _blank> Mac 128K</a>,
<a href="https://en.wikipedia.org/wiki/Macintosh_512K" target = _blank> Mac 512K</a>,
<a href="https://en.wikipedia.org/wiki/Macintosh_512Ke" target = _blank> Mac 512Ke</a>,
<a href="https://en.wikipedia.org/wiki/Macintosh_Plus" target = _blank> Mac Plus</a>,
<a href="https://en.wikipedia.org/wiki/Macintosh_SE" target="_blank">Mac SE</a>,
<a href="https://en.wikipedia.org/wiki/Macintosh_Classic" target="_blank">Mac Classic</a>,
<a href="https://en.wikipedia.org/wiki/Macintosh_II_family" target="_blank">Mac II</a>
   * can be hosted on the following systems:
     * Mac OS X
     * Windows
     * Linux
     * FreeBSD
     * NetBSD
     * OpenIndiana
* #### Windows
 * <a href="https://www.qemu.org/" target="_blank">QEMU</a> - a generic emulator that has the ability to emulate _any_ guest computing environment (operating system and hardware) on any other host, but is most often hosted on Linux.

* #### DOS
 * <a href="https://sourceforge.net/projects/dosbox/" target ="_blank">DOSBox</a> – emulates MS-DOS using the command line. Primary use is to run old computer games. Start <a href="https://www.dosbox.com/wiki/Basic_Setup_and_Installation_of_DosBox" target ="_blank">here</a>.
    * can be hosted on the following systems:
      * Mac OS X
      * Windows
      * Linux
      * Others with less documentation

## Putting together an emulator:
Emulators are assembled  of several pieces, and different emulating applications will require different levels of user involvement to put them together. The documentation for the application should walk you through the process. You will likely need to gather these three critical components before you start:
* **Emulating Application – ** open source and downloadable
  * <a href="http://sheepshaver.cebix.net/#download" target="_blank">SheepShaver</a>
  * <a href="https://basilisk.cebix.net/#download" target="_blank">Basillisk II</a>
  * <a href="http://www.gryphel.com/c/minivmac/dnld_std.html" target ="_blank">Mini vMac</a>
  * <a href="https://www.qemu.org/download/" target="_blank">QEMU</a>
  * <a href="https://sourceforge.net/projects/dosbox/" target ="_blank">DOSBox</a>  
  <br>
* ***Operating System Installer – ** this is an installation disk of the OS  you want to emulate (could be a physical object or a downloaded disk image)
 * <a href="https://winworldpc.com/library/operating-systemsWinWorld" target="_blank">WinWorld</a> – library of operating system disk images for download
  * <a href="https://archive.org/details/cdromsoftware" target="_blank">Internet Archive CD-ROM Software Library</a> – includes many operating system disk images for download  
<br>
* ***ROM File –**  this is an extractable or downloadable file that will mimic data contained in a read-only memory chip from a compatible piece of legacy hardware.
  * <a href="https://github.com/macmade/Macintosh-ROMs" target="_blank">Macintosh-ROMs</a> – collection of obsolete Macintosh ROM files.
  *   <a href="hhttp://www.redundantrobot.com/sheepshaver.html" target="_blank">Redunant Robot</a> – Mac ROMs to use with SheepShaver and Basillisk II
  * <a href="https://archive.org/details/mac_rom_archive_-_as_of_8-19-2011" target="_blank">Internet Archive Mac ROM Archive</a> – collection of obsolete Mac ROM files
  * [Not sure if PC emulators require a ROM in the same way]

***NOTE:** Operating system installation disks and ROMs are under copyright. Unfortunately, it's often not possible to purchase them anymore. In an effort to promote digital preservation, many users have shared disk images of this "abandonware" on the internet.
