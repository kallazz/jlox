JFLAGS = -g
JC = javac
.SUFFIXES: .java .class
.java.class:
	$(JC) $(JFLAGS) $*.java

CLASSES = \
	Lox.java \
	Token.java \
	TokenType.java \
	Scanner.java \

default: classes

classes: $(CLASSES:.java=.class)

clean:
	$(RM) *.class