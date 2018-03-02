# Did-I-Check
The ultimate did I check list for programming

found [here](https://blogs.msdn.microsoft.com/micahel/2004/07/07/did-i-remember-to/).

Accessibility

- Check the following MSAA property settings for every control on every dialog, command bar, and other UI feature: NAME, ROLE, STATE, VALUE, KBSHORTCUT, and DEFACTION
- Change values in edit boxes and verify those values are reflected in the MSAA property set
- Run in high contrast mode
- Run in large font mode
- Run with Sound Sentry
- Run with sticky keys and other mouse key settings
- Verify focus events are passed when controls receive focus
- Verify that all audio, video, and animations have supporting textual scripts, screen narration, and/or closed captioning
- Verify that text is rendered as text, not as bitmaps
- Verify tabbing order
- Verify shortcut keys exist for each control
- Verify that each actionable color item can have its color customized (e.g., red squiggly lines)
- Verify that all flashing objects flash to the system cursor blink rate
Alerts

- Verify each alert identifies the problem first and then a solution
- Verify alert text is not unnecessarily long (i.e., more than 3 lines)
- Verify alert text is consistently worded and consistent in style
- Verify alert text is correct and appropriate for the situation
- Verify alert text contains complete sentences with correct capitalization and punctuation
- Verify alert text avoids using abbreviations and acronyms
- Verify alert text does not use an accusatory tone but rather is polite and helpful
- Verify alert text uses the product name where necessary, not "we"
- Verify the buttons work correctly
- Verify the buttons have unique access keys
- Verify alert text is localized correctly
- Verify the correct icon (Information, Warning, Critical) is displayed on the left hand side
- Verify the title bar contains the name of the product (e.g., "Microsoft Bob")
- Verify the buttons are centered below the message text
Anti-Virus

- Test with and without anti-virus software installed
Application Interoperability 

- Verify clipboard operations (i.e., cut/copy/paste) between this and other features, between this and other applications
- Verify drag and drop operations between this and other features, between this and other applications
Boundary Cases 

- Text length (e.g., of a list entry, in a field)
- Extra-long filenames
- Spaces in the text (e.g., of a list entry, field name)
- Duplicate items
- Large selection (e.g., the entire document or list)
- Giant files
- 4096 x 4096 pixel image
- Maximum number of objects (e.g., shapes, columns)
- Maximum and minimum values (e.g., for margins, values in edit boxes)
CPU

- Multiple processors
- Multiple vendors CPU's (e.g., Intel, AMD)
- Laptop configurations
Dialogs

- Verify default edit focus and default button focus is correct
- Verify tab order
- Verify dialog and terms used therein are consistent with those in the rest of the application
- Verify ninched controls are shaded
- Verify mutually exclusive controls work correctly
Verify any samples in the dialog reflect the actual formatting in the document
- Verify all commands that launch dialogs (e.g., F12 to Save As)
- Verify every control has a short-cut letter, that all short-cuts work, and that every action can be executed via the keyboard
- Verify every accelerator is unique within the dialog
- Verify the dialog's title is correct
- Verify the menu command to show dialovg is followed with "..."
- Verify the sizing and spacing of all controls matches the design standard
- Verify all dialog states, especially including more or less controls being visible due to application state or settings
- Verify the correct system controls display on the title bar, and that they work correctly
- Verify help topics are correct
- Verify dialog tips (right-click on a control) are correct
- Verify status bar text is correct
- Verify the dialog displays and functions correctly with different color, font, and high contrast settings
- Verify the dialog displays and functions correctly in high DPI mode
- Verify all bitmaps being used with the text in the dialog are correctly localized
- Verify controls respond correctly to valid and invalid input
- Verify controls respond correctly to boundary case input (e.g., correct alerts are shown)
- Verify Escape cancels the dialog
- Verify the dialog is sticky (or not, as appropriate); i.e., it displays in same position as when last dismissed
- Verify settings in the dialg are saved (or not, as appropriate) the next time the dialog is invoked
- Verify the dialog is sized correctly in relation to its controls
File Names

- With and without the complete path
- With and without the extension
- Long file names
- Short file names
- Deep directory levels
- International characters
- Invalid characters (e.g., '?')
- Invalid filenames (e.g., COM1, COM1.txt)
Hardware

- Tablet PC
- Removable Media
- Pocket PC
- Run with Power Management settings enabled and disabled
International Sufficiency 

- Look for geo-political sensitivity issues (e.g., borders may be disputed between neighboring countries)
- Run with Complex scripts and Right to Left (RTL) support
- Verify all controls function correctly with the East Asian (IME)
- Verify switching the keyboard to a different mapping works correctly
- Verify system locale, unicode, and non-active code page support functions correctly
- Verify ANSI, double-byte, and Unicode text are handled correctly for display, input, and elsewhere (e.g., double-byte characters - will be split if treated as ANSI)
- Verify any language-dependant features work correctly
- Verify extended and non-standard characters are displayed and handled correctly
- Verify the executable and other core files function correctly on any code page and any supported OS language
- Verify the correct sorting order is used.
- Verify user locale or system locale are used as appropriate.
Localization 

- Look for geo-political sensitivity issues (e.g., borders may be disputed between neighboring countries)
- Verify you know which languages to test
- Verify controls in dialogs and elsewhere are aligned and sized correctly (e.g., text is not truncated)
- Verify any functionality affected by the localization process works correctly
- Verify data is ordered correctly
- Verify tab order is correct
- Verify no unlocalized strings remain
- Verify accelerators are localized
- Verify hot keys are localzied
- Verify each accelerator is unique and consistent
- Verify each hot key is unique and consistent
Menus and Command Bars 

- Verify all commands work from menus and command bars
- Verify keyboard shortcuts are correct on all platforms
- Verify built-in menu items on a custom commandbar work correctly
- Verify commands are visible and/or enabled only when appropriate
- Verify command captions are correct and consistent with similar terms used elsewhere
- Verify custom commands work when dragged onto built-in menus and toolbars
- Verify voice command works correctly
- Verify menu/command bar item context menus work correctly
- Verify status bar text is correct and not truncated
Miscellaneous -- Have you

- Completed the spec inspection has been completed
- Discussed the feature design and target users with your Program Manager
- Done real world testing (i.e., used the application the way the user will)
- Talked with your developer about the areas they think need special attention
- Brainstormed test cases with the rest of your team
- Discussed cross-feature implications with the rest of your team
- Discussed the feature/application with Product Support
- Perused bugs and other feedback from beta releases
- Considered backward compatibility problems resulting from something that has been moved or modified changing default values or - - breaking something in a previous version
Networking

- Verify correct handling of different levels of user access and permissions
- Verify correct handling of loss of network access
- Verify correct handling of user authentication requests
- Verify correct handling of file access via mapped drive (mapped root drive where supported)
- Verify correct handling of file access via UNC
- Verify correct handling of Print Preview when the network printer is disconnected
- Verify correct handling of long file name and long-file-name-to-short-file-name conversion correctly
Open/Save

- Open/Save from/to Sharepoint Document Library
- Context menu | Open, New, Print
- Drag-and-drop
- Double-click a shortcut on the Desktop
- Most Recently Used list
- Command line argument
- Read-only files, directories, floppies, drives
- Open from/save to over various types and speeds of network connections
- Open from/save to different types of prototols (e.g., FAT, NTFS, UNC, http://, ftp://, floppy)
- Open from/save to previous versions; roundtrip from/to previous versions
- Open/save documents created in a different language-version of the application
- Interrupted
- File/Path name (e.g., long filenames, spaces in name)
- Auto-save
- Save when no documents are dirty, one document is dirty, multiple documents are dirty
- Save when multiple documents are dirty but the user chooses to not save some of them
- Save As
Out Of Memory (OOM)/Stress Testing 

- Low memory
- Low disk space
- OOM caused via automation
- OOM caused via real world scenarios
- Minimum requirements machine
- Flaky network
- Too may users
- Working with floppies
- Aborting operations (e.g., user cancels, network cable pulled)
- Pen And Speech Input
- Speech Tips
- Handwriting Tips (non-TabletPC)
- Microsoft and non-Microsoft Input Method Editors (IMEs)
- Unaware application support enabled and disabled (Windows SP1 or later only)
- Handwriting/speech/IME on Tablet PC Windows
Performance

- Verify perf testing has been done
- Verify perf targets exist and are being met
- Verify the correct data is being benchmarked
- Verify performance with Clear Type turned on
- Verify performance optimizations actually have the intended effect
- Compare performance with previous versions
- Compare performance with similar applications
Platforms

- Run on every supported platform; at a minimum, probably, Win XP, Win Vista, Win 7, Win 10, Mac, Linux
Printing

- Verify changing orientation works properly
- Verify printing to a file works properly
- Verify collation works properly
- Verify "Number of Copies" works properly
- Verify color printing works properly
- Verify canceling printing works properly
- Verify scaling works properly
- Verify line or page numbering works properly (if supported)
- Print to both local and network printers
- Print to Adobe Acrobat to create PDF files
Registry / Configuration File Settings

- Verify settings that should modify behavior do
- Verify the appropriate settings are available in policy templates
- Verify settings roam with the user
Security 

- Consider what buffer overrun attacks might be possible
- Consider what denial of service attacks might be possible
- Consider what SQL injection attacks might be possible
- Consider what virus attacks might be possible
- Verify no NULL DACLS are created or used.
- Verify security for links and macros is sufficient and works correctly
- Verify filenames such as "......file" are handled correctly
- Verify any temporary files are created in appropriate locations and have appropriate permissions
- Verify any user-created files have appropriate permissions
- Verify the application functions correctly under different user rights and roles
- Verify user-specified input is handled correctly (e.g., are SQL injection attacks possible)
- Verify every input is bounds-checked
- Verify user privacy is not violated (e.g., file paths are stripped, user aliases and other identifying data can be removed)
Setup - General

- Consider what problems could appear when installing as Minimum, Typical, Install on First Use, Run from Network, Custom, and Not Available.
- Verify registry items are created/modified appropriately, and that other registry items are not created or modified.
- Verify the application works correctly when portions of it have been disabled by an administrator
- Verify any files shared with another feature or application are handled correctly
- Verify installing and uninstalling the application or feature has the correct effect (which may be "nothing should change) on other features and applications
- Verify "normal" users can use the application when it is installed by an administrator
- Verify the correct files are installed when the application is installed via Install On First Use
- Verify mass deployment (e.g., via Systems Management Server) works correctly
- Verify the application works correctly on Terminal Server
- Verify the application works correctly on Virtual PC and Virtual Server
Setup - Local Caching 

- Verify the correct CABs are cached
- Verify any files shared with another feature or appliation are handled correctly by install/uninstall/reinstall
- Verify multiple SKUs share the cache correctly
- Verify deleting a CAB from the cache causes a reinstall and the CAB is recached
Setup - MSI Authoring

- Verify the MSI includes the correct components, files, and registry settings
- Verify custom actions, conditions, shortcut creation, and other special authoring works correctly
- Verify the default installation type (e.g., Typical, Minimum) is correct
- Verify the correct install states are available
- Verify the application works correctly in all possible install states
Setup - Multi-User

- Verify the application works correctly for User2 after User1 installs it
- Verify per-user features must be installed by User2 even after User1 has installed them
- Verify User2's per-user settings do not change when User1 changed them
Setup - Network Setup 

- Does your feature uninstall cleanly when installed from the network (Post-Admin install)
- Verify the correct files are installed when the application is installed via Run From Network
- Verify the application can be uninstalled
Special Modes and States 

- Safe Mode (e.g., booting with /safe to disable some settings) works correctly (if supported)
- Zoomed (e.g., 100%, 25%, 200%)
- Send To
- Sharing documents between multiple users/machines
- Cut, copy, delete
- MDI, SDI
- No file open (just app shell)
- Full screen view
- No command bars visible
- Application and document (e.g., minimized, maximized, sized really small)
- OLE
- Autosave on
- System background color changed
- Multiple selection
Undo/Redo 

- Edit/Undo, Edit/Redo
- Multi-level Undo/Redo
- Menu command text strings
Upgrade and Migration - Application Upgrade

- Verify upgrading over a previous version replaces appropriate files but no others
- Verify side-by-side installs work correctly
- Verify the correct files (and versions thereof) exist after an upgrade
- Verify default settings are correct
- Verify previously existing settings and files are modified correctly by an upgrade
- Verify the application functions correctly when the previous and/or new version are set to Run From Network
- Verify any features or applications dependent on files or functionality affected by the upgrade work correctly after the upgrade
Upgrade and Migration - OS Upgrade 

Verify upgrading over a previous version replaces appropriate files but no others
Verify the application works correctly after the upgrade
Verify any features dependent on OS files or functionality work correctly after the upgrade
Verify the application works correctly after upgrading both the application and the OS
User Assistance/Help

Verify each error message is accurate, easily understood, and actionable
Verify input validation error messages refer to the correct problem
Verify the tutorial is correct (e.g., the UI it depicts matches the actual UI, the steps it takes are correct)
Verify all help topics have been reviewed for technical accuracy
Verify all context sensitive help is correct
Video

Multi-monitor environments (two, three and four monitors)
Video resolutions (1024x768 through 1600x1200)
color depths (8-, 16-, 24-, and 32-bit)
Color themes
Window Interactions 

IME
Z-ordering, especially Help on top
Modal, modeless dialogs
Window and dialog focus
Window size after a restore-from-minimize, restore-from-maximize
Window size on first launch, on subsequent launches
Window size after a manual resize
Multiple windows (MDI)
Multiple instances of the application
Arrange Vertical, Horizontal, All, Tiled, Cascade (both MDI children and application windows on the Desktop)
Windows Logo Requirements

Run all applicable Application Verifier tests (especially check that NULL DACLs are not used or created)
Install and run under Application Verifier with the “High Version Lie” test enabled
Install and run with Fast User Switching enabled, while Fast User Switched
Install and run on Windows 2000, then upgrade to Windows XP
Install and run in a highly secure Windows environment (“%system%securitytemplateshisecwsinf)
Run as a limited user
Verify temp files are placed properly
Verify System File Protection files are not overwritten
Verify that My Documents is the initial default location for Open and Save
Verify all UI inherits Windows XP themes
Verify files outside of the application folder are associated with a particular file type (i.e., double-clicking does the right thing)
Verify all executable components have a (correct) digital signature
Verify all UI is legible and accessible at 133DPI (high DPI)
Year 2000 

Verify dates entered with a two-digit year are interpreted as:
 1/1/00 through 12/31/29 are interpreted as 1/1/2000 through 12/31/2029
 1/1/30 through 12/31/99 are interpreted as 1/1/1930 through 12/31/1999
Verify dates on leap years are correctly interpreted (e.g., 2/29/2000, 2/29/2004)
Verify dates at least to 2035 are supported
 
