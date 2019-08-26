# ucc - Unattended Cross Compiler
I simply got tired of building a new i686-elf cross compiler for every development machine I used :/  

I made this build script locally before uploading it here, that's so I don't have to carry a USB stick around with me constantly with the shell script on it. You can use --clean or -c to delete the downloaded and compiled sources (after they've been installed), and --download or -dl to download just the sources of the specified versions of GCC, binutils, and GDB.  
  
If you just want a bog-standard i686-elf-gcc cross compiler with binutils and GDB too, then simply run:  
```
git clone https://github.com/Arawn-Davies/ucc/ && cd ucc  
chmod +x deploy.sh  
./deploy.sh  
```  
  
If you don't even want to bother cloning the source, 'cause you're that so much of a 1337 h4ck3r, then run:  
```  
wget https://raw.githubusercontent.com/Arawn-Davies/ucc/master/deploy.sh && chmod +x deploy.sh && ./deploy.sh
```  
