### Dart Programming Language 

#### Hello World Code

```dart
// write a programme hello dart
void main (){
  print("Hello world");
  print("This is Tuhin Hossain");
}

```
Explain This code:

void - keyword, main -function

### Variable: 
Dart Variable - var, final, const 

 1 .variable declare and initialization before use (var)

  a = variable 
10 = data or value
```dart
void main(){
  // variable declare before use var
  var a=10; 
  var b =30;
  var c = a+b;
  print(c);
}
```
### Dart Data Type :
Dart Data Type- number, string, boolean, list, map 

### Dart Number Type 
1- integer , 2- double
```dart
void main(){
  var number = 100;
  var doubleNumber = 100.33;
  var totalNumber = number+doubleNumber;
  print(totalNumber);
}
/*
number =100 - this is integer number
doubleNumber = 100.33- this is double number
 */
```
### Dart String Type
```dart
void main(){
  var myName = "Tuhin";
  var nickName = "Mahafuj"; // string
  var sureName ='Mr Tuhin'; // string
  print(sureName);
  print(myName);
  print(nickName);

}
```

### Dart Boolean Type
```dart
void main(){
  var isBangladeshi = true; // boolean = bool
  var isNotBangladeshi = false; //boolean =bool
  bool name= true;
  print(name);
  print(isBangladeshi );
  print(isNotBangladeshi);
}
```
### Dart List
```dart
void main(){
  var city = ['Kushtia','Khulna','Varamara','Daulatpur'];
  print(city);
  print(city[3]); // access element from list
  // list item access -use index number
  // index number start 0 ,1,2,3,3 .....
  // dart list create and initializing square brackets -> []
  // every value separate use comma -> ,
}
```
### Dart Map
```dart
void main(){
  var student = {
    'name':'Tuhin',
    'age': 20,
    'school': "Pragpur High School",
  };
  // any key access
  print(student['name']);
  print(student);
}
/*
map - don't support index number
map = key : value --> key -> name , value -> Tuhin
key -> age, value -> 20
key - school , value -> Pragpur High School
 */
```