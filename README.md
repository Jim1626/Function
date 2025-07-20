import 'dart:io';

double calculateArea(double length, double width) {
  double area = length * width;
  print('Full area: $area');
  return area;
}

void main() {
  print('Now we calculate the area');

  
  double length1 = 3.2267;
  double width1 = 7.89;
  double area1 = length1 * width1;
  print('Area 1: $area1');

  double length2 = 16.456;
  double width2 = 12.77;
  double area2 = length2 * width2;
  print('Area 2: $area2');

  print('Area-1 calculation with function: ${calculateArea(5.98, 32.33)}');
  print('Area-2 calculation with function: ${calculateArea(10.00, 32.93)}');
  print('Area-3 calculation with function: ${calculateArea(75.98, 42.93)}');
}
