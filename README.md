iSetMail
========

Create an App for OS X Mail for Click to Configure e-mail settings. The structure of the App is like :

iSetMail.App
|
|-Contents
		|
		|
		|--MacOS
			|--applet
		|
		|--Resources
			|
			|--Scripts
				|--main.scpt
			|--description.rtfd 	
			|--applet.icns
			|--applet.rsrc
			|--domain.txt
			|--host.txt
			|--maildir.txt
			|--user.txt
			|--useroot.txt
			|--usessl.txt
		|--_CodeSignature
			|--CodeResources
		|--config
			|--host.txt
			|--maildir.txt
			|--user.txt
			|--useroot.txt
			|--usessl.txt
		|--Info.plist
		|--Pkginfo
		

You must edit the files for your own setup. These files should go under Contents under name-op-app.App

