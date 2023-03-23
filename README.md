# Assignment-VIIFileI-O
Editing .txt with java
Write a program that edits a text file to display each complete sentence with a period at the end in a
separate line. Your program should work as follows: Ask the user to input file name containing
sentences separated with a period (sentences may be in single line as a paragraph contains multiple
sentences). Create a temporary file, copy from the source file to a temporary file and perform the
required operation (write all sentences at a different line without a period). Copy the contents of the
temporary file back into the source file. Use a method (or methods) in the class File to remove the
temporary file.
You will also want to use the class File for other things in your program. The temporary file should
have a name that is different from all existing files so that the existing files are not affected (except for
the file being edited). Your program will ask the user for the name of the file to be edited. However,
it will not ask the user for the name of the temporary file but will instead generate the name within
the program. You can generate the name any way that is clear and efficient. One possible way to
generate the temporary file is to start with an unlikely name, such as "Temp1", and to append a digit,
such as '1', until a name is found that does not name an existing file.
