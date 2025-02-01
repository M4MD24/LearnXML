# XML Concepts

## Introduction
XML (Extensible Markup Language) is a flexible and structured markup language used to store and transport data. It is widely used in web services, configuration files, and data exchange between different systems.

## Key XML Concepts

### 10. XML DTD (Document Type Definition)
Defines the structure and rules for an XML document.
```xml
<!DOCTYPE note [
    <!ELEMENT note (to, from, heading, body)>
    <!ELEMENT to (#PCDATA)>
    <!ELEMENT from (#PCDATA)>
    <!ELEMENT heading (#PCDATA)>
    <!ELEMENT body (#PCDATA)>
]>
```

### 11. Parsing XML
XML can be parsed using various technologies like:
- **DOM (Document Object Model)**
- **SAX (Simple API for XML)**
- **StAX (Streaming API for XML)**
- **XPath (Querying XML Data)**
- **XSLT (Transforming XML)**

### 12. Example XML Document
```xml
<?xml version="1.0" encoding="UTF-8"?>
<library>
    <book id="101">
        <title>XML Basics</title>
        <author>John Doe</author>
    </book>
    <book id="102">
        <title>Advanced XML</title>
        <author>Jane Smith</author>
    </book>
</library>
```

## Conclusion
XML is a powerful and flexible format used in various applications for data representation and exchange. Understanding these key concepts will help in working efficiently with XML.

