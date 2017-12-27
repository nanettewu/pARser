# parsAR

XML parser for mobile augmented reality library.

This project serves as a file-loading extension to an existing cloud-computing augmented reality library. 
By utilizing the Persister class parser from the Simple framework, this Android application acts as a scene loader 
that deserializes information describing virtual objects from an XML file, which contains descriptive attributes 
such as positioning and lighting. These objects can either be primitives, as defined by the Rajawali package, 
or user-defined models (.obj or .mtl). After processing the inputted information, objects generated on a mobile 
augmented reality (MAR) interface are superimposed on a camera preview layer. Ultimately, the library extension can 
simplify and expedite the process of creating MAR applications and displays.

Key Words: augmented reality, file parser, mobile device, Android.
