difference b/w original files and updated files, apply the changes to original files..

a) create 2 directories named as "Original" and "Updated".
using command-> mkdir , create a new directory as 'original' and 'updated'.

b)copy files to respective folders.
using command touch command create .txt files at c drive, and let the files copy to those 2 directories using copy command.
command--> $ cp -r filename(source) directoryname(destination).

c)find the diff b/w two directories using linux command.

command-> $ diff original updated
Only in original: original-backup
Only in original: original-file.sh
Only in updated: updated-file.sh

d)make copy of 'original' to some other directory as 'original-backup' and apply changes to 'original-file.sh' file.

command--> cp -r original original-backup
then, comman-> cd original-backup
then, command-> notepad original-file.sh ---- apply changes and save it.








