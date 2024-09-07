# TastyBook_Flutter

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


Container
    decoration
    Decoration
    BoxDecoration
        gradient
            Gradient
            LinearGradient
            color: List<Color>
            begin: Alignment
            end: Alignment
            

Homework:

1. Style the hello world Text() widget
   1. Change the text color to "white"
   2. Change the text font size to 28
2. Using BoxDecoration and LinearGradient to change background color:
   1. Change the background color to array : [Color.fromARGB(255, 26, 2, 80), Color.fromARGB(255, 45, 7, 98)]
3. create a class to extract HelloWorld Widget.


```dart
class GradientContainer extends StatelessWidget {
  
  const GradientContainer({super.key});

  @override
  Widget build(context) {
    return ; // render Widget.
  }
}
```

## Useful Link
To understand [What is the difference between Scaffold and Container in Flutter?](https://stackoverflow.com/questions/59242815/what-is-the-difference-between-scaffold-and-container-in-flutter)
