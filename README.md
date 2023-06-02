## Java
In order to be able to `compile and run` Java code in your computer, you must install the Java JDK<br />
JDK stands for "<b>Java Development Kit</b>"<br />
<br/>
Once you have JDK installed on your computer you can navigate to the folder<br/>
where all the executable files are located<br/>
<br/>
<b>Java's Bin folder location</b>
![java-bin-folder](https://github.com/danielurra/java/assets/51704179/4f3bdd3e-75f1-45d1-9259-722647880bb3)</br>
<br/>
The first thing you'll have to do is to add the Java's bin folder path inside the system's PATH<br/>
<br/>
PATH is an "<b>environment variable</b>" that tells the OS where to find executable files<br/>
<br/>
You must use the "<b>set path</b>" CLI command as shown below:<br/>
```
set path=%path%;C:\Program Files\Java\jdk-19\bin
```
![set-path](https://github.com/danielurra/java/assets/51704179/d1f00084-d495-4ed8-a6a6-799b2ea30620)<br/>
You can echo the variable to see if the new entry is there now
```
echo %PATH%
```
![echo path](https://github.com/danielurra/java/assets/51704179/2c7e7a29-2d8d-43bc-abe2-35d072ac6b17)
<br/>
## Java Hello World!
As you can see, even the simple and classic "<b>Hello World</b>" code looks as a little bit</br>
complicated in Java</br>
<img src="images/java-hello-world.png" alt="" width=""><br />

## Compile then run
We are going to use 2(two) executable files, <b>"javac.exe"</b> when compiling and <b>"java.exe"</b> when running<br/>
<b>java.exe</b> will invoke the java Virtual Machine in the background, totally transparent for us<br/>
<br/>
<b>Before Compilation</b><br />
<img src="images/compilation-01-before.png" alt="" width=""><br />
## Compiling with javac<br />
<img src="images/compiling_with_javac.png" alt="" width="351px"><br />
<br/>
<b>After Compilation</b><br/>
Immediately after the compilation is done, you'll see that another file was created<br />
that file with extension <b>".class"</b> is what in Java is known as <b>"bytecode"</b><br />
<img src="images/compilation-02-after-v3.png" alt="" width=""><br />
## Running java code<br />
<img src="images/running_with_java.png" alt="" width=""><br />
## JShell
Those of you who are new to Java programming, could take advantage of "JShell" which is often helpful for trying out the code snippets.
JDK 9 and above include this tool that lets you execute a snippet of Java code instead of writing a full Java program.
This is very helpful for beginners.
## Java version
```bash
java --version
```
![jshell-00](https://github.com/danielurra/java/assets/51704179/d18fbe3a-35ac-4088-a9c7-fca64626d53d)
## Launch JShell
```bash
jshell
```
![jshell-01](https://github.com/danielurra/java/assets/51704179/45345190-7348-4e1d-8361-ad5883d8442f)
## Eexecute your first Java snippet of code
```bash
System.out.println("Hello JDK 19!")
```
![jshell-02](https://github.com/danielurra/java/assets/51704179/39fbe7de-e7a1-46c3-b2bc-63f6941b2d1c)
## Exit JShell
```bash
/exit
```
![jshell-03](https://github.com/danielurra/java/assets/51704179/0370a258-e7b6-4354-9803-76bab3890759)
## Eclipse IDE
![Eclipse-Luna-Logo](https://github.com/danielurra/java/assets/51704179/e4b37f7e-005f-477b-a13f-049895bcc9fe)<br/>
A Package declaration is something needed when running the java Hello World code using Eclipe IDE
![eclipse-ide-hello-world](https://github.com/danielurra/java/assets/51704179/ffc979c5-0060-4ead-80ff-90eb5f0bd7b9)<br/>
## Declare a Variable as Integer and set a value
``` java
package package01;

public class HelloWorld {

	public static void main(String[] args) {
//		Declare and set in one line 
		Integer myfirstvar = 77;
//		 Print the value concatenated (plus sign +) with some random text for better understanding
		System.out.println("My first variable has a value of: " + myfirstvar);
	}
}
```
## See the console

![declare-and-set-in-one-line](https://github.com/danielurra/java/assets/51704179/0cbb9d8b-95d9-4562-85f3-5e9f746004c2)


