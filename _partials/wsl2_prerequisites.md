# Setup your machine!

Welcome to this setup where we are going to install the tools required to make your machine a true developer environment :muscle:.
The following instructions will help you to get ready for [Le Wagon](http://www.lewagon.org) fullstack bootcamp:

- Install a code editor, where you will spend your days and nights
- Install a package manager
- Pimp your Terminal
- Setup git and GitHub
- Install Ruby



## Prerequisites

Before we start, it is important you meet the following prerequisites to ensure the smooth running of the setup.
Take your time to read through everything and do not hesitate to ask for help if you feel stuck.
Ready? Let's go :sunglasses:

If you already applied all the instructions that we sent you by email, please go directly to the [Virtualization](#Virtualization).


### Latest version of Windows

For this setup, you need to be using the latest version of Windows.

This means that you need to be on Windows 10, with all the latest updates installed.

You can check your software version by clicking on **Start>Settings>System>About**. Look where it says **Edition**. If you see something that starts with "Windows 10..." you're good to go :muscle:.

Not the case? Don't panic :scream: You can always install Windows 10 from [Microsoft]( https://www.microsoft.com/en-gb/windows/get-windows-10) (it should take roughly an hour to install but this is dependent on your computer). Click on **Check for Updates**, then follow the instructions on the screen. Come back to this setup when Windows 10 is installed.

Once you're sure that you're using Windows 10, you will need to check that your computer has all the latest updates. For this click on **Start>Settings>Updates & Security>Windows Update**, then click on **Check updates**. If you have updates available please install them and repeat the process until it says that you are up to date :star:.



### The Insider program

For the best development tools we need to be part of the **Windows Insider** program which gives access to pre-release versions of various tools.

Go to **Start → Settings → Updates & Security → Insider Program**

Click on **Get Started**. It will ask you to **Link an account**; follow the instructions on screen. You will be asked to choose your Insider parameters, choose the second setting, the **fast** one :zap:. Then confirm and restart your computer when you are asked to do so.

After your computer has restarted you can double-check that you are now part of the Insider program by clicking on **Start → Settings → Updates & Security → Insider Program**. You should then be prompted with the Insider parameter that you chose earlier, i.e. **fast**.

By joining the Insider program you have unlocked more content and updates — which we also need to install. Go to **Start → Settings → Updates & Security → Windows Update**, you should see new updates available.
:warning: These updates can take a rather long time of more than 30 minutes, so make sure your computer has enough battery left, and that you won't have to close it during the installation :warning:

Start the update and go grab a coffee :coffee: or tea :tea:.

After your computer has restarted, go to **Start → Settings → System → About**. This time check the **Version**, if it says at least 2004, you are good to go :sunglasses:. 

### Virtualization

We need to ensure that the Virtualization options are enabled in the BIOS of your computer.

For many computers, this is already the case. Let's check:

- Press `Ctrl + Alt + Del`.
- Select **Task Manager**.
- Click on the **Performance** tab.
- Click on **CPU**.
- The status will be listed under the graph and will say "Virtualization: Enabled" if this tool is enabled.

![task_manager.jpg](images/task_manager.jpg)

If **Virtualization** is already enabled, go directly to [Github account](https://github.com/lewagon/setup/blob/master/WINDOWS.md#github-account).

If not, we need to enable it, which is a process that is different for each model of computer, so we can only offer vague guidelines in this guide. Please ask a teacher as soon as you get stuck!

Let's retrieve your motherboard model :muscle:

Click on **Start** and type **System Information** and open it.

Locate the **System Model** line, the value on the right is your motherboard model.

Now because everything is dependant on your motherboard model, we will have to do a Google search on how to enable the Virtualization option with this model. 

:warning: We invite you to contact a teacher so you can complete this part of the setup together, as it might be a bit scary to not have clear guidelines. Choose the communication tool of your choice so the teacher can see your screen (your computer will have to be turned off during the setup so please use your phone, WhatsApp, Facetime etc..) :man_mechanic:​ :warning:

If we take my example:

![wsl2_virtualization.png](images/wsl2_virtualization.png)

So I googled "*UX310UA bios enable virtualization*" and the first video in the results taught me how to do it. Part of being a developer is searching for information and applying it to your work :nerd_face:.

Follow the instructions you found to enable Virtualization and come back here, we will be waiting :smile:.
