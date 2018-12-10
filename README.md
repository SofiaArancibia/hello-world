## Breakdown 
- file.yara:66 
- registry.yara:262 
- exploitation.yara:7 
- process.yara:93 
- malicious.yara:21 
- network.yara:7 
- supported.yara:132 
- API.yara:4 


 ## Rules Dependencies 

<details closed>
<summary>_process_copyfile</summary>
<br>
<li>_process_stickykeys</li> 
</details> 

<details closed>
<summary>_apt_process_usergroup</summary>
<br>
<li>_apt_process_user</li> 
<li>_apt_process_newuser</li> 
<li>_apt_process_userdelete</li> 
</details> 

<details closed>
<summary>_reg_ep0055_cmdorder</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_apt_process_mstsc</summary>
<br>
<li>_apt_process_mstscserver</li> 
</details> 

<details closed>
<summary>_file_ep0154_0553_petostartupxp</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_findstravprocess</summary>
<br>
<li>_apt_process_tasklist</li> 
</details> 

<details closed>
<summary>_reg_wincestartup</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_lsapackages</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_wevtutilevents</summary>
<br>
<li>_process_remotewevtutilevents</li> 
</details> 

<details closed>
<summary>_process_psnewservice</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_injected</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0007_urlredir</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_malware_flashflood</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_explorer</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_malware_kovter_family</summary>
<br>
<li>_reg_ep0104_run</li> 
</details> 

<details closed>
<summary>_process_psfromoffice</summary>
<br>
<li>_process_psparams</li> 
</details> 

<details closed>
<summary>_reg_ep0133_cmdinvoke_low</summary>
<br>
<li>_reg_ep0133_cmdinvoke</li> 
</details> 

<details closed>
<summary>_process_cmdassoc</summary>
<br>
<li>_process_cmdassocexec</li> 
</details> 

<details closed>
<summary>_reg_shellfolders</summary>
<br>
<li>_reg_ep0052_usershellfolders</li> 
<li>_iexplore</li> 
</details> 

<details closed>
<summary>_reg_ep0084_delknown</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_file_servicemmc</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0017_lsapackages</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_apt_process_netremote</summary>
<br>
<li>_apt_process_netadminshare</li> 
</details> 

<details closed>
<summary>_reg_ep0021_customverifier</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0142_wow16bithandle</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_autoload</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_apt_process_tscon</summary>
<br>
<li>_apt_process_tscondest</li> 
</details> 

<details closed>
<summary>_file_execattributes_cmd</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0044_officesecure</summary>
<br>
<li>_reg_ep0044_officeprotect</li> 
</details> 

<details closed>
<summary>_apt_process_ping</summary>
<br>
<li>_ping</li> 
<li>_apt_process_pinglots</li> 
</details> 

<details closed>
<summary>_network_trusted_developer_utilities</summary>
<br>
<li>_network_assignedport</li> 
<li>_network_knownport</li> 
</details> 

<details closed>
<summary>_reg_ep0156_winlogon_savedumpstart_low</summary>
<br>
<li>_reg_ep0156_winlogon_savedumpstart</li> 
</details> 

<details closed>
<summary>_file_ep0060_delhistory</summary>
<br>
<li>_iexplore</li> 
</details> 

<details closed>
<summary>_reg_ep0139_newrunhandler</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_malware_genbackdoor</summary>
<br>
<li>_file_driverfolder</li> 
<li>_reg_winservicedll</li> 
<li>_file_ep0058_syspe</li> 
</details> 

<details closed>
<summary>_file_dllhijacksystem32</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0034_setup_low</summary>
<br>
<li>_reg_ep0034_setup</li> 
</details> 

<details closed>
<summary>_reg_ep0055_cmdorder_low</summary>
<br>
<li>_reg_ep0055_cmdorder</li> 
</details> 

<details closed>
<summary>_reg_ep0115_winlogon_appinit_low</summary>
<br>
<li>_reg_ep0115_winlogon_appinit</li> 
</details> 

<details closed>
<summary>_malware_autorun_generic</summary>
<br>
<li>_reg_ep0088_ext_exploreradvanced</li> 
</details> 

<details closed>
<summary>_process_psrunkey</summary>
<br>
<li>_process_psparams</li> 
<li>_reg_ep0104_run</li> 
</details> 

<details closed>
<summary>_reg_explorer_dir</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_apt_process_psfilecopy2</summary>
<br>
<li>_apt_process_psfilecopy</li> 
</details> 

