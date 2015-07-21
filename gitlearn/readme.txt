:: use installer to install appium 
appium-installer.exe /SP- /silent /noicons /closeapplications /dir=expand:%1

:: delete the installer 
del appium-installer.exe

:: start the appium application
::Appium.exe  :: no longer need to launch the application since the installer starts the application automatically

:: delete update.bat file 
call :deleteSelf&exit /b
:deleteSelf
start /b "" cmd /c del "%~f0"&exit /b

we are learning git as a beginner!
that is why I want to test git command.
but why I can't see the difference.

git has a mutable area called stage.
