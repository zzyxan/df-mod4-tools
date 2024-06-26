# df-mod4-p4
# Exercise 1
### I downloaded the NSRL database from the link, then went to Tools > Options > Hash Sets in Autopsy to import the database.
![alt text](https://github.com/zzyxan/df-mod4-tools/blob/main/images/Hash%20Set%20Import%20SS.png)
# Exercise 2 
### For this exercise I started off by importing the Ch09 project file into Autopsy, then running a keyword search for "Special Project-A". The book tells you to look for file extensions, then images, since the known bad files are all images, but I felt like using the keyword search was more usefull. Then I tagged all the files as "Special Project-A", then ran a report that exported to excel to get all the hashes for the files. After that I created a new hash set using the Tools > Options > Hash Sets and added the hashes to the database.
![alt text](https://github.com/zzyxan/df-mod4-tools/blob/main/images/Special%20Project%20A%20Hash%20Database%20SS.png)
# Exercise 3
### For exercise 3 I created a sample word doc to use as a test, downloaded and ran WinHex and got the hash for the file. Then I used that hash to verify with powershell that WinHex was operational. After that I opened up the "Jeffersonian Quotes" document in WinHex and selected the first sector. I had to use the book's instructions for this one as I'm not quite sure how to tell how many bytes the first sector has in WinHex, it would be a usefull feature to add I think.
![alt text](https://github.com/zzyxan/df-mod4-tools/blob/main/images/Jefferson%20Quotes%20First%20Sector%20Hash.png)
# Exercise 4
### This exercise was really interesting to me. CyberChef is an interesting tool, and the comparison to recipes is whimsical. I created a sample text file, evidence.txt, used the Vigenere Encode recipe to encode the text with a key, "Rowan" and then saved the output to nothing.txt . I was then able to decode the gibberish file using the same key and saved that as the recovered.txt file. Although the process was interesting, I think it would be very hard to decode a ciphered message without knowing both the cipher method, and the key. I guess that's why theres a whole field of study around Cryptography.
![alt text](https://github.com/zzyxan/df-mod4-tools/blob/main/images/Ex4%20Bit%20shifting%20SS.png)
