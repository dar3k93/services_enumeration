### SMB:
  It's protocol for sharing files and resources. Runs on port 445 or on port 139
  
##### nmap:

##### smbmap
  -smbmap -H <victim_ip>
  -smbmap -H <victim_ip> -R
  -smbmap -H <victim_ip> -U anonymous -d <directory>
  
  ***H***: hostname
  ***R***: recursive, go through each directory and oyt the files
  ***U***: username
  
#### smbclinet
  -smbclient \\\\<victim_ip>\\<directory>
  
#### working with smb
  -file upload
  ***smb:> get "filename"***