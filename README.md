# job_application_tools

## print_cover is a command line bash script that takes 4 arguments and uses the cover file as a template to copy a cover letter

### make sure the print_cover is executable for you
### after you download the repo cd into the root and execute:
> chmod ug+x print_cover

### make this file executable and pass it the 4 arguments below as strings.
### example if this file were an executable called print_cover
### execute:
>  print_cover "Full Stack Engineer" "Company Name" "My reasons" "My skills"

### enclose in "" if any spaces in the arguments
### write a template called cover in the same directory
### place __postion __company __reason __skills in the template where you want to perform sed string substitution
### the file will be output to the command line as well as copied to clipboard so you can control-V your text into a form. A cover_log file will also be generated that prints the date along with the arguments for each execution.
