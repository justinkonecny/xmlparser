# XML File Parser
Parses an XML file and outputs the results in a readable format.

## Usage
* <code>xmlparser <xml input file> [xml input files...] [options]</code>
    * <code>-v, --values</code>:        print attribute values only
    * <code>-n, --names</code>:         print host names only
    * <code>-p, --print</code>:         print without writing to CSV file
    * <code>-o=<file name></code>:      specifies output csv file name
    * <code>-{format}</code>:           %h for host name, %p for port, e.g. '-%h:%p'
    * <code>-h, --help</code>:          print usage information
