#!/bin/bash
#cat sort uniq grep tee wc head tail
#grep is a powerful program used to find text patterns in files
# Usage: grep pattern [file(s)...]
# /dev/null the bit bucket
# op > file
# op 1> file
# op > file 2>&1
# op &> file
# op &>> file
# op >> file # appends to the file
# cat --- CTRL + D == EOF
# cat somefiles > combined_file
# cat > output_file #write text to the output file
# In linux there is no meaning of the file extensions -- inodes/nodes -- folders/devices etc. are also treated as files

ls /bin /usr/bin | sort | uniq -d | less # sqhows duplicates

df

echo ~

# Arithmetic Expression -- Arithmetic Exapnsion
# $((arithmetic_expression))

# Brace Expansion -- Brace Expression
echo Number_{1..10}
echo {001..10}
echo {Z..A}
echo {z..a}
echo {A{1,2},B{a..c}}

printenv # see the variables
#Command Substitution
echo $(ls)
# OLDER: Use of back quotes for COMMAND SUBSTITUTION
echo `ls`
# word plitting by shell removes extra space
echo This is a    test.
echo I earn $1100000000 daily.
# <READ> Learn Quoting -- from page number 99 +
# Inside double quotes all special chars lose their special meaning except $ backslash and back quote.
#Parameter expansion, Arithmetic expansion and command substitution takes place inside double quotes.
echo "$USER $((2+200)) $(cal)"
# Spaces Tabs and newlines -- Line Feed Characters
# Line feed chars work as delimiters
echo "See the difference"
echo $(cal)
echo "$(cal)"
# Single Quotes suppress all expansions

