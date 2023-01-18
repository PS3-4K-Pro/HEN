<div align="center"> 

# Homebrew Enabler Pro™
A exploit that allows the console to run unsigned code.<br>

[![Github downloads (by repository)](https://img.shields.io/github/downloads/LuanTeles/HEN/total?style=social)](https://github.com/LuanTeles/HEN/releases/)

![Hen Disabled](https://user-images.githubusercontent.com/74815634/148464759-62bed1d8-b944-411a-b9f5-209a5d73b1b4.png)
![Hen Enabled](https://user-images.githubusercontent.com/74815634/148464786-72e35270-5e68-4abd-996f-10fb53713dda.png)

# Exclusive Features:

|HEN™ 4K Pro|
|----------------------
| Custom what's new items |
| Custom PlayStation™Store (Video/Game/PSN) shortcut items |
| HEN icon changes when enabled |
| IP adress on XMB™ |
| Gameboot logo & sound enabled |
| PSN™ Blocker |

<br>

***Requires PS3™ 4K Pro installed***
 
#  Changelogs (by PS3XPloit Team)
 
<details><summary>Spoiler</summary>

# v3.3.0
### Plugin:
-Added: Check for Remaps to avoid Kernel Panic if destination file is missing.<br>
-Added: Automatic cleaning of logs sent when connecting to PSN in order to reduce the risk of a ban. (CI.TMP, MI.TMP and PTL.TMP)<br>

### Payload:
-Added: Ability to restore syscalls.<br>
-Added: PSN™ Blocker (PSN Access is blocked if syscalls are enabled).<br>

# v3.2.0
### Plugin:
-Added: Automatic reboot after successful initial HEN installation from Network and USB.<br>
-Added: Blacklist access to homebrews NP0APOLLO / NP00PKGI3 when CFW syscalls are disabled by @aldostools.<br>
-Added: Dynarec Support by @OsirizX.<br>
-Added: Libcrypt Support for PS1 games (LSF/SBI files) by @aldostools.<br>
-Added: PSX Bios patched with product code 0x85 for PAL games.<br>
-Added: Support for .RAP extension (in addition to .rap) by @aldostools.<br>
-Added: Toggle for Audio Patch by @in1975.<br>
-Added: Toggle for Build types. (DEV/Release)<br>
-Added: Toggle to clean Web Browser user information upon HEN activation. (Auth, Cache,Cookies, History)<br>
-Improved: Simplified Backup/Restore of the act.dat on every boot by @bucanero.<br>

### Payload:
-Added: Improved open_path logs.<br>
-Added: Pad Combos (Hold R2 to disable boot_plugins.txt and Hold L2 to disable map_path).<br>
-Improved: Map_path.<br>
-Improved: PS3MAPI.<br>

# v3.1.2 (Exclusive)
### Plugin:
-Removed: Version notification.<br>

### Payload:
-Added: Automatically HEN swap icon enabled/disabled.<br>
-Added: IP address on XMB™.<br>
-Added: Custom what's new items.<br>
-Added: Gameboot logo & sound.<br>
-Added: System update unlock after HEN is enabled.<br>

# v3.1.1
### Resources:
-Added: CEX Version of explore_plugin.sprx.<br>
-Removed: Unused RCO files.<br>
-Fixed: Display issues with Trophies, Package Manager and other XMB items.<br>

# v3.1.0
### Global:
-Added: Support for Firmware 4.88.<br>

 ### Plugin:
-Added: Backup/Restore of the act.dat on every boot by @bucanero<br>
 
 ### Payload:
-Added: Dump PSID option to HFW tools.<br>

### Resources:
-Added: Toggle automatic update option to HFW tools.<br>
-Added: New icons for updated HFW tools options. (Thanks @xps3riments)<br>
-Updated: Text on theme selector in HFW tools.<br>
-Updated: RCO files to fix display issues with 4.89 only. (Thanks sandungas<br>
-Updated: layout_grid_table files for 480p and 272p to fix display issues in Remote Play with 4.89 only. (Thanks @sandungas)<br>
 
# v3.0.3
### Global:
-Added: Support for Firmware 4.88.<br>

# v3.0.2
### Global:
-Added: Support for Firmware 4.87.<br>

### Resource:
- HEN Loader.<br>

# v3.0.1
### Global:
-Added: Support for Firmware 4.86.<br>

### Cobra PS3MAPI:
-Added: Better set process memory by using the function used to actually write to process, this will allow user to write to memory where writing permissions are disabled.<br>
-Added: Ps3mapi_process_page_allocate this function will allocate memory into the eboot process allowing your to write/read/execute code into start_address parameter.<br>
-Added: Ps3mapi_get_process_module_info which will get the name, module path, module segments, module start and module stop address all in one function.<br>
-Added: Ps3mapi_create_process_thread to create thread into the process, This is useful if you want to load a small function into the process without needed make and load a sprx module.<br>

# v3.0.0
### Global:
-Removed: Support for Firmware 4.82.<br>

### Plugin:
-Fixed: System Freeze if DVD or CD is already inserted into PS3™ when HEN is enabled.<br>
-Fixed: Error message if reply length is too short from server.<br>

### Payload:
-Fixed: Freeze problems on all models.<br>
-Fixed: Issues with incompatible models.<br>
-Improved: Sanity checks.<br>

# v2.4.0
### Global:
-Improved: The size of stage2 has been reduced.<br>

### Payload:
-Added: DLC/PSX games RAP support added.<br>
-Added: VSH patches and disabled signature check of RIF, now other tools are compatible.<br>
-Fixed: Hitching of PSX PAL on NTSC TV and vice versa.<br>
-Fixed: Issue where people sometimes got stuck downloading games from PSN.<br>
-Improved: Disabled VSH check in RIF that R and S cant be just 0.<br>
-Improved: PS3MAPI can now write to VSH text segment like CFW <br>
-Improved: Speed when loading NPDRM type 2 games (need original or RAP Activated RIF), CPU couldnt generate ECDSA fast enough.<br>
-Removed: Unnecessary hooks on CellFsOpen/CellFsRead/CellFsClose, possibly increasing stability.<br>

# v2.3.3
### Payload:
-Improved: Remapping HFW XML from /dev_flash/ instead of /dev_hdd0/.<br>

### Resource:
-Improved: Updated path pointing to ps3hen_updater.<br>xml in hfw_settings.xml.<br>

# v2.3.2
### Global:
-Added: Support for Firmware 4.85.<br>

# v2.3.1

### HEN 
### Plugin:
-Fixed: Issue when network is disabled.<br>

Resource
-Added: Duplicated icon fix.<br>

# v2.3.0
### Global:
-Improved: Fast exploit initialization.<br>
-Improved: Increased sleep in html, removed from bins.<br>

### Plugin:
-Added: Automatic reboot upon HEN fail.<br>
-Added: HEN Updater with version check.<br>
-Fixed: Random crash on initialization.<br>
-Removed: Infinite loop.<br>

### Payload:
-Fixed: Blackscreen issues.<br>
-Fixed: SELF Decrypter.<br>
-Fixed: System freeze after enabling hen when its already enabled.<br>
-Improved: Extended download plugin patches.<br>
-Improved: HEN queue is drained before the patches get disabled, and also synchronized properly the check to synchronize remove and do patches.<br>
-Improved: Handler requests are passed fast, removed many branch conditions there for faster handling.<br>
-Improved: Optimizations added to how much stack is available to the syscalls.<br>

# v2.2.2
### Payload:
-Added: USB Package installation support for HEN installer. (/dev_usb000/HEN_UPD.pkg)<br>
-Fixed: HEN initialization freeze.<br>
-Fixed: HashCalc bug.<br>
-Fixed: Syscall handler bug.<br>

### Resource:
-Improced: Updated videoplayer_plugin.<br>sprx to use proper DEX version for each firmware version.<br>

# v2.2.1
### Global:
-Added: HEN refresh and version display on initialize, using embedded plugin.<br>
-Improced: Replaced dev_blind with dev_rewrite to maintain RW state at all times.<br>
-Improved: The stackframe and PS3HEN bins are now merged as a single payload binary. (PS3HEN.BIN)<br>

### Plugin:
-Added: HEN version notification on boot.<br>
-Added: Game and Network Category refresh.<br>
-Added: In-game Screenshot feature.<br>

### Payload:
-Added: Embedded buffers and removed memory fragmentation.<br>
-Added: Fail-safe for stage0 incase stage2 not found.<br>
-Added: Get map path opcode.<br>
-Added: HMAC Hash Validation.<br>
-Added: Missing COBRA patches & BT/USB passthrough support.<br>
-Added: PS2™ Classics launcher activation on the fly.<br>
-Added: PSP™ ISO Launcher Support.<br>
-Added: Self Threading Support, fixing the issue with a few games. (SC Trilogy and etc) <br>
-Added:: Cleanup thread.<br>
-Fixed: Encryption.<br>
-Fixed: Kernel plugin bug.<br>
-Fixed: PS3MAPI bug and stability.<br>
-Improved: Compatibility with apps like MultiMan and others which replace syscall 6-10.<br>
-Improved: Faster boot times for apps.<br>
-Improved: Memory Management of map_path.<br>
-Improved: Memory Optimization. (no embedded buffer for kernel plugin, only allocs when requested) <br>
-Improved: SELF auth.<br>
-Improved:: HEN Installer feature and memory management changes.<br>

#### Resource:
-Improved: Default theme pack removed from main package and can now download from themes updater.<br>
-Improved: HEN theme pack downloadable package updated with fixed icons.<br>
-Improved: New coldboot, icons and JS/HTML overlay.<br>
-Improved: PKG linker is now located under Package Manager -> Install Packages.<br>
-Improved: Replaced manual link from network column with PS3Xploit Home link.<br>
-Removed:: Unused XML Entries.<br>

# v2.2.0
### Stackframe Binary:
-Added: Support for Firmware 4.82.<br>
-Improved: Each FW version has its own payload, stackframe, package, and update XML.<br>

### Plugin:
-Added: HEN check added to verify if HEN enabled, and to prevent freezing.<br>
-Fixed: PSNPatch freeze.<br>
-Improved: Remap for HFW settings is now fully protected, no more disappearing HFW tools.<br>
-Improved: Stability patches added on initial boot process.<br>

### Resource:
-Added: PKG Linker entries added to category_game.xml.<br>

# v2.1.0
### Payload:
-Added: Advanced QA Flag.<br>
-Added: Debug Settings.<br>
-Improved: AES calculation now uses internal library from LV2.<br>
-Improved: Payload size is reduced by 20kb.<br>
-Improved: RAP can now be loaded / accessed from dev_hdd0/exdata.<br>
 
### Plugin:
-Added: HEN check added to verify if HEN enabled, and to prevent freezing.<br>
-Fixed: PSNPatch freeze.<br>
-Improved: Remap for HFW settings is now fully protected, no more disappearing HFW tools.<br>
-Improved: Stability patches added on initial boot process.<br>

### Resource:
-Added: Update Themes option to PS3HEN Updater menu.<br>
-Added: Theme pack by to PS3HEN Updater -> Update Themes.<br>

# v2.0.2
### Stackframe Binary:
- Added: C00 unlocker activated by default.<br>

### Payload:
-Added:	Advanced download plugin patches.<br>
-Added: App restriction on RemotePlay with PC removed.<br>
-Added: Dev_blind enabled by default.<br>
-Added: Hybrid Firmware Tools available when HEN's activated.<br>
-Added: Multiple path on boot_plugins & boot_plugins_kernel (HDD & USB).<br>
-Added: PS2™ classics launcher support.<br>
-Added: RAP activation on the fly.  (usb000/exdata/<rap> or usb001/exdata/<rap>)<br>
-Fixed: Explore_plugin.sprx patches.<br>
-Fixed: Install All Packages.<br>
-Fixed: Issue with official NPDRM content rif deletion and unable to boot error.<br>
-Improved: Games compatibilty.<br>

### Resource:
-Added: HEN updater support available under Network Category.<br>
-Added: Official firmware updates via internet blocked.<br>
-Fixed: Infinite spinning wheel when in-game.<br>

# v2.0.1
### Payload:
-Added Option to re-enable cfw syscall by accessing the system update menu on XMB Settings.<br>
-Improved: Mappath for enabling xai_plugin.sprx.<br>

# v2.0.0
### Payload:
-Added: Full BD/DVD ISO support. (AACS decryption required for BDRip)<br>
-Added: ISO support.<br>
-Added: KW stealth extensions.<br>
-Added: Kernel plugins support.<br>
-Added: Opcode 1339, returns HEN version. (0x0200) <br>
-Added: Photo gui opcode support for webMAN.<br>
-Fixed: Blackscreen crashes.<br>
-Fixed: Random lv2 panic.<br>
-Fixed: Random recovery kicks.<br>
-Fixed: Removed HEN Check From Offline Packages.<br>
-Improved: Syscall 389/409 product mode check disabled.<br>
-Improved: PS3MAPI support can now read/set process mem using webMAN.<br>
-Remoced: Fake flash is no longer used, in favor of on-the-fly patching.<br>

# v1.0.0
### Payload:
-Added: BD/DVD Region patches.<br>
-Added: BDISO support.<br>
-Added: Boot plugins support.<br>
-Added: Debug PKG install.<br>
-Added: Homebrew Root Flags.<br>
-Added: Kernel memory RWX. (execute kernel payload like this at high locations or hook syscalls etc) <br>
-Added: PS3MAPI support.<br>
-Added: PSXISO support.<br>
-Added: RWX permissions for processes executed after HEN has been enabled.<br>
-Added: Support for HAN PKG.<br>
-Added: Support for Homebrew resigned with 3.55 keys and lower.<br>
-Added: Syscall 6,7,8,15.<br>

</details> 
 
# Credits

PS3Xploit Team:<br>
-W.<br>
-esc0rtd3w.<br>
-bguerville.<br>
-Habib.<br>

# Website
Official website: [http://ps3xploit.com/](http://ps3xploit.com/)
 
</div>