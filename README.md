# kal-gta3_rebuild
A rebuilding of the GTA3 PS2 Kalisto Release .CUE/.BIN file from DVD ISO version.
  
# 0.WHY??????????
  

It's fun!   
Seeing GTA3 running on PS2 CD.   
The .cue/.bin files are a lost from the digital abyss known as WWW.    
It would be a good exercise to the optical drive after a tune up with PMAP or greasing up with lube.   
Bad laser that can only read CD.
  
  
# 1.How to use
  You'll need get  
   Win10/Win7 or WinXP computer. It's not tested on Wine or Win11, but it SHOULDa work.   
   A good internet connection for Archive dot org.  
   A very low speed CD burnner, 4X would work the best, 16X would work but some SF-HD7 or PWR-803W ops. might not like discs burnt at 16X.  
   A PS2, perferibly with KHS-400C, with Matrix Infinty mod chip or its clones.  
   Any CD-R. As cheap as you can get. You might need a lot of them and they can't be all that bad, so long as you'd burn at low speed.  
   BR~~.A.I.N~~S! (There's a zombie at my lawn~ )  
  
  
 Steps:    
  a.clone/download the whole repo.  
  b.get KAL-GTA3.iso (no CRC32?? :P ) from Archive dot org  
  c.get the tools in ./TOOLS folder. Extract or download somewhere else. (see README.md in the folder)  
  d.Extract the KAL-GTA3.iso into the ./KAL-GTA3 folder, overwrite the place holding file/folders.  
  e.Open CDGenPS2.exe.  
     Click 'Advanced' --- 'Import Tree File from IsoBuster'  
     Make sure the Sleect mode is 'Import by LB'(A?), then click 'OK'  
   You should now see all the files in the folder mapped in the window. If not check the steps.  
     Click 'File' --- 'Edit Volume'  
     Change the 'Name' from 'USERS' to 'SLUS_200_62', click 'OK'  
     Click 'File' --- 'Save Image', make sure the file type is '.bin', save the image.  
  
  You now have an image that can work with MI and maybe other mod chips. To patch in the PS2 logo, it's optional to use DiscPatcher3 to patch the image.  
    Open up the software, select the .bin file, click 'Patch'.  
  
  
Now burn the disc at low speed and have fun.
  
  
# Other notes.  
  
Look me up if you've found KAL-VICE!!!  
  
'If one really wants a ready-to-burn image?'  
  File an issue, I'd gladly send you something nice. wink wink.   
  If you have a way to upload archive dot org, pls do upload it there.  
   
It'll read your NTSC/U saves.  
 
You'll need to skip the 1st cut-secen to load the game if no savefile or MC.  
 All the quirks are well documented somewhere.  

!!!No warranty!!!  
Do note that even if it's burnt at 4X resulting a lower jitter, it's still combinning the mod chip, at a greater risk of triggering the mechcon crash when playing.     
Note that any backups or unoffical-pressed badly-scrached disc has this effects on 39000x GH-019 onwards PS2s.   
You should look at Matrix-PIC fix if you don't care for huffing enamel smoke.  
(F.Y.I. Don't play games on DVD-+RW, ask me how I konw.)  


https://archive.md/20201112142148/https://www.obscuregamers.com/threads/how-to-create-a-working-playstation-2-master-cd-r-or-dvd-r-image.772/



  
