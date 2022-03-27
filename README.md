void main(){

  var name = 'Siti Nur Aisah Jamil';

  print(name);

  print(name);

  print(name);

  print(name);

  var firstName = 'Siti';
  final lastName = 'Aisah';

  firstName = 'Sity';

  print(firstName);
  print(lastName);

  final array1 = [1,2,3];
  const array2 = [1,2,3];

  print(array1);
  print(array2);

  late var value = getValue();
  print('Variable sudah dibuat');
  print(value);

}

String getValue(){
  print('getValue() dipanggil');
  return 'Siti Nur Aisah Jamil';
}
