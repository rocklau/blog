# How To Install & Run ActiveSync 4.5 on Windows 2003 Server SP2 #

old device ,old window

run regedit and find this node
> HKEY_CURRENT_USER\AppEvents\Schemes\Apps 

Create New Key
> Wcescomm

Create New Key
> PegConnectConfirm

Create New Key 
> .current

double click on Name: (default)

and change this Vaule Data
> A481880F-E3C4-4CA3-8BCF-FCF1C29BF8FC

Ok.you can relaunch ActiveSync
