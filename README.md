# java-antlr-parser

## To test
	# follow quick start guild on: [http://www.antlr.org](http://www.antlr.org)
	mkdir build/
	antlr4 -o build/ Java.g4
	javac -d build/ build/Java*.java
	# to execute
	cd build; grun Java compilationUnit ../Test.java; cd ..

