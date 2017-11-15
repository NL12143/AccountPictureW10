# Account Picture Win10 
Automatic provision of Account Picture in Windows 10 from Active Directory 

#Set-ADPicture-Keys.ps1
#source Blog http://blog.jocha.se/tech/ad-user-pictures-in-windows-10, 
#based on https://blog.jourdant.me/post/ps-setting-windows-8-account-picture-from-ad, 
#uses module Resize-Image-A-PowerShell-3d26ef68, by Patrick Lambert
#edits for company and added image resizing using function 


Script uses the following regions: 

#Set script variables and load image resizer 
#Get user object from AD and store in script variables 
#Prepare image sizes and base path
#Create folder to store temp images 
#Prepare registry keys for AccountPictures 
#Save photo imported from AD 
#Load module for image resizer 

#ForEach ($size in $image_sizes)  
   #Save image to disk C:\Users\Public\AccountPictures\<User_SID>\ 
   #Save image path in registry, overwrite existing entries

