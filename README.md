# quiz_master

Quiz Master Project

## Getting Started

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(const MaterialApp(
    home: ToDoApp(),
  ));
}

class ToDoApp extends StatefulWidget {
  const ToDoApp({Key? key}) : super(key: key);

  @override
  State<ToDoApp> createState() => _ToDoAppState();
}

class _ToDoAppState extends State<ToDoApp> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Container(
        child: Text('Sangeee'),
      ),
    );
  }

}
```