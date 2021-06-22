# dotnet_2
LEARN second exercise 
Below is a code snippet that requires the FluentAssertions library. Create a new project and add the FluentAssertions library to that project along with a reference to the FluentAssertions namespace in your class file to make this work!

public class exampleClass {
    public void additionMethod() {
        var first = 3;
        var second = 7;
        var result = first + second;

        result.Should().Be(10);
    }
}

After adding the code above to your project and the appropriate references to FluentAssertions in your class file, execute the dotnet build command to validate that the project builds. It should look similar to the screen shot below.

Once your application compiles add it to a public GitHub repository and paste the link below.
