# Welcome to SIPVicious OSS security tools

The SIPVicious OSS toolset consists of the following tools:

- svmap
- svwar
- svcrack
- svreport
- svcrash

![SIPVicious mascot](https://blog.sipvicious.com/images/sipvicious.png)

## The tools

### svmap

	this is a sip scanner. When launched against
	ranges of ip address space, it will identify any SIP servers 
	which it finds on the way. Also has the option to scan hosts 
	on ranges of ports.

### svwar

	identifies working extension lines on a PBX. A working 
	extension is one that can be registered. 
	Also tells you if the extension line requires authentication or not. 

### svcrack
	
	a password cracker making use of digest authentication. 
	It is able to crack passwords on both registrar servers and proxy 
	servers. Current cracking modes are either numeric ranges or
	words from dictionary files.

### svreport

	able to manage sessions created by the rest of the tools
	and export to pdf, xml, csv and plain text.

### svcrash
	
	responds to svwar and svcrack SIP messages with a message that
	causes old versions to crash. 

For usage help make use of `-h` or `--help` switch. Full usage help can be found on our [Wiki](https://github.com/EnableSecurity/sipvicious/wiki).

A getting started post can be found on the Communication Breakdown blog: [Attacking a real VoIP System with SIPVicious OSS](https://www.rtcsec.com/2020/06/02-attacking-voip-system-with-sipvicious/).

## Installation

Please refer to the [installation documentation](https://github.com/EnableSecurity/sipvicious/wiki/Basics#installation).

## A note to vendors and service providers

If you are looking for a professional grade toolset to test your RTC systems, please consider [SIPVicious PRO](https://www.sipvicious.pro) which is available as a closed beta version.

## Further information

Check out the [wiki](https://github.com/enablesecurity/sipvicious/wiki) for documentation.

