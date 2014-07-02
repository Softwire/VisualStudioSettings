Visual Studio settings
======================

Standard ReSharper and CodeMaid settings for .NET projects. Enforces a sensible default code styling.

(The style enforced is not meant to be dogmatic, but it is hopefully a useful starting point for most projects!)

####Usage

######ReSharper

**To apply generally**

* In Visual Studio, navigate to `ReSharper > Manage Options`.
* Select `This computer`.
* Click `Import / Export Setting > Import From File`.
* Import the `MyProject.sln.DotSettings` file.

**Project specific**

* Copy the `MyProject.sln.DotSettings` to the root folder of your Visual Studio solution.
* Replace `MyProject` with the name of your solution.
* ReSharper project settings should be automatically applied in Visual Studio without restart.
* To update, select `team-shared` in the `Save To` picker in the ReSharper options dialog.

######CodeMaid

**Apply generally**
* In Visual Studio, navigate to `CodeMaid > Configuration`, click `Import` and select the settings file.
* To update, save changed options in the CodeMaid configuration dialog and select `Export` to save to the settings file.

**Project specific**
* As it stands, CodeMaid does not automatically apply to projects like ReSharper does.
* However it is probably worth renaming the file to match your project and checking it in to source control.

####Related
If you also need a standard gitignore for your project, grab `VisualStudio.gitignore` from https://github.com/github/gitignore (and rename to just .gitignore).
