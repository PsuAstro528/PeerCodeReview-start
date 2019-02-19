# Astro 528 Peer Code Review

## Formalities
- GitHub ID of reviewer:

- GitHub ID(s) of developers for project being reviewed:

- Date/version/tag of commit being: 

- Files that were reviewed:



## Specific Suggestions

First, please review the README (or other documentation separate from the code).  Then review the code submitted, providing specific on individual issues.  Examples of specific suggestions that could be useful include suggestions for:
- Readability & Documentation (1 point)
   - General organization of the code
   - Functions that could benefit from better documentation of purpose, inputs or puts
   - Functions that could benefit from better documentation of their design or implementation 
   - Type or modules that could benefit from documentation
   - Documentation that is obsolete, redundant or not helpful
   - Old code that could be removed (never reached or commented out) 
- Style 
   - Indentation & spacing that could be improved
   - Places where an error/warning messages could be added/improved
   - Fixing inconsistencies in coding style (e.g., [Julia Style Guide](https://docs.julialang.org/en/v1/manual/style-guide/index.html)
- Testing & Assertions (1 point)
   - Additional assertions
   - Additional unit tests
   - Additional integration and/or regression tests
- Organization, Modularity & Maintainability (1 point)
   - Repeated code could be moved into a function
   - Defining a composite type to improve code readability/organization
   - Places where could use interfaces (rather than directly accessing fields)
   - Improving names for variables, functions, types, modules, etc.
   - Opportunities to make functions more generic
- Efficiency & Performance (1 point)
   - Data structures that may inhibit memory/cache performance
   - Places were unnecessary/repeated work could be eliminated
   - Functions where another algorithm may be more efficient
   - Non-const global variables that could be avoided
   - Functions where type instability could affect performance
   - Places where developer might want to try benechmarking an alternative implementation

In most cases, I think it will generally be easiest to place specific suggestions at the point of the issue in responce to the developer(s) pull request.  


INSERT FEEDBACK

## General Suggestions

Next, step back to think about the big picture.  Try to provide constructive suggestions for how the developer(s) could improve their programming practices.  If it would be useful to add comments at specific lines of code on the pull request, you're welcome to do so.  Even in you do that case, please provide a summmary of your main suggestsions below.  (1 point)

INSERT FEEDBACK

### Bugs?
If you think you may have found a bugs, then please let the developer know.
If it's an implementation detail (e.g., missing minus sign, need to use `deepcopy` instead of `copy`), then please comments at the point of the bug in responce to the developer(s) pull request.  
If it's a bigger issue, then you can create an "Issue" via GitHub, where the developer and user can discuss that potential bug.  

INSERT FEEDBACK

### Any other constructive feedback


