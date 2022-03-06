# dart-code-for-AND-logic-gate
Here is my simple program for AND logic gate in dart language

import 'dart:io';
main()
{
  int A, B;
  print('enter the value of A');
  A = int.parse(stdin.readLineSync()!);
  print('enter the value of B');
  B = int.parse(stdin.readLineSync()!);
   print('A | B | AB');
  if(A == 0 && B == 0)
  {print('0 | 0 | ${A*B}');}
  else if(A == 1 && B == 0)
  {print('1 | 0 | ${A*B}');}
  else if(A == 1 && B == 1)
  {print('1 | 1 | ${A*B}');}
  else if(A == 0 && B == 1)
  {print('0 | 1 | ${A*B}');}
}
