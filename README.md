# WinFormsSample-eyexSignalR
An example shows how to use SignalR to provide server broadcast functionaility, which sends gaze data from Tobii EyeX. The
SignalR server is hosted in a Windows Form application that connects to the EyeX or REX eye tracker and plots gaze whenever they are available. 

You will need to install the following packages to create a SignalR server: 
- Microsoft.AspNet.SignalR.SelfHost
- Microsoft.Owin.Cors

The code is adapted from the "WinFormsSample" project available in the Tobii gazeSDK. So you will also need to install the Tobii Gaze SDK. 


