import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: MyHomePage(),
    );
  }
}

class MyHomePage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        actions: [
          const ElevatedButton(onPressed: null, child: Icon(Icons.people)),
          const ElevatedButton(onPressed: null, child: Icon(Icons.bus_alert)),
        ],
        title: const Text("Burası AppBar'dır."),
        leading: const Icon(Icons.list),
        backgroundColor: Color(0xff108914),
        foregroundColor: Colors.white,
      ),
      body: const Center(
        child: Column(children: [
          Text("Bedirhan"),
          Text("İsmail"),
        ]),
      ),
      floatingActionButton: FloatingActionButton(
        onPressed: () {},
        child: const Icon(Icons.add),
      ),
    );
  }
}
