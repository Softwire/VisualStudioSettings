Visual Studio settings
======================

####Visual Studio (Template.vssettings)

Changes to some of the default settings for Visual Studio, e.g. auto-reload files if saved, show line numbers. Also sets up ReSharper shortcuts.

If you have spent lots of time setting up Visual Studio the way you like it you probably don't want this! Hopefully a couple of useful bits for new people.

*Applying*
* In Visual Studio, navigate to `Tools > Import and Export Settings`.
* Select `Import selected environment settings`.
* (Decide whether to export current settings or not, only matters if you want the option to go back).
* Browse to and select `Template.vssettings`, then click through to `Finish`.

####ReSharper (Template.sln.DotSettings)

Sets up some useful ReSharper things (e.g. colour identifiers, code decompilation options) and enforces a sensible default code style. The style enforced is not meant to be dogmatic but hopefully it is a useful starting point for most projects.

*Applying generally*
* In Visual Studio, navigate to `ReSharper > Manage Options`.
* Select `This computer`.
* Click `Import / Export Setting > Import From File`.
* Import the `Template.sln.DotSettings` file.

*Project specific*

* Copy the `Template.sln.DotSettings` to the root folder of your Visual Studio solution.
* Replace `Template` with the name of your solution.
* ReSharper project settings should be automatically applied in Visual Studio without restart.
* To update, select `team-shared` in the `Save To` picker in the ReSharper options dialog.

####CodeMaid (Template.CodeMaid.settings)

Works together with the ReSharper settings to enforce style.

*Applying*
* In Visual Studio, navigate to `CodeMaid > Configuration`
* Click `Import`.
* Import the `Template.CodeMaid.settings` file.

####Related
If you also need a standard gitignore for your project, grab `VisualStudio.gitignore` from https://github.com/github/gitignore (and rename to just `.gitignore`).
