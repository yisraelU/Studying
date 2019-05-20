# FTP
  - about
    - FTP is unique in the sense that most application protocols use the same connection for the transfer of data as they do for managing the connection like http and the like
    - FTP has a separate connection for data transmission , It set up in one of 2 ways
      - active : Client turns into a server, It sends the FTP server a PORT command that says which port t is listening on .
      This creates a ton of problems as the client is mosty behind some firewall whether at the OS evel or NAT etc.. 
      This is the reason for the advent of Passive mode
      - passive: Passive mode puts the nus on the server to setup the additional connection configs
        The client issues the PASV (thats instead of the PORT) command that tells the server to setup passive mode .
        The server has a configuration os a range of a few thousand ports available for it to start a new session for the client to connect to.
# HTTP
  - about
        
      
