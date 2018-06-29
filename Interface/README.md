# Interface
A class's interface is the **collection of methods and field that a class permits object of other classes to access**.
</br>(This interface usually represents a commitment that the methods will perform the operation implied by their names and as specified by code comments and other documentation.)
</br> A class's implementation is the code that lies within its methods.
</br>
Interface looks like a class but it is not a class. An interface can have methods and variables just like the class but the methods declared in interface are by default abstract (only method signature, no body, see: Java abstract method). Also, the variables declared in an interface are public, static & final by default. 
</br>
Java elevates the notion of interface to be a separate construct, expressly separating interface—what an object must do—from implementation—how an object fulfills this commitment
</br>
Java interfaces allow several classes to provide the same functionality, and they open the possibility that a class can implement more than one interface.

### Example
Your design intent will sometimes go beyond the simple definition of an interface.
For example, you might use an interface to adapt a class's interface to meet a client's needs, applying the ADAPTER pattern. You might also create an interface to a collection of classes, applying the FACADE pattern.
</br>
You might also create an interface to a collection of classes, applying the FACADE pattern. In this case, you create a new interface by creating a new class rather than a new interface.
