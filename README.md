# atarigamer (Skip to the end for GitHub info.)
#
# From the software author: Aaron Bergstrom
#    First, Atari is still it's own company,
#    so I should say that I should probably 
#    change the name of the software. I'm 
#    aware of that... so maybe in the future.
# 
# Background AtariGamer
# ============================
# I began writing this program back in early 
# 2002, and I probably stopped working on it
# around early 2005. I was in grad school at
# the time and my brother had died less than 
# two years before. 9/11 had only happened 
# 6-7 months before I began working on this 
# and it was fresh on everyone's mind.
#
# As such, the software was probably a
# mechanism for me to process grief. I had
# burried the grief of my brother's death
# and had distracted myself from it by
# focusing on my work. But 9/11 was a slap
# in the face of everyone, and the thought
# of all those families having to deal with
# the instantaneious death of their loved
# ones, brought all my personal grief
# pouring back.
#
# To deal with my grief and try to reconnect
# with my brother, I started collecting
# Atari games, and I became facinated by the
# fact that people were still making 2600
# homebrew games, and I wanted to do it too.
# Yet, I just don't have the patients for the
# text arts, and I found it difficult to make
# sense of the of the 2600 hardware.
#
# So to address that issue, I decided to create
# tools to make the process easier for me to
# understand. This is something I have done
# several times over my career. Most notably,
# my RawKee plugin for Maya is the best example
# of this.
#
# Why Did I Stop Working On AtariGamer?
# =============================
# Well, by 2005 AtariGamer and homebrew had become 
# an obsession for me, and that's not a good thing
# when you're in grad school. Also my marriage at
# the time wasn't going well either. As such, I 
# decided to take a break of few months so I could
# focus on grad school and my marriage. Needless to 
# say, a few months became a year, and then I 
# graduated, got divorced, yadda, yadda, yadda, you 
# all know how it goes.
#
# Why Are You Releasing It Now?
# =============================
# I actually hadn't given it much thought since 2008,
# but I stared dabbling again in Maya software plugins,
# so I logged back on to SourceForge to look at my old
# RawKee code for some pointers, only to notice that
# my VCS Graphics Editor software was being downloaded
# on a regular basis.
#
# There's like 4 different versions of the AtariGamer 
# development environment, of which VCSGE is just one. 
# I thought I had uploaded to most robust version to 
# SourceForge, but apparently that was not the case.
# In fact the version on Source Forge is probably the
# least developed version of AtariGamer, and not
# usable at all.
#
# Once I realized this, I felt kind of bad about it.
# The downloads for VCSGE are not atronomical, but
# they range from 5-25 per month. Over 700 since I 
# first put it online. I felt like I cheated a bunch
# of fellow Atari enthusiasts. So I decided to dig
# out the most robust version of the software, it
# had the following features:
# ----
# 1) Robust Playfield Editor with Photoshop-like
#    paint tools for drawing and translating these
#    brush strokes into PF0, PF1, & PF2 register
#    byte format.
# 2) Robust Sprite Editor with Photoshop-like
#    paint tools for drawign and translating brush
#    strokes into playfield graphics.
# 3) A multi-scanline NTSC/PAL/SECAM color chooser 
#    which could be applied to playfield and sprite
#    graphics.
# 4) Playfield and sprite graphics had their own
#    file formats that could be saved and reopened
#    in a usable state.
# 5) Paint tools actually had a usable Text tool
#    with the ability to use whatever font was
#    on your system to draw a rough approximation
#    of the text into your playfield and sprite
#    registers.
# 6) Built in ASM editor (basically just a simple 
#    Java text editor) that was integrated DASM, 
#    into the development pipeline so you could 
#    save your ASM, and immediately assemble a BIN 
#    with DASM and then run the BIN using Stella
#    all with a single button push.
# 7) It had a console that would capture DASM and 
#    Stella output, so you could immediately see
#    errors.
# 8) It had a basic Java-based WebBrowser so you 
#    could have your favorite development page 
#    open while you work.
#
# AtariGamer had progressed to the point where I 
# was actually using it for real homebrew 
# development. If I didn't have to work, or go
# to school, or fight with my wife, I probably 
# would have actually used it to produce a game.
#
# 10 Years Is A Long Time
# ===============================
# But it had been a really long (aka 2005) since 
# I had really looked at any of this, and 
# needless to say, I didn't know where any of 
# the more robust code was at anymore.
#
# After about a week of looking, I finally found
# the damaged IDE drive with one of the more
# robust versions of AtariGamer on it. 
# Unfortunately, it wasn't the super awesome
# everything is working version, but it's way 
# more than what is on the VCSGE SourgeForge
# site.
#
# So with a fresh start, I've put what I've found
# up on GitHub under:
# https://github.com/flickertail/atarigamer.git
# 
# Grab it if you want it. Use at your own risk.
# 
# AtariGamer uses the old Sun Microsystems
# Graphics Layer Framework" API, or glf.jar.
# I placed a copy of it in the repo as part 
# of the Eclipse project. In fact the repo
# is basically an Eclipse project folder.
#
# If you don't trust that this glf.jar is
# safe, you can also download it from DocJar.com,
# which is where I got it from recently.
#
# Lots of things are broken, but I plan to 
# start fixing them, though it will happen 
# slowly. Let me put a bit of extra emphasis
# on the word "slowly". Basically, this version 
# compiles and does simple single-line color 
# choosing. Other than that it does very little.
# Once I can start fixing features and producing
# content with it, I'll start making YouTube
# tutorials.
#
# Any updates, I'll put out through my AtariAge
# blog, where my forum name is "flickertail",
# after my defunct video game company,
# Flickertail Interactive.