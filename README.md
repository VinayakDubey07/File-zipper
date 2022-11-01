# File-zipper

To compress :
   
Step1:   g++ encode.cpp huffman.cpp -o main
Step2:   ./main inputFile.txt compressedFile.huf   

For Decompressing:

Step1:   g++ decode.cpp huffman.cpp -o main
Step2:   ./main compressedFile.huf outputFile.txt
