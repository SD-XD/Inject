# Inject
This is my first project on GitHub. As a rookie, I have limited skills. Please bear with me

This script is the first script I wrote. Its function is to inject a DLL into a process, and it can also be injected into the system process. However, if there is anti-virus software, this method will not work

You can use it with CMD, if it is a system process, you need administrator privileges, normal processes do not need administrator privileges, please choose a different loader according to the specific process is 32-bit or 64-bit, here I provide two test DLL, also a 32-bit and 64-bit, if you want to use your own DLL, Remember to generate different bits of DLLs based on different bit loaders. In Windows 10, I successfully injected the 64-bit loader into WinLogon. exe, lsass.exe, etc. However, in other versions of Windows, I found some problems during testing. The specific reason is not clear yet, but I will keep updating. Finally, remember that this loader does not have the ability to bypass the anti-virus software, it will be later, but not now, because I am a rookie


