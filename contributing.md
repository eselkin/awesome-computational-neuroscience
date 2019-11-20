# Contributing to the awesome computational neuroscience list

1. You must have a github account (create one or log in)
2. You must submit changes by pull-request (i.e. Fork this repository, make your changes in your version of the repository, then make a pull request with your pushed changes)
3. Abuses of anything or anyone are not tolerated.

## Contributing a new school

While most schools do not have a computational neuroscience or theoretical neuroscience department or Ph.D. program, we would like to solely accept schools that have at least a graduate specialization/training program in these areas. Any school, in the U.S.A. or elsewhere is welcome as long as it meets this criterion. Faculty who have been identified as PIs should be listed unless current publications cannot be located... It's really important to be able to read the publications of the people with whom you are interested in working!

1. Each school is preceded by a #### or a ##### followed by a space followed by the name of the school. Check the other schools within the region for the correct heading depth.
2. Make sure the name of the school is unique
3. Make a list element in the Contents section. The list element should be a link to the section of the school `[Name of School](#name-of-school-spaces-replaced-with-dashes-and-punctuation-ignored)`
4. Immediately following the section header, a list of relevant items should inform the user what is required when applying to that school. Also a link to the application or information about the application is important.
    - Include relevant things such as GRE institution and department IDs (usually found on the application page for the program). If there is a minimum GRE requirement or a GRE subject test requirement, please list them.  
5. Each school faculty list should begin with the header row

```{markdown}
| PI(Ph.D.s) | Department | Research Areas | Research | +/=/- computational |
```

6. Following the header row, a header row separator

```{markdown}
| - | - | - | - | - |
```

7. [Add faculty to a school](#contributing-to-a-school)

## Contributing to a school

1. Each row of the table has 5 columns. Each column is separated by a pipe (|) and there is a single pipe at the start of the row and at the end.
2. The first column should include the principal investigator for the lab or group of graduate students. The format should be `[Last name], [First name] [Middle initial optional]`.
3. The second column should be the list of departments with which the professor is affiliated.
4. The third column should be a quote from the faculty bio or laboratory research page as a link. `[quote](link to faculty or lab page containing the quote)`. The quote should roughly explain what research methods the PI is using that warrants that person being on the list. It should likely have the word computation or circuit or something similar in it.
5. The fourth column should be a link with actively updated peer-reviewed journal articles. I say actively, because professors are notorious for starting a list and never updating it. It is often best to use a link to the professor's Google scholar user with their attributed papers. If the professor has not registered Google scholar user, then possibly insert the most appropriate search query.
6. The fifth column identifies whether the faculty member associated with the program has a clearly identified goal or research method that is in line with computational methods in neuroscience.
    - It is often the case that faculty are listed with the program that may have limited interest in the field.
    - If the faculty member is truly not focused on the subject matter and no articles can be found that link that professor to the subject, then put a `-`
    - If the faculty member has some association to computational neuroscience, then put a `=`
    - If the faculty member is solely focused on computational or theoretical neuroscience, put a `+`
