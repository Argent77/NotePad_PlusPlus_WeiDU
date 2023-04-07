WeiDU Syntax Highlighters for Notepad++
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Author: Argent77
Version: 3.15

Syntax highlighting support for:
- TP2 files (*.tp2, *.tph, *.tpa, *.tpp)
- BAF files (*.baf)
- D files (*.d)
- TRA file (*.tra)

Auto-Completion support for:
- TP2 files (*.tp2, *.tph, *.tpa, *.tpp)
- BAF files (*.baf)
- D files (*.d)

Syntax highlighting and auto-completion files require Notepad++ 6.3 or higher.


Setting up Syntax Highlighting
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Method 1: in your file manager (preferred)
1. Open the file manager and enter the path "%AppData%\Notepad++\userDefineLangs" (without the quotes) into the address bar.
   The path should resolve to "C:\Users\<your username>\AppData\Roaming\Notepad++\userDefineLangs" (on Windows Vista or later).
   Alternatively, open Notepad++ and select menu Language > User Defined Language > Open User Defined Language folder...
2. If the folder "userDefineLangs" doesn't exist yet, create it.
3. Copy all desired highlighter XML files from the "userDefineLangs" subfolder of the zip archive into the folder.
4. Restart Notepad++ to make the changes visible. You should now see new entries (WeiDU_TP2, WeiDU_BAF, ...) in the Language menu.

Method 2: in Notepad++ (deprecated)
1. Select Language->Define your language... in your Notepad++ menu.
2. (optional) If you already have an older version installed, you should remove it by selecting the appropriate language from the
   drop-down menu and click the "Remove" button to avoid duplicate entries.
3. Click the "Import..." button and select the respective XML file from the "userDefineLangs" subfolder of the zip archive.
4. Repeat step 2 and 3 for all syntax highlighters you need.
5. Restart Notepad++ to make the changes visible. You should now see the new entries in the Language menu.


Setting up Auto-Completion
~~~~~~~~~~~~~~~~~~~~~~~~~~

1. Open the file manager and navigate to the directory where Notepad++ is installed.
   By default Notepad++ is installed in "C:\Program Files\Notepad++" or "C:\Program Files (x86)\Notepad++".
   Alternatively, use Windows Search to find the location of "notepad++.exe".
2. Open the subfolder "autoCompletion" and copy all desired auto-completion XML files from the "autoCompletion" subfolder
   of the zip archive into the folder. Elevated privileges may be needed for the copy operation.
3. Start or restart Notepad++ and navigate to menu Setting > Preferences. Select "Auto-Completion" in the options list and
   activate the checkbox "Enable auto-completion on each input". Choose "Function and word completion" and enable the
   "Function parameters hint on input" checkbox. Close the Preferences dialog.


Have fun!


History:
v4.0
  - added auto-completion support for TP2, BAF and D files
  - improved syntax highlighting coloring and structure
  - internal mod restructuring
v3.15
  - added new TP2 keywords introduced by WeiDU 247
  - added several missing TP2 keywords
  - added more symbols and keywords to BAF, D and TP2
  - added more internal TP2 variables
  - removed syntax folding from TP2
  - fixed ambiguous coloring of several TP2 keywords
  - internal cleanups
v3.14
  - added new TP2 keywords introduced by WeiDU 245
  - added several missing TP2 keywords
  - added more script triggers and actions added by EE patch 2.5
v3.13
  - added new keywords introduced by WeiDU 243
  - added new script triggers added by EE patch 2.5
v3.12
  - added double quote string delimiter support to WeiDU_TRA
  - added colored text delimiter to WeiDU_TRA
  - added new keywords introduced in WeiDU 241
  - added convenience trigger command TriggerOverride
v3.11
  - added new object specifiers
  - added new script actions, triggers and keywords introduced in game engine v2.0
  - added new keywords introduced in WeiDU 240
v3.10
  - added new TP2 keywords introduced in WeiDU 239
  - added a missing RACE.IDS identifier
  - added fixed versions of misspelled EigthNearestEnemyOfType and
    EigthNearestMyGroupOfType object specifiers
  - fixed misspelled FIND_FREE_PRVZ_INDEX function name
  - moved CREATE from patch to action category
v3.9
  - added several new and undocumented TP2 keywords and function names
  - added missing sound slot identifiers
v3.8
  - removed variable delimiters (%)
  - added new TP2 keywords introduced in WeiDU 237
  - added a couple of missing keywords to TP2
  - added new script actions, triggers and objects to WeiDU_BAF, WeiDU_D and
    WeiDU_TP2 introduced in IWD:EE
v3.7
  - added tokens, triggers, actions and keywords introduced in BG:EE and BG2:EE
v3.6
  - added new keywords introduced in WeiDU 232
v3.5
  - Added a couple of new triggers introduced by the BG2 Fixpack to WeiDU_BAF,
    WeiDU_D and WeiDU_TP2
  - Added lots of new or missing identifiers from SPELL.IDS, KIT.IDS, GENDER.IDS
    and ANIMATE.IDS to WeiDU_BAF and WeiDU_D
v3.4
  - Fixed support for string numbers in WeiDU_TRA, it should now recognize
    negative numbers too
  - Had to remove support for WeiDU variables from WeiDU_TRA again, as it were
    causing trouble for regular percent signs
v3.3
  - Improved the highlighting scheme for strings in WeiDU_D and WeiDU_TRA
  - Added support for variables and tokens to WeiDU_TRA
  - Added file extension *.tpp to WeiDU_TP2
  - Added several keyword aliases to WeiDU_D
  - Added new and undocumented keywords to WeiDU_D and WeiDU_TP2
v3.2
  - Updated files to UDL v2.1 supported by Notepad++ v6.3 and later
  - Added missing dialog filenames to WeiDU_D
v3.1
  - Added support for hex, octal and binary numbers to WeiDU_TP2
v3.0
  - Updated files to UDL v2.0 supported by Notepad++ v6.2 and later
