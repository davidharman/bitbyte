# bitbyte
A simple bash tool to convert quickly from different data sites

I wanted:
- To quickly convert a data size to another size without using a browser every time or working it out in my head
- To convert from different data sizes, e.g. bytes, GB, TB, etc 

To install: place script in bin folder and chmod +x to make it executable

To run enter a value and datasize separated by a space
bitbyte <value> <datasize>


Example:
  $> bitbyte 1024 MB
  Input  value 1024 MegaBytes
  
  Bytes:1073741824
  KiloBytes:1048576
  MegaBytes:1024
  Gigabytes:1
  TeraBytes:0
  PetaBytes:0
  
  $> bitbyte 1125899906842624 KB
  Input  value 1125899906842624 KiloBytes
  
  Bytes:1152921504606846976
  KiloBytes:1125899906842624
  MegaBytes:1099511627776
  Gigabytes:1073741824
  TeraBytes:1048576
  PetaBytes:1024
 
