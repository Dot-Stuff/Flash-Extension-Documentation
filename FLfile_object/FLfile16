## FLfile.readBinary()

#### Availability

???

#### Usage

*FLfile.readBinary(fileURI)*

#### Parameters

**fileURI** A string, expressed as a file:/// URI, specifying the binary-based file (such as .png, .txt, or .jpeg) that you want to read.

#### Returns

The contents of the specified file as a string wrapped in Base32, or null if the read fails.

#### Description

Method; returns the contents of the specified file as a string wrapped in Base32, or null if the read fails.

#### Examples

```javascript
The following example reads the file mydata.txt and, if successful, displays an alert box with the contents of the file.

var fileURI = "file:///c|/temp/mydata.txt"; var str = FLfile.readBinary( fileURI);
if (str) {
    alert( fileURL + " contains in Base32: " + str);
}

The following example reads the ActionScript code from a class file and stores it in the code variable:

var classFileURI = "file:///C|/MyApplication/Dog.jpeg"; 
var code = FLfile.readBinary(classFileURI);

```
