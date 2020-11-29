Everyone knows Dropbox, so it is not necessary to introduce what is Dropbox and how some kind of Dropbox-like services come to help users. <br />

One thing to remember, Dropbox is a Cloud Storage system. So what do we wish to achieve from a Cloud Storage system? Those followings are the top-level requirements for a Dropbox-like service </br>

1. Users should be able to upload and download their files from any device.
2. Users should be able to share files or folders with other users.
3. Service should support automatic synchronization between devices
4. The system should support storing large files up to GB(s)
5. ACID-ity is required. 
6. The system should support offline editing. Users should be able to add/delete/modify files while offline, and as soon as they come online, all their changes should be synced to the remote
servers and other online devices.
7. (Extended Requirements) The system should support snapshotting of the data so that users can go back to any version of the files.
