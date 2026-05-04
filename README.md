# raid-skos
Set of SKOS files that can be aggregated to form the full RAiD vocabulary.

Use `aggregate_turtle.py` script to generate the aggregated skos vocabulary file. 

The script takes two parameters: 
* Input data directory. Default value "data". Content of this directory is read recursively and scanned for files with "ttl" filename extension.
* Output file. Name of the file where the aggregated vocabulary is written. Default value "aggregated-raid-skos.ttl". 

`python aggregate_turtle.py <input data directory> <output file>`
 