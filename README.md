# 🧰 Microsoft Windows Control Panel
Zoznam príkazov a možnosti pre ovládací panel (control panel - control.exe) v Microsoft Windows

| N   | Položka ovládacieho panelu                       | Príkazy                                                                                              |
|-----|--------------------------------------------------|------------------------------------------------------------------------------------------------------|
| 1   | Add a Device wizard                              | %windir%\System32\DevicePairingWizard.exe                                                            |
| 2   | Add Hardware wizard                              | %windir%\System32\hdwwiz.exe                                                                         |
| 3   | Add a Printer wizard                             | rundll32.exe shell32.dll,SHHelpShortcuts_RunDLL AddPrinter                                           |
| 4   | Additional Clocks                                | rundll32.exe shell32.dll,Control_RunDLL timedate.cpl,,1                                              |
| 5   | Administrative Tools                             | control /name Microsoft.AdministrativeTools                                                          |
| 6   | Administrative Tools                             | control admintools                                                                                   |
| 7   | AutoPlay                                         | control /name Microsoft.AutoPlay                                                                     |
| 8   | Backup and Restore (Windows 7)                   | control /name Microsoft.BackupAndRestoreCenter                                                       |
| 9   | BitLocker Drive Encryption                       | control /name Microsoft.BitLockerDriveEncryption                                                     |
| 10  | Color and Appearance                             | explorer shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921} -Microsoft.Personalization\pageColorization  |
| 11  | Color Management                                 | control /name Microsoft.ColorManagement                                                              |
| 12  | Credential Manager                               | control /name Microsoft.CredentialManager                                                            |
| 13  | Date and Time (Date and Time)                    | control /name Microsoft.DateAndTime                                                                  |
| 14  | Date and Time (Date and Time)                    | control timedate.cpl                                                                                 |
| 15  | Date and Time (Date and Time)                    | control date/time                                                                                    |
| 16  | Date and Time (Date and Time)                    | rundll32.exe shell32.dll,Control_RunDLL timedate.cpl,,0                                              |
| 17  | Date and Time (Additional Clocks)                | rundll32.exe shell32.dll,Control_RunDLL timedate.cpl,,1                                              |
| 18  | Default Programs                                 | control /name Microsoft.DefaultPrograms                                                              |
| 19  | Desktop Background                               | explorer shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921} -Microsoft.Personalization\pageWallpaper     |
| 20  | Desktop Icon Settings                            | rundll32.exe shell32.dll,Control_RunDLL desk.cpl,,0                                                  |
| 21  | Device Manager                                   | control /name Microsoft.DeviceManager                                                                |
| 22  | Device Manager                                   | control hdwwiz.cpl                                                                                   |
| 23  | Device Manager                                   | devmgmt.msc                                                                                          |
| 24  | Devices and Printers                             | control /name Microsoft.DevicesAndPrinters                                                           |
| 25  | Devices and Printers                             | control printers                                                                                     |
| 26  | Ease of Access Center                            | control /name Microsoft.EaseOfAccessCenter                                                           |
| 27  | Ease of Access Center                            | control access.cpl                                                                                   |
| 28  | File Explorer Options (General tab)              | control /name Microsoft.FolderOptions                                                                |
| 29  | File Explorer Options (General tab)              | control folders                                                                                      |
| 30  | File Explorer Options (General tab)              | rundll32.exe shell32.dll,Options_RunDLL 0                                                            |
| 31  | File Explorer Options (View tab)                 | rundll32.exe shell32.dll,Options_RunDLL 7                                                            |
| 32  | File Explorer Options (Search tab)               | rundll32.exe shell32.dll,Options_RunDLL 2                                                            |
| 33  | File History                                     | control /name Microsoft.FileHistory                                                                  |
| 34  | Fonts                                            | control /name Microsoft.Fonts                                                                        |
| 35  | Fonts                                            | control fonts                                                                                        |
| 36  | Game Controllers                                 | control /name Microsoft.GameControllers                                                              |
| 37  | Game Controllers                                 | control joy.cpl                                                                                      |
| 38  | Get Programs                                     | control /name Microsoft.GetPrograms                                                                  |
| 39  | Get Programs                                     | rundll32.exe shell32.dll,Control_RunDLL appwiz.cpl,,1                                                |
| 40  | HomeGroup                                        | control /name Microsoft.HomeGroup                                                                    |
| 41  | Indexing Options                                 | control /name Microsoft.IndexingOptions                                                              |
| 42  | Indexing Options                                 | rundll32.exe shell32.dll,Control_RunDLL srchadmin.dll                                                |
| 43  | Infrared                                         | control /name Microsoft.Infrared                                                                     |
| 44  | Infrared                                         | control irprops.cpl                                                                                  |
| 45  | Infrared                                         | control /name Microsoft.InfraredOptions                                                              |
| 46  | Internet Properties (General tab)                | control /name Microsoft.InternetOptions                                                              |
| 47  | Internet Properties (General tab)                | control inetcpl.cpl                                                                                  |
| 48  | Internet Properties (General tab)                | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,0                                               |
| 49  | Internet Properties (Security tab)               | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,1                                               |
| 50  | Internet Properties (Privacy tab)                | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,2                                               |
| 51  | Internet Properties (Content tab)                | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,3                                               |
| 52  | Internet Properties (Connections tab)            | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,4                                               |
| 53  | Internet Properties (Programs tab)               | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,5                                               |
| 54  | Internet Properties (Advanced tab)               | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,6                                               |
| 55  | iSCSI Initiator                                  | control /name Microsoft.iSCSIInitiator                                                               |
| 56  | Keyboard                                         | control /name Microsoft.Keyboard                                                                     |
| 57  | Keyboard                                         | control keyboard                                                                                     |
| 58  | Language                                         | control /name Microsoft.Language                                                                     |
| 59  | Mouse Properties (Buttons tab 0)                 | control /name Microsoft.Mouse                                                                        |
| 60  | Mouse Properties (Buttons tab 0)                 | control main.cpl                                                                                     |
| 61  | Mouse Properties (Buttons tab 0)                 | control mouse                                                                                        |
| 62  | Mouse Properties (Buttons tab 0)                 | rundll32.exe shell32.dll,Control_RunDLL main.cpl,,0                                                  |
| 63  | Mouse Properties (Pointers tab 1)                | control main.cpl,,1                                                                                  |
| 64  | Mouse Properties (Pointers tab 1)                | rundll32.exe shell32.dll,Control_RunDLL main.cpl,,1                                                  |
| 65  | Mouse Properties (Pointer Options tab 2)         | control main.cpl,,2                                                                                  |
| 66  | Mouse Properties (Pointer Options tab 2)         | rundll32.exe shell32.dll,Control_RunDLL main.cpl,,2                                                  |
| 67  | Mouse Properties (Wheel tab 3)                   | control main.cpl,,3                                                                                  |
| 68  | Mouse Properties (Wheel tab 3)                   | rundll32.exe shell32.dll,Control_RunDLL main.cpl,,3                                                  |
| 69  | Mouse Properties (Hardware tab 4)                | control main.cpl,,4                                                                                  |
| 70  | Mouse Properties (Hardware tab 4)                | rundll32.exe shell32.dll,Control_RunDLL main.cpl,,4                                                  |
| 71  | Network and Sharing Center                       | control /name Microsoft.NetworkAndSharingCenter                                                      |
| 72  | Network Connections                              | control ncpa.cpl                                                                                     |
| 73  | Network Connections                              | control netconnections                                                                               |
| 74  | Network Setup Wizard                             | control netsetup.cpl                                                                                 |
| 75  | Notification Area Icons                          | explorer shell:::{05d7b0f4-2121-4eff-bf6b-ed3f69b894d9}                                              |
| 76  | ODBC Data Source Administrator                   | control odbccp32.cpl                                                                                 |
| 77  | Offline Files                                    | control /name Microsoft.OfflineFiles                                                                 |
| 78  | Performance Options (Visual Effects)             | %windir%\system32\SystemPropertiesPerformance.exe                                                    |
| 79  | Performance Options (Data Execution Prevention)  | %windir%\system32\SystemPropertiesDataExecutionPrevention.exe                                        |
| 80  | Personalization                                  | explorer shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921}                                              |
| 81  | Phone and Modem                                  | control /name Microsoft.PhoneAndModem                                                                |
| 82  | Phone and Modem                                  | control telephon.cpl                                                                                 |
| 83  | Power Options                                    | control /name Microsoft.PowerOptions                                                                 |
| 84  | Power Options                                    | control powercfg.cpl                                                                                 |
| 85  | Power Options - Advanced settings                | control powercfg.cpl,,1                                                                              |
| 86  | Power Options - Create a Power Plan              | control /name Microsoft.PowerOptions /page pageCreateNewPlan                                         |
| 87  | Power Options - Edit Plan Settings               | control /name Microsoft.PowerOptions /page pagePlanSettings                                          |
| 88  | Power Options - System Settings                  | control /name Microsoft.PowerOptions /page pageGlobalSettings                                        |
| 89  | Presentation Settings                            | %windir%\system32\PresentationSettings.exe                                                           |
| 90  | Programs and Features                            | control /name Microsoft.ProgramsAndFeatures                                                          |
| 91  | Programs and Features                            | control appwiz.cpl                                                                                   |
| 92  | Recovery                                         | control /name Microsoft.Recovery                                                                     |
| 93  | Region (Formats tab)                             | control /name Microsoft.RegionAndLanguage                                                            |
| 94  | Region (Formats tab)                             | control /name Microsoft.RegionalAndLanguageOptions /page /p:"Formats"""                              |
| 95  | Region (Formats tab)                             | control intl.cpl                                                                                     |
| 96  | Region (Formats tab)                             | control international                                                                                |
| 97  | Region (Location tab)                            | control /name Microsoft.RegionalAndLanguageOptions /page /p:"Location"""                             |
| 98  | Region (Administrative tab)                      | control /name Microsoft.RegionalAndLanguageOptions /page /p:"Administrative"""                       |
| 99  | RemoteApp and Desktop Connections                | control /name Microsoft.RemoteAppAndDesktopConnections                                               |
| 100 | Scanners and Cameras                             | control /name Microsoft.ScannersAndCameras                                                           |
| 101 | Scanners and Cameras                             | control sticpl.cpl                                                                                   |
| 102 | Screen Saver Settings                            | rundll32.exe shell32.dll,Control_RunDLL desk.cpl,,1                                                  |
| 103 | Security and Maintenance                         | control /name Microsoft.ActionCenter                                                                 |
| 104 | Security and Maintenance                         | control wscui.cpl                                                                                    |
| 105 | Set Associations                                 | control /name Microsoft.DefaultPrograms /page pageFileAssoc                                          |
| 106 | Set Default Programs                             | control /name Microsoft.DefaultPrograms /page pageDefaultProgram                                     |
| 107 | Set Program Access and Computer Defaults         | rundll32.exe shell32.dll,Control_RunDLL appwiz.cpl,,3                                                |
| 108 | Sound (Playback tab)                             | control /name Microsoft.Sound                                                                        |
| 109 | Sound (Playback tab)                             | control mmsys.cpl                                                                                    |
| 110 | Sound (Playback tab)                             | %windir%\System32\rundll32.exe shell32.dll,Control_RunDLL mmsys.cpl,,0                               |
| 111 | Sound (Recording tab)                            | %windir%\System32\rundll32.exe shell32.dll,Control_RunDLL mmsys.cpl,,1                               |
| 112 | Sound (Sounds tab)                               | %windir%\System32\rundll32.exe shell32.dll,Control_RunDLL mmsys.cpl,,2                               |
| 113 | Sound (Communications tab)                       | %windir%\System32\rundll32.exe shell32.dll,Control_RunDLL mmsys.cpl,,3                               |
| 114 | Speech Recognition                               | control /name Microsoft.SpeechRecognition                                                            |
| 115 | Storage Spaces                                   | control /name Microsoft.StorageSpaces                                                                |
| 116 | Sync Center                                      | control /name Microsoft.SyncCenter                                                                   |
| 117 | System                                           | control /name Microsoft.System                                                                       |
| 118 | System                                           | control sysdm.cpl                                                                                    |
| 119 | System Icons                                     | explorer shell:::{05d7b0f4-2121-4eff-bf6b-ed3f69b894d9} \SystemIcons,,0                              |
| 120 | System Properties (Computer Name)                | %windir%\System32\SystemPropertiesComputerName.exe                                                   |
| 121 | System Properties (Hardware)                     | %windir%\System32\SystemPropertiesHardware.exe                                                       |
| 122 | System Properties (Advanced)                     | %windir%\System32\SystemPropertiesAdvanced.exe                                                       |
| 123 | System Properties (System Protection)            | %windir%\System32\SystemPropertiesProtection.exe                                                     |
| 124 | System Properties (Remote)                       | %windir%\System32\SystemPropertiesRemote.exe                                                         |
| 125 | Tablet PC Settings                               | control /name Microsoft.TabletPCSettings                                                             |
| 126 | Text to Speech                                   | control /name Microsoft.TextToSpeech                                                                 |
| 127 | Troubleshooting                                  | explorer shell:::{26EE0668-A00A-44D7-9371-BEB064C98683}\0\::{C58C4893-3BE0-4B45-ABB5-A63E4B8C8651}   |
| 128 | User Accounts                                    | control /name Microsoft.UserAccounts                                                                 |
| 129 | User Accounts                                    | control userpasswords                                                                                |
| 130 | User Accounts (netplwiz)                         | netplwiz                                                                                             |
| 131 | User Accounts (netplwiz)                         | control userpasswords2                                                                               |
| 132 | Windows Defender Firewall                        | control /name Microsoft.WindowsFirewall                                                              |
| 133 | Windows Defender Firewall                        | control firewall.cpl                                                                                 |
| 134 | Windows Defender Firewall Allowed apps           | explorer shell:::{4026492F-2F69-46B8-B9BF-5654FC07E423} -Microsoft.WindowsFirewall\pageConfigureApps |
| 135 | Windows Defender Firewall with Advanced Security | %WinDir%\System32\WF.msc                                                                             |
| 136 | Windows Features                                 | %windir%\System32\OptionalFeatures.exe                                                               |
| 137 | Windows Features                                 | rundll32.exe shell32.dll,Control_RunDLL appwiz.cpl,,2                                                |
| 138 | Windows Mobility Center                          | control /name Microsoft.MobilityCenter                                                               |
| 139 | Work Folders                                     | %windir%\System32\WorkFolders.exe                                                                    |
