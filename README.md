# Windows fixes

## Can't install updates from 'Store' 
- Failed to install or upgrade Microsoft Store package. Error code: 0x800706d9

Solution:
- Open services.msc
- Find "Storage Service" -> Properties
- Probably set to disabled which causes the issue
- Set to "Automatic (delayed)"
- Retry updates and they should work
