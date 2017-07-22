WeiDU Syntax Highlighters for Notepad++
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Author: Argent77
Version: 3.12

Highlighters included:
- WeiDU_TP2.xml: WeiDU script files (*.tp2,*.tph,*.tpa,*.tpp)
- WeiDU_BAF.xml: Script text files (*.baf)
- WeiDU_D.xml: WeiDU dialog files (*.d)
- WeiDU_TRA.xml: WeiDU translation files (*.tra)
The syntax highlighter files work in Notepad++ 6.3 and higher.

Installing the syntax highlighters:
1. Select Language->Define your language... in your Notepad++ menu.
2. (optional) If you already have an older version installed, you should 
   remove it by selecting the appropriate language from the drop-down menu 
   and click the "Remove" button to avoid duplicate entries.
3. Click the "Import..." button and select the respective XML file.
4. Repeat step 2 and 3 for all syntax highlighters you need.
5. Restart Notepad++ to make the changes visible. You should now see the new 
   entries in the Language menu.

Note:
As more and more keywords have been added to the highlighters, Notepad++ 
may become slower to apply the color schemes. This is especially apparent when 
you switch tabs or change view modes within Notepad++.
That's why I'm offering WeiDU Syntax Highlighters 'Light' for Notepad++ as an 
alternative. It reduces the number of keywords to a bare minimum. You can find 
it somewhere in the download section of the Spellhold Studios website.

If you want to install both the full and the light package of the WeiDU Syntax 
Highlighters, the order of installation determines which version is applied 
automatically when opening a script file in Notepad++. The editor applies the 
first highlighting scheme found in the list of user-defined languages matching 
the file type.

Have fun!


History:
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
