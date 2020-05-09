# Shell Command Wiki

Welcome to the command-wiki wiki!

* Find the text in file and replace it in the same file : 
  - sed -i -e 's/2019/2020/g' <filename>

* Remove last character from awk
  - ... | awk '{if (NR!=1) {print substr($2, 1, length($2)-1)}}'


* Find sub string in string:
 - if [[ $item == *"ty20"* ]]
