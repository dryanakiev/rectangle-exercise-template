# rectangle-exercise

You have been tasked with implementing a Rectangle class that represents a rectangle. The Rectangle class should have a Width property (a double) and a Height property (a double). The Rectangle class should also have a method called Area that returns the area of the rectangle.

Your task is to write unit tests for the Rectangle class. Your tests should cover a range of scenarios, including:

1. Testing for correct behavior of the Area method.
2. Testing for correct handling of null input values for the Width and Height properties.
3. Testing for correct handling of negative input values for the Width and Height properties.
4. Testing for correct handling of edge cases, such as a rectangle with zero width or height.
5. Testing for correct handling of rectangles with non-double values for the Width and Height properties, such as a rectangle with a width of 3.5 and a height of 2.

Here's a sample code structure to get you started:

```
[TestFixture]
public class RectangleTests {
    [Test]
    public void TestArea() {
        // TODO: Write test for Area method
    }

    [Test]
    public void TestWidthNullInput() {
        // TODO: Write test for null input value for Width property
    }

    [Test]
    public void TestHeightNullInput() {
        // TODO: Write test for null input value for Height property
    }

    [Test]
    public void TestWidthNegativeInput() {
        // TODO: Write test for negative input value for Width property
    }

    [Test]
    public void TestHeightNegativeInput() {
        // TODO: Write test for negative input value for Height property
    }

    [Test]
    public void TestEdgeCases() {
        // TODO: Write test for edge cases
    }

    [Test]
    public void TestNonDoubleValues() {
        // TODO: Write test for non-double value for Width and Height properties
    }

    // TODO: Write additional tests as necessary
}
```
Your task is to complete the TODO comments with the appropriate code to write the unit tests to verify the correctness of the Rectangle class. Good luck!
