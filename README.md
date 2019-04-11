# Case Study: Flutter
## Technology and Platform used for Development
### What coding languages are used? Do you think the same languages would be used if the project was started today? What languages would you use for the project if starting it today?

The code language used in flutter is dart. I believe the same language would be used even if the project started today because it is strongly typed, unlike JavaScript. It is a relatively high performance language and is very simple as well.

### What build system is used (e.g. Bazel, CMake, Meson)? What build tools / environment are needed to build (e.g. does it require Visual Studio or just GCC or ?)

It uses gradle as it's build tool

### What frameworks / libraries are used in the project? At least one of these projects don’t use any external libraries or explicit threading, yet is noted for being the fastest in its category--in that case, what intrinsic language techniques is it using to get this speed.

Dart platform
Flutter engine
Foundation library
Design-specific widgets

## Testing: describe unit/integration/module tests and the test framework
### How are they ensuring the testing is meaningful? Do they have code coverage metrics for example?
They use coveralls
### What CI platform(s) are they using (e.g. Travis-CI, AppVeyor)?
They use Cirrus CI
### What computing platform combinations are tested on their CI? E.g. Windows 10, Cygwin, Linux, Mac, GCC, Clang
Windows, Linux and Mac
## Software architecture in your own words, including:
### How would you add / edit functionality if you wanted to? How would one use this project from external projects, or is it only usable as a standalone program?
In order to add functionality, you would need to first set up the flutter environment on your system following the instructions given on: https://flutter.dev/docs/get-started/install

After setting this up, you would fork the flutter github repo into your own local repo and then make changes that you think are necessary. You should follow the coding style guidelines put in place by google and test it.
### What parts of the software are asynchronous (if any)?
I did not really find any information on this
### Please make diagrams as appropriate for your explanation

### How are separation of concerns and information hiding handled?

### What architectural patterns are used

### Does the project lean more towards object oriented or functional components
It seems to be leaning towards being object oriented
## Analyze two defects in the project--e.g. open GitHub issue, support request tickets or feature request for the project
1. The first issue is that comparing a Flutter app with an iOS system app, the haptic feedback is inconsistent for switch widgets.
   issue #30510
2. The second issue is the camera plugin for flutter is not very high quality
   issue #30872
### Does the issue require an architecture change, or is it just adding a new function or?
Both of these issues should be fixed with a new function or slight tweaking of current architectural blocks, but no change to the actual architecture should have to be made.
### make a patch / pull request for the project to fix problem / add feature

## Demonstration Application of the system
For my demo I created a basic app using flutter that also incorporates a simple authentication (the authentication may or may not actually work, tbd)
