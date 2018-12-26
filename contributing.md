# Contributing to the awesome computational neuroscience list
1. You must have a github account (create one or log in)
2. You must submit changes by pull-request (i.e. Fork this repository, make your changes in your version of the repository, then make a pull request with your pushed changes)
3. The only file that will accept pull-requests is the ```README.md``` file.
4. Abuses of anything are not tolerated.

## Contributing a new school
While most schools do not have a computational neuroscience or theoretical neuroscience department or Ph.D. program, we would like to solely accept schools that have at least a graduate specialization/training program in these areas. Any school, in the U.S.A. or elsewhere is welcome as long as it meets this criterion.

1. Each school is preceded by a ## followed by the name of the school. The name of the school should be a hyperlink to the faculty page or the application to graduate education page for the program in computational neuroscience.
2. A `<div id="unique_school_name">` tag should be surrounding the name of the school with an id attribute that is specific to that school.
3. Make a list element in the table of contents with a link to the section of the Readme for that school: `<a href="#unique_school_name>School name</a>`
4. Immediately following the ## section name for the school a list element should be included for all ways to apply to graduate programs at that school and particularly how to enter the computational neuroscience program. Include relevant things such as GRE institution and department IDs (usually found on the application page for the program). If there is a minimum GRE requirement or a GRE subject test requirement, please list them.  
5. Each school faculty list should begin with the header column: 
* ``` | PI(Ph.D.s) | Research Areas | DOIs | +/=/- (likely related to more computational methods) |``` 

followed on the next line by the  row separator: 
* ```|---|---|---|---|```
6. <a href="#add_to_school">Adding faculty to a school</a>

## <div id="add_to_school">Contributing to a school</div>
1. Each row of the table has 4 columns. Each column is separated by a pipe (|) and there is a single pipe at the start of the row and at the end.
2. The first column should include the principal investigator for the lab or group of graduate students. The format should be `Last name, First name Middle initial`. 
3. The second column should be a quote from the faculty bio or laboratory research page as a link. `[quote](link to faculty or lab page containing the quote)`. The quote should roughly explain what research methods the PI is using that warrants that person being on the list. It should likely have the word computation or circuit or something similar in it.
4. The third column should be a link with actively updated peer-reviewed journal articles. I say actively, because professors are notorious for starting a list and never updating it. It is often best to use a link to the professor's Google scholar user with their attributed papers. If the professor has not registered Google scholar user, then possibly insert the most appropriate search query.
5. The fourth column identifies whether the faculty member associated with the program has a clearly identified goal or research method that is in line with computational methods in neuroscience. 
    * It is often the case that faculty are listed with the program that may have limited interest in the field. 
    * If the faculty member is truly not focused on the subject matter and no articles can be found that link that professor to the subject, then put a `-`
    * If the faculty member has some associate to computational neuroscience, then put a `=`
    * If the faculty member is solely focused on computational or theoretical neuroscience, put a `+`
