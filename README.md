# Text Compressor
Sophia Reynolds

# Text Compressor

*~Part 1~* of this project is capable of taking a properly formatted txt file, 
parsing compressed text from it, and using the associated mapping information to uncompress
the file. It also features a compression ratio function which shows the degree to
which our data is being saved!

~*Part 2*~ of this project is capable of taking txt and compressing it, and the function
it contains also provides a list of all the relevan the character pairs and the unused 
ASCII characters that they would be associated with

~*Part 3*~ of this project uses everything from the last two sections
to write compressed text and its associated mapping into a file. 

## Python Version -- 3.11
* uses 're' and 'collections'
## File Format
* takes text files in the form of:
  * [TEXT]
  * \<ascii encoded text>
  * [MAPPING]
  * \<pair>":="\<char>
  * \<pair>":="\<char>
  * ...
    * where _pair_ is a commonly used character sequence in the given text
    * and _char_ is a corresponding ascii character which is absent in the provided text

## Use
________________
All my own work!


