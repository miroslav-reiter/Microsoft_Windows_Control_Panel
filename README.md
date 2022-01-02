# 🧰 Microsoft Windows Control Panel
Zoznam **139 príkazov** a možnosti pre **ovládací panel** (control panel - **control.exe**) v Microsoft Windows.

V systéme Microsoft Windows 8/10/11 existuje niekoľko rôznych spôsobov, ako nájsť a zmeniť nastavenia: 
1. **Aplikácia Nastavenia** (Settings app)
2. **Ovládací panel** (Control panel)
3. **Nastavenia aplikácie** (App settings)
4. **Vyhľadávanie** (Search)

Väčšinu nastavení, ktoré budete chcieť zmeniť, nájdete v aplikácii Nastavenia. Ovládací panel umožňuje prezerať a meniť nastavenia (ovládacie prvky) pre Windows prostredníctvom systémových apletov (najčastejšie majú **príponu cpl** - **control panel item** - položka ovládacieho panela).

| N   | Položka ovládacieho panelu [EN]                  | Položka ovládacieho panelu [SK]                               | Príkazy                                                                                              |
|-----|--------------------------------------------------|---------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| 1   | Add a Device wizard                              | Pridať zariadenia cez sprievodcu                              | %windir%\System32\DevicePairingWizard.exe                                                            |
| 2   | Add Hardware wizard                              | Pridať hardvér cez sprievodcu                                 | %windir%\System32\hdwwiz.exe                                                                         |
| 3   | Add a Printer wizard                             | Pridať tlačiareň  cez sprievodcu                              | rundll32.exe shell32.dll,SHHelpShortcuts_RunDLL AddPrinter                                           |
| 4   | Additional Clocks                                | Ďalšie hodiny                                                 | rundll32.exe shell32.dll,Control_RunDLL timedate.cpl,,1                                              |
| 5   | Administrative Tools                             | Administratívne nástroje                                      | control /name Microsoft.AdministrativeTools                                                          |
| 6   | Administrative Tools                             | Administratívne nástroje                                      | control admintools                                                                                   |
| 7   | AutoPlay                                         | Autoplay                                                      | control /name Microsoft.AutoPlay                                                                     |
| 8   | Backup and Restore (Windows 7)                   | Zálohovanie a obnovenie (Windows 7)                           | control /name Microsoft.BackupAndRestoreCenter                                                       |
| 9   | BitLocker Drive Encryption                       | Šifrovanie jednotky BitLocker                                 | control /name Microsoft.BitLockerDriveEncryption                                                     |
| 10  | Color and Appearance                             | Farba a vzhľad                                                | explorer shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921} -Microsoft.Personalization\pageColorization  |
| 11  | Color Management                                 | Správa farieb                                                 | control /name Microsoft.ColorManagement                                                              |
| 12  | Credential Manager                               | Správca poverení                                              | control /name Microsoft.CredentialManager                                                            |
| 13  | Date and Time (Date and Time)                    | Dátum a čas (dátum a čas)                                     | control /name Microsoft.DateAndTime                                                                  |
| 14  | Date and Time (Date and Time)                    | Dátum a čas (dátum a čas)                                     | control timedate.cpl                                                                                 |
| 15  | Date and Time (Date and Time)                    | Dátum a čas (dátum a čas)                                     | control date/time                                                                                    |
| 16  | Date and Time (Date and Time)                    | Dátum a čas (dátum a čas)                                     | rundll32.exe shell32.dll,Control_RunDLL timedate.cpl,,0                                              |
| 17  | Date and Time (Additional Clocks)                | Dátum a čas (ďalšie hodiny)                                   | rundll32.exe shell32.dll,Control_RunDLL timedate.cpl,,1                                              |
| 18  | Default Programs                                 | Základné programy                                             | control /name Microsoft.DefaultPrograms                                                              |
| 19  | Desktop Background                               | Pozadie pracovnej plochy                                      | explorer shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921} -Microsoft.Personalization\pageWallpaper     |
| 20  | Desktop Icon Settings                            | Nastavenia ikon na ploche                                     | rundll32.exe shell32.dll,Control_RunDLL desk.cpl,,0                                                  |
| 21  | Device Manager                                   | Správca zariadení                                             | control /name Microsoft.DeviceManager                                                                |
| 22  | Device Manager                                   | Správca zariadení                                             | control hdwwiz.cpl                                                                                   |
| 23  | Device Manager                                   | Správca zariadení                                             | devmgmt.msc                                                                                          |
| 24  | Devices and Printers                             | Zariadenia a tlačiarne                                        | control /name Microsoft.DevicesAndPrinters                                                           |
| 25  | Devices and Printers                             | Zariadenia a tlačiarne                                        | control printers                                                                                     |
| 26  | Ease of Access Center                            | Jednoduché prístupové centrum                                 | control /name Microsoft.EaseOfAccessCenter                                                           |
| 27  | Ease of Access Center                            | Jednoduché prístupové centrum                                 | control access.cpl                                                                                   |
| 28  | File Explorer Options (General tab)              | Možnosti programu Explorer (Všeobecné karty)                  | control /name Microsoft.FolderOptions                                                                |
| 29  | File Explorer Options (General tab)              | Možnosti programu Explorer (Všeobecné karty)                  | control folders                                                                                      |
| 30  | File Explorer Options (General tab)              | Možnosti programu Explorer (Všeobecné karty)                  | rundll32.exe shell32.dll,Options_RunDLL 0                                                            |
| 31  | File Explorer Options (View tab)                 | Možnosti programu Explorer (Zobraziť kartu)                   | rundll32.exe shell32.dll,Options_RunDLL 7                                                            |
| 32  | File Explorer Options (Search tab)               | Možnosti programu Explorer (karta Vyhľadávanie)               | rundll32.exe shell32.dll,Options_RunDLL 2                                                            |
| 33  | File History                                     | História súborov                                              | control /name Microsoft.FileHistory                                                                  |
| 34  | Fonts                                            | Písma                                                         | control /name Microsoft.Fonts                                                                        |
| 35  | Fonts                                            | Písma                                                         | control fonts                                                                                        |
| 36  | Game Controllers                                 | Herné ovládače                                                | control /name Microsoft.GameControllers                                                              |
| 37  | Game Controllers                                 | Herné ovládače                                                | control joy.cpl                                                                                      |
| 38  | Get Programs                                     | Získať programy                                               | control /name Microsoft.GetPrograms                                                                  |
| 39  | Get Programs                                     | Získať programy                                               | rundll32.exe shell32.dll,Control_RunDLL appwiz.cpl,,1                                                |
| 40  | HomeGroup                                        | Homegroup                                                     | control /name Microsoft.HomeGroup                                                                    |
| 41  | Indexing Options                                 | Možnosti indexovania                                          | control /name Microsoft.IndexingOptions                                                              |
| 42  | Indexing Options                                 | Možnosti indexovania                                          | rundll32.exe shell32.dll,Control_RunDLL srchadmin.dll                                                |
| 43  | Infrared                                         | Infračervené zariadenia                                       | control /name Microsoft.Infrared                                                                     |
| 44  | Infrared                                         | Infračervené zariadenia                                       | control irprops.cpl                                                                                  |
| 45  | Infrared                                         | Infračervené zariadenia                                       | control /name Microsoft.InfraredOptions                                                              |
| 46  | Internet Properties (General tab)                | Internetové vlastnosti (General Tab)                          | control /name Microsoft.InternetOptions                                                              |
| 47  | Internet Properties (General tab)                | Internetové vlastnosti (General Tab)                          | control inetcpl.cpl                                                                                  |
| 48  | Internet Properties (General tab)                | Internetové vlastnosti (General Tab)                          | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,0                                               |
| 49  | Internet Properties (Security tab)               | Internetové vlastnosti (karta zabezpečenia)                   | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,1                                               |
| 50  | Internet Properties (Privacy tab)                | Internetové vlastnosti (karta Súkromie)                       | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,2                                               |
| 51  | Internet Properties (Content tab)                | Internetové vlastnosti (karta obsahu)                         | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,3                                               |
| 52  | Internet Properties (Connections tab)            | Internetové vlastnosti (karta Pripojenia)                     | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,4                                               |
| 53  | Internet Properties (Programs tab)               | Internetové vlastnosti (karta Programy)                       | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,5                                               |
| 54  | Internet Properties (Advanced tab)               | Internetové vlastnosti (pokročilé karty)                      | rundll32.exe shell32.dll,Control_RunDLL inetcpl.cpl,,6                                               |
| 55  | iSCSI Initiator                                  | iniciátor ISCSI                                               | control /name Microsoft.iSCSIInitiator                                                               |
| 56  | Keyboard                                         | Klávesnica                                                    | control /name Microsoft.Keyboard                                                                     |
| 57  | Keyboard                                         | Klávesnica                                                    | control keyboard                                                                                     |
| 58  | Language                                         | Jazyk                                                         | control /name Microsoft.Language                                                                     |
| 59  | Mouse Properties (Buttons tab 0)                 | Vlastnosti myši (Tlačidlá karty 0)                            | control /name Microsoft.Mouse                                                                        |
| 60  | Mouse Properties (Buttons tab 0)                 | Vlastnosti myši (Tlačidlá karty 0)                            | control main.cpl                                                                                     |
| 61  | Mouse Properties (Buttons tab 0)                 | Vlastnosti myši (Tlačidlá karty 0)                            | control mouse                                                                                        |
| 62  | Mouse Properties (Buttons tab 0)                 | Vlastnosti myši (Tlačidlá karty 0)                            | rundll32.exe shell32.dll,Control_RunDLL main.cpl,,0                                                  |
| 63  | Mouse Properties (Pointers tab 1)                | Vlastnosti myši (Tab 1)                                       | control main.cpl,,1                                                                                  |
| 64  | Mouse Properties (Pointers tab 1)                | Vlastnosti myši (Tab 1)                                       | rundll32.exe shell32.dll,Control_RunDLL main.cpl,,1                                                  |
| 65  | Mouse Properties (Pointer Options tab 2)         | Vlastnosti myši (Ukazovateľ Možnosti karty 2)                 | control main.cpl,,2                                                                                  |
| 66  | Mouse Properties (Pointer Options tab 2)         | Vlastnosti myši (Ukazovateľ Možnosti karty 2)                 | rundll32.exe shell32.dll,Control_RunDLL main.cpl,,2                                                  |
| 67  | Mouse Properties (Wheel tab 3)                   | Vlastnosti myši (karta 3 kolesá)                              | control main.cpl,,3                                                                                  |
| 68  | Mouse Properties (Wheel tab 3)                   | Vlastnosti myši (karta 3 kolesá)                              | rundll32.exe shell32.dll,Control_RunDLL main.cpl,,3                                                  |
| 69  | Mouse Properties (Hardware tab 4)                | Vlastnosti myši (karta Hardware 4)                            | control main.cpl,,4                                                                                  |
| 70  | Mouse Properties (Hardware tab 4)                | Vlastnosti myši (karta Hardware 4)                            | rundll32.exe shell32.dll,Control_RunDLL main.cpl,,4                                                  |
| 71  | Network and Sharing Center                       | Centrum sietí a zdielania                                     | control /name Microsoft.NetworkAndSharingCenter                                                      |
| 72  | Network Connections                              | Sieťové pripojenia                                            | control ncpa.cpl                                                                                     |
| 73  | Network Connections                              | Sieťové pripojenia                                            | control netconnections                                                                               |
| 74  | Network Setup Wizard                             | Sprievodca nastavením siete                                   | control netsetup.cpl                                                                                 |
| 75  | Notification Area Icons                          | Ikony oznámení                                                | explorer shell:::{05d7b0f4-2121-4eff-bf6b-ed3f69b894d9}                                              |
| 76  | ODBC Data Source Administrator                   | Správca zdrojov údajov ODBC                                   | control odbccp32.cpl                                                                                 |
| 77  | Offline Files                                    | Offline súbory                                                | control /name Microsoft.OfflineFiles                                                                 |
| 78  | Performance Options (Visual Effects)             | Možnosti výkonu (vizuálne efekty)                             | %windir%\system32\SystemPropertiesPerformance.exe                                                    |
| 79  | Performance Options (Data Execution Prevention)  | Možnosti výkonu (prevencia vykonávania údajov)                | %windir%\system32\SystemPropertiesDataExecutionPrevention.exe                                        |
| 80  | Personalization                                  | Prispôsobenie                                                 | explorer shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921}                                              |
| 81  | Phone and Modem                                  | Telefón a modem                                               | control /name Microsoft.PhoneAndModem                                                                |
| 82  | Phone and Modem                                  | Telefón a modem                                               | control telephon.cpl                                                                                 |
| 83  | Power Options                                    | Možnosti napájania                                            | control /name Microsoft.PowerOptions                                                                 |
| 84  | Power Options                                    | Možnosti napájania                                            | control powercfg.cpl                                                                                 |
| 85  | Power Options - Advanced settings                | Možnosti napájania - Rozšírené nastavenia                     | control powercfg.cpl,,1                                                                              |
| 86  | Power Options - Create a Power Plan              | Možnosti napájania - Vytvorte plán napájania                  | control /name Microsoft.PowerOptions /page pageCreateNewPlan                                         |
| 87  | Power Options - Edit Plan Settings               | Možnosti napájania - Upraviť nastavenia plánu                 | control /name Microsoft.PowerOptions /page pagePlanSettings                                          |
| 88  | Power Options - System Settings                  | Možnosti napájania - Nastavenia systému                       | control /name Microsoft.PowerOptions /page pageGlobalSettings                                        |
| 89  | Presentation Settings                            | Nastavenia prezentácie                                        | %windir%\system32\PresentationSettings.exe                                                           |
| 90  | Programs and Features                            | Programy a príslušenstvo                                      | control /name Microsoft.ProgramsAndFeatures                                                          |
| 91  | Programs and Features                            | Programy a príslušenstvo                                      | control appwiz.cpl                                                                                   |
| 92  | Recovery                                         | Obnovenie                                                     | control /name Microsoft.Recovery                                                                     |
| 93  | Region (Formats tab)                             | Oblasť (karta formátov)                                       | control /name Microsoft.RegionAndLanguage                                                            |
| 94  | Region (Formats tab)                             | Oblasť (karta formátov)                                       | control /name Microsoft.RegionalAndLanguageOptions /page /p:"Formats"""                              |
| 95  | Region (Formats tab)                             | Oblasť (karta formátov)                                       | control intl.cpl                                                                                     |
| 96  | Region (Formats tab)                             | Oblasť (karta formátov)                                       | control international                                                                                |
| 97  | Region (Location tab)                            | Oblasť (karta Umiestnenie)                                    | control /name Microsoft.RegionalAndLanguageOptions /page /p:"Location"""                             |
| 98  | Region (Administrative tab)                      | Oblasť (administratívna karta)                                | control /name Microsoft.RegionalAndLanguageOptions /page /p:"Administrative"""                       |
| 99  | RemoteApp and Desktop Connections                | Pripojenia RemoteApp a Desktop                                | control /name Microsoft.RemoteAppAndDesktopConnections                                               |
| 100 | Scanners and Cameras                             | Skenery a kamery                                              | control /name Microsoft.ScannersAndCameras                                                           |
| 101 | Scanners and Cameras                             | Skenery a kamery                                              | control sticpl.cpl                                                                                   |
| 102 | Screen Saver Settings                            | Nastavenia šetriča obrazovky                                  | rundll32.exe shell32.dll,Control_RunDLL desk.cpl,,1                                                  |
| 103 | Security and Maintenance                         | Bezpečnosť a údržba                                           | control /name Microsoft.ActionCenter                                                                 |
| 104 | Security and Maintenance                         | Bezpečnosť a údržba                                           | control wscui.cpl                                                                                    |
| 105 | Set Associations                                 | Nastaviť asociácií/prípon pre súbory                          | control /name Microsoft.DefaultPrograms /page pageFileAssoc                                          |
| 106 | Set Default Programs                             | Nastaviť predvolené programy                                  | control /name Microsoft.DefaultPrograms /page pageDefaultProgram                                     |
| 107 | Set Program Access and Computer Defaults         | Nastaviť programové prístupy a predvolené nastavenia počítača | rundll32.exe shell32.dll,Control_RunDLL appwiz.cpl,,3                                                |
| 108 | Sound (Playback tab)                             | Zvuk (karta Prehrávanie)                                      | control /name Microsoft.Sound                                                                        |
| 109 | Sound (Playback tab)                             | Zvuk (karta Prehrávanie)                                      | control mmsys.cpl                                                                                    |
| 110 | Sound (Playback tab)                             | Zvuk (karta Prehrávanie)                                      | %windir%\System32\rundll32.exe shell32.dll,Control_RunDLL mmsys.cpl,,0                               |
| 111 | Sound (Recording tab)                            | Zvuk (záznam kartu)                                           | %windir%\System32\rundll32.exe shell32.dll,Control_RunDLL mmsys.cpl,,1                               |
| 112 | Sound (Sounds tab)                               | Zvuk (Sounds Tab)                                             | %windir%\System32\rundll32.exe shell32.dll,Control_RunDLL mmsys.cpl,,2                               |
| 113 | Sound (Communications tab)                       | Zvuk (komunikačná karta)                                      | %windir%\System32\rundll32.exe shell32.dll,Control_RunDLL mmsys.cpl,,3                               |
| 114 | Speech Recognition                               | Rozpoznávanie reči                                            | control /name Microsoft.SpeechRecognition                                                            |
| 115 | Storage Spaces                                   | Skladovacie priestory                                         | control /name Microsoft.StorageSpaces                                                                |
| 116 | Sync Center                                      | Centrum synchronizácie                                        | control /name Microsoft.SyncCenter                                                                   |
| 117 | System                                           | Systém                                                        | control /name Microsoft.System                                                                       |
| 118 | System                                           | Systém                                                        | control sysdm.cpl                                                                                    |
| 119 | System Icons                                     | Systémové ikony                                               | explorer shell:::{05d7b0f4-2121-4eff-bf6b-ed3f69b894d9} \SystemIcons,,0                              |
| 120 | System Properties (Computer Name)                | Vlastnosti systému (názov počítača)                           | %windir%\System32\SystemPropertiesComputerName.exe                                                   |
| 121 | System Properties (Hardware)                     | Vlastnosti systému (hardvér)                                  | %windir%\System32\SystemPropertiesHardware.exe                                                       |
| 122 | System Properties (Advanced)                     | Vlastnosti systému (pokročilé)                                | %windir%\System32\SystemPropertiesAdvanced.exe                                                       |
| 123 | System Properties (System Protection)            | Vlastnosti systému (ochrana systému)                          | %windir%\System32\SystemPropertiesProtection.exe                                                     |
| 124 | System Properties (Remote)                       | Vlastnosti systému (diaľkové)                                 | %windir%\System32\SystemPropertiesRemote.exe                                                         |
| 125 | Tablet PC Settings                               | Nastavenia počítača Tablet PC                                 | control /name Microsoft.TabletPCSettings                                                             |
| 126 | Text to Speech                                   | Prevod textu na reč                                           | control /name Microsoft.TextToSpeech                                                                 |
| 127 | Troubleshooting                                  | Riešenie problémov                                            | explorer shell:::{26EE0668-A00A-44D7-9371-BEB064C98683}\0\::{C58C4893-3BE0-4B45-ABB5-A63E4B8C8651}   |
| 128 | User Accounts                                    | Používateľské kontá                                           | control /name Microsoft.UserAccounts                                                                 |
| 129 | User Accounts                                    | Používateľské kontá                                           | control userpasswords                                                                                |
| 130 | User Accounts (netplwiz)                         | Používateľské kontá (NetPLWIZ)                                | netplwiz                                                                                             |
| 131 | User Accounts (netplwiz)                         | Používateľské kontá (NetPLWIZ)                                | control userpasswords2                                                                               |
| 132 | Windows Defender Firewall                        | Windows Defender Firewall                                     | control /name Microsoft.WindowsFirewall                                                              |
| 133 | Windows Defender Firewall                        | Windows Defender Firewall                                     | control firewall.cpl                                                                                 |
| 134 | Windows Defender Firewall Allowed apps           | Windows Defender Firewall povolené aplikácie                  | explorer shell:::{4026492F-2F69-46B8-B9BF-5654FC07E423} -Microsoft.WindowsFirewall\pageConfigureApps |
| 135 | Windows Defender Firewall with Advanced Security | Windows Defender Firewall s pokročilou bezpečnosťou           | %WinDir%\System32\WF.msc                                                                             |
| 136 | Windows Features                                 | Funkcie systému Windows                                       | %windir%\System32\OptionalFeatures.exe                                                               |
| 137 | Windows Features                                 | Funkcie systému Windows                                       | rundll32.exe shell32.dll,Control_RunDLL appwiz.cpl,,2                                                |
| 138 | Windows Mobility Center                          | Centrum mobility systému Windows                              | control /name Microsoft.MobilityCenter                                                               |
| 139 | Work Folders                                     | Pracovné priečinky                                            | %windir%\System32\WorkFolders.exe                                                                    |

## 📚 Dôležité zdroje
1. [Liferwire Command Line Commands for Control Panel Applets](https://www.lifewire.com/command-line-commands-for-control-panel-applets-2626060)
2. [Lizardsystems 112 Windows run commands](https://lizardsystems.com/articles/112-windows-run-commands/)
3. [Microsoft Forum a odpovede](https://answers.microsoft.com/en-us/windows/forum/all)
