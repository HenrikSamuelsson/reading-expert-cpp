# Reading Expert C++

Content related to reading the book Expert C++, written by Vardan Grigoryan and Shunhugang Wu, released by Packt in April 2020.

## Resources

Source files for the code in the book can be found at the official [Github repro](https://github.com/PacktPublishing/Expert-CPP).

## Questions and Answers

Questions are from the book and the answers are my own, feel free to suggest changes to the answers should I have misunderstood anything.

### Low-Level Programming with C++

Question 1

How many parameters does the `main()` function have?

Answer 1

The main function shall have either zero or two parameters.

A main function with zero parameters:

```cpp
int main()
{
    // Code intentionally omitted.
}
```

A main function with two parameters and the conventionally used parameter naming:

```cpp
int main(int argc, char *argv[])
{
    // Code intentionally omitted.
}
```

Note that non-standard C++ implementations can support a `main()` function with other form of parameters, such as a third parameter `char*[]` pointing at an array of pointers to the execution environment variables.
