# Stegraz

<img src="https://img.shields.io/static/v1?label=%F0%9F%8C%9F&message=NiL0V3R&style=style=flat&color=BC4E99" alt="Star Badge"/>
Stegraz is a steganography static analysis tool, gathers most known commands to analyze files for hidden data.
Features here arent new, it's just for time saving + so you don't forget to try/run any command/tool while analyzing. <br>
    
> This tool is made with bash script and mostly for ubuntu, also it depende on some previous installed basic tools (needs dependencies)
   

## Manual

[Manual-page](stegraz.1)

Here you can read more about how to use the tool, the included features, dependencies ... etc  <br>
To make the manual page work on your systeme you should follow next steps :  <br>

`1- install the manual script : stegraz.1 `  <br>
`2- chmod 644 stegraz.1 ` <br>
`3- sudo mv stegraz.1 /usr/share/man/man1/`  <br>

after that running `man stegraz` or one of this commands `stegraz -h, stegraz --help` will display the manual that explains what can this command do, its options, and its needed dependencies :


[Screencast from 2024-03-12 21-46-40.webm](https://github.com/shadow1004/Stegraz/assets/68519098/dd5dae59-aaea-4b52-8719-887839e4423f)


## Stegraz : the script of the tool

 [Stegraz](stegraz) 

To run the tool from anywhere on your computer you should follow next steps :  <br>

` 1- install the tools's script : stegraz` <br>
` 2- chmod 755 stegraz` <br>
` 3- sudo mv stegraz /usr/bin`  <br> 

(if you don't want to put this command in the "/usr/bin" you can put it anywhere and make sure to add that location to your $path so you can run it from anywhere). <br>

## Future perspective

 1- make it in a package so you can install the tool from your terminal (making sure its runnable in different distros) so people wont have to manually configure the path <br>
 2- Adding some commands `(foremost, steghide/stegseek .. etc)` <br>
 3- Display a reference table for most known/famous magic bytes or add some unique decryption methods <br>

My tool actually is not perfect yet it helps me, so i wanted to share it with the community maybe it helps everyone as well, so if you ever notice something i can add or i should change
don't hesitate to contact me, thanks for using my tool hope you like it.
