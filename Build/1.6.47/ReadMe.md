This build was made using:

* Microsoft Windows 10 Pro 22H2 Build 19045.5487.
* CMake 3.31.6.
* Microsoft Visual Studio Community 2022 (64-bit) Version 17.13.5.

Source codes: https://sourceforge.net/projects/libpng/  
Performer: McArcher.  
Day: 2025-04-07.  

### Build Notes

* `zlib` library: version 1.3.1.
* To build `libpng` with an external `zlib` library one should do the following:
	* Open CMake GUI
    * Set the source & build folders
    * Press "Add Entry" and add an entry:
      * Name: ZLIB_INCLUDE_DIR
      * Type: String
      * Value: Path to zlib `include` folder
    * Press "Add Entry" and add an entry:
      * Name: ZLIB_LIBRARY
      * Type: String
      * Value: Path to `zlib.lib` file
    * Press "Configure"
    * Press "Generate"
    * Open the created solution in Visual Studio
    * Build the solution using "Release" target

## Integrity Meta Data

Integrity can be verified using following parameters:
* File sizes
    * See the `file_sizes.txt` file, [Link](./file_sizes.txt).


* CRC32 check sums
    * See the `crc32_sums.txt` file, [Link](./crc32_sums.txt).


* MD5 check sums
    * See the `md5_sums.txt` file, [Link](./md5_sums.txt).


* SHA-256 check sums
    * See the `sha256_sums.txt` file, [Link](./sha256_sums.txt).

**Notes**

Checks of hash sums & sizes can be performed with a `Hasher` tool.  
Hasher's repository: https://github.com/vault-thirteen/Hasher
