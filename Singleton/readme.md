A singleton is a class designed to only ever have one instance
Eg:- Access to File System, Access to a shared network resource

Singleton features
1. At any time, only 0 or 1 instance of the Singleton class exists in the application
2. Singleton classes are created without parametes
3. Assume lazy instantiation as the default ( meaning initialize the class only when someone request them(performace reason)) Alternatively
   we can initialze the class during the start of the program and use the instance till end of the program

4. A single, private parameterless constructor , so sub classing is not allow, so we can mark the singleton class "sealed"
5.  "private static" field holds the The only reference to the instance
6. rest of the application references the class through A public static method the class exposes for this purpose
