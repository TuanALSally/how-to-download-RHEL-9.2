Step 1: Turn on the "Linux Mode"
Open your Command Prompt (search for cmd in your start menu) and type this:

DOS

wsl --install
Wait for it to finish and restart your computer! This is the most important part.

Step 2: Get the "Cool" Terminal
The old black box is okay, but the Windows Terminal is way better. It lets you open Linux and Windows at the same time in different tabs.

Go to the Microsoft Store.

Search for Windows Terminal.

Hit Install.

Look for this button: [Image:e.png]

Step 3: How to use it
Now, you have two ways to be a "hacker":

Inside CMD: Just type wsl before any command.

Example: wsl ls (This shows your files the Linux way!)

The Linux Tab: Open your new Windows Terminal, click the down arrow, and click Ubuntu. Boom! You're in Linux.

Step 4: Where are my files? 📂
Don't lose your work!

To see your Windows files in Linux: Go to /mnt/c/

To see your Linux files in Windows: Open a folder and paste this at the top: \\wsl$

[Image: r.png]

Quick Shortcuts to Remember
sudo apt update — Makes your Linux smart and updated.

code . — Opens your folder in VS Code (if you have it).

exit — Leaves Linux and goes back to Windows.
