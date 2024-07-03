##What this command does:
 When given a directory, this command returns the number of files, the total number of bytes, and the number of bytes of the largest file in the directory.
##Why/When this command is useful:
 This command is useful when you are running out of storage and need to clean up directories that are taking up a lot of space.
##How you can use this command:
 You can use this command by calling it and the name of a directory you wish to see.

#Examples:

I made a test directory with three files in it: file1.txt, file2.txt, and file3.txt. each of the files had a different word.
I ran the command using `./filesize ./test`

The results showed
```
./test/file1.txt
./test/file2.txt
./test/file3.txt
3 files in ./test
15 total bytes in ./test
the biggest file is 5 bytes
```