<details closed>
<summary>_reg_ep0099_explorerlangbar_low</summary>
<br>
<li>_reg_ep0099_explorerlangbar</li> 
</details> 

<details closed>
<summary>_file_ep0154_0553_petostartup3</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_file_ep0154_0553_petostartup2</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0115_winlogon_appinit</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0005_exploreroverlay_low</summary>
<br>
<li>_reg_ep0005_exploreroverlay</li> 
</details> 

<details closed>
<summary>_reg_ep0034_setup</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0112_policies2</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_shellexapproved</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_schtasks_low</summary>
<br>
<li>_process_schtasks</li> 
</details> 

<details closed>
<summary>_reg_ep0148_remotestartup</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0519_hostdetect</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0104_run</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_apt_process_netshinterface</summary>
<br>
<li>_apt_process_netshinterfacetcpip</li> 
</details> 

<details closed>
<summary>_process_wmicprocesslist</summary>
<br>
<li>_process_wmicprocess</li> 
<li>_process_wmicprocessinfo</li> 
</details> 

<details closed>
<summary>_reg_ep0040_smartfilter</summary>
<br>
<li>_iexplore</li> 
</details> 

<details closed>
<summary>_reg_ep0124_winlogon_devicenotify</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_setttingsdisnotify</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_file_ep0121_dosbatini</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_regexport</summary>
<br>
<li>_process_regsam_system</li> 
</details> 

<details closed>
<summary>_reg_ep0136_scmextension</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_run</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_numterminated</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0043_smknowndlls_low</summary>
<br>
<li>_reg_ep0043_smknowndlls</li> 
</details> 

<details closed>
<summary>_file_sysscript</summary>
<br>
<li>_file_sysscript_exclude</li> 
</details> 

<details closed>
<summary>_reg_ep0117_safeboot</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0156_winlogon_userinit</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0101_newdrv32</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_pslsapass</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_file_macroaddins</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0124_winlogon_devicenotify_low</summary>
<br>
<li>_reg_ep0124_winlogon_devicenotify</li> 
</details> 

<details closed>
<summary>_reg_ep0122_mediaproviders</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0044_officeprotect</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_file_ep0061_delfileswindows</summary>
<br>
<li>_file_ep0061_delexecfileswindows</li> 
</details> 

<details closed>
<summary>_malware_genericworm</summary>
<br>
<li>_reg_ep0104_run</li> 
<li>_file_ep0058_syspe</li> 
<li>_file_ep0057_newpe</li> 
</details> 

<details closed>
<summary>_malware_fin7_family</summary>
<br>
<li>_apt_process_mshta</li> 
<li>_process_schtasks</li> 
<li>_reg_ep0104_run</li> 
<li>_process_jsmshta</li> 
<li>_process_vbsmshta</li> 
</details> 

<details closed>
<summary>_reg_ep0019_netproviders</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_psgetrun</summary>
<br>
<li>_process_psparams</li> 
<li>_process_psbitsadmin</li> 
<li>_process_psdownload</li> 
</details> 

<details closed>
<summary>_reg_ep0043_smknowndlls</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_file_attributes</summary>
<br>
<li>_file_execattributes</li> 
</details> 

<details closed>
<summary>_apt_process_whoami2</summary>
<br>
<li>_apt_process_whoami</li> 
</details> 

<details closed>
<summary>_file_ep0060_delhistoryxp</summary>
<br>
<li>_iexplore</li> 
</details> 

<details closed>
<summary>_reg_ep0034_setup2</summary>
<br>
<li>_reg_ep0034_setup</li> 
</details> 

<details closed>
<summary>_reg_ep0041_abouturls</summary>
<br>
<li>_iexplore</li> 
</details> 

<details closed>
<summary>_reg_ep0099_explorerlangbar</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_apt_process_nslookup2</summary>
<br>
<li>_apt_process_nslookup</li> 
</details> 

<details closed>
<summary>_reg_winlogon_appsetup</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_findstrtext</summary>
<br>
<li>_process_findstrpass</li> 
<li>_process_findstrav</li> 
<li>_process_findstravprocess</li> 
</details> 

<details closed>
<summary>_reg_ep0129_credproviders</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0130_imageexecution_low</summary>
<br>
<li>_reg_ep0130_imageexecution</li> 
</details> 

<details closed>
<summary>_process_wmicprocessinfo</summary>
<br>
<li>_process_wmicprocess</li> 
</details> 

