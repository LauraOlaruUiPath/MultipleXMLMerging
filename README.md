With this package you can automatically merge multiple XML files into one.

It uses a given Source XML File Path and a given Destination XML File Path in order to merge the two of them into the overridden Destination XML File.


General parameters

Input:

SourceXMLFilePath: String containing the XML file path that needs to be merged into destination.

Input/Output:

DestinationXMLFilePath: String containing the XML file path that is resulted from the merging between the source XML file and the destination XML file - provide a variable for Destination in order to make it work (you can use an Assign activity for defining the destination variable which contains the destination XML file path).

Important Notes: 

Both files SourceXMLFilePath and DestinationXMLFilePath need to have the same XML format (the same structure of nodes in order to be correctly merged).

This method overrides the Destination file with the newly created merged file and puts the merged result in a root node.

Empty strings are not allowed.