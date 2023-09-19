# sub2ip.py
Convert a list of subdomains to IP addresses, output into a .CSV
---
usage: python3 sub2ip2.py -i <filename> -o <file_output>

Resolve subdomains to IP addresses and save results to a CSV file.

optional arguments:
  -h, --help            show this help message and exit
  -i INPUT_FILE, --input_file INPUT_FILE
                        Path to the input file containing subdomains.
  -o OUTPUT_FILE, --output_file OUTPUT_FILE
                        Path to the output CSV file. Default is
                        'subdomains.csv'.
