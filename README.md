# audioto
Very simple scripts to convert audio bitrate using ffmpeg.
These are one-liners, but with no prior knowledge or very regular use, these are useful. In my case, used for converting audio to fit Quaver requirements.

Installation
------

### Windows

1. Copy the contents of the `windows` folder in a permanent folder
2. Add the folder to your PATH (environment variables settings)
3. (Optional) To save space, if you already have ffmpeg in your PATH somewhere else, you can delete ffmpeg.exe

### Linux

1. Copy the contents of the `linux` folder in a permanent folder
2. Add the folder to your PATH
3. Install the "ffmpeg" package


Usage
------

### Windows

1. Open a command prompt in the same folder as the file to convert, if you don't know how to, there are two ways :
   - Shift + Right click > Open command window here  
   or  
   - Click on the path in the top, type `cmd` and press Enter  
   Guide: https://www.thewindowsclub.com/how-to-open-command-prompt-from-right-click-menu
2. Type `audioto <number> <filename>`  
   - <number> the bitrate to convert the file to  
   - <filename> the name with extension of the file to convert  
3. `audioto192 <filename>` or `audioto128 <filename>` are also available

### Linux

1. In a terminal, navigate to the same folder as the file to convert
2. Type `audioto <number> <filename>`  
   - <number> the bitrate to convert the file to  
   - <filename> the name with extension of the file to convert  
3. `audioto192 <filename>` or `audioto128 <filename>` are also available
