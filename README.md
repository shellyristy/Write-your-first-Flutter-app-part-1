# **Tugas Pertemuan 20**
## **Project startup_namer**

### Praktikum 1 : Create the starter Flutter app
![Screenshot hello_world](images/01.png)

### Praktikum 2 : Use an external package
* tambahkan english_words package pada pubspec.yml
![Screenshot hello_world](images/02.png)

* import package baru pada main.dart
![Screenshot hello_world](images/03.png)

### Praktikum 3 : Add a stateful widget
* Tambah stateful widget RandomWords dengan membuat state class _RandomWordState
![Screenshot hello_world](images/04.png)

* Update the build() method in _RandomWordsState
![Screenshot hello_world](images/05.png)

* Remove the word-generation code from MyApp
![Screenshot hello_world](images/06.png)
![Screenshot hello_world](images/07.png)

### Praktikum 4 : Create an infinite scrolling ListView
* Add some state variables to the _RandomWordsState class.
![Screenshot hello_world](images/08.png)

* Update the build method for _RandomWordsState. Change it to use _buildSuggestions(), rather than directly calling the word-generation library.
![Screenshot hello_world](images/09.png)

* Update the build method for MyApp, changing the title in two places.
![Screenshot hello_world](images/10.png)
![Screenshot hello_world](images/07.png)