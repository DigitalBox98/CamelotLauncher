# CamelotLauncher

Connect to custom DAOC Freeshard with the launcher tool and Avalonia GUI.<br>

This version requires dotnet 8 runtimes

<img width="512" alt="camelotlauncher" src="https://github.com/DigitalBox98/CamelotLauncher/assets/57635141/724ea4d0-6e99-4346-aa70-278145226029">


# Generate solution

Open the solution in Visual Studio and proceed with the build.<br>
Note: the connect.exe will be copied after compilation in the destination folder (ie CopyCustomContent in csproj file)

# Launch 

Once the solution has been generated, you can run the launcher.<br>

For Windows users : <br>
  - There's no need to use wine option, you only need to provide login/password to connect to the freeshard.
  - You can tick the option "customized settings" and specify the DAOC folder if needed. You can also specify a customized freeshard address

For Mac/Linux users : <br>
  - You will need to tick the wine option
  - Default folder which will be used is ".wine" and you can specify the wine command name (default is "wine", but you can specify for instance "wine32on64")
 
# Packaging

For Windows/Mac : <br>
  - A ZIP file containing the solution should be enough to distribute the solution



