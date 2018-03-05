# Update-Utilities-2018
Really all this does is run command line commands, but we use it to update python plugins/libraries.

## Instructions:
1. Put a batch (.bat) file with command line commands or batch code into InstallerPackages.
2. Then place the name of said file into AddNamesOfInstallerPackagesHere.bat with the format `call FileNameHere`.
3. To run the code, run the RunMeToUpdate.bat file and allow admin permissions when asked.

## Other Info:
Installer packages are just batch files with command line in them.

The default packages are explained here:
1. ExamplePackage: Echoes (prints) some text that says its an example.
2. UpdatePyFRC: Updates/installs the PyFRC python libraries.
3. UpdateRobotPy-CTRE: Updates/installs the RobotPy-CTRE python libraries.

Special thanks to the guy who authored [this StackOverflow answer](https://stackoverflow.com/a/12264592) for the UAC admin permissions code.
