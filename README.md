# TensorflowLiteForXamarin
A Xamarin bindings library for TensorflowLite 1.14.1

# Instructions

Download the solution and open the solution in Visual Studio. The recommended version of Visual Studio is Visual Studio 2019 but 2017 should work fine as well although it 
hasn't been tested.

Build the project. The Project will create an assembly file (the file with extension with extension .dll) in the debug folder inside the bin folder of the solution. In the 
project where you want to use tensorflow, add a reference to this file. Note that this binding is for the Android project. 

Add a using statement as Org.Tensorflow.Lite and you should now have access to the tensorflow lite 1.14.1 library in Xamarin Android!
