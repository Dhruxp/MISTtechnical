The task involved learning about basic ciphers like base64 and ceaser cipher that form the basics of cryptography.
Base64: Not necessarily a cipher but more of an encription tactic, it just converts files that are binary coded like texts, images and files into readable data like the english alphabets. It's application could be in safe internet data transfer and also to encode images inside text formats like JSON
Ceaser's cipher: One of the most basic cryptographic tools, it just involves moving each alphabet up by a certain fixed number and the wrap around from the last alphabet. Ex: If the number is 2 - A becomes C and Z becomes B and so on.
We also had to finish the first 2 modules of linux luminarium DOJO on pwn.college:
It had basic linux commands and dealt with how to code on the terminal.
Firstly, started of with the 'cd' command that changes directories and moves around the linux filesystem. In the same challenge, I was also introduced to the concept of home and root directories.
Then, I learnt to differentiate between absolute paths (that start with /) anf relative paths that are only used when we need to navigate in the cwd (Current working directory).
Then I also learnt to navigate using the ./ command(implicit and explicit relative paths)
Secondly, I moved to the basics of file sysytem:
cat : Concatenation or reading of files, I learnt what the impacts of cat are, if given with an absolute path or given without any parameter. 
grep: This is used to search for a particular substring under a file, as cat reads out the whole file finding a single substring might prove to be difficult and therefore we can use grep to perform this operation.
diff: This will give only the difference between the 2 files formatting in one of 2 ways i.e. <lineno.1>c<lineno.2> or <lineno.1>a<lineno.2> where c means that the line number in file one CHANGED to something else in line number 2 of file two and the a stands for addition if an extra line is present in the next file this will show.
ls: This lists all files under the specified directory or under the cwd if no parameter is specified.
touch: This creates a new file but only under the cwd.
rm: Removes file mentioned
mv: Moves the content of file1 to file2 and deletes file1 fully
cp: Copies the content from file2 to file2 and doesn't delete file1.
ls -a: ls by default doesn't display the file if the name starts with a (.), this command will ensure it does.
mkdir: This makes a new directory.
find: This will find files according to the parameter given (name or location), if no parameter it will list all files.
These basic commands were all new to me and working with hands on tasks and examples made it very easy to understand. The 'Home sweet home' challenge and the 'Epic filesystem quest' were the 2 challenges that took the most time out of all of them but they were also fun to solve.