<details closed>
<summary>_reg_ep0095_bho</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0112_policies_low</summary>
<br>
<li>_reg_ep0112_policies</li> 
</details> 

<details closed>
<summary>_reg_ep0141_winlogon_notify</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_bypassUAC_sdclt</summary>
<br>
<li>_process</li> 
<li>_registry</li> 
</details> 

<details closed>
<summary>_reg_winlogon_shell</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_file_ep0120_autoruninf</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_wmicshadow</summary>
<br>
<li>_process_wmicshadowdel</li> 
</details> 

<details closed>
<summary>_file_tosysdrive</summary>
<br>
<li>_file_ep0058_syspe</li> 
</details> 

<details closed>
<summary>_reg_ep0014_cryptoproviders</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0148_remotestartup2</summary>
<br>
<li>_reg_ep0148_remotestartup</li> 
</details> 

<details closed>
<summary>_reg_ep0163_officeperf</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_malware_ransomlock</summary>
<br>
<li>_file_ep0057_newpe</li> 
<li>_reg_safemode</li> 
<li>_reg_ep0130_imageexecution</li> 
<li>_reg_ep0104_run</li> 
</details> 

<details closed>
<summary>_reg_ep0130_imageexecution</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_winservicedll</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_malware_cerber_ransom</summary>
<br>
<li>_file_ep0057_newpe</li> 
<li>_reg_ep0092_filterdrv</li> 
<li>_reg_winlogon_shell</li> 
<li>_reg_systools</li> 
</details> 

<details closed>
<summary>_file_ep0154_0553_petostartup</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_file_ep0168_reservenames</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_findstrav</summary>
<br>
<li>_process_findstravprocess</li> 
</details> 

<details closed>
<summary>_file_deleted</summary>
<br>
<li>_file_ep0060_delhistoryxp</li> 
<li>_file_ep0060_delhistory</li> 
<li>_file_ep0061_delexecfileswindows</li> 
<li>_file_ep0061_delfileswindows</li> 
<li>_file_ep0171_deletecmd</li> 
<li>_file_defenderdel</li> 
</details> 

<details closed>
<summary>_reg_ep0018_winsock_low</summary>
<br>
<li>_reg_ep0018_winsock</li> 
</details> 

<details closed>
<summary>_reg_ep0156_winlogon_savedumpstart</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_file_driverfolder_del</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0145_smssboot</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_disabledefender</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0059_explorerdelayload_low</summary>
<br>
<li>_reg_ep0059_explorerdelayload</li> 
</details> 

<details closed>
<summary>_reg_ep0096_explorerservice</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0155_subssystems</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_injectattempt</summary>
<br>
<li>_process_injected</li> 
</details> 

<details closed>
<summary>_reg_ep0049_smbparams</summary>
<br>
<li>_reg_ep0049_1_signsmb</li> 
<li>_reg_ep0049_2_hidecomp</li> 
<li>_reg_ep0049_3_restrictshareaccess</li> 
</details> 

<details closed>
<summary>_reg_ep0014_cryptoproviders_low</summary>
<br>
<li>_reg_ep0014_cryptoproviders</li> 
</details> 

<details closed>
<summary>_reg_ep0145_initcommand_smssboot</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0064_bypassfirewall2</summary>
<br>
<li>_reg_ep0064_bypassfirewall</li> 
</details> 

<details closed>
<summary>_reg_ep0145_exec_smssboot</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0085_ietabproc</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_bitsadmin</summary>
<br>
<li>_process_psbitsadmin</li> 
</details> 

<details closed>
<summary>_reg_ep0059_explorerdelayload</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_unrestrictnullsessions</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_setup</summary>
<br>
<li>_reg_ep0133_cmdinvoke</li> 
</details> 

<details closed>
<summary>_reg_ep0006_protocolfilter</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_disableservice</summary>
<br>
<li>_file_ep0167_sysutils</li> 
</details> 

<details closed>
<summary>_reg_iestyles</summary>
<br>
<li>_iexplore</li> 
</details> 

<details closed>
<summary>_malware_trojan_sysreplacedll</summary>
<br>
<li>_file_ep0057_newpe</li> 
<li>_file_ep0058_syspe</li> 
<li>_reg_coreaccessibility</li> 
<li>_reg_mediadevice</li> 
</details> 

<details closed>
<summary>_reg_ep0073_winlogon_fsprotect_low</summary>
<br>
<li>_reg_ep0073_winlogon_fsprotect</li> 
</details> 

