# windows-gamepad-off-center-deadzone-dll
This is a dll replacing to fix windows gamepad analog stick off center problem (stick drift) by implementing deadzone.

You may enter windows 'safe mode' and change the dll owner from 'trustedinstaller' to 'Users' to get permission to replace the system dll.
Or just place the patched dll in game execution directory. (it's not working in some case)

The files are win10 solution now.

You can compare them to see how to implement it on other windows version.
Or change the deadzone range if you want(it's 0...24 deadzone, full range is 0...128).

I don't have XBOX controller, so please let me know whether it works if you meet this requirement:)

Me happy.
