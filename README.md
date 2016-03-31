# job_application_tools

## print_cover is a bash script that takes 4 arguments and uses the cover file as a template to copy a cover letter to your clipboard and generate a cover_log file.

### Make sure the print_cover file is executable.
### After you download the repo cd into the root and execute:
> chmod ug+x print_cover

### After it is made executable pass it the 4 arguments below as strings.
### example if this file were an executable called print_cover(provided in this repo)
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

>  A bit about myself --  I recently built this application1 with this tech.

>  Also, recently built this application2 with this tech.

>  I feel that my experience with ***My skills***, as well as my passion for building maintainable scalable software could potentially be a great match with what you’re looking for in a ***Full Stack Engineer*** at ***Company Name***.


>  Thanks for your time,


### Enclose arguments in "" if there are any spaces in the arguments.
### Write a template called cover (provided as a sample in this repo) in the same directory.
### place __postion __company __reason __skills in the template where you want to perform sed string substitution.
### The file will be output to the command line as well as copied to clipboard so you can command-v your text into a form. A cover_log file will also be generated that prints the date along with the arguments for each execution of print_cover.

### I've also noticed that the script will not work with "/" and "!" in any arguments. So escape sequences need to be used if you want to use those punctuation marks.

###  Let me know if you have any questions calvin.settachatgul@gmail.com

