# total_commander_best_file_manager

**I make acrobatics with files all day long.  I could not live without TotalCommander.**  
***version: 1.0  date: 2019-05-15 author: [bestia.dev](https://bestia.dev) repository: [GitHub](https://github.com/bestia-dev/total_commander_best_file_manager)***  

Primarily for Windows:  
![totalcmd_1](https://github.com/bestia-dev/total_commander_best_file_manager/raw/main/images/totalcmd_1.png "totalcmd_1")
But today for Android too:  
![android_1](https://github.com/bestia-dev/total_commander_best_file_manager/raw/main/images/android_1.png "android_1")

## History

I am old. I don't feel it, but I am. I grew up with Sinclair Spectrum 48 and Commodore 64 computers. The battle was between Z80 and Motorola MC6800 microprocessors.

I was already very productive in the old MSDOS times with Intel 80286 on 6 MHz.  
There was a magic tool everybody used: Norton Commander.  
It was very difficult to be productive without it. Can you imagine typing folder/file names all day? Just plain crazy!  
MSDOS was slowly dying and the new star of graphic user interface Windows emerged. It had a nice looking File Manager. But it was a game for kids, not a true tool. You learned about mouse movements, Click, DoubleClick, drag&drop. (there was not right click in the old times). Fine. Totally useless for practical purposes. It was a game, not a tool.  
Then a Swiss guy Ghisler had this idea to remake the Norton Commander, but for Windows. Fantastic! Great tool!  
He called it Windows Commander. After a few years he had a phone call from the lawyers of Microsoft that "windows" is their trademark. He renamed it to `Total Commander` or `TotalCmd`.  
I think it is now 30 years I am using it and nothing comes close to it as a practical tool.  

## Functional Shareware

You can use it for free for a limited time (very long), but buying it for 37€ was the best purchase I ever made. I have bought it 2 times: one for personal use and one for my workplace.  
You can find all the information and download it here: <https://www.ghisler.com/>
Hahaha, it still uses a blue and red 3.5" diskette icon. The kids nowadays don't even know what it represents. In the old times Ghisler was working hard to have the installation so small (1.4Mb), that it stays on only one diskette. In the modern internet times it does not matter any more. But it is still very compact.  

## Configuration - Options

Do this the first time you open the application. It will make it much more user-friendly.  
Layout  

- Show drive buttons
- Show folder tabs
Operation  
- Left mouse button (Windows standard)
Quick search  
- Letter only

## Basics

What do you expect from a `File Manager`? To make file manipulation easy and fast.  
TotalCmd has 2 panels with files and folders. If you copy or move files the one with the focus is the `Source` and the other is the `Destination` of the operation. Very practical.  
The mouse is a nice toy, but super slow and not precise. Use the keyboard instead. Learn the shortcuts you use often and be super fast and precise. Move up and down with the `arrows keys`. Change from one panel to the other with the `Tab key`. Use `F5` for copy and `F6` for move.  Does it feel right?  
To Delete a file use `F8` or the key `Del`.
The first row in the panel is `two dots`. In the old days it meant the `Parent folder`. Move to it with the `Home key` and press `Enter`. You will got into the `Parent folder`.  
You can press `Enter` on a `Folder` (yellow icon) to go into it. Or press `Enter` on a `File` to open it with the associated application. Don't overthink it, just try it.

This is just the beginning. But the way of thinking about it is always the same.  

## Tabs and favorite folders

We use tabs every day in Chrome. Why not use it in TotalCmd?  
Press `Ctrl + t` and it will open a new tab. Now you have one more folder you can easy switch to (with the mouse this time). Very useful in everyday work.  
Do you have some favorite folders that you use often? Press `Ctrl + d` and save them for later.  
If you want a Tab to be there for you forever you can choose RightClick and `Lock this tab`.  
Like in a browser you have the Back and Forward button in the toolbar. So you can jump to the folders you have recently watched.

## Sort and select

Click on the column header to fast sort by: Name, Ext, Size or Date.  
Move up and down with the arrows and press Space. You selected a file/folder. Do it again and again. You have a selection. Very similar is `Shift + Up` and `Shift + Down`. There is also the `menu Mark - Select Group` to select with wildcard characters e.g. `*.jpg`. Once you have a selection all operations work on all the selected files together.  

## Rename FileName

To rename a file press `Shift + F6`.  
I often need for one file the `menu Mark - Copy names with path to clipboard`.  

## Zip and other Packers

A Zip file is very similar to a Folder. If you press `Enter` on it, you will see the content. All the usual operation work just like with normal folder in both directions.  
It is the same for many other packers. Some of them are already in the default installation. Other can be added as Plugins. I think there is a plugin for everyone of them.  
To Pack and Unpack in one go use `Alt + F5` and `Alt + F9` shortcuts.  

## Network and cloud disks, ftp, SSH and WebDAV

Today a lot of data is in a remote location. TotalCmd offer a wide range of possibilities to connect to this folders. From that moment on it treats them just as regular folders and all operations just work on them the same as with local folders. Some of them are in the default installation. For others install this plugins from <https://www.ghisler.com/plugins.htm>:  

- Cloud 2.0 - for DropBox,...
- WebDAV 2.9 - for Android WebDAV server, ...
- SFTP 2.20 - for SSH,...  
After you download the plugin, open the zip file with TotalCmd. It will recognize it is a plugin and it will offer to install it. It is that simple.  
If you save the passwords inside TotalCmd use the MasterKey password to have them secure.  

## Synchronize dirs

From the `menu Commands - Synchronite dirs` open a strong, fast, easy and complete tool to synchronize folders. You first Compare two folders. Than you choose what to do for every file and then you Synchronize.  
There is also the tool `File - Compare by content` the two selected files from the left and right panel.

## Search

`Alt + F7` opens the Search tool. You can search and filter by anything you imagine.  
There is also a `Find duplicate` tool in the Advanced Tab. Very useful.  

## Working with photos

I like to have my photos very well organized. It is a hard work because of many different cameras and sources. I decided that the only true information I have is the Photo Date and time. So I decided that all my photos will have this file name format:  
LF2019-04-04 12-12-12 blabla.jpg  
I start with my initials, then the date and time and maybe some description.  

## Import photos

I have a Sony camera with a SD card. I put that in my notebook. In TotalCmd on the left I have an empty local folder and on the right the SD card. On the right side I select all the jpg with `Mark - Select Group - *.jpg` then I copy that with `F5`. I can extract the CD and return it into my Sony camera where I format it.  

## Rename photos

In the local folder I press `Ctrl + a` to Select All and then `Ctrl + m` for the Multirename tool. I choose a saved rename mask:  

```text
LF[Y]-[M]-[D] [h]-[m]-[s][N20-]
```  

![multi_rename](https://github.com/bestia-dev/total_commander_best_file_manager/raw/main/images/multi_rename.png "multi_rename")  
It will use the file date/time to rename all files. I can see the future filenames so I can decide if I am happy or not. Then I press `Start!`. Boom - renamed - all at once!  
I can save the mask with the button `F2 Save/Load` for future use.  
I can move now this "processed" photos somewhere else.  

## iPhone

My girlfriend has an iPhone. I want that pictures also in my albums.  
When I attach it with USB to my notebook I can choose it in TotalCmd from the `Drive Combobox`.  
Copying is always the same: select the files and press `F5`.  
Apple is very innovative and the file date/time is never the true date/time. Very confusing, but I'm sure it was an `apple-smart` decision. I have to use EXIF data. I install the Exif 2.4 plugin from  
<https://www.ghisler.com/plugins.htm>.  
Now, I can use this kind of Rename mask:  
`LF[=exif.DateOriginal.Y-M-D] [=exif.TimeOriginal.h-m-s]`  
Great !  
But only for photos. Videos don't have Exif. For them I will use the saved Rename mask from file date/time. Surprisingly apple has the date/time quasi right here.  

## Watch the photos

You can press `Enter` and the photo will open in your associated application.  
TotalCmd can internally use a photoviewer called IrfanView:  
<https://www.irfanview.com/>  
It is old school, but very effective. You can say to TotalCmd to use it as its default viewer in  `Configuration - Options - Edit/View - Configure internal viewer - Use IrfanView/Xnview to load graphics`  
Now you can choose to see the files as thumbnails from `Show - Thumbanil View`.  

![thumbnails](https://github.com/bestia-dev/total_commander_best_file_manager/raw/main/images/thumbnails.png "thumbnails")  

You can return to `Show - Full` later. You can choose the size of the thumbnails if they are too small or too big in `menu Configuration - Options - Thumbnails - Thumbnail size`.  
All the operations work just the same no matter what view you use.  

## The separator

The two panels are divided by a Separator. With the mouse you can move it. So you can make more space for one panel and less for the other. That is great to make more space for the Thumbnail view.  

## Total Commander for Android

I waited a long time for a good File Manager for Android. And I was lucky, because Ghisler decided to work in that direction. The result is phenomenal: `Total Commander for Android`.  
<https://www.ghisler.com/android.htm>  
The smartphone screen is pretty small. You can see only one panel at a time. But on the edge there are three big arrows to remind you there is another panel on the other side. You touch them and you can see the other panel.  
You have the basic stuff: select, copy, move, delete, sort, new folder, search. Very impressive!  
I you want to ask why there is not an iPhone version, it is because iPhone limits the access to the filesystem so badly, that a File Manager can do nothing at all.  

## WebDAV server

But most of all I like the `WiFi direct file transfer (plugin)`. I think the name is terrible, because this is a normal `WebDAV server`. But I can understand, that ordinary people will never know what WebDAV means. So the name is downgraded for ordinary people. I doubt also, that this is a plugin. It should be a separate standalone app. But I am merely a user here and not the programmer.  
When you start the `WebDAV server` `WiFi direct file transfer (plugin)` you can read the URL. Something like this:  
<http://192.168.1.43:8081/6552>  
On the other computer or smartphone you can use a `WebDAV client` to connect to this URL and you will enable a two side file transfer and other files operations.  
Sure, the best `WebDAV client` to use here is exactly Total Commander in both variants: Windows and Android. There is the plugin for WebDAV client you need to install on windows.  
On Android you can even use the QR code to connect fast two android phones. Windows is usually bad with QR codes.  
I often use this way of file transfer between my computer and smartphone and it is working great !  

## Linux and Mac

TotalCmd does not work on Linux or Max. But there are very good alternatives with similar functionality.  
Linux has the `mc` file manager that works inside the text console:  
`sudo apt install mc`  
<http://linuxcommand.org/lc3_adv_mc.php>  
Mac has the muCommander:  
<https://www.mucommander.com/>  

## This is not all

But I have to stop somewhere.  
Discover by yourself more things that I didn't mention.  
Have a lot of fun and be more productive with TotalCmd.  
Enjoy!  
