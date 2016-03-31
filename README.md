# job_application_tools

## print_cover is a command line bash script that takes 4 arguments and uses the cover file as a template to copy a cover letter

### make sure the print_cover is executable for you
### after you download the repo cd into the root and execute:
> chmod ug+x print_cover

### make this file executable and pass it the 4 arguments below as strings.
### example if this file were an executable called print_cover
### execute:
>  ./print_cover "***Full Stack Engineer***" "***Company Name***" "***My reasons***" "***My skills***"
>  ***Full Stack Engineer***
>  ***Company Name***
>  ***My reasons***
>  ***My skills***


>  appended date position company reason skills to cover_log
>  ******************************************************************
>  ******************************************************************
>  Hello!

>  I am very interested in your open ***Full Stack Engineer*** position at ***Company Name***.  I feel that I would contribute greatly to building maintainable scalable application platforms for ***Company Name***.

>  A bit about myself --  I recently built this project1 with this tech.

>  Also, recently built this projec2 with this tech.

>  I feel that my experience with ***My skills***, as well as my passion for building maintainable scalable software along the entire stack could potentially be a great match with what you’re looking for in a ***Full Stack Engineer*** at ***Company Name***.


>  Thanks for your time,


### enclose in "" if any spaces in the arguments
### write a template called cover in the same directory
### place __postion __company __reason __skills in the template where you want to perform sed string substitution
### the file will be output to the command line as well as copied to clipboard so you can control-V your text into a form. A cover_log file will also be generated that prints the date along with the arguments for each execution.


