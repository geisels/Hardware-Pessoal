# How to Configure Gaming Mouse on Linux Using Piper GUI Tool

Source: https://itsfoss.com/piper-configure-gaming-mouse-linux/

Brief: Piper is a nifty GUI application that helps you configure your gaming mouse on Linux.

Usually, when you switch from Windows to Linux, you lose access to a lot of GUI (Graphical User Interface) tools to manage gaming peripherals. You can still enjoy playing games on Linux, but the ability to configure your mouse is a big deal if you are more than a casual gamer.

Recently, I came across a handy tool that lets you configure your gaming mouse on Linux. Let me share how it works and whether it is worth trying.
SaleBestseller No. 1
Razer DeathAdder Essential Gaming Mouse: 6400 DPI Optical Sensor - 5 Programmable Buttons - Mechanical Switches - Rubber Side Grips - White
Razer DeathAdder Essential Gaming Mouse: 6400 DPI Optical Sensor - 5 Programmable Buttons - Mechanical Switches - Rubber Side Grips - White
Durable Mechanical Switches: Supports up to 10 million clicks, backed by a 2 year warranty
$29.99
Piper: A GUI tool to manage your gaming mouse on Linux
Piper Gui

Piper is an open-source tool that you can use for configure gaming peripherals on Linux. Technically, Piper is a graphical frontend to the ratbagd DBus daemon — but you don’t need to worry about it if you aim to use the GUI.

In this article, I’ll give you a brief overview as I test it on my Logitech G502 gaming mouse.
Preview 	Product 	Price 	
Logitech G502 Proteus Spectrum RGB Tunable Gaming Mouse, 12,000 DPI On-The-Fly DPI Shifting, Personalized Weight and Balance Tuning with (5) 3.6g Weights, 11 Programmable Buttons 	Logitech G502 Proteus Spectrum RGB Tunable Gaming Mouse, 12,000 DPI On-The-Fly DPI Shifting,... 	$99.00 	Buy on Amazon
Features of Piper

It’s a dead simple tool. You get the ability to configure the following things of your gaming mouse with the help of Piper:

    Change DPI (Resolution) and Polling rate
    Map buttons
    Control LEDs
    Add multiple profiles

Please note that not all gaming mouse work with Piper at this time. Please check the list of support devices before you try it out.

Here’s how it works and looks:
Change DPI & Polling Rate
Piper Dpi

With Piper, you get to set different DPI levels to switch from. It’s quite easy tweak it because of the slider present.

Not just limited to the DPI settings, but you can also control the polling rate (or the sensitivity). Of course, depending on your mouse, the option may look different, but you don’t really need to change the sensitivity of your mouse for the most part.
Configure Buttons
Configure gaming mouse buttons in Linux with Piper

This is extremely important for most of the users, especially, if you want to utilize macros or simply want to change the mapping of your buttons.

As you can observe in the screenshot above, I was able to tweak each and every button.

I’ve re-mapped the DPI increase/decrease button and replaced it with a macro to dabble between multiple workspaces on Pop OS 20.04.
Control LEDs
Piper Led Control

Well, there’s no use of having RGB lighting if you can’t tweak or control them. With Piper, you can easily control the LED lights of your gaming mouse (if your mouse has this feature). It works pretty well for my G502.
Multiple Profiles

You also get the ability to manage multiple profiles to switch from — so you don’t have to fiddle around with the settings always.

In case you didn’t know, each profile can have different button mapping, LED setting, and DPI settings.

Recommended Read:
Map Your Gamepad Buttons With Keyboard, Mouse, or Macros/Scripts Using AntiMicroX in Linux
Map Your Gamepad Buttons With Keyboard, Mouse, or Macros/Scripts Using AntiMicroX in Linux
Installing Piper On Linux

To get started, you need to ensure that you have libratbag installed. Some Linux distributions have it pre-installed, like Pop!_OS.

For Ubuntu-based distros, you can type in the following command to install it if you didn’t have it already:

    ```
    sudo apt install ratbagd
    ```

You can follow the official installation instructions if you need it for Debian, Arch or Fedora.

Once done, you can finally install Piper by typing the following command (for Ubuntu-based distros):

    ```sh 
    sudo apt install piper```

You can get installation instructions for other Linux distributions in their wiki on GitHub.

You also get a Flatpak package available. In case you don’t know how to install it, I suggest you to refer our Flatpak guide to know more.
Download Piper
Wrapping Up

Piper is an amazing GUI tool to easily configure a gaming mouse on Linux considering that you have one of the supported devices.

You will find many supported devices from Logitech, Etekcity, GSkill, Roccat, and Steelseries. So, I’d say it should come in handy for serious Linux gamers.

Have you tried Piper yet? Let me know your thoughts in the comments below.
