# cloak
A command receive stdin to output temporary file and output temporary file name to stdout.

It's very tiny command.
Just a `tempname=$(mktemp);cat > $tempname;echo $tempname`
