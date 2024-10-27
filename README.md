# Process-EventLogs
Process select Event Logs and Event ID's with EvtxECmd

PS > .\Process-Evtx.ps1 -source <source_dir> -dest <dest_dir> -logs <logs>
  
PS > .\Process-Evtx.ps1 -source E:\C\Windows\system32\winevt\logs -dest G:\extracted_winevt -logs .\EventLogs2Process.txt

## TO DO: 
- Modify: `$evtxecmd_path   = "C:\Forensic Program Files\ZimmermanTools\EvtxExplorer"`  to provide the user option to specifiy the directory where EvtxECmd is installed. 
