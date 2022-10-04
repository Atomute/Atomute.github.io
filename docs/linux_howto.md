[<-- HOME PAGE](index.md)

# How to download Window Subsystem for Linux

Let's me show you how I install Window Subsystem for Linux(WSL2). WSL provide you with a useful Linux tools. Also thanks to [Pureinfotech](https://www.youtube.com/c/Pureinfotech) that make the video tutorial of how to do all of this. You can check out his video down below.

<iframe width="560" height="315" src="https://www.youtube.com/embed/n-J9438Mv-s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## 1. See the distribution that suit you the most.
Linux come with many distribution or Distros. Picture below is some of them go check it yourself. I chose to install Kali linux because I heard it use for hacking and that sound really cool!

## 2. Enable the window feature
Search for "Turn Window features on or off". Look for "Window subsystem for Linux" and "Virtual Machine Platform" then tick both of them,click ok. This will enable wsl features of your computer and you will have to restart.<br>
![windowfeature](https://cdn.discordapp.com/attachments/717596102194364490/1004411286559404083/unknown.png)
 
## 3. Download wsl package
First you have to install wsl package to youe computer. I download it from this link https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi. Or you can just open your terminal and type "wsl --install". You will have to reboot your computer either ways. You can check your wsl version by running this command.
```
 wsl -v
```
If your wsl is not on version 2 you may want to update it by running this command.
```
 wsl --update
```

## 4. Download linux distros you want 
 There are two ways to download linux distro for wsl (I just know two).
  * First is to download it via microsoft store. Just search linux in microsoft store, and find the one that you want and download it.(I downloaded it this way)
  * Second is through command line in your terminal,type 
 ```
  wsl -l --online
 ```
and bam a list of distros that you can download are lying there.  
![distros list](https://cdn.discordapp.com/attachments/717596102194364490/1004435393908850828/unknown.png)<br>
Type
```
 wsl --install -d DISTRO NAME
```

## 5. Set up your Linux
After you downloaded it the linux distro that you download will pop up automatically,you will have to set your name and password. And it's done!
  
  

