Use linux command to search word and print Occurance.

step1) use command to search (grep) to filter the word which we need.

step 2) To print the reqiured word we need to split the data input into individual varaibles, for the use command (AWK).

step 3) then we use command in terminal like:
 $ cat file_name | grep WORD | awk '{print $wordposition no.}'
