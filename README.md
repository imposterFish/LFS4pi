# LFS4pi
My take/experience on a Linux From Scratch project for my RPi4.  

# Guides, Sources, Materials, and anything I found useful
[PiLFS](https://intestinate.com/pilfs/)  
[CLFS](https://clfs.org/view/clfs-embedded/arm/)
[LFS](https://www.linuxfromscratch.org/lfs/)  

# My Set-up
- My personal computer - where I cross compile :)  
- My Raspberry Pi 4.

# My Journey
[The Big Choice](https://intestinate.com/pilfs/guide.html) - None of the above. The PiLFS guide assumes that you want to build on the Pi. I don't.

## Host set-up
The CLFS guide...
I just set up my machine according to the [CLFS](https://clfs.org/view/clfs-embedded/arm/introduction/hostreqs.html) guide.  

### Part I
1. Check required tools. Use `<tool name> --version`
2. Or use the script on the guide to check...
3. These things may be helpful(?)
   - The version of the book being used (in this case CLFS Embedded GIT-20190419).
   -  The value of the ${CLFS_TARGET}, and ${BUILD} environment variables.
   -  TODO Mention any deviation from CLFS.

### Part II - Preparing for the Build
- I made my direcotry `/mnt/clfspi4`
- 'Assign it to the CLFS environment variable'... I followed that direction, but I think that CLFSPI4 would have been better.
- Really, more packages?

# My personal thoughts, ideas, Unimportant TODOs, ...
- Apparently building for the pi zero, on the pi zero takes 60 hours!!! I want to subject myself to that, I think. 