<details closed>
<summary>_reg_winlogon_taskman</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_wevtutillist</summary>
<br>
<li>_process_remotewevtutillist</li> 
</details> 

<details closed>
<summary>_reg_ep0133_cmdinvoke</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_malware_ups_family</summary>
<br>
<li>_process_schtasks</li> 
<li>_process_psparams</li> 
<li>_process_psgetrun</li> 
<li>_process_psdownload</li> 
<li>_file_ep0057_newpe</li> 
</details> 

<details closed>
<summary>_reg_ep0149_winlogon_system_low</summary>
<br>
<li>_reg_ep0149_winlogon_system</li> 
</details> 

<details closed>
<summary>_reg_ep0050_sessions</summary>
<br>
<li>_reg_ep0145_smssboot</li> 
<li>_reg_ep0084_delknown</li> 
<li>_reg_ep0155_subssystems</li> 
<li>_reg_ep0131_pendingrename</li> 
<li>_reg_ep0547_protectmode</li> 
</details> 

<details closed>
<summary>_file_ep0113_hostmodification</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0054_scrsaver</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_apt_process_nltestserver</summary>
<br>
<li>_apt_process_nltestsc</li> 
</details> 

<details closed>
<summary>_reg_ep0088_modfolder</summary>
<br>
<li>_reg_ep0514_hidefolder</li> 
<li>_reg_ep0088_ext_exploreradvanced</li> 
</details> 

<details closed>
<summary>_reg_ep0145_setupexec_smssboot</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_ransom_extensions</summary>
<br>
<li>_ransom_extensions1</li> 
<li>_ransom_extensions2</li> 
<li>_ransom_extensions3</li> 
</details> 

<details closed>
<summary>_reg_ics</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_exploit_powercat</summary>
<br>
<li>_process_psparams</li> 
</details> 

<details closed>
<summary>_file_ep0061_delexecfileswindows</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0149_winlogon_system</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0052_usershellfolders</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0104_run_low</summary>
<br>
<li>_reg_ep0104_run</li> 
</details> 

<details closed>
<summary>_reg_ep0148_remotestartup_low</summary>
<br>
<li>_reg_ep0148_remotestartup</li> 
</details> 

<details closed>
<summary>_reg_explorer_dll</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_apt_process_netuselocal</summary>
<br>
<li>_apt_process_netremote</li> 
<li>_apt_process_netadminshare</li> 
</details> 

<details closed>
<summary>_malware_pirpi_family</summary>
<br>
<li>_reg_ep0052_usershellfolders</li> 
<li>_file_ep0154_0553_petostartupxp</li> 
<li>_file_ep0154_0553_petostartup</li> 
<li>_apt_process_user</li> 
<li>_apt_process_querysoftware</li> 
<li>_apt_file_dir</li> 
</details> 

<details closed>
<summary>_reg_ep0116_remoteaccess2</summary>
<br>
<li>_reg_ep0116_remoteaccess</li> 
</details> 

<details closed>
<summary>_malware_trojan_goodkit</summary>
<br>
<li>_reg_ep0059_explorerdelayload</li> 
<li>_reg_ep0011_shims</li> 
</details> 

<details closed>
<summary>_file_ep0075_76_ransom</summary>
<br>
<li>_ransom_extensions</li> 
</details> 

<details closed>
<summary>_process_regsvr32</summary>
<br>
<li>_process_remoteregsvr32</li> 
</details> 

<details closed>
<summary>_reg_newrunhandler</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0139_newrunhandler_low</summary>
<br>
<li>_reg_ep0139_newrunhandler</li> 
</details> 

<details closed>
<summary>_reg_ep0129_credproviders_low</summary>
<br>
<li>_reg_ep0129_credproviders</li> 
</details> 

<details closed>
<summary>_process_wevtutilclear</summary>
<br>
<li>_process_remotewevtutilclear</li> 
</details> 

<details closed>
<summary>_reg_ep0156_winlogon_userinit_low</summary>
<br>
<li>_reg_ep0156_winlogon_userinit</li> 
</details> 

<details closed>
<summary>_reg_ep0136_scmextension_low</summary>
<br>
<li>_reg_ep0136_scmextension</li> 
</details> 

<details closed>
<summary>_file_peattrib</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0018_winsock</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_file_ep0025_ads</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_malware_genericmalware</summary>
<br>
<li>_reg_ep0104_run</li> 
<li>_file_ep0058_syspe</li> 
<li>_file_ep0057_newpe</li> 
<li>_reg_systools</li> 
<li>_reg_ep0088_ext_exploreradvanced</li> 
</details> 

