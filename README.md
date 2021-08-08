# procedure
1. copy following files into operation server.
    * template.json
    * check_bios_settings.py
2. execute "python ./check_bios_settings.py"

# help
    usage: check_bios_settings.py [-h] [-u USERNAME] [-p PASSWORD] [-f FILEPATH]
                                  [-l {DEBUG,INFO,WARNING,ERROR,CRITICAL}]
                                  host
    
    This script compares actual bios settings
    
    positional arguments:
      host                  target BMC ipv6 address or hostname.
    
    optional arguments:
      -h, --help            show this help message and exit
      -u USERNAME, --username USERNAME
                            username to log into target.
      -p PASSWORD, --password PASSWORD
                            password to log into target.
      -f FILEPATH, --filepath FILEPATH
                            path for json file including expected bios settings.
      -l {DEBUG,INFO,WARNING,ERROR,CRITICAL}, --loglevel {DEBUG,INFO,WARNING,ERROR,CRITICAL}
