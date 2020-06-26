
#             AutoAlignForEclipse

如果你想要課以直接執行的程式，請下載資料夾executable。
然後去https://www.mathworks.com/products/compiler/matlab-runtime.html 下載符合你作業系統的runtime compiler
把你想要對齊的檔案放進solar_eclipse的資料夾(預設)，執行AutoAlignForEclipse.exe，按下OK後，等一下會跳出進度視窗，然後就可以等待對齊完成。
如果影像未正確對齊，則應更改Threshold的值。

If you want execute the program directly, please download the executable folder.
Then go to https://www.mathworks.com/products/compiler/matlab-runtime.html to download a runtime compiler that matches your operating system.
Put your image file into the solar_eclipse folder (default), execute AutoAlignForEclipse.exe, press OK, wait a moment, a progress window will pop up, and then you can wait for the alignment to complete.
If the image did not aligned properly, you should change the Threshold level.

For source code:
Auto align partial/annular solar eclipse image.  
This script will detect Sun and center it.  
Aligned image would be saved in destination folder as the origin file type with same name.
The function, 'minboundcircle', is written by John D'Errico

 **To use this script, you need to install image processing toolbox.
 **This script was written in R2019b

 Author: Shun-Chia Yang
 E-mail: a26413768@gmail.com
 Release: 1.0
 Release date: 2020/6/24
