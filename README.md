# Inject
This is my first project on GitHub. As a rookie, I have limited skills. Please bear with me

This script is the first script I wrote. Its function is to inject a DLL into a process, and it can also be injected into the system process. However, if there is anti-virus software, this method will not work

You can use it with CMD, if it is a system process, you need administrator privileges, normal processes do not need administrator privileges, please choose a different loader according to the specific process is 32-bit or 64-bit, here I provide two test DLL, also a 32-bit and 64-bit, if you want to use your own DLL, Remember to generate different bits of DLLs based on different bit loaders. In Windows 10, I successfully injected the 64-bit loader into WinLogon. exe, lsass.exe, etc. However, in other versions of Windows, I found some problems during testing. The specific reason is not clear yet, but I will keep updating. Finally, remember that this loader does not have the ability to bypass the anti-virus software, it will be later, but not now, because I am a rookie


Like this, run it by loader name, PID and dll path
![image](https://user-images.githubusercontent.com/82760569/115146153-dfc21600-a087-11eb-9cad-db106c6d340e.png)
For example
![image](https://user-images.githubusercontent.com/82760569/115146306-827a9480-a088-11eb-84cc-921321f36caf.png)
![image](https://user-images.githubusercontent.com/82760569/115146315-958d6480-a088-11eb-82a5-1fdd1c112027.png)
Remember that the dll path is an absolute path. If the loading fails, you can run it several times, or check whether the cmd is an administrator, it should be no problem!
