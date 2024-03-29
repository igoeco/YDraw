# A Teaching Tool for Tablet PCs#

YDraw is a free Drawing software authored by Ramesh Yerraballi.
It is licensed under [GNU Lesser General Public License v3.0](http://www.gnu.org/licenses/lgpl-3.0.txt)

For documentation click here: [http://igoeco.github.io/YDraw/](http://igoeco.github.io/YDraw/)

## Note - Windows10 WinTab update
The latest Windows 10 update breaks JPen's ability to acquire pressure sensitivity information from the Windows Tablet driver. You will need to install this WinTab driver update ([Wintab_x64_1.0.0.20.zip](https://www.microsoft.com/en-us/download/details.aspx?id=49498)) to restore pressure sensitivity. Without this update the pen will loose it smoothness.

## Note - Alternate Implementation without JPen
JPen is old and has not been updated in a while. So, I rewrote the software to use a Windows native Java API called JWP. You can find this version under YDrawTool/YDrawJWP.jar. This may be the way forward on Windows but will not work on Mac OSX or Linux.