<details closed>
<summary>_reg_ep0064_bypassfirewall</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_file_execattributes_fs</summary>
<br>
<li>_file_execattributes_cmd</li> 
</details> 

<details closed>
<summary>_apt_process_netstat</summary>
<br>
<li>_apt_process_netstattcp</li> 
<li>_apt_process_netstatpe</li> 
</details> 

<details closed>
<summary>_malware_ramnit_family</summary>
<br>
<li>_reg_secureoverride</li> 
<li>_reg_ep0164_securecenter</li> 
<li>_reg_disabledefender</li> 
<li>_reg_disableupdates</li> 
</details> 

<details closed>
<summary>_regwinlogon_shell2</summary>
<br>
<li>_reg_winlogon_shell</li> 
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_explorer_folder</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_apt_process_user</summary>
<br>
<li>_apt_process_newuser</li> 
<li>_apt_process_userdelete</li> 
</details> 

<details closed>
<summary>_reg_ep0124_explorer_devicenotify</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_malware_APT15</summary>
<br>
<li>_Api_WriteProcessMemory</li> 
<li>_Api_CreateRemoteThread</li> 
<li>_process_APT15</li> 
</details> 

<details closed>
<summary>_reg_excludefromdefender</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0131_pendingrename_low</summary>
<br>
<li>_reg_ep0131_pendingrename</li> 
</details> 

<details closed>
<summary>_malware_shellcode</summary>
<br>
<li>_file_certcopy</li> 
<li>_file_sysscript</li> 
<li>_Api_WriteProcessMemory</li> 
<li>_Api_CreateRemoteThread</li> 
<li>_process_injected</li> 
<li>_process_injectattempt</li> 
</details> 

<details closed>
<summary>_reg_ep0164_securecenter_low</summary>
<br>
<li>_reg_ep0164_securecenter</li> 
</details> 

<details closed>
<summary>_reg_winlogon_gina</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0039_urlprefix</summary>
<br>
<li>_iexplore</li> 
</details> 

<details closed>
<summary>_reg_ep0021_customverifier_low</summary>
<br>
<li>_reg_ep0021_customverifier</li> 
</details> 

<details closed>
<summary>_file_tostartup4</summary>
<br>
<li>_file_ep0154_0553_petostartupxp</li> 
<li>_file_ep0154_0553_petostartup</li> 
<li>_file_ep0154_0553_petostartup2</li> 
<li>_file_ep0154_0553_petostartup3</li> 
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0096_explorerservice_low</summary>
<br>
<li>_reg_ep0096_explorerservice</li> 
</details> 

<details closed>
<summary>_malware_OceanLotus</summary>
<br>
<li>_process_schtasks_low</li> 
<li>_process_remoteregsvr32</li> 
<li>_apt_process_wscript</li> 
</details> 

<details closed>
<summary>_reg_disableupdates</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_process_deleteservice</summary>
<br>
<li>_file_ep0167_sysutils</li> 
</details> 

<details closed>
<summary>_file_ep0086_normaldot</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0098_iconconvert</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0170_winservices</summary>
<br>
<li>_reg_ep0018_winsock</li> 
<li>_reg_disableupdates</li> 
<li>_reg_disabledefender</li> 
<li>_reg_ep0064_bypassfirewall</li> 
<li>_reg_ep0064_bypassfirewall2</li> 
</details> 

<details closed>
<summary>_apt_process_tasklist</summary>
<br>
<li>_apt_process_tasklistname</li> 
<li>_apt_process_tasklistservices</li> 
<li>_apt_process_tasklistremote</li> 
</details> 

<details closed>
<summary>_reg_bypassUAC_eventvwr</summary>
<br>
<li>_process</li> 
<li>_registry</li> 
</details> 

<details closed>
<summary>_reg_ep0141_winlogon_notify_low</summary>
<br>
<li>_reg_ep0141_winlogon_notify</li> 
</details> 

<details closed>
<summary>_reg_ep0112_policies</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_file_ep0168_reservenames2</summary>
<br>
<li>_file_ep0168_reservenames</li> 
</details> 

<details closed>
<summary>_reg_ep0142_wow16bithandle_low</summary>
<br>
<li>_reg_ep0142_wow16bithandle</li> 
</details> 

<details closed>
<summary>_reg_handlerapps</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0005_exploreroverlay</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_file_ep0057_newpe</summary>
<br>
<li>_file_ep0058_syspe</li> 
</details> 

