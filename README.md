# Update-Utilities-2018
Really all this does is run command line commands, but we use it to update python plugins/libraries.

# Instructions:
Put a batch (.bat) file with command line commands or batch code into InstallerPackages.

Then place the name of said file into AddNamesOfInstallerPackagesHere.bat with the format "call FileNameHere".

To run the code, run the RunMeToUpdate.bat file and allow admin permissions when asked.

# Other Info
Installer packages are just batch files with command line in them.

The default packages are explained here:

  ExamplePackage: Echoes (prints) some text that says its an example.
  
  UpdatePyFRC: Updates/installs the PyFRC python libraries.
  
  UpdateRobotPy-CTRE: Updates/installs the RobotPy-CTRE python libraries.
