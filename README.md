arrow-generator
=========================
This is a script that uses AutoHotkey to automatically generate arrows in the Stepmania/OpenITG chart editor.
r21freak thread: http://r21freak.com/phpbb3/viewtopic.php?f=38&t=21866

Rules/Restrictions:
- No crossovers
- No double steps
- Doesn't repeat an alternating arrow more than 3 times (left right left down left up ____ <- will not be another left)
- Patterns will switch directions around every half measure (http://r21freak.com/insanesteve/guide/f ... ection.PNG)

How to use:
1. Download the script and autohotkey.
2. Install autohotkey
3. Open autohotkey and right click the icon on the taskbar (bottom right of your screen, it should be a green button with a white H)
4. Click "Edit This Script" and paste the script into the text file
5. Save and right click the autohotkey icon again
6. Click "Reload This Script" and it should be ready to use

Controls:
- Numpad1 - Generates a single arrow that fits with previously generated arrows. If there are no previous arrows it will start on either a left or right arrow. Generates 3 arrows when switching directions/transitioning.
- Numpad2 - Same as Numpad1 but continually generates arrows without having to hold down.
- Numpad3 - Stops the arrow generation from Numpad2.
- Numpad4 - Clears the generator's history. When you start generating a new pattern with Numpad1/2 it will start facing left.
- Numpad5 - Clears the generator's history. When you start generating a new pattern it will start facing left or right.
- Numpad6 - Clears the generator's history. When you start generating a new pattern it will start facing right.