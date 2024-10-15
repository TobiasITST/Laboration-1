Tested on windows

Requires 'python-nmap'. available via pip

Menu structure:

### Main menu
    - nMap, Enter the Nmap menu to run nMap scans, open result file etc.
    - IP, Enter the IP-address menu
    - Exit, exits this program and does NOT save any results
    - --help, show program commands again


### nMap menu
    - nMap, execute nMap commands
    - Show, show result of current session
    - Open, open previous result from JSON-file
    - Save, save current session result to JSON-file
    - Show IP, show IP addresses in current list
    - Back, goes back to main menu. Careful! Save to file if you done any changes
    - --help, show menu commands again

### Ip address menu
    - Show, show IP addresses in current list
    - Open, open desired IP address list from file
    - Save, save current IP address list to file
    - Add, add an IP address to current list
    - Remove, remove an IP address from current list
    - Back, goes back to main menu. Careful! Save to file if you done any changes
    - --help, show menu commands again