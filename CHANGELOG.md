# new
- Add Index file parsing (not yet finished, but is done for faster access)

# 2025.12.26.2
- support netstandard 2.0

# 2025.12.26.1
- check user credentials

# 2025.12.19.1
- fix empty stl networks

# 2025.12.14.1
- support nw interfaces on touch, and also pb interfaces

# 2025.12.5.1
- fixed zipped 10.5 projects
- V21 support
- fix export of some projects created wrong SCL

# 2025.11.17.1
- Lazy parse of "MemberValues" cause of perfomance issues with large arrays
- SCL Code fixes in export

# 2025.11.11.1
- fix multi lang comments in SCL XML export

# 2025.11.3.1
- Remove SharpCompress dependency
- thread safe access of MemberInstance

# 2025.10.31.1
- LID support in HmiTagTables and MemberValues

# 2025.10.30.1
- perf fixes (lazy parse memberValues)

# 2025.10.20.1
- fixes in xml export of scl blocks (global access quoteing)
- fix xml parsing, some had no namespaces
- know how protection of datablocks
  
# 2025.9.30.1
- fix some wincc script commands
- export wincc from librarys
- library version as folders

# 2025.8.4.2
- fix graph xml export

# 2025.8.4.1
- Fix errors with some V13 Projects (interface parsing)
- Fix decryption in some projects blocks
- Some images in WinCC Unified Projects could not be loaded
- Fix Interface Parsig in some Projects (StackOverflowExc)
- Patch V15 Metadata for IpiTragetInstance (bug not yet found)
- few null ref fixes
- sub interface parts in V11-13 disabled atm. they cause stackoverflow, but will be fixed

# 2025.7.29.1
- Convert options are now records
- Network export contains mor information
- Cache now works with different options
- Read OPC Client Lists

# 2025.7.10.1
- Absolute Offset Adresses support
- Export of Technology Objects
- Export of Array DBs
- CFC Charts more support
- Interface export fixes
- Multiple SimaticML creation fixes.
  
# 2025.7.2.2
- Work on DDC Charts (add types)

# 2025.7.2.1
- Work on Parsing of Charts (fix System.Drawing types)

# 2025.6.30.1
- SimaticML for Graph Blocks

# 2025.6.27.2
- bit-offsets in interface in sub structs
 
# 2025.6.27.1
- massive work on automation xml for SCL blcoks
- bit-offsets in interface

# 2025.6.24.2
- Fixes in Automation XML generation for LAD, FDB, SCL, STL
- Enable Cache for Interface Parsing
- Tag Table parsing fixes

# 2025.6.24.1
- Fixes in Automation XML generation for LAD, FDB, SCL, STL

# 2025.6.23.3
- Type for StorageBusinessObjects
- Easier to use NetworkParser

# 2025.6.23.2
- Changed Versioning, so multiple versions per day could be released
- Fixes for V10.5, V11, V12, V13 and V14
- Fixes in AutomationXML export for all versions
- AutomationXML export for thoes Versions with most KOP Blocks should work.

# 1.25.6.23
- Fixes for TIA V10.5

# 1.25.6.17
- first version as nuget package
