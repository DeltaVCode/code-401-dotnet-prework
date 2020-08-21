# Computer Setup for Mac

Below are the machine requirements for the class. Please read through them and confirm your machine is ready for day 1 of class.

1. On a Mac, you will need to either dual boot or use a Virtual Machine to run windows to complete the assignments in this class. **[Guide from former Code Fellows student](https://gist.github.com/jeremymaya/a36c1de8220d76beca85a2804a2cecc4)**
	- Mac Users - It is recommended that you allocate approx. 80 GBs of hard-drive space, and as much RAM as you can spare (4GB min). 
	- The Fall Creator's Update includes the Windows Subsystem for Linux. 
	- **In theory**, Visual Studio Code can be used for .NET Core development on Mac/Linux, but **class demos will use full Visual Studio**. Deviate at your own risk.
		 

| | Pros | Cons |
|:- |:-| :-|
| BootCamp | <ul><li>Native Windows 10 environment on macOS devices</li></ul> | <ul><li>Needs to split hard drive space</li><li>Drivers from BootCamp are not well optimized</li><li>Trackpad's multi-touch functionality is limited</li><li>Device runs hot and battery runs out fast</li><li>Shortcut keys are configured differently</li><li>Windows 10 needs to be purcahsed</li></ul> |
| Parallels/VMware Fusion | <ul><li>Virtualization offers more seamless and better experience than Windows 10 via BootCamp</li></ul> | <ul><li>Virual machine takes 30-40GB of hard drive</li><li>Possibilty of running into issues with folder/network setting that may take few hours to troubleshoot</li><li>Windows 10 and either Parallels or VMware Fusion need to be pruchased</li><li>Would not recommended if laptop's hardware spec is less than Quad Core, 16GB RAM and 258GB SSD</li></ul> |
| Visual Studio for macOS | <ul><li>Native IDE for macOS</li><li>Runs well on less powerful macOS devices                        </li><li>Free</li></ul> | <ul><li>Less developer firendly compare to Visual Studio 2019.                 </li></li>Supports .NET Core only</li> |

----


2. Setup your Visual Studio Community Version and install .NET Core SDK

## Install Visual Studio for Mac and .NET Core 3.1 SDK

* Install Visual Studio for Mac [here](https://visualstudio.microsoft.com/vs/mac/).
* Install the .NET Core 3.1 SDK [here](https://dotnet.microsoft.com/download/dotnet-core/3.1).

![SDK Install Window](/assets/macInstallSDK.png/)

----

	- [Check for latest iOS here](https://support.apple.com/en-us/HT201260#:~:text=From%20the%20Apple%20menu%20%EF%A3%BF,followed%20by%20its%20version%20number.){:target="_blank"} 

	- Installation instructions for .NET Core 3.0 SDK and VS2019 Community. If you install the most up to date version if VS2019, .NET Core 3.0 is included.
	   - [Visual Studio Community Version Documentation](https://docs.microsoft.com/en-us/visualstudio/mac/?view=vsmac-2019){:target="_blank"}  
	   - Required Visual Studio packages
	     - .Net Desktop Development
	     - ASP.NET and Web Development
	     - Data Storage and Processing 
	   
	- Add the [GitHub extension](https://docs.microsoft.com/en-us/visualstudio/mac/working-with-git?view=vsmac-2019){:target="_blank"}  to Visual Studio
		- [Visual Studio Git Process](https://www.visualstudio.com/en-us/docs/git/tutorial/gitworkflow){:target="_blank"} 
	
    - (optional) [SQL Server Management Studio (SSMS)](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms){:target="_blank"}

	- (optional) [VSCode](https://code.visualstudio.com/docs/setup/mac){:target="_blank"} 
	
3. Install Slack & Git
	- [Download Slack](https://slack.com/downloads/osx){:target="_blank"} 
	- Verify you have the [latest version](https://git-scm.com/downloads){:target="_blank"}  of Git installed
	- Setup an account on [GitHub](http://www.github.com){:target="_blank"}  with a recent profile picture

4. Need a refresher on git? 
   - [UDemy Git Tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/){:target="_blank"} 
   - [Git Tutorial](https://learngitbranching.js.org/){:target="_blank"} 


**We do not spend any time in class or lab time setting up personal machines**, If you require assistance to set up you machine, schedule a time before the start of class with your instructor. 


## Submission Instructions
To submit this assignment, please run the following commands in your powershell terminal to confirm your .NET core SDK install `dotnet --version`. Record in Canvas the version that comes up. Confirm that it is at least 3.0.

