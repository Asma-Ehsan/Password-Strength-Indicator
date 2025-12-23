✅ What is ::placeholder?

It is a selector that targets only the placeholder text inside an <input> or <textarea>.

Example:

<input type="text" placeholder="Enter your name">


The words “Enter your name” are the placeholder, not the actual input value.

✅ Why do we use it?

Because placeholder text has its own default style (usually light gray).
If you want to change how it looks, you need a special selector.

For example:

::placeholder {
    font-size: 15px;
    color: #ccc;
}


This changes:

the size of the placeholder text

the color

the font

the opacity, etc.

Regular CSS rules (like input {}) do not affect placeholder text.
That’s why ::placeholder exists.