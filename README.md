# Simple-Problem-Solving-Using-Dart
<b>Problem:</b>
<br>
Declare two constant variables "a" and "b" with any integer values of your choice.
Perform addition, subtraction, multiplication, division, and modulus directly on "a"
and "b".
Print the results of each operation to the console using appropriate messages.


Sample Output
<br>
a = 7, b = 3
<br>
Addition: 7 + 3 = 10
<br>
Subtraction: 7 - 3 = 4
<br>
Multiplication: 7 * 3 = 21
<br>
Division: 7 / 3 = 2.3333333333333335
<br>
Modulus: 7 % 3 = 1

<b>Solution:</b>
<br>
void main() {
    <br>
  const int a = 7;
   <br>
  const int b = 3;
 <br>
  // Addition
   <br>
  int addition = a + b;
   <br>
  print("Addition: $a + $b = $addition");
 <br>
  // Subtraction
   <br>
  int subtraction = a - b;
   <br>
  print("Subtraction: $a - $b = $subtraction");
 <br>
  // Multiplication
   <br>
  int multiplication = a * b;
   <br>
  print("Multiplication: $a * $b = $multiplication");
 <br>
  // Division
   <br>
  double division = a / b;
   <br>
  print("Division: $a / $b = $division");
 <br>
  // Modulus
   <br>
  int modulus = a % b;
   <br>
  print("Modulus: $a % $b = $modulus");
   <br>
}