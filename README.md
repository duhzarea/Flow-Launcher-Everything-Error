# Flow-Launcher-Everything-Error
Flow Launcher Everything Error


Flow Launcher version: 1.15.0
OS Version: 23481.1000
IntPtr Length: 8
x64: True

Python Path: 
Node Path: 
Date: 06/24/2023 22:45:22
Exception:
System.ComponentModel.Win32Exception (2): An error occurred trying to start process 'MsiExec.exe \Everything.exe' with working directory 'C:\Users\***\AppData\Local\FlowLauncher\app-1.15.0'. O sistema não pode encontrar o arquivo especificado.
   at System.Diagnostics.Process.StartWithCreateProcess(ProcessStartInfo startInfo)
   at System.Diagnostics.Process.Start(ProcessStartInfo startInfo)
   at Flow.Launcher.Plugin.Explorer.Search.Everything.EverythingSearchManager.ClickToInstallEverythingAsync(ActionContext _) in C:\projects\flow-launcher\Plugins\Flow.Launcher.Plugin.Explorer\Search\Everything\EverythingSearchManager.cs:line 55
   at Flow.Launcher.ViewModel.MainViewModel.OpenResultAsync(String index) in C:\projects\flow-launcher\Flow.Launcher\ViewModel\MainViewModel.cs:line 277
   at CommunityToolkit.Mvvm.Input.AsyncRelayCommand.AwaitAndThrowIfFailed(Task executionTask)
   at System.Threading.Tasks.Task.<>c.<ThrowAsync>b__128_0(Object state)
   at System.Windows.Threading.ExceptionWrapper.InternalRealCall(Delegate callback, Object args, Int32 numArgs)
   at System.Windows.Threading.ExceptionWrapper.TryCatchWhen(Object source, Delegate callback, Object args, Int32 numArgs, Delegate catchHandler)
