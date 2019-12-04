# Usage guide

    XML_tool.py [-a | -d | -r | -f]

Read from console and write into an XML file

Arguments:

    -a, --add

Add message to XML

    -d, --delete

Delete message from XML

    -r, --read

Read messages from XML

    -f, --find

Find message in XML

***
**N.B.**

The 'add' mode requires formatted( and optionally minified) XML for creation of new file as well as addition to existing file.

**Example**:
With reference to 'sample.xml', one can enter the following to find and add to its parents automatically

    <id>007</id>

The 'delete' and 'find' modes use filter of the form 'element = value' or 'element' or 'value'

**Example**: 
With reference to 'sample.xml', one can enter any of the following as filters

    safetyrating = 4
          
    id
    
    1337
