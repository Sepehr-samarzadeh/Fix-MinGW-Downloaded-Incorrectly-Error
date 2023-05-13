# Fix-MinGW-Downloaded-Incorrectly-Error
 In this repository, I will teach you how to fix this annoying error! since I came across it and couldn't find any updated solution to this particular problem.
### How to Fix The File Has Been Downloaded Incorrectly MinGW W64 Error - MinGW Downloaded Incorrectly :
   1. head to [this address](https://sourceforge.net/projects/mingw-w64/files/mingw-w64/)
   2. Scroll down until you find a list containing different versions of MinGW
   3. Look for the x86_64-posix-seh ( if you are using 64bit windows ) in my case the latest version is minGW-w64 GCC-8.1.0
   4. Wait for the download to start and then extract the downloaded file (zip file)
   5. Copy the extracted file to "C"(local disk)
   6. Open the folder
   7. head to the "bin" folder
   8. From the address bar, copy the path
   9. Go to the search bar on your Windows machine and search for "Edit the system Environment Variable"
   10. In the "advance" section of system properties, Click on the Environment Variables
   11. From the system variables tab, find "Path"
   12. Click on the "Edit" button
   13. Click on the "new" button
   14. Now paste the address path (step:8) on the empty field 
   15. Click Ok 
   16. Restart your system 
  <hr>
  <h3>To make sure you have successfully passed these steps:<h3>
    *Open CMD on your windows and type "gcc --version"
