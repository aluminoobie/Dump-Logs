# Dump-Logs

.SYNOPSIS

  Dump-Logs retrives all log files with a Record Count greater than 0, 
dumps the logs to CSV files, and archives all the CSV files into a
ZIP file. 

.DESCRIPTION

  PowerShell script or module to dump every windows log on a system with 
entries.  The script will query a remote or local system for all logs 
with  entries.  The identified logs will be written to a CSV, archived 
in a .zip file, and returned to the system running the script.

.PARAMETER path

  The path to save the ZIP archive.  Default is user Documents.

.EXAMPLE

  Dump-Logs -path C:\Users\example\Desktop
