# Connecting to the Yoda Network Disk on Windows

These pages contains information about methods for connecting to
the Yoda Network Disk on PCs and laptops that run Microsoft Windows. There are 2 basic ways to access the Yoda Network 
Disk from Windows. Using a tool to mount the Yoda Disk as a drive letter or file transfer tools. Which one works best
 depends on your workflow.
 
### File transfer
There are numerous free file transfer tools. Using these tools you must download the files you want to work on to 
your computer and upload the changes. This way of working is more stable and robust. 

- [Cyberduck](yoda-disk-cyberduck.md) is a free file transfer tool for Mac and Windows. Cyberduck is the preferred
way to access the Yoda Disk. There is also a paid addon "Mountainduck" which adds functionality to access via a drive 
letter.

- [WinSCP](yoda-disk-winscp.md) is an alternative free file transfer tool.

### Drive letter
Using these tools you can access the Yoda Disk via a drive letter.

- [WebDrive](yoda-disk-webdrive.md) is a VU-supported method to remotely access files and can also be used on "green"
pc's.

- Directly in [Windows Explorer](yoda-disk-windowsnative.md). However, this has restrictions: a maximum
file size of 4GB on Windows 11 and 50MB(!) on Windows 10 and a maximum of 1000 files per folder (Windows 10&11). Take care if you expect your dataset to exceed these limitations.

### Commandline
If you are familiar with commandline tools [rclone](yoda-disk-rclone.md) is also a good option to access the Yoda Network disk via Webdav. It also provides the option to use a drive letter.