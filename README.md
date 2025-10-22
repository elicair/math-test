# math-test
<label for="userName">Name:</label>
<input type="text" id="userName" name="userName" placeholder="Enter your name" required>
Explanation of the attributes:
<label for="userName">Name:</label>: This creates a label associated with the input field. The for attribute of the <label> should match the id attribute of the <input> for accessibility purposes, allowing screen readers to correctly associate the label with its input.
<input type="text">: This is the core element for creating a single-line text input field.
id="userName": This provides a unique identifier for the input field, useful for linking with labels and for JavaScript manipulation.
name="userName": This attribute is used to identify the input field when the form data is submitted to a server.
placeholder="Enter your name": This provides a hint to the user about what kind of input is expected in the field. This text disappears when the user starts typing.
required: This attribute makes the field mandatory, meaning the user must fill it out before submitting the form.
