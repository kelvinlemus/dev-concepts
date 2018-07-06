# Parse vs Serialize

**Parse**  
- Parsing is, generally speaking, the processing of an input stream into meaningful data structures; in the XML context, parsing is the process of reading a sequence of characters conforming to the grammar and other constraints of the XML spec into whatever internal representation of XML your program uses.

**Serialize**  
- Serialization is the opposite process: processing the internal data structures of a program (in this context, your internal representation of an XML document) and creating a character sequence (typically written to an output stream) that conforms to the angle-bracket syntax of the spec.

> Use a parser to read XML from a character stream into data structures; use a serializer to write data structures out into a character stream.

### Links
- https://stackoverflow.com/questions/11965419/xml-serialization-vs-xml-parsing
