Changing from alarm-multiple to alarm-mega

First browse to our /pintos/src/tests/threads directory
-make a copy of alarm-multiple and rename it alarm-mega
-change the number of alarms generated from 7 to 70

Browse to /pintos/src/threads
-run terminal
-run the command grep -r alarm-multiple *
	this searches for all instances of the phrase "alarm-multiple"
-run the command grep -r alarm_multiple *
	this searches for all instances of the phrase "alarm_multiple"

For each instance of alarm-multiple and alarm_multiple, edit the file to include alarm-mega and alarm_mega

make clean
make
