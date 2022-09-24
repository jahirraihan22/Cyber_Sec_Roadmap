<!-- @format -->

### Filesystem

Linux recognize everything as a file, it the one of the defining features of Linux and Other Unix like operating system. In Linux filesystem some files appear but actually they are not files. they are special files that represent your hardware from keyboard to your cpu. To manage directories and files Linux uses **Directory Tree**.

<p align="center">
 <img src="./resources/directory-tree.jpg?raw=true" alt="cloud is linux" width="50%" height="50%" />
</p>

- **/ (root)** : In Linux system, all other directories are derived from the root directory. It is is closely related to the boot, repair and restore of the Linux system.

- **/bin** : It contains common system commands that can be executed by any users.

- **/boot** : It saves files related to system startup, such as kernel files and boot loader (grub) files etc.

- **/dev** : It contains the device files for every hardware device attached to the system.

- **/etc** : It contains the local system configuration files for the host computer, such as user information, service startup scripts, configuration files for common services, etc. It's similar to Windows Registry.

- **/home** : It's the default location to log in and save user data. Each user has a subdirectory in /home.
- **/lib** : It contains shared library files that are required to boot the system.
- **/media** : It's the place used to mount external removable media devices such as floppy disks, CDs, and USB thumb drives that may be connected to the host.
- **/mnt** : It's the traditional mount point for regular hard drive partitions (file systems). But most people like to mount hard drives under /home
- **/misc** : It's the place used to mount the shared directory of the NFS service.
- **/opt** : It's the place used to place and install other software.
- **/usr** : Its full name is Unix Software Resource. It is the default installation location of the software and similar to the complex of "C:\Windows\ + C:\Program files\" in the Windows system.

- **/sbin** : It saves commands related to system environment settings. Only root can use these commands, but there are also commands that allow ordinary users to view.
- **/srv** : It contains data for services. After some system services are started, they can call out or save necessary data in this directory.
- **/tmp** : It is a place where the system stores temporary files, under which all users can access and write.
- **/lost+found** : When the system crashes unexpectedly or shuts down unexpectedly, some file fragments will be stored here. During system startup, the fsck tool will check this directory and repair the damaged file system.
- **/proc** : The data in this directory is not saved on the hard disk, but in the memory. It mainly saves the system's kernel, process, external device status and network status, etc.
- **/sys** : It's similar to the /proc directory and the data in this directory is stored in memory, but it mainly stores information related to the kernel.
- **/var** : It is used to store dynamic data, such as caches, log files, and files generated during software operation.

> Note: The Linux system does not support the NTFS file system by default, but you can manually download and install the NTFS file system driver (such as the NTFS-3G plug-in) to make Linux support the NTFS file system.
