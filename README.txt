Deluge Music Player is made by EncodedTerabyte on the team of Cybersoft Studios.
Please do not claim that this project is your own.

Do not delete "libcurl-d.dll" or "zlibd1.dll" as they're used to make http requests to roblox.
Windows may say that this exe is dangerous. I ensure you that it is not. 
Windows flags any app as dangerous if it isn't registered under the government.
You would have to pay up to 20k USD / GBP / EUROS to get an application license.

Errors you may get:

["MSVCP140P.dll" is untraceable] meaning that you do not that the Microsoft libraries like "multimedia". To fix this download the Microsoft C++ Redistributable.
Follow his Article + the download for the redistributable.
> https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-160
> https://answers.microsoft.com/en-us/windows/forum/all/how-to-reinstall-msvcp140dll/7754cd78-04b0-4750-bb94-8228a0bf4da5 
or open CMD / Command prompt and run:
> sfc /scannow
> regsvr32 MSVCP140P.dll
