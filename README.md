# Dart
Flutter
void main() {
  for(var i=4;i>=0;i--){
     print('hello $i');
   }
 }
// void main() {
  //for(var i=4;i>=0;i--){
    // print('hello $i');
   //}
 //}
// void main()  
// {  
//     var name = "Khushi";  
//     var roll_no = 99;  
//     print("My name is ${name} My roll number is ${roll_no}");  
// } 
// void main(){  
//     var heart_symbol = '\u2665';  
//     var laugh_symbol = '\u{1f600}';  
//     print(heart_symbol);  
//     print(laugh_symbol);  
// }  
// void main(){  
//   print("Example of Assignment operators");  
//   var n1 = 10;  
//   var n2 = 5;  
    
//   print("n1+n2 = ${n1+n2}");  
//   print("n1-n2 = ${n1-n2}");  
//   print("n1*n2 = ${n1*n2}");  
//   print("n1/=n2 = ${n1/n2}");   
//   print("n1%n2 = ${n1%n2}");     
// }  
// void main() {   
//    var x = 30;   
//    print(x++);                  //The postfix value  
     
// var y = 25;  
// print(++y);                 //The prefix value,  
         
// var z = 10;  
// print(--z);                  //The prefix value  
  
// var u = 12;                                           
//    print(u--);    }  //The postfix value 
//  void main(){  
//   print("Example of Assignment operators");  
    
//    var n1 = 10;  
//    var n2 = 5;  
    
//    n1+=n2;  
//    print("n1+=n2 = ${n1}");  
    
//    n1-=n2;  
//    print("n1-=n2 = ${n1}");  
    
//    n1*=n2;  
//    print("n1*=n2 = ${n1}");  
    
//    n1~/=n2;  
//    print("n1~/=n2 = ${n1}");  
//    n1%=n2;  
//    print("n1%=n2 = ${n1}");    
//  }  
// void main() {   
// var a = 30;  
// var b = 20;  
  
// print("The example of Relational Operator");  
  
// var res = a>b;  
// print("a is greater than b: "+res. toString());  // We will learn the toString in next tutorial  
  
// var res0 = a<b;  
// print("a is less than b: "+res0. toString());  
//   
// var res1 = a>=b;  
// print("a is greater than or equal to b: "+res1. toString());  
  
// var res2 = a<=b;  
// print("a is less than and equal to b: "+res2. toString());  
  
// var res3 = a!= b;  
// print("a is not equal to  b: "+res3. toString());  
  
// var res4 = a==b;  
// print("a is  equal to  b: "+res4. toString());  
// }  
// void main()  
// {  
//   var num = 10;  
//   var name = "JavaTpoint";  
//   print(num is int);    
//   print(name is! String );  
// } 
// void main(){  
//   bool bool_val1 = true, bool_val2 = false;   
//   print("Example of the logical operators");  
    
//   var val1 = bool_val1 && bool_val2;  
//   print(val1);  
    
//   var val2 = bool_val1 || bool_val2;  
//   print(val2);  
    
//   var val3 = !(bool_val1 || bool_val2);  
//   print(val3);   
// } 
// void main(){  
//    print("Example of Bitwise operators");  
    
//    var a  = 55;  //Convert it binary no
//    var b = 127;  //convert binary no
//    var c = 0;  
    
//    // Bitwise AND Operator  
//    print("a & b = ${a&b}");  //do binary no and operation and 
    
//    // Bitwise OR Operator  
//   print("a | b = ${a|b}");  
    
// //   // Bitwise XOR  
//   print("a ^ b = ${a^b}");  
    
// //   // Complement Operator  
//    print("~a = ${(~a)}");  
    
// //   // Binary left shift Operator  
//    c = a <<2;  
//    print("c<<1= ${c}");  
    
// //   // Binary right shift Operator  
//    c = a >>2;  
//    print("c>>1= ${c}");  
// }  
// void main() {   
//    var x = null;   
//    var y = 20;   
//    var val = x ?? y;   
//    print(val);   
// }  
// void main() {   
//    var a = 30;   
//    var output = a > 42 ? "value greater than 10":"value lesser than equal to 30";   
//    print(output);   
// }  
// void main () {  //Using final keyword
//   final a = 10;  
//   final b = 20;  
    
//  print(a);  
//  print(b);  
// }  
// void main() {  //Using const keyword
//    const name= "sanvi";  
//    print(name);  
// } 
// 
// void main(){  
// var a = num.parse("20.56");  //no will not change whole no will be taken
// var b = num.parse("15.63");  
  
// var c = a+b;   
// print("The sum is = ${c}");  
// }  
//  void main() {   // string
//    String str1 = 'this is an example of a single-line string';   
//    String str2 = "this is an example of a double-quotes multiline line string";   
//    String str3 = """this is a multiline line   
// string using the triple-quotes""";   
  
//    var  a = 10;  
//    var b = 20;  
   
//    print(str1);  
//    print(str2);   
//    print(str3);   
  
//  // We can add expression using the ${expression}.  
//    print("The sum is  = ${a+b}");  
// }  
// void main() {   
//    String str1 = 'Welcome To ';   
//    String str2 = "Wonderland";   
//    String str3 = str1+str2;  
  
//    print(str3);   
// }  

// void main() {   // whole done in string
//    String str1 = 'GIET ';   
//    String str2 = "University";   
//    String str3 = str1+str2;  
     
//  print(str3);   
  
//    var x = 10;  
//    var y = 100;  
  
//    print("The result is  = ${x%y}");  
  
//    var name = "Jyoti Kumari";  
//    var roll_nu = 100; 
//   var marks="A++";
     
//    print("My name is ${name}, my roll number is ${roll_nu} ,my overall grade is ${marks}");  
// }  
//Note:
// toLowerCase()
// It converts all characters of the given string in lowercase.
// toUpperCase()
// It converts all characters of the given string in uppercase.
// trim()
// It eliminates all whitespace from the given string.
// compareTo()
// It compares one string from another.
// replaceAll()
// It replaces all substring that matches the specified pattern with a given string.
// split()
// It splits the string at matches of the specified delimiter and returns the list of the substring.
// substring()
// It returns the substring from start index, inclusive to end index.
// toString()
// It returns the string representation of the given object.
// codeUnitAt()
// It returns the 16-bits code unit at the given index.
