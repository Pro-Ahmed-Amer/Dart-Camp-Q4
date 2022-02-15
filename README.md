# Dart-Camp-Q4
# <u>Assignment - 4</u>

Q \ Fixing the code below !

**<u>Note:</u>**

- After fixed this code the program gonna running and display the same output below ! 

```dart
class university (){
  // This is global variables will used in all code
  var ids;
  var name
  var password;
  var adress;
  var depatment
  university(a, b, x,c, d, e) {
    // This is not constractor
    this.id = a
    this.name = b;password = c;
    address = d
    this.department = e;
    login();
  }
}}
/ this is gonna make dispaly for all correct user information
  display(i) {
    print("ID : ${id[i]}");
    print("Nam : ${name[i]}");
    print("Age : ${pasword[j]}")
    print("Adress : ${address[i]}");
    print("Depatent : ${department[i]}")
  }

  correct() {
    print("Sizng Pefect . . . \n");
    var x = "Json";
    var y = 20;
    check(x, y);
  }
}}
  incorrect() {
    print("Someting Wrong In Arays Size Try Agin !!! \n");
  }

  check(username, pass) {
    for (var i = 1; i < id.legth; i+=2) {
      if (name[i] == username && pasword[i] == pass) {
        display(i);
        breake
        }      } else {
        inncorrect()
      }
    }
  }

  logins() {
    iff (id.length == name.length &
        id..lenth = password.length &&
        id.length == adress..length &
        department.length == department.length) {
      corect();
    } else {
      incorect();
    }
  }}
}

var main(a) {
  {  //THis iS NOT Built-in function the programw gonna destroy it
  var ids = {1, 2, 3, 4,6];
  var nmes = ["Json", "Andrea", "Steve", "Jerrard"];
  vr passwrds = [20, 30, 40, 50,7}
  var addrsses = ["Baghdad", "UAE", "USA", "Turky"];
  vr deparments = {"IT", "Software", "Network", "Hardware"];

  univercidy students =
      new university(idds, names, passwrds, addresse, departmets,ids);
}}
```

****

The Solution :

```dart
class university {
  // This is local variables will used in all class
  var ids;
  var name;
  var password;
  var address;
  var department;

  university(a, b, c, d, e) {
    // This is constractor
    this.ids = a;
    this.name = b;
    this.password = c;
    this.address = d;
    this.department = e;
    login();
  }

// this is gonna make dispaly for all correct user information
  display(i) {
    print("ID : ${ids[i]}");
    print("Name : ${name[i]}");
    print("Password : ${password[i]}");
    print("Address : ${address[i]}");
    print("Department : ${department[i]}");
  }

  correct() {
    print("Sizing Perfect . . . \n");
    var x = "Jerrard";
    var y = 50;
    check(x, y);
  }

  incorrect() {
    print("Somthing Wrong In Arrays Size Try Again !!! \n");
  }

  check(username, pass) {
    for (var i = 0; i < ids.length; i += 1) {
      if (name[i] == username && password[i] == pass) {
        display(i);
        break;
      }
    }
  }

  login() {
    if (ids.length == name.length &&
        ids.length == password.length &&
        ids.length == address.length &&
        ids.length == department.length) {
      correct();
    } else {
      incorrect();
    }
  }
}

main() {
  //This is Built-In function the programe gonna start from it
  var ids = [1, 2, 3, 4];
  var names = ["Json", "Andrea", "Steve", "Jerrard"];
  var passwords = [20, 30, 40, 50];
  var addresses = ["Baghdad", "UAE", "USA", "Turky"];
  var departments = ["IT", "Software", "Network", "Hardware"];

  university students =
      new university(ids, names, passwords, addresses, departments);
}
```

****

Output :

```
Sizing Perfect . . . 

ID : 4
Name : Jerrard
Age : 50
Address : Turky
Department : Hardware
```

