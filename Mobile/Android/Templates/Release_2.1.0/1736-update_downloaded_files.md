###  Update downloaded files 

#### Pr: https://github.com/owncloud/android/pull/1736


---

 
| TestID | Test Case | Steps | Expected Result | Result | Related Comment |
| :----: | :-------- | :---- | :-------------- | :----: | :-------------- |
| 1 | Update file |  1. In app, download a file<br>2. In server, update the file<br>3. In app, pull down and tap on the file|  The new version is downloaded and displayed. The modification date is updated   |  |  |
| 2 | Update pic |  1. In app, download a pic<br>2. In server, update the pic by overwritting it with another pic using the same name<br>3. In app, pull down and tap on the pic|  The new version is downloaded and displayed. The modification date is updated. The thumbnail is updated   |  |  |
| 3 | Conflict local|  1. In app, download a file<br>2. Switch the device connection off<br>3. In app, update the file<br>4. In server, update the file<br>5. Restore the connection<br>6. In app, sync the file |  The conflict is detected (solve with local)    |  |  |
| 4 | Conflict server|  1. In app, download a file<br>2. Switch the device connection off<br>3. In app, update the file<br>4. In server, update the file<br>5. Restore the connection<br>6. In app, sync the file |  The conflict is detected (solve with server)    |  |  |
| 5 | Conflict both|  1. In app, download a file<br>2. Switch the device connection off<br>3. In app, update the file<br>4. In server, update the file<br>5. Restore the connection<br>6. In app, sync the file |  The conflict is detected (solve with both)    |  |  |
| 6 | Conflict local - Av. offline|  1. In app, download a file and set it as av. off.<br>2. Switch the device connection off<br>3. In app, update the file<br>4. In server, update the file<br>5. Restore the connection |  The conflict is detected (solve with local) |  |  |
| 7 | Conflict server - Av. offline|  1. In app, download a file and set it as av. off.<br>2. Switch the device connection off<br>3. In app, update the file<br>4. In server, update the file<br>5. Restore the connection |  The conflict is detected (solve with server) |  |  |
| 8 | Conflict both - Av. offline|  1. In app, download a file and set it as av. off.<br>2. Switch the device connection off<br>3. In app, update the file<br>4. In server, update the file<br>5. Restore the connection |  The conflict is detected (solve with both) |  |  |
| 9 | Update audio |  1. In app, download a audio<br>2. In server, update the audio by overwritting it with another audio using the same name<br>3. In app, pull down and tap on the audio|  The new version is downloaded and reproduced . The modification date is updated.    |  |  |
| 10 | Update video |  1. In app, download a video<br>2. In server, update the video by overwritting it with another video using the same name<br>3. In app, pull down and tap on the video|  The new version is downloaded and reproduced . The modification date is updated.    |  |  |
| 11 | Update file without preview |  1. In app, download non previewable file <br>2. In server, update the file by overwritting it with another file using the same name<br>3. In app, pull down and choose open with option|  The new version is open in the selected program. The modification date is updated.    |  |  |
