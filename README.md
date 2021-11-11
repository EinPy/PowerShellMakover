# Windows terminal makeover

This will be accomplished using the oh-my-Posh library and modifying 
the JSON file of windows PowerShell

Steps:
1. Downlaod windows PowerShell
2. Download oh-my-Posh
	This can be done using the command:
	`Install-Module oh-my-posh -Scope CurrentUser`
	One will also need to change the excecution policies 
	of windows to make it work : https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-7.2
3. Install a nerdFont systemwide to make oh-my-Posh symbools work
	Can be found here: https://www.nerdfonts.com/font-downloads
	Unizip the file, select all, right click and install as admin
4. Change the font in the JSON file to the nerdFont
5. Open the $PROFILE of windows PowerShell and write 
the code that you want to excecute on startup of PowerShell