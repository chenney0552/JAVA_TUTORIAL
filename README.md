# JAVA_TUTORIAL

## DAY 1 JAVA Tutorial 

**Java Development Kit**
We use Java Development Kit (JDK) to build Java applications. JDK contains a
compiler, the Java Runtime Environment (JRE) and a library of classes that we use
to build applications.

**Java Editions**
• _Java Standard Edition (SE):_ the core Java platform. It contains all of the
libraries that every Java developer must learn.
• _Java Enterprise Edition (EE):_ used for building very large scale,
distributed systems. It’s built on top of Java SE and provides additional
libraries for building fault-tolerant, distributed, multi-tier software.
• _Java Micro Edition (ME):_ a subset of Java SE, designed for mobile
devices. It also has libraries specific to mobile devices.
• _Java Card:_ used in smart cards.

**How Java Code Gets Executed**
The Java compiler takes Java code and compiles it down to Java Bytecode which is
a cross-platform format. When we run Java applications, Java Virtual Machine
(JVM) gets loaded in the memory. It takes our bytecode as the input and translates
it to the native code for the underlying operating system. There are various
implementations of Java Virtual Machine for almost all operating systems.

**Architecture of Java Applications**
The smallest building blocks in Java programs are **_methods_** (also called functions
in other programming languages).We combine related methods in **_classes_**, and
related classes in **_packages_**. This modularity in Java allows us to break down large
programs into smaller building blocks that are easier to understand and re-use.

_function:_
smallest building block in java
A block of code that performs task
Ex: sending email, converting, validate user’s input

_Void: _
ReturnType, reserved keyword in java

Void Name(pass values to the function) { 
}

_main:_ 
Java should have at least one function and it’s called “main”
The main function belong to a class 

void main() {
}

_Class: _
(container for one or more related functions)
Java should have at least one class that contains the main function
Naming: PascalNamingConvention

class Main {
	void main() {
	}
}

_method: _
When the function belongs to a class, it’c called a method of the class
Naming: camelcase notation----camelNamingConvention

_An access modifier: _
a special keyword that determines if other functions or methods in this program can access the ones we have;
Ex: public, private
Put in front of the class	and method declarations
 
public class Main {
	public void main() {
	}

**5 Interesting Facts about Java**
1. Java was developed by James Gosling in 1995 at Sun Microsystems (later
acquired by Oracle).
2. It was initially called Oak. Later it was renamed to Green and was finally
renamed to Java inspired by Java coffee.
3. Java has close to 9 million developers worldwide.
4. About 3 billion mobile phones run Java, as well as 125 million TV sets and
every Blu-Ray player.
5. According to indeed.com, the average salary of a Java developer is just over
$100,000 per year in the US.

## DAY 2 JAVA Tutorial 
###### Variables
We use variables to temporarily store data in computer’s memory. In Java, the type
of a variable should be specified at the time of declaration.

//Naming: 
camelcase notation----camelNamingConvention
ex: int myAge = 30;

//Types:
• _Primitives🔲: for storing simple values like numbers, strings and booleans.
• _Reference Types🔲: for storing complex objects like email messages.


**Primitive Types**🔺
byte, short, int, long, float, double, char, boolean

//Declaring Variables🔺
1. byte age = 30;
2. long viewsCount = 3_123_456L;
3. float price = 10.99F;
4. char letter = ‘A’;
5. boolean isEligible = true;

• In Java, we terminate statements with a semicolon.
• We enclose single characters with single quotes and strings (series of characters) with
double quotes. ex:4
• The default integer type in Java is int. To represent a long value, we should add **L**
to it as a postfix. ex: 2
• The default floating-point type in Java is double. To represent a float, we should
append **F** to it as a postfix. ex:3
