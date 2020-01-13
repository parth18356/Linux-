Linux Kernel Compilation


This first basic task requires you get hands-on experience with Linux Kernel
compilation. This would be essential for various future assignments that you
need to work on.


You would require the following:
1. A virtual machine (VMWare or VirtualBox).
2. Ubuntu server 14.10 (Utopic Unicorn) installed and running on the VM
(created from step 1 above).
3. Kernel source, version 3.16, downloaded from repositority (apt repository).


What you need to do with the downloaded kernel:
1. Use the .config file in the the kernel source header directory which is
already present in the functional distribution and copy it into the downloaded kernel source directory.
2. Compile the downloaded kernel using instructions that are packaged along
with the kernel. The kernel binary can be appended with customized
strings. You need to add your name as the customized string.
3. Make sure that (using appropriate make arguments) that the compiled
kernel binary, modules and the initrd files are copied in the appropriate
directory.
4. Reconfigure grub bootloader to ensure that the new kernel is booted the
next time you restart the VM.
5. Restart the VM and test the newly compiled kernel. The newly compiled/booted kernel should bear your name in the kernel string.