<details closed>
<summary>_reg_ep0145_bootexec_smssboot</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0116_remoteaccess</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_safemode</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0139_2_newrunhandler</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0116_remoteaccess_low</summary>
<br>
<li>_reg_ep0116_remoteaccess</li> 
</details> 

<details closed>
<summary>_file_driverfolder</summary>
<br>
<li>_trusted_process</li> 
</details> 

<details closed>
<summary>_reg_ep0117_safeboot_low</summary>
<br>
<li>_reg_ep0117_safeboot</li> 
</details> 


 ## Rules Severity 

 Severity | Quantity 
 ------------ | ------------- 
1|108
0|446
3|1
2|37


 ## Rules Score 

 Score | Quantity 
 ------------ | ------------- 
42|29
36|5
53|3
66|3
67|9
68|2
69|1
24|2
25|62
26|32
27|10
20|36
21|14
22|5
05|1
23|1
28|15
43|15
40|49
41|21
1|7
0|3
5|47
7|5
8|1
75|8
70|5
29|1
51|24
39|31
38|3
15|1
58|1
55|10
54|8
57|2
56|10
37|14
50|33
35|38
52|13
32|3
65|9


 ## Techniques covered by yara rules 

<details closed>
<summary>Techniques</summary>
<br>
<li>T1091</li> 
<li>T1093</li> 
<li>T1095</li> 
<li>T1097</li> 
<li>T1096</li> 
<li>T1098</li> 
<li>T1158</li> 
<li>T1204</li> 
<li>T1019</li> 
<li>T1018</li> 
<li>T1012</li> 
<li>T1015</li> 
<li>T1014</li> 
<li>T1016</li> 
<li>T1082</li> 
<li>T1083</li> 
<li>T1081</li> 
<li>T1086</li> 
<li>T1087</li> 
<li>T1085</li> 
<li>T1088</li> 
<li>T1089</li> 
<li>T1124</li> 
<li>T1127</li> 
<li>T1126</li> 
<li>T1121</li> 
<li>T1123</li> 
<li>T1002</li> 
<li>T1003</li> 
<li>T1006</li> 
<li>T1128</li> 
<li>T1004</li> 
<li>T1005</li> 
<li>T1007</li> 
<li>T1037</li> 
<li>T1035</li> 
<li>T1034</li> 
<li>T1033</li> 
<li>T1031</li> 
<li>T1039</li> 
<li>T1038</li> 
<li>T1136</li> 
<li>T1137</li> 
<li>T1134</li> 
<li>T1135</li> 
<li>T1130</li> 
<li>T1189</li> 
<li>T1024</li> 
<li>T1027</li> 
<li>T1183</li> 
<li>T1182</li> 
<li>T1119</li> 
<li>T1103</li> 
<li>T1107</li> 
<li>T1105</li> 
<li>T1109</li> 
<li>T1108</li> 
<li>T1196</li> 
<li>T1197</li> 
<li>T1191</li> 
<li>T1192</li> 
<li>T1110</li> 
<li>T1199</li> 
<li>T1028</li> 
<li>T1055</li> 
<li>T1054</li> 
<li>T1057</li> 
<li>T1056</li> 
<li>T1118</li> 
<li>T1050</li> 
<li>T1053</li> 
<li>T1117</li> 
<li>T1059</li> 
<li>T1112</li> 
<li>T1047</li> 
<li>T1042</li> 
<li>T1043</li> 
<li>T1048</li> 
<li>T1049</li> 
<li>T1073</li> 
<li>T1070</li> 
<li>T1077</li> 
<li>T1076</li> 
<li>T1075</li> 
<li>T1074</li> 
<li>T1172</li> 
<li>T1173</li> 
<li>T1170</li> 
<li>T1078</li> 
<li>T1176</li> 
<li>T1145</li> 
<li>T1179</li> 
<li>T1219</li> 
<li>T1140</li> 
<li>T1214</li> 
<li>T1068</li> 
<li>T1069</li> 
<li>T1064</li> 
<li>T1065</li> 
<li>T1066</li> 
<li>T1067</li> 
<li>T1060</li> 
<li>T1061</li> 
<li>T1062</li> 
<li>T1063</li> 
</details> 


 ## Techniques not covered by yara rules 

