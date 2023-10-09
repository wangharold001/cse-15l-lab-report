Harry Wang
Professor Onat
CSE 15L
9 October 2023
Lab Report 1

cd:

The terminal did not show anything. My working directory was just home. The reason I got no output was because cd stands for change directory, and I did not input an argument directory to change my working directory to. The output isn’t an error since I didn’t input any arguments, so nothing happened.

The terminal updated my working directory from /home to /home/lecture1, and then to /home/lecture1/messages. This shows that I changed my working directory using the cd command. There was no error.

I ran this command with a working directory /home/lecture1/messages.The terminal reminded me that the text file I inputted was not a directory. The reason I got this output is because I requested to change the directory to a text file instead of another directory. As a result, an error was returned.

ls: 



The working directory was the messages subfolder. The terminal outputted what files/directories were contained in the working directory. The reason is that “ls” lists the relevant files in the wd. This was not an error.

My working directory was home/lecture1. The terminal outputted again the files in the messages subdirectory, since I passed in the messages directory as an argument. This was not an error.


My working directory was home/lecture1. The terminal outputted the name of the file I passed in, since I asked it to list the files contained in a file, which is just referring to the file itself. This was not an error.
cat: 

My working directory was home/lecture1. The terminal did not skip to the next line, and waited for me to pass in an argument. I had to Ctrl+C to exit out. The reason is because cat asks for a file argument to output. As a result, simply typing cat with no intended output file is an error.
My working directory was home/lecture1. The terminal reminded me that messages is a directory, and cat only operates on files. As a result, an error was returned.
My working directory was home/lecture1/messages. The terminal outputted the contents of the text file I passed in as an argument. This is expected since this is the use case of the cat command. No error.
