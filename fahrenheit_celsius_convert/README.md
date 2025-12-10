# Fahrenheit <--> Celcius Calculator

**Source file:** 'conv_f_to_c.cpp'
**Language:** C++

## Purpose

Write a c++ program that:

1. Asks if you would like to convert fahrenheit to celsius or vice versa
2. Depending on choice, use formulas to convert value to desired units
$$ T_c = (T_f - 32.0) \frac{5.0}{9.0}$$
$$ T_f = \frac{9.0T_c}{5.0} + 32.0 $$

## How to compile

```bash
g++ -o conv_f_to_c conv_f_to_c.cpp
./conv_f_to_c