<details closed>
<summary>Techniques</summary>
<br>
<li>T1021</li> 
<li>T1010</li> 
<li>T1221</li> 
<li>T1115</li> 
<li>T1201</li> 
<li>T1013</li> 
<li>T1025</li> 
<li>T1180</li> 
<li>T1131</li> 
<li>T1113</li> 
<li>T1193</li> 
<li>T1100</li> 
<li>T1208</li> 
<li>T1181</li> 
<li>T1026</li> 
<li>T1032</li> 
<li>T1046</li> 
<li>T1106</li> 
<li>T1092</li> 
<li>T1200</li> 
<li>T1001</li> 
<li>T1079</li> 
<li>T1210</li> 
<li>T1132</li> 
<li>T1207</li> 
<li>T1120</li> 
<li>T1138</li> 
<li>T1099</li> 
<li>T1104</li> 
<li>T1090</li> 
<li>T1040</li> 
<li>T1052</li> 
<li>T1029</li> 
<li>T1194</li> 
<li>T1129</li> 
<li>T1213</li> 
<li>T1209</li> 
<li>T1216</li> 
<li>T1203</li> 
<li>T1080</li> 
<li>T1058</li> 
<li>T1044</li> 
<li>T1045</li> 
<li>T1023</li> 
<li>T1084</li> 
<li>T1116</li> 
<li>T1198</li> 
<li>T1008</li> 
<li>T1017</li> 
<li>T1174</li> 
<li>T1102</li> 
<li>T1217</li> 
<li>T1030</li> 
<li>T1071</li> 
<li>T1114</li> 
<li>T1022</li> 
<li>T1185</li> 
<li>T1125</li> 
<li>T1220</li> 
<li>T1009</li> 
<li>T1020</li> 
<li>T1190</li> 
<li>T1094</li> 
<li>T1036</li> 
<li>T1171</li> 
<li>T1133</li> 
<li>T1072</li> 
<li>T1222</li> 
<li>T1223</li> 
<li>T1218</li> 
<li>T1175</li> 
<li>T1187</li> 
<li>T1011</li> 
<li>T1188</li> 
<li>T1202</li> 
<li>T1195</li> 
<li>T1122</li> 
<li>T1101</li> 
<li>T1177</li> 
<li>T1111</li> 
<li>T1051</li> 
<li>T1178</li> 
<li>T1186</li> 
<li>T1211</li> 
<li>T1212</li> 
<li>T1041</li> 
</details> 


 ## Techniques with tests 

<details closed>
<summary>Techniques</summary>
<br>
<li>T1093</li> 
<li>T1095</li> 
<li>T1096</li> 
<li>T1099</li> 
<li>T1098</li> 
<li>T1150</li> 
<li>T1151</li> 
<li>T1152</li> 
<li>T1153</li> 
<li>T1154</li> 
<li>T1155</li> 
<li>T1156</li> 
<li>T1158</li> 
<li>T1201</li> 
<li>T1202</li> 
<li>T1206</li> 
<li>T1207</li> 
<li>T1018</li> 
<li>T1013</li> 
<li>T1012</li> 
<li>T1015</li> 
<li>T1014</li> 
<li>T1016</li> 
<li>T1082</li> 
<li>T1083</li> 
<li>T1081</li> 
<li>T1086</li> 
<li>T1087</li> 
<li>T1084</li> 
<li>T1085</li> 
<li>T1088</li> 
<li>T1089</li> 
<li>T1126</li> 
<li>T1124</li> 
<li>T1127</li> 
<li>T1009</li> 
<li>T1121</li> 
<li>T1123</li> 
<li>T1122</li> 
<li>T1002</li> 
<li>T1003</li> 
<li>T1128</li> 
<li>T1004</li> 
<li>T1005</li> 
<li>T1007</li> 
<li>T1037</li> 
<li>T1036</li> 
<li>T1035</li> 
<li>T1034</li> 
<li>T1033</li> 
<li>T1031</li> 
<li>T1030</li> 
<li>T1166</li> 
<li>T1038</li> 
<li>T1136</li> 
<li>T1137</li> 
<li>T1134</li> 
<li>T1135</li> 
<li>T1132</li> 
<li>T1133</li> 
<li>T1130</li> 
<li>T1131</li> 
<li>T1138</li> 
<li>T1139</li> 
<li>T1021</li> 
<li>T1022</li> 
<li>T1023</li> 
<li>T1027</li> 
<li>T1028</li> 
<li>T1182</li> 
<li>T1181</li> 
<li>T1180</li> 
<li>T1186</li> 
<li>T1119</li> 
<li>T1103</li> 
<li>T1101</li> 
<li>T1100</li> 
<li>T1107</li> 
<li>T1105</li> 
<li>T1104</li> 
<li>T1108</li> 
<li>T1144</li> 
<li>T1197</li> 
<li>T1191</li> 
<li>T1193</li> 
<li>T1059</li> 
<li>T1183</li> 
<li>T1055</li> 
<li>T1057</li> 
<li>T1056</li> 
<li>T1118</li> 
<li>T1050</li> 
<li>T1053</li> 
<li>T1115</li> 
<li>T1116</li> 
<li>T1117</li> 
<li>T1110</li> 
<li>T1058</li> 
<li>T1112</li> 
<li>T1113</li> 
<li>T1169</li> 
<li>T1047</li> 
<li>T1044</li> 
<li>T1045</li> 
<li>T1042</li> 
<li>T1043</li> 
<li>T1040</li> 
<li>T1160</li> 
<li>T1163</li> 
<li>T1165</li> 
<li>T1164</li> 
<li>T1048</li> 
<li>T1049</li> 
<li>T1073</li> 
<li>T1071</li> 
<li>T1070</li> 
<li>T1077</li> 
<li>T1076</li> 
<li>T1075</li> 
<li>T1074</li> 
<li>T1173</li> 
<li>T1170</li> 
<li>T1176</li> 
<li>T1177</li> 
<li>T1159</li> 
<li>T1219</li> 
<li>T1178</li> 
<li>T1147</li> 
<li>T1146</li> 
<li>T1145</li> 
<li>T1179</li> 
<li>T1142</li> 
<li>T1141</li> 
<li>T1140</li> 
<li>T1217</li> 
<li>T1216</li> 
<li>T1214</li> 
<li>T1211</li> 
<li>T1148</li> 
<li>T1069</li> 
<li>T1064</li> 
<li>T1065</li> 
<li>T1067</li> 
<li>T1060</li> 
<li>T1062</li> 
<li>T1063</li> 
<li>T1046</li> 
<li>T1168</li> 
</details> 


  ## Techniques with tests and without rules 

