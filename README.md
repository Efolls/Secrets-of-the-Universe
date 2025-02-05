<h1>Welcome to <i><b>THE SECRETS OF THE UNIVERSE!!</b></i>i></h1>

Allow Windows Hello:
1. Search for 'Edit Group Policy" in the start menu and open the utility.
2. Navigate to 'Computer Configuration, Administrative Template, Windows Components, Windows Hello for Business'.
3. Double Click 'Use Windows Hello for Business' and Enable it.
4. Double Click 'Use Biometrics' and Enable it.
5. Done!

Set Up Windows Hello:
1. Search for 'Settings' in the start menu and open the application. (or alternatively press CTRL+I)
2. Navigate to 'Accounts' and then 'Sign-In Options'
3. Select your chosen Biometric Authentication Method and follow the setup procedure.
4. Once you are prompted select Use another authenticator app.
5. Install the Authenticator Chrome Extension on a chosen browser with no extension restrictions. (https://chromewebstore.google.com/detail/authenticator/bhghoamapcdpbohphigoooaddinpkbai)
6. Screenshot the qr code and upload it to the authenticator app by pressing the 'Pencil, +, Import QR Images'.
7. Type in the 6 digit code from the authenticator app.
8. Done!
(The authenticator setup prosses may not work if the page has been open for too long. If it does not work correctly, restart the hello setup prosses.)

Remove Blocked Chrome Extensions:
1. Search for 'Registry Edit" in the start menu and open the utility.
2. Navigate to 'Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome\ExtensionInstallBlocklist'.
3. Open the value named '1' and replace the asterisk with any text of your choice. (I chose 'no')
4. Reopen Chrome or reload the Policies.
5. Done!

All of these processes are reversable by simply renaming the edited values or switching the policies back to 'Not Defined'.
