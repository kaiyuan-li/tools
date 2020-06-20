# infinite login loop
Go to terminal mode:
`Ctrl+Shift+F3`

I did this:
`sudo vi /etc/default/grub`

update the line to
`GRUB_CMDLINE_LINUX_DEFAULT="nomodeset"`

Then run in terminal
`update-grub`

Just log in with startx:
`ctrl+alt+f3`
`startx`#

# Sound issue
`alsamixer`

# Chinese input
`sudo apt-get install ibus-pinyin`

`ibus restart`

System->Settings->Add Input Method

# [Nodejs install](https://github.com/creationix/nvm)

# Stuck on the GRUB page
[Tested workflow](https://askubuntu.com/questions/978886/i-cant-get-out-of-grub-you-need-to-load-the-kernel-first/1002240)
