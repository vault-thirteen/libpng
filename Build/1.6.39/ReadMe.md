This build was made using:

* Microsoft Windows 10 Pro 22H2 Build 19045.2728.
* CMake 3.26.2.
* Microsoft Visual Studio Community 2022 (64-bit) Version 17.5.3.

Source codes: https://sourceforge.net/projects/libpng/  
Performer: McArcher.  
Day: 2023-04-02.  

### Build Notes

* zlib library: version 1.2.13.
* To build libpng with an external zlib library one should do the following:
	* Open CMake GUI
    * Set the source & build folders
    * Press "Add Entry" and add an entry:
      * Name: ZLIB_INCLUDE_DIR
      * Type: String
      * Value: Path to zlib "include" folder
    * Press "Add Entry" and add an entry:
      * Name: ZLIB_LIBRARY
      * Type: String
      * Value: Path to "zlib.lib" file
    * Press "Configure"
    * Press "Generate"
    * Open the created solution in Visual Studio
    * Build the solution using "Release" target


| File           |    Size | CRC32 | SHA-256                                                          | 
|:---------------|--------:|-------|------------------------------------------------------------------|
| .exe    |  17 408 | xxx   | 1FE1F846DF4E5945BE3A2B5724BF330393A087F437A239465E15E7384A229B4B |
| minigzip.exe   |  14 336 | xxx   | 59081A5518C7909C045A81F64D149C2A312B7A015B388CBFF4698DA0E5680E74 | 
| zlib.dll       |  83 968 | xxx   | 5E9146CD405BF46C3C23BFCDC21CC63AE650EDCB5822AF22BABA6A1161924432 |
| zlib.exp       |   9 714 | xxx   | 2B78F169A8B67140F2C1FFCC315340EA811B74FF8AF666DAEAE5A88F7D2E470A |
| zlib.lib       |  16 638 | xxx   | C06F434053FE74FACA7584BDBCB12E5104D031F24441FAD0E5BCAE7CC43423F1 |
| zlibstatic.lib | 181 244 | xxx   | 50D0C749226971D89921C6EE1ECB72B482793B6023F94D4E544BF185823C4970 |
