Visual Studio settings
======================

Standard ReSharper and CodeMaid settings for .NET projects. Enforces a sensible default code styling.

(The style enforced is not meant to be dogmatic, but it is hopefully a useful starting point for most projects!)

####Usage

######ReSharper

* Copy the `MyProject.sln.DotSettings` to the root folder of your Visual Studio solution.
* Replace `MyProject` with the name of your solution.
* ReSharper project settings should be automatically applied in Visual Studio without restart.
* To update, select `team-shared` in the `Save To` picker in the ReSharper options dialog.

######CodeMaid
* Copy the `MyProject.CodeMaid.settings` to the root folder of your Visual Studio solution.
* Replace `MyProject` with the name of your solution (though name is not actually important here).
* In Visual Studio, navigate to `CodeMaid > Configuration`, click `Import` and select the settings file.
* To update, save changed options in the CodeMaid configuration dialog and select `Export` to save to the settings file.
