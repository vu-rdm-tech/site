# Connecting to the Yoda Network Disk on Windows Using WebDrive

Windows users can use [WebDrive](https://webdrive.com/) to access their data via the Yoda Network Disk,
as an alternative to the [native WebDAV client](yoda-disk-windowsnative.md) and
[CyberDuck](yoda-disk-cyberduck.md). With WebDrive the Yoda Network Disk can be connected via as a drive in 
Windows Explorer. 

As a VU user you can download a licensed version of WebDrive from [download.vu.nl](https://download.vu.nl).

Note that you should always [disable caching](#disable-the-cache) in WebDrive!

## Using WebDrive

Start Webdrive from the Desktop icon or the Start menu.

![alt text](screenshots/screenshot-webdrive-start.png "Screenshot WebDrive: start")

In the initial Window click new.

![alt text](screenshots/screenshot-webdrive-choose.png "Screenshot WebDrive: choose connection")

Choose Secure WebDAV and click Next.

![alt text](screenshots/screenshot-webdrive-account.png "Screenshot WebDrive: account information")

Enter https://data.yoda.vu.nl/ in the Url/Address field.

Enter the Username (an emailaddress). Create a [data access password](data-access-password.md) and copy it to the Password field.

You can click Test Connection to see if the credentials are correct. 

Click Next

![alt text](screenshots/screenshot-webdrive-ready.png "Screenshot WebDrive: ready")

Choose a Drive letter and Connect Now.

![alt text](screenshots/screenshot-webdrive-explorer.png "Screenshot WebDrive: explorer")

You should now see the Yoda Disk in your Windows Explorer.

## Disable the cache
By default WebDrive enables a caching mechanism and suggests this as a way to enable syncing and working offline.   
This functionality is not implemented very well and you should **always disable** this to prevent data loss.

![](screenshots/screenshot-webdrive-properties.png)

- Right click on "data.yoda.vu.nl" in the server list

![](screenshots/screenshot-webdrive-cache.png)

- Set Cache Mode to None and Cache Limit to 0.