This is my current (INCOMPLETE) progress of the project. 
I plan on resubmitting a completed functional version.

Build setting has been completed with a series of models in the level environment
(Personalized Custom model & textures with separate attachments i.e. armor, 
undersuit, helmet, backpack, etc.)

Additionally, a (nonfunctional) build is 

On first compile, the UE Log gives SocketException Errors.
On second compile, the UE log gives apk installation fail errors.


Notable last log snippet for debugging.
LogPlayLevel: UAT: ==== Template target file up to date so not writing. ====
LogPlayLevel: UAT: Cleaning up files based on template dir C:\Users\Donald\Desktop\School Assignments\2024\VR\Project 1\Osborn_Donald_PRJ1\Build\Android\src\com\epicgames\Osborn_Donald_PRJ1
LogPlayLevel: UAT: UPL Init: arm64-v8a
LogPlayLevel: UAT: Oculus mobile init
LogPlayLevel: UAT: Android Permission Plugin Init
LogPlayLevel: UAT: Subsystem Google Play SDK Android init
LogPlayLevel: UAT: AndroidFileServer Plugin Init
LogPlayLevel: UAT: Google Cloud Messaging init
LogPlayLevel: UAT: GCMClientSenderID set: false
LogPlayLevel: UAT: GooglePAD Plugin Init
LogPlayLevel: UAT: GooglePAD enabled: false
LogPlayLevel: UAT: Android Voice init
LogPlayLevel: UAT: OculusOpenXRLoader
LogPlayLevel: UAT: GoogleGameSDK Android init
LogPlayLevel: UAT: HWCPipe init
LogPlayLevel: UAT: heapprofd init
LogPlayLevel: UAT: APK contains data.
LogPlayLevel: UAT: Disabling Show Launch Image for Meta Quest enabled application
LogPlayLevel: UAT: OculusOpenXR: manifest updates for com.epicgames.unreal.GameActivity
LogPlayLevel: UAT: Output .apk file(s) are up to date (dependencies and build settings are up to date)
LogPlayLevel: UAT: GetPackageInfo ReturnValue: com.epicgames.Osborn_Donald_PRJ1
LogPlayLevel: UAT: Did not find package with activity
LogPlayLevel: UAT: GetPackageInfo ReturnValue: com.epicgames.Osborn_Donald_PRJ1
LogPlayLevel: UAT: GetPackageInfo ReturnValue: 1
LogPlayLevel: UAT: GetPackageInfo ReturnValue: com.epicgames.Osborn_Donald_PRJ1
LogPlayLevel: UAT: GetPackageInfo ReturnValue: com.epicgames.Osborn_Donald_PRJ1
LogPlayLevel: UAT: GetPackageInfo ReturnValue: 1
LogPlayLevel: UAT: GetPackageInfo ReturnValue: com.epicgames.Osborn_Donald_PRJ1
LogPlayLevel: UAT: GetPackageInfo ReturnValue: com.epicgames.Osborn_Donald_PRJ1
LogPlayLevel: UAT: GetPackageInfo ReturnValue: 1
LogPlayLevel: UAT: GetPackageInfo ReturnValue: com.epicgames.Osborn_Donald_PRJ1
LogPlayLevel: UAT: GetPackageInfo ReturnValue: com.epicgames.Osborn_Donald_PRJ1
LogPlayLevel: UAT: GetPackageInfo ReturnValue: 1
LogPlayLevel: UAT: GetPackageInfo ReturnValue: com.epicgames.Osborn_Donald_PRJ1
LogPlayLevel: UAT: Running: C:\Users\Donald\AppData\Local\Android\Sdk\platform-tools\adb.exe -s 2G0YC1ZF7X05YC install -r "C:\Users\Donald\Desktop\School Assignments\2024\VR\Project 1\Osborn_Donald_PRJ1\Binaries/Android\Osborn_Donald_PRJ1-arm64.apk"
LogPlayLevel: UAT: adb.exe: device offline
LogPlayLevel: UAT: Took 0.06s to run adb.exe, ExitCode=1
LogPlayLevel: UAT: Running: C:\Users\Donald\AppData\Local\Android\Sdk\platform-tools\adb.exe -s 2G0YC1ZF7X05YC install "C:\Users\Donald\Desktop\School Assignments\2024\VR\Project 1\Osborn_Donald_PRJ1\Binaries/Android\Osborn_Donald_PRJ1-arm64.apk"
LogPlayLevel: UAT: adb.exe: device offline
LogPlayLevel: UAT: Took 0.07s to run adb.exe, ExitCode=1
LogPlayLevel: UAT: Installation of apk 'C:\Users\Donald\Desktop\School Assignments\2024\VR\Project 1\Osborn_Donald_PRJ1\Binaries/Android\Osborn_Donald_PRJ1-arm64.apk' failed
LogPlayLevel: UAT: (see C:\Users\Donald\AppData\Roaming\Unreal Engine\AutomationTool\Logs\C+Program+Files+(x86)+UE_5.3\Log.txt for full exception trace)
LogPlayLevel: UAT: AutomationTool executed for 0h 2m 36s
LogPlayLevel: UAT: AutomationTool exiting with ExitCode=35 (Error_AppInstallFailed)
LogPlayLevel: Completed Launch On Stage: Deploy Task, Time: 75.603938
LogPlayLevel: UAT: BUILD FAILED
PackagingResults: Error: Launch failed! Failed to Install app