int main(){
  int a=5;
  print(a);

  String myName='bobby';
  double age=21;
  print(age);
  print(myName);
  //decision making statements

  if(age<17){
    print('bobby');
  }
  else{
    print('syam');
  }
  //for loop
  for(int i=0;i<5;i++){
    print('hello${i+1}');
  }
  var ages=[12,23,32];
  for(int i in ages){
    print(i);
  }
  /*Make format comments: It is a single line comment (//)
Block Comments: It is a multi-line comment (/*...*/)
Doc Comments: It is a document comment that used for member and types (///)*/

final b=10;

const d=100;
var c=b+1;
print(c);
print(d);

//records
var record=('first',a:2,b:true,'last');
print(record);

/*sets
Sets
A set in Dart is an unordered collection of unique items. Dart support for sets is provided by set literals and the Set type.

Here is a simple Dart set, created using a set literal:

var halogens = {'fluorine', 'chlorine', 'bromine', 'iodine', 'astatine'};
*/
var list=[1,2,3,4,2,3,2];
var setoflist={list,list};
print(setoflist);

//creating an empty set
var setof =<String>{};
setof.add('bobby');
setof.add('vinnu');
print(setof);


//functions in dart
//The => expr syntax is a shorthand for { return expr; }. The => notation is sometimes referred to as arrow syntax.


  return 0;
}
