Engram keyboard layout for Mac OSX
===========

There are 2 layout options. 
* Engram - all inputs will use the Engram layout.
* Engram + QWERTY ⌘ - all command shortcuts will use the QWERTY layout.

## Installation

 * Copy to a Keyboard Layouts directory:
   * Copying the bundle to /Library/Keyboard Layouts/ requires administrator rights to the computer, but will allow the layout system-wide, including the OS X login screen. To enable input options on the login window, check the option in System Preferences / Users & Groups / Login Options / Show Input menu in login window.
	* ~/Library/Keyboard Layouts/ needs less access and is specific to just the user’s account it is saved to.
 * Log out of OS X and log back in.
 * Open System Preferences, click on the Language & Text icon, and in the Input Menu tab enable the Engram layout.
 * Make sure that the Show input menu in menu bar box is also checked.

## Tools

Ukelele to create the layout:
http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele

----------

## Extensions

Since Engram has the center zone for symbol letters, combinations with Control key and them are dead.
So I added alternative places to the farest letters as follows.

| key       | generated code |
|-----------|----------------|
| Control-' |     `     |
| Control-" |     @     |
| Control-, |     \     |
| Control-. |     /     |
| Control-- |     $     |
| Control-? |     #     |

Now the path delimiter is in the home position!

**Warning: this does not work on standard terminal of macOS.** I use Alacritty.
