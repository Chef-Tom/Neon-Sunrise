# Revisiting the NEON Sunrise 65816 project

In 2020 and through 2021, I started dreaming of a community 65816 based computer.
And about the same time The 8-Bit Guy announced the Commander X16.
At first I was excited.  But then he went the FPGA route for the video.
Which kind of took the wind out of the sails for me with it.  That video chip has more power than the rest of the computer.
But I kept watching Ben Eater's videos, and learning how the 6502 worked.
And I followed along with Adrien Kohlbecker's BB816 project.
Now I'm *[definitely not]* ready to try this again!

# Project Goals
*I've kept the goals the same for now, but more than willing to adjust them.*

- All parts must be off-the-shelf or at least easy to obtain. And no FPGAs.
- There may end up being some programmable logic chips, but they’d just be to consolidate 7400 series logic chips, and would be no more complex than 22V10 GALs.
- Open source architecture, hardware, and software.
  - Everything will be open source with this.  I’ll put snapshots up in my GitHub as we go along, so anyone following the videos can see what happened at each step, but the main branch will be live and fully accessible, branchable, and hopefully inspiring.
- Keyboard input, VGA output
  - This is going to be some of the harder bits to work out, but I do want this to be full standalone by the time we are done.
  - I have a dream of where I’d like to get this, but I know just about nothing on this front.
- ATX Power
- LCD Status Display (system status, clock/uptime)
- 4MHz system bus.
- Boots to a usable state (FORTH, BASIC, or other command line)
  - Ideally I’d like to have the ROM load to a BASIC that can fully use the 65186.
- User Hackable
  - Pin Headers
  - Expansion slots
  - Open Source

