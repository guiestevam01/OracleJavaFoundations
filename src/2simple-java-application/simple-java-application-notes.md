Just like human language, programming language have keywords, reserved words and literas that constituied instructions that made the program do things.
We have, control program flow(like if, else, continue, break...), code structured(private, public, import,...) literals (true, false, 123,null),work with objects,handle exceptions
JAVA SYNTAX:
Java code is grouped into classes, just as C code is grouped into functions (in C++ the code is grouped into functions or classes.)

    class name{                void greet(){             int main(){       
	source-code		    code		    code
    }				}			}

	JAVA		       class Greeter {             C
			       public:
				   void greet(){
				       std::cou
				   }
				   C++

Classes contain: fields(instance variable), methods, constructors, initialization blocks, nested classes (classes internas), interface, enums,annotations and other elements like package, imports,  lambdas, oop.
code blocks are delimited with {}
Statements(Declaração) are terminated with;
EXAMPLE:
public class Example {
    private static final int CONSTANT = 10;    // static constant field
    private int count;                          // instance field
    private String name;

    // instance initializer block
    {
        System.out.println("Instance initializer block");
    }

    // static initializer block
    static {
        System.out.println("Static initializer block");
    }

    // constructor
    public Example() {
        count = 0;
        name = "default";
    }

    public Example(String name) {
        this();                // calls the default constructor
        this.name = name;
    }

    // instance method
    public void increment() {
        count++;
    }

    // instance method
    public int getCount() {
        return count;
    }

    // static nested class
    public static class Nested { }

    // inner class
    public class Inner { }
}

