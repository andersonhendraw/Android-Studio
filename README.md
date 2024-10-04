# Android-Studio
Tugas Mobile Programming

main.dart

import 'package:flutter/material.dart';
import 'package:andersonapps/home.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      theme: ThemeData(
        useMaterial3: false,
      ),
      home: const Scaffold(),
    );
  }
}


home.dart

import 'package:flutter/material.dart';

class HelloWorld extends StatelessWidget{
  const HelloWorld({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: const Text('Belajar Flutter'),
      ),

      body: const Center(
        child: Text('Hello World'),
      ),
    );
  }
}
