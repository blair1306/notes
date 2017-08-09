## Get compile_commands.json
1. 
cmake -DCMAKE_EXPORT_COMPILE_COMMANDS=1 .
1. 
make clean
bear make

## Start the Rtags daemon (rdm)
rdm &

## Index the project
rc -J .