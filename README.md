# awesome-incident-response
A curated list of tools for incident response

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

- [Disk Image Creation Tools](#disk-image-creation-tools)
- [Memory Analysis Tools](#memory-analysis-tools)
- [Memory Imaging Tools](#memory-imaging-tools)
- [Process Dump Tools](#process-dump-tools)
- [Timeline tools](#timeline-tools)
- [All in one tools](#all-in-one-tools)
- [Videos](#videos)

## IR tools Collection

### Disk Image Creation Tools

* [GetData Forensic Imager](http://www.forensicimager.com/) - GetData Forensic Imager is a Windows based program that will acquire, convert, or verify a forensic image in one of the following common forensic file formats
* [Guymager](http://guymager.sourceforge.net) - Guymager is a free forensic imager for media acquisition on Linux
* [AccessData FTK Imager](http://accessdata.com/support/adownloads#FTKImager) - AccessData FTK Imager is a forensics tool whose main purpose is to preview recoverable data from a disk of any kind. FTK Imager can also acquire live memory and paging file on 32bit and 64bit systems

### Memory Analysis Tools
* [Volatility](https://github.com/volatilityfoundation/volatility) - An advanced memory forensics framework
* [Evolve](https://github.com/JamesHabben/evolve) - Web interface for the Volatility Memory Forensics Framework
* [WindowsSCOPE](http://www.windowsscope.com/index.php?page=shop.product_details&flypage=flypage.tpl&product_id=35&category_id=3&option=com_virtuemart) - another memory forensics and reverse engineering tool used for analyzing volatile memory. It is basically used for reverse engineering of malwares. It provides the capability of analyzing the Windows kernel, drivers, DLLs, virtual and physical memory
* [Responder PRO](http://www.countertack.com/responder-pro) - Responder PRO is the industry standard physical memory and automated malware analysis solution
* [KnTList](http://www.gmgsystemsinc.com/knttools/) - Computer memory analysis tools 

### Memory Imaging Tools
* [OSForensics](http://www.osforensics.com/) - OSForensics can acquire live memory on 32bit and 64bit systems. A dump of an individual process’s memory space or physical memory dump can be done
* [Belkasoft Live RAM Capturer](http://forensic.belkasoft.com/en/ram-capturer) - A tiny free forensic tool to reliably extract the entire content of the computer’s volatile memory – even if protected by an active anti-debugging or anti-dumping system

### Process Dump Tools
* [PMDump](http://ntsecurity.nu/toolbox/pmdump/) - PMDump is a tool that lets you dump the memory contents of a process to a file without stopping the process
* [Microsoft User Mode Process Dumper](http://www.microsoft.com/en-us/download/details.aspx?id=4060) - The User Mode Process Dumper (userdump) dumps any running Win32 processes memory image on the fly

### Timeline tools
* [Plaso](https://github.com/log2timeline/plaso) -  a Python-based backend engine for the tool log2timeline
* [Timesketch](https://github.com/google/timesketch) -open source tool for collaborative forensic timeline analysis

### All in one Tools
* [X-Ways Forensics](http://www.x-ways.net/forensics/) - X-Ways is a forensics tool for Disk cloning and imaging. It can be used to find deleted files and disk analysis
* [The Sleuth Kit & Autopsy](http://www.sleuthkit.org) - The Sleuth Kit is a Unix and Windows based tool which helps in forensic analysis of computers. It comes with various tools which helps in digital forensics. These tools help in analyzing disk images, performing in-depth analysis of file systems, and various other things
* [Open Computer Forensics Architecture](http://sourceforge.net/projects/ocfa/) - Open Computer Forensics Architecture (OCFA) is another popular distributed open-source computer forensics framework. This framework was built on Linux platform and uses postgreSQL database for storing data
* [Digital Forensics Framework](http://www.arxsys.fr/discover/) - DFF is an Open Source computer forensics platform built on top of a dedicated Application Programming Interface (API). DFF proposes an alternative to the aging digital forensics solutions used today. Designed for simple use and automation, the DFF interface guides the user through the main steps of a digital investigation so it can be used by both professional and non-expert to quickly and easily conduct a digital investigations and perform incident response
* [Osquery](https://osquery.io/) - with osquery you can easily ask questions about your Linux and OSX infrastructure. Whether your goal is intrusion detection, infrastructure reliability, or compliance, osquery gives you the ability to empower and inform a broad set of organizations within your company. Queries in the *incident-response pack* help you detect and respond to breaches. 
* [MozDef](https://github.com/jeffbryner/MozDef) - The Mozilla Defense Platform (MozDef) seeks to automate the security incident handling process and facilitate the real-time activities of incident handlers.
* [GRR Rapid Response](https://github.com/google/grr) - GRR Rapid Response is an incident response framework focused on remote live forensics. It consists of a python agent (client) that is installed on target systems, and a python server infrastructure that can manage and talk to the agent.
* [MIG](http://mig.mozilla.org/) - Mozilla Investigator (MIG) is a platform to perform investigative surgery on remote endpoints. It enables investigators to obtain information from large numbers of systems in parallel, thus accelerating investigation of incidents and day-to-day operations security.


### Videos
* [Demisto IR video resources](https://www.demisto.com/videos/) - Video Resources for Incident Response and Forensics Tools
