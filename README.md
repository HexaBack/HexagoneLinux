# Hexagone Linux
Check **Releases** every month or so for updated system images.

This is a little passion project of mine, so these early builds might not be as stable as other systems out there. However, over time, it should get more stable and polished up as more people leave feedback. So, yes, you, please test out HL and let me know of what I should add/change/fix (HL serves a very niche and specific use-case - old fashioned computing; so please don't complain that the system is "too difficult", otherwise HL might not be a good choice for you. But if you love old computers and how their operating systems worked, you're in luck, as that is exactly what HL is trying to accomplish!).

# TODO
 - Make some Welcome Tour type of application on first boot
 - Make a better installer
 - Make a prettier README
 - Make a website for Hexagone Linux

# How I made Hexagone Linux
I made a modified base BookwormPup64 image with just plain Debian, not even a desktop. Then I installed the TDE Desktop and some TDE software I thought would be useful, configured every setting there is in hopes of making the desktop experience feel smoother. Package all the changes into a new hl-main-*.sfs file, then package that with the other .sfs files into an ISO, test in a VM, rinse and repeat.

I really don't know what to put in READMEs so sorry if it feels a little rambly
