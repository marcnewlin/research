### Here you will find my public facing research, whitepapers, open source projects, and conference talks. 

# Research

## MouseJack / KeySniffer

MouseJack was my first vulnerability research project, resulting in a bunch of keystroke 
injection vulnerabilities affecting non-Bluetooth wireless mice from many first-tier vendors.  

KeySniffer followed a few months later, resulting more keystroke injection vulnerabilities 
affecting wireless mice and keyboards, as well as a set of keystroke sniffing vulnerabilities 
affecting a number of unencrypted wireless keyboards. 

As part of this project, I developed research firmware for nRF24LU1+ USB dongles. This enables
simple sniffing and packet injection for nRF24LU1+ compatible devies. The firmware can be flashed 
to a variety of nRF24LU1+ USB dongles, including Logitech Unifying dongles. 

- [nRF24LU1+ research firmware](https://github.com/BastilleResearch/nrf-research-firmware/tree/master)
- [DEF CON 24 whitepaper](https://github.com/BastilleResearch/mousejack/blob/master/doc/pdf/DEFCON-24-Marc-Newlin-MouseJack-Injecting-Keystrokes-Into-Wireless-Mice.whitepaper.pdf)
- [DEF CON 24 slide deck](https://github.com/BastilleResearch/mousejack/blob/master/doc/pdf/DEFCON-24-Marc-Newlin-MouseJack-Injecting-Keystrokes-Into-Wireless-Mice.slides.pdf)
- [DEF CON 24 talk video](https://www.youtube.com/watch?v=00A36VABIA4)
- [MouseJack vulnerability advisories](https://github.com/BastilleResearch/mousejack/tree/master/doc/advisories)
- [KeySniffer vulnerability advisories](https://github.com/BastilleResearch/keysniffer/tree/master/doc/advisories)

I also presented versions of this talk at ToorCon 2017, Hack Con 2017, Georgia Tech, Kennesaw State University, and eyeo GmbH.

# Open Source Projects

## gr-nordic

As part of my MouseJack/KeySniffer research, I released an open source GNU Radio module enabling two-way 
communication with nRF24L-based devices. 

- [gr-nordic source](https://github.com/BastilleResearch/gr-nordic)

## MouseJack NES Controller

As a precursor to the MouseJack project, I built a wireless NES controller which can hijack nearby Logitech wireless mice, 
enabling you to control the victim's cursor with the d-pad, and right and left click with the A/B buttons. 

- [MouseJack NES Controller source and build guide](https://github.com/marcnewlin/mousejack-nes-controller)

## 1024 LED Top Hat

I really like bright and shiny LED projects, so I made a Teensy-controlled top hat covered with a matrix of 
1024 addressable LEDs. 

- [1024 LED Top Hat source and build guide](https://github.com/marcnewlin/led-top-hat)

# Conference Talks

## So You Want To Hack Radios

Matt Knight and I developed a series of talks titled "So You Want To Hack Radios."

Our thesis is that RF reverse engineering (and SDRs in general) scare people more than they should, 
so we formalized our reverse engineering methodology in order to demonstrate that this stuff isn't actually 
wizardry. 

- [So You Want To Hack Radios @ HITB 2017 slide deck](http://conference.hitb.org/hitbsecconf2017ams/materials/D1T4%20-%20Marc%20Newlin%20and%20Matt%20Knight%20-%20So%20You%20Want%20to%20Hack%20Radios.pdf)
- [So You Want To Hack Radios @ HITB 2017 talk video](https://www.youtube.com/watch?v=QeoGQwT0Z1Y)

We also presented versions of this talk at ShmooCon 2017 and TROOPERS17.

## OSINT RF Reverse Engineering

I am a bit of an OSINT nerd, and lean on it heavily when reverse engineering wireless devices, so I gave a talk 
on applying regulatory data (i.e. FCC application exhibits) to the RF reverse engineering process.

- [OSINT RF Reverse Engineering @ HITB 2016 slide deck](https://conference.hitb.org/hitbsecconf2016ams/materials/D1%20COMMSEC%20-%20Marc%20Newlin%20-%20Applying%20Regulatory%20Data%20to%20IoT%20RF%20Reverse%20Engineering.pdf)
- [OSINT RF Reverse Engineering @ HITB 2016 talk video](https://www.youtube.com/watch?v=JUAiav674D8)

I also presented versions of this talk at Jailbreak Security Summit 2016 and TakeDownCon Rocket City 2016. 
