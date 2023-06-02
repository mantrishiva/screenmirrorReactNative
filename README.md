# screenmirrorReactNative
download scrcpy from
https://github.com/Genymobile/scrcpy/blob/master/doc/windows.md

create a folder scrcpy-tool in Android\Sdk\
copy the adb file from C:\Users\<user name>\AppData\Local\Android\Sdk\platform-tools to SDK\scrcpy-tool

in windows create .cmdrc file
 and paste the below code 
 
 export SCRCPY_TOOLS=${HOME}/Android/Sdk/scrcpy-tools
function scrcpy_run () {
    ADB=$SCRCPY_TOOLS/adb scrcpy
}
