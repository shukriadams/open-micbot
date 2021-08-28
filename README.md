# open-micbot

Motorized, remote-controllable unit to automate positioning of mic. Intended as a studio aid for guitar amp micing.

- fully open source - all electronics, STLs, etc
- supports 2 planes of movement (x, z) and yaw in two axes. Y is not supported to simplify design, and because it's not necessary, as all theoretical cone positions are covered by just x + z.
- supports replicatable amp-relative positioning - if place centered to a speaker cap and leveled, will reproduce the same results if torn down and relaced.
- must be assembled from 3d printable parts, or wood. All electronics, joints etc must be easily procured parts
- must be simple enough for someone with basic technical skills to build
- controlled by arduino + pi, or equivalents. Should not require specialized PCBs or controllers
- usb powered (5v)
- can support bluetooth connections from mobile phones
- has a mobile phone app for android + iphone, also open source
- can be controlled from a pc over wifi or ethernet. can allow remote control so someone else can help you mic a good sound.
- can save + replay mic positioning profiles. profiles are single files with metadata that can easily be shared between people.
- can support weight of standard mics, can be weighed down easily for stability
- has universal mic-stand screw
- small enough to allow two units to operate side-by-side on a single 12" speaker, meaning must allow mic to be positioned at edge of unit
- step-by-step assembly guide with plenty of checks to ensure each stage works, and troubleshooting.
- must be broken down into separate units / sub-projects. Each sub-system can be swapped out and iterated up without requiring changes to other sub-systems, or with only minor adjustments to settings. 
- extremely simple calibration, lots of built-in diagnostics, the target audience is musicians, assume they are not interested in modding / tinkering.
