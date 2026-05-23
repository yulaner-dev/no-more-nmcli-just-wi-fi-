# no-more-nmcli-just-wi-fi-
an program for linux that makes ACESSING WI-FI stuff rom the terminal more efficent!

heres how to make it work,

Step 1) Make a file called "wi-fi" in "/usr/local/bin" via the "nano" command in terminal, soooo- 
`cd /usr/local/bin` then type `nano wi-fi`

Step 2) Take the "wi-fi" file in here, oepn it up in Terminal,copy and paste the Code into your new file!

`cd (type the path to where you saved the "wi-fi" file i gave to you` then.
`nano "wi-fi` and COPY the Code,then we are rady for step 3!

Step 3) After you have copied the Code off My file,

go back to `/usr/local/bin` by typing `cd /usr/local/bin` into the terminal,then
type `nano "wi-fi` to go back into your own file,then Copy and Paste the Code,
`Ctrl O` to Write the Copied Code,then `Crtl X` to exit and dont forget to,
COMFIRM the changes you made in the file,and last step time ,step 4 time!
Step 4) make the file executable,or else it wont run.
go back to `/usr/local/bin` in the termianl so `cd /usr/local/bin` then,type `chmod +x wi-fi` into the terminal,
and done!

Just dont forget to Reboot linux after this.

Step 5)How to use?

to connect to a network,type `sudo wi-fi connect (Password) (ssid)`
fill the (password) with the password to that network,and...
fill the (ssid) with the ssid of that network.

to search for a network,just type `sudo wi-fi list` to see available Newtworks,and enjoy this tool made by me!!!
