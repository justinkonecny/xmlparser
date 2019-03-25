# XML File Parser
Parses an XML file and outputs the results in a readable format.

## Usage
* <code>xmlparser <xml input file> [xml input files...] [options]</code>
    * <code>-v</code>, <code>--values</code>:        print attribute values only
    * <code>-n</code>, <code>--names</code>:         print host names only
    * <code>-p</code>, <code>--print</code>:         print without writing to CSV file
    * <code>-o=<file name></code>:      specifies output csv file name
    * <code>-{format}</code>:           %h for host name, %p for port, e.g. '-%h:%p'
    * <code>-h</code>, <code>--help</code>:          print usage information
