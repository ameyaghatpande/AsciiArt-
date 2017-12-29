### ASCII art is a graphic design technique that uses computers for presentation and consists of pictures pieced together from the 95 printable (from a total of 128) characters defined by the ASCII Standard

#### This code will create an AsciiArt Encoder/Decoder in python

#### Steps to run the code
1. Download the above jupyter notebook(AsciiArt-Encoder-Decoder.ipnyb) in a folder
2. Keep the input "data.txt" in the same folder
3. Run each cell of the jupyter notebook from top to bottom by pressing (Shift + Enter)on each cell
4. Function definitions and test cases have been explained in jupyter notebook

##### Data format - I am using Run Length Encoding(RLE) to compress the input Ascii Art. This encoding is useful to compress the input data when it contains "CONSECUTIVE" similar characters. I choose this compression type because Ascii Art has lot of consecutive characters and also has lot of tabs/spaces at start/end of each line (which is again a character " "). This helps to compress the data effeciently
##### Sample input = "AAA2222CCCCCCA"  
##### Sample encoded output by RLE = [(3, A), (4, 2), (6, C), (1,A)]
