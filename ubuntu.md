# infinite login loop
I did this:
`sudo vi /etc/default/grub`

update the line to
`GRUB_CMDLINE_LINUX_DEFAULT="nomodeset"`

Then run in terminal
`update-grub`

# Chinese input
`sudo apt-get install ibus-pinyin`

`ibus restart`

System->Settings->Add Input Method

# [Nodejs install](https://github.com/creationix/nvm)

# Stuck on the GRUB page
[Tested workflow](https://askubuntu.com/questions/978886/i-cant-get-out-of-grub-you-need-to-load-the-kernel-first/1002240)
