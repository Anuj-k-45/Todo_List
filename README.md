# todo_list

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

After getting to know about the Widget tree and the element tree, we know that elements are being created in refrence to each and every widget and when the position of these widgets swap, the refrence(elements does change) and no longer is the same for the same widget, to lock this thing and keep the refrence of an element to a specific widget only even if the position of a widget changes we use "keys".