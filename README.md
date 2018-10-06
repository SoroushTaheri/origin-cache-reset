# Origin Cache Cleaner
This is a simple batch script which helps you to clear "EA Origin" application cache.
## Details
Appreantly, Origin software has a minor bug within its login process where after logging in, It will not able to load the actual home screen. Instead, this text is shown:
```
Well, that didn't go as planned
Origin encountered an issue loading this page. Please try reloading it.
If that doesn’t work, restart the client or try again later.
```

## Diving Deeper
The script simply deletes all the cache files related to Origin which are stored on your hard drive. The exact directory is located in ```AppData``` folder which can be found in ```%username%``` folder.


## Notes
Please be aware:
- No critical file will be removed unnecessarily.
- After the process is done, "Username Autofill" feature will not be available since the cache has been cleared. You have to enter your username by yourself for the first time you run the software.

