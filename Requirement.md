# Natural Language

- Users (MPU professors and IET supervisors) are able to access the image storage system encrypted by AES(CBC mode) based on current filesystem. 
- The system should store encrypted images from intrusion by hackers or misuse of users to ensure privacy.
- （The store period should have limitation? If yes, how much time.)
- 
-  Users can upload and download images with key entered. The system can automatically encrypt and decrypt the images with the key.
- The size of image should be limited when uploading. Times of uploads should also be limited for system safety.
- (The size should have a specific limitation. The times also and I think the times of download also need limitations?)
- 
- Stored images should be accessible by all the users who has been authenticated by existing filesystem.
- When selecting a file to be encrypted, the system will determine whether the file to be encrypted is an image format.
- Users must login to the system. Users who are not logged in can view files in the system, but cannot upload or download files.

