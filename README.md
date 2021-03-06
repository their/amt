For the website mturk.com, Amazon.com's Mechanical Turk workplace. A set of tools to improve Worker productivity.

Adds a Tools button and Tools Menu. The tools edit parts of the user interface of the site, such as modifying the display of the job window. Other tools include a "Return and Accept" button, placing the cursor in the CAPTCHA text box.

✫ Full-screen mode to help maximize productivity on tasks.

✫ Customize full-screen settings including task window height, width, and vertical offset.

✫ Setting to always check the checkbox for "Automatically accept the next HIT".

✫ "Open and accept" button to quickly open up to 25 tabs (New Feature!)

✫ Button to turn off "Automatically accept the next HIT" checkboxes in all open tabs and windows.

✫ CAPTCHA-simplification features including: 1) Place the cursor in CAPTCHA box when a CAPTCHA appears; 2) Clears wrong answer from the CAPTCHA text box if CAPTCHA is incorrectly entered; 3) Show an alert notification on all job windows when any job window loads a CAPTCHA; 4) Play an alert notification sound when a CAPTCHA is first encountered; 5) Seven bell notifications to select from, or select Random.

✫ "Return and Accept" button to return a current job and accept another job in the group.

The extension's source code is on github.com: https://github.com/their/amt.

Notes:
There are no guarantees made regarding the safety of using this extension on Amazon's Mechanical Turk website. The extension's author is not responsible for any risks associated with the use of this extension.

Version History:

1.1.4: Update extension to work on the new AMT website, plus add new features. Add "Open and Accept" slider. Add "Full Screen Mode" to simplify iframe settings.

1.1.3: CSS zIndex of iframe needs to be adjusted. The iframe is showing beneath some elements on the parent window.

1.1.2: Move iframe to offset when in "continue" mode but URL is "/preview". Ensures to not move to offset when actually in "preview" mode.

1.1.1: Update styles. Add support for workersandbox.mturk.com.

1.1.0: Fix to match changed "return task" elements at mturk.com.

1.0.9: In Firefox 34 calls to localStorage.hasOwnProperty() causes the script to exit prematurely. This is now fixed. Fix to a TypeError in Chrome.

1.0.8: Fixed small bug, audio did not play in one case.

1.0.7: Removed base64 audio snippets. Removed adding audio snippets from Pastebin. Placed the audio .ogg files within the extension.

1.0.5: Added button 'Disable "Automatically accept the next HIT" in all tabs and windows'. Added click to the dimmer closes the menu. Added pressing "Enter" key while cursor is in any of the two input text fields, saves the settings and closes the menu. Enabled extension in Private Browsing mode. Enabled compatibility for Firefox for Android. Removed an unnecessary setInterval, replaced with addEventListener. Some other small layout changes added.

1.0.4: Layout edits. Default settings for new users/incognito users reset to none. Add Enable All/Disable All buttons. Add a button to reset iframe's offset top.

1.0.3: Note: A change in this version makes it necessary to re-enable "Allow in incognito". Add http://pastebin.com/raw.php?i=14R5zCYR to include_globs.  Turn on some settings by default for Incognito use and/or a first-time user (Height/Width, CAPTCHA focus, CAPTCHA audio/visual alert). Small layout changes (select field focus fix). Plays an audio alert in same tab 50 seconds after last audio alert (new), in a new tab 30 seconds after last audio alert (old), replay audio alert in same tab after 60 seconds (new). Remove "key" from manifest requires user to click check box for "Allow in Incognito".