<details closed>
<summary>Techniques</summary>
<br>
<li>T1193</li> 
<li>T1099</li> 
<li>T1178</li> 
<li>T1177</li> 
<li>T1150</li> 
<li>T1151</li> 
<li>T1152</li> 
<li>T1153</li> 
<li>T1154</li> 
<li>T1155</li> 
<li>T1156</li> 
<li>T1030</li> 
<li>T1201</li> 
<li>T1202</li> 
<li>T1113</li> 
<li>T1100</li> 
<li>T1206</li> 
<li>T1207</li> 
<li>T1071</li> 
<li>T1132</li> 
<li>T1133</li> 
<li>T1131</li> 
<li>T1115</li> 
<li>T1013</li> 
<li>T1058</li> 
<li>T1138</li> 
<li>T1139</li> 
<li>T1045</li> 
<li>T1046</li> 
<li>T1146</li> 
<li>T1159</li> 
<li>T1084</li> 
<li>T1044</li> 
<li>T1147</li> 
<li>T1021</li> 
<li>T1022</li> 
<li>T1023</li> 
<li>T1142</li> 
<li>T1141</li> 
<li>T1217</li> 
<li>T1216</li> 
<li>T1181</li> 
<li>T1180</li> 
<li>T1186</li> 
<li>T1211</li> 
<li>T1148</li> 
<li>T1169</li> 
<li>T1168</li> 
<li>T1101</li> 
<li>T1009</li> 
<li>T1040</li> 
<li>T1122</li> 
<li>T1160</li> 
<li>T1163</li> 
<li>T1104</li> 
<li>T1165</li> 
<li>T1164</li> 
<li>T1166</li> 
<li>T1144</li> 
<li>T1036</li> 
<li>T1116</li> 
</details> 


  ## Techniques without tests 

<details closed>
<summary>Techniques</summary>
<br>
<li>T1091</li> 
<li>T1097</li> 
<li>T1204</li> 
<li>T1019</li> 
<li>T1006</li> 
<li>T1039</li> 
<li>T1189</li> 
<li>T1024</li> 
<li>T1109</li> 
<li>T1196</li> 
<li>T1192</li> 
<li>T1199</li> 
<li>T1054</li> 
<li>T1172</li> 
<li>T1078</li> 
<li>T1068</li> 
<li>T1066</li> 
<li>T1061</li> 
</details> 
