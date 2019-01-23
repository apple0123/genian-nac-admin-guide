Genian NAC v5.0.15 Release Notes (October 2018)
===============================================

Release Date: 10/25/2018

:download:`Download 5.0.15 <https://www.genians.com/get-files/12761/?version=5.0.15>` 

For upgrading system software, please see :doc:`/system/system-software` 

New Features
------------

- #18009 Add HTTP header setting function to log filter web-hook settings. You can set Authorization, Content-type and more headers
- #17944 Add multi-domain setting function with LDAP authentication integration
- #17081 Add ability to collect open port information in macOS network information collection plug-in
- #17680 Add macOS agent appearance and personalization plugin
- #17949 Add Windows device chassis type information (laptop, desktop, etc.)

Enhancements
------------

- #18357 RADIUS server now provided in professional edition.
- #18171 RADIUS authentication and accounting secrets and client IP settings are combined into single setting.
- #18102 Policy menu structure change. Moves the Windows Update and External Device menus that were under Node Policy to the top and move device under a group to external device policy.
- #18154 Add a virtual machine default node group using most popular hypervisor vendor's MAC OUI.
- #17969 Add node group condition's agent needs indication icon for easy to determine agent is required.
- #17081 Add ability to collect open port information in macOS network information collection plug-in.
- #17927 Add a hyperlink to switch and port information in node details.
- #18011 Add audit record if log filter's web-hook return error code.
- #18088 Add to switch management screen so that MAC can be output as tooltip in IP column.
- #18161 User Information Synchronization Error Audit Record Improved to stay in detail.

Bug Fixes
---------

- #17924 Fixed an issue where wireless LAN information collection did not work through agent action in Windows 10 with virtual wireless LAN interface.
- #17967 Fixed an issue where SSID is displayed as MAC in log when using HP Aruba Access Point.
- #18012 Fixed an issue where the "Promiscuous enabled interface does not exist" node group condition was abnormal.
- #18114 Fixed an issue where after inputting value in search condition of audit log, search is not performed when hit the enter key.
- #17997 Fixed a problem where the menu bar was hidden in the matrix when scrolling occurred when enlarging the matrix view.