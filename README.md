archiso
=======
Caution : This is just my fork of the original project here : https://github.com/EvoLutionLinux/archiso

Since the project moved its focus from Evo/Lution to Makeiso. I have
forked the repo to maintain this for my own needs.

Right now i'm only making changes to make sure I can still build the
Evolution ISO using this, so it should not be very different from what
you expect it to be. But sometime in the future I might start
tweaking this and customizing it for my own needs.

**USAGE INSTRUCTIONS:**

On an Archlinux Box

1. Install archiso 

        packman -S archiso
2. Clone the repo

        git clone git@github.com:surdy/archiso.git
3.  Execute build.sh

        usage build.sh [options]
                                                                 
        General options:
           -N <iso_name>      Set an iso filename (prefix)
                               Default: evolution 
           -V <iso_version>   Set an iso version (in filename)
                               Default: <YYYY.MM.DD> 
           -L <iso_label>     Set an iso label (disk label)
                               Default: Evolution-<YYMM>-64bit
           -D <install_dir>   Set an install_dir (directory inside iso)
                               Default: arch
           -w <work_dir>      Set the working dir
                               Default: work
           -o <out_dir>       Set the output dire
                               Default: out
           -v                 Enable verbose outp
           -h                 This help message
