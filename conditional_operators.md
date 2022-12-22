# Conditional operators

## Integer comparison

`-eq - is equal to - if [ "$a" -eq "$b" ]`

`-ne  - is not equal to - if [ "$a" -ne "$b" ]`

`-gt - is grater then -  if [ "$a" -gt "$b" ]` 

`-ge - is grater then or equal to -  if [ "$a" -ge "$b" ]` 

`-lt - is less then - if [ "$a" -lt "$b" ]`

`-le - is less then or equal to - if [ "$a" -le "$b" ]`

`< - is less then - (("$a" < "$b""))`

`<= - is less then or equal to - (("$a" <= "$b""))`

`> - is grater then - (("$a" > "$b""))`
 
`>= - is grater then or equal to - (("$a" >= "$b""))`


# String comparison

`= - is equal to - if [ "$a" = "$b" ]`

`== - is equal to - if [ "$a" == "$b" ]`

`!= - is not equal to - if [ "$a" != "$b" ]`

`< - is less then, in ASCII alphabetical order - if [[ "$a" < "$b" ]]`

`> - is grater then, in ASCII alphabetical order - if [[ "$a" > "$b" ]]`

`-Z - string is null, that is, has zero length`