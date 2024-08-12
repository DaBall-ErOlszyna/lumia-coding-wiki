># Lumia coding wiki

Welcome to Lumia coding wiki. Here you will learn how to set up Visual Studio 2017, and your Lumia phone for debugging.

> WARNING! Work in progress

> Table of contents

1. [Wiki News](#news)
2. [Installing Visual Studio 2017](#installVS)
3. (coming soon) [Setting up debugging for your phone](#debugging)

>## Wiki News {#news}

- 12.08.2024 
    - The wiki has been created.
    - The *Lime store* is in the works.

>## Installing Visual Studio 2017 {#installVS}

To install Visual Studio 2017 you need to go to https://aka.ms/vs/15/release/vs_community.exe, because it's not possible to install using "Older downloads".
After that, Visual Studio Installer should pop up. You need to take these steps or else it **won't** work.

1. Under first tab check "Universal Windows Platform development".
2. After that, go to "Invidual components tab".
3. Search up "Windows 10 SDK (10.0.15063.0)"
4. Check both Windows 10 SDK for UWP.
5. Start Installing.

After that, you can start Visual Studio 2017. After some time you may get a prompt about needing a **Product key**. You can get one at https://gist.github.com/avazak/e893b6c3811b84347ba68f7457007207. Thank you Avazak!

>## Setting up debugging for your phone {#debugging}

1. Go to settings of your Windows 10 Phone.
2. Go to Updates and Security
3. Click on For developers
4. Check "Developer mode"
5. Check "Make your device visible to USB connections and your local network" as well as "Turn on remote diagnostics over USB and local area network connections".

> After you create a project...

On top you can see the "Start debugging" button. On the left of it there's probably x86 or x64 you need to change it to ARM instead. Then the "Start debugging" button should be set to Device, if it isn't, then set it to Device, and configure your Windows Phone.