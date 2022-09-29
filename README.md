# AndroidPasswordStorage

This program implement password storage in memory using RoomDatabase in format:
- Name of resource
- Login
- Password
- Description

<p align="center">
  <img src="https://user-images.githubusercontent.com/55932416/193133628-b3771e7c-5671-4888-9c22-386c03520258.png" />
</p>

All records displaying on main menu where you can swipe its up-down for scroll list or swipe left for delete record. 
  
  <p align="center" width="25%" height="25%">
  <img src="https://user-images.githubusercontent.com/55932416/193136204-b825f6a2-5475-488b-aab0-2f27de621764.png" />
</p>

Database records encrypt with AES-CBC-PKCS5Padding algorithm based on user password which is set on first open.
After it is used for authorization in application.  

  <p align="center" width="25%" height="25%">
  <img src="https://user-images.githubusercontent.com/55932416/193137324-4c6ffc2f-f254-42f8-9cde-1a8705185a63.png" />
</p>

Change password you can in extended menu on main screen.
Also in this menu you can export/import database in CSV format or clear it.

 <p align="center" width="25%" height="25%">
  <img src="https://user-images.githubusercontent.com/55932416/193136228-fa48f303-5dd9-4f20-ad4b-20f14771bde8.png" />
</p>
  
  
Main sources directory in repository - *"AndroidPasswordStorage/app/src/main/java/com/example/mystorage"*
