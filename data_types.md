### Data types
Data types indicates which type of value can be stored in variable

In java there are two types of data types
  - Primitive data types
  - Non-Primitive data types

#### Primitive data types
Primitive data types are the most basic data types available in java language
There are total 8 types
  - byte
  - char
  - boolean
  - short
  - int
  - long
  - float
  - double

Following table describes primitive data types charactristics

Data Type | Size | Range | Default Value
--------- | ---- | ----- | -------------
byte | 1 byte | -128 to 127 | 0
char | 2 bytes | 0 to 65,535 |  '\u0000'
boolean | 1 bit | 0 to 1 | false
short | 2 bytes | 32,678 to 32,677 | 0
int | 4 bytes | -2<sup>32</sup> to 2<sup>32</sup> - 1 | 0
long | 8 bytes | -2<sup>63</sup> to 2<sup>63</sup> - 1 | 0
float | 4 bytes | | 0.0
double | 8 bytes | | 0.0

1. #### `boolean` data type:
   - The boolean data type has only two possible values, `true` and `false`
   - Use this type for simple flags, that track true/false condition
   - Example code:
     ```java
     boolean isCompleted = false;
     ```
