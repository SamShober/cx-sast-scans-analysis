# cx-sast-scans-analysis
Powershell utility to pull scan data / build metrics from a CxSAST instance

# Usage
Running the utility will launch a powershell UI to collect the following information

* CxSAST server URL
* CxSAST username
* CxSAST password

If the utility is being run from a machine that has MS Excel installed, the user will be presented with two output format options.  Otherwise, only the second option will be available.

* MS Excel (one file)
* Summary.txt and data.csv

There is also an option to redact identifiable information from the result set including:

* Project names
* Team paths/names
* SCM paths
* Scan comments

# Authors
Chris Merritt, Checkmarx Professional Services - Initial work

# License
This project is licensed under TBD
