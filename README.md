# Tapp-Tesla-macOS

Having troubles?

1. "Application downloaded from an unknown source"
Go to System Preferences -> Security [General], and click on "Open Anyway" in the bottom section of the pane.

2. No data or messed up data
  This can be caused by: 
    A: Your access token has expired. Solution: Press Logout, then log back in.
    B: You have more than one Tesla vehicle. Solution: Yell at the developer to include multi vehicle support.
    C: Network connection issues. Solution: Connect to the internet.
    D: If none of those apply, open an issue.

3. Views reloading every millisecond/strobe effect in applications.

  Close the app right away, I'm in the midst of getting to the bottom of this.

4. "Move 'Tapp' to the trash"

This is due to codesigning issues. You may have to download the xcproject file and build the application in xcode on your machine. 

[Update 1.5]
Login, Logout, new features, bug fixes


All commands currently use https json requests - updated to V1.2 which adds some fun easter eggs and bug fixes. Should be pretty self explanitory.

UserDefaults now saves the access_token for later use. V1.3 will include full Login/Logout features and more battery controls.

Depending upon the amount of updates to the application, the V1.3 release date will likely be in the last week of April. As far as V1.5 and even V2.0, May and June will be the target release dates.
