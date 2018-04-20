# bash-challenge
This is intended to be an approachable challenge for someone with little to no exposure to bash scripting or terminal use on a mac computer. Links to popular learning resources are provided, as well as an input file for the challenge. Please return a copy of your script to the person handling your interview process for consideration. 

* http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html#toc1
* http://tldp.org/LDP/abs/html/

Oldies but goodies:

* http://linuxcourse.rutgers.edu/rute/node1.html
* http://coewww.rutgers.edu/linux/lessons/lesson9/shell_script_tutorial.html

Using the above links as starting points / reference, plus anything else you can glean from the internet, complete the following challenge:

The included file `users.csv` starts with a header line and is followed by a short amount of records. Using tools already available to you via the terminal of your mac computer:

Produce a shell script which either accepts the contents of the file as a pipe from a `cat` or is passed as an argument on the command line. The script should filter for only users with the role of "actor" and should discard the header line of the input csv. Output should be a list of users on stdout in the following format:

"FirstName LastName &lt;email&gt;"

The script should sort the output so the list of filtered users is presented in reverse alphabetical order by username.
The script should not output any of the quotation marks from the input csv.

Please add comments to your script file explaining your approach / how your script accomplishes its goal.
