Litterally check the history of the file to see it's intended purpose  
this version sorts shit out, and will only download what if we don't have what we need

Proper command requires the following

```-title [TITLEID] -keyfile -cianame "[NAME OF CIA]" -type "[DSIWare/eShop/etc]" -reg "[USA/EUR/JP]" -pserial "CTR-X-XXXX"```

Example, An ```eShop``` file with ```USA``` with the pserial of ```CTR-A-BCDE```  
will be stored in ```cia/USA/eShop``` folder as ```Awesome Game -- TITLEID -- CTR-A-BCDE```  
They are only so the python script can place cia files in the correct locations.
Filenames are so files can be easily found in directory searches. By ID, serial or title.

Raws are deleted to free up hard drive space, I created this with that limitation in mind. Speed wasn't, so I could just redownload an application upon failure
