
***

![/QSharp_1.png](/QSharp_1.png)

### Learning QSharp

I am not too experienced with the Q# programming language at the moment. This document will go over my knowledge of the Q# language so far.

This document used version ? of the Q# programming language. The version will be listed with each example.

#### Comments in QSharp

Comments in Q# are similar to languages lika C, C++, C#, Java, JavaScript, Google Go, etc.,

```qsharp
// This is a single line comment
/* This is
a multi-line
comment */
```

This example works with every version of Q#

#### Break keyword in QSharp

Q# does NOT support the `break` keyword.

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

#### Hello World in QSharp

A hello world program in Q# is 

```qsharp
namespace Quantum.HelloWorld
{  
    // Import Quantum.Primitive  
    open Microsoft.Quantum.Primitive;  
      
    // Create an operation that adds two int and returns a total int  
    operation Add (a : Int, b : Int): (Int)  
    {  
        body  
        {  
            return (a + b);  
        }         
    }  
}
```

This example is currently a little too complicated for me to figure out without testing, so it was taken from [c-sharpcorner.com](https://www.c-sharpcorner.com/article/getting-started-with-q-programming/)

This example works with every version of Q#

_/!\ This example has not been tested yet, and may not work_

#### Source

The majority of my Q# knowledge comes from self-experimentation, and Wikipedia. Self experimentation didn't go far, and I can't test the language without a Q# compiler. I don't even know how to write a Hello World program here, I took it from:

[https://www.c-sharpcorner.com/article/getting-started-with-q-programming/](https://www.c-sharpcorner.com/article/getting-started-with-q-programming/)

#### Other knowledge of QSharp

1. Q# is a curly bracket and semicolon language

2. Q# has a syntax similar to C#

3. Q# uses the `*.qs` file extension

4. Q# is a quantum computer programming language

5. Q# is a programming language by Microsoft

6. Q# is a language recognized by GitHub

7. I am not sure whether Q# is an open source programming language or not.

8. No other knowledge of QSharp at the moment.

***

**File version:** `1 (2022, Tuesday, April 19th at 3:42 pm PST)`

***
