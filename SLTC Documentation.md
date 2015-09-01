# Documentation Template

## Project Description

This should be aimed at a developer, unlike the [Project Plan](SLTC%20Project%20Plan.md) which is meant for a manager. This section should contain a short description of the project and maybe some links to wiki.

## Code Commenting

The code is expected to be heavily commented. Language-appropriate comments should be used, however even if the language does not provide a particular feature the following must be included:

* Class header
  * Name of the person who started the class
  * Basic description of what the class does
* Method/function/subroutine header
  * One sentance description of what it does
  * Input parameters (use @param if no other synthax is supported)
  * What does it return? (use @returns if no other synthax is supported)
* Generally anything which takes longer than one line should be commented even if it is brief

If the language or IDE support it, make sure you specify what class the function was defined in.

Remember, comments are not only for you, they are also for the next developer.

## Convention

Document which convention you used throughout the code in Documentation.md file. Consistent conventions help everyone. Something simple as follows will do, but this is developer and project specific. The only exception is a project with multiple developers, in that case the convention must be written before any code is produced.

* *lowerCammelCase()* for local methods
* *UpperCammelCase* for classes
* *UPPER_CASE* for global constants
* All booleans start with *is* as in *isReported*
* Each field in DB uses *SHORT_FIELD_NAME* where *SHORT* is the short name of the table
* *lower_case_type* is used for every variable where *type* is the data type link Int or String

## Variable Naming

Variable name should tell someone who has software experience what the variable is, otherwise the comment must be made at the time of variable definition. Error on the side of long variable names, most modern IDE's have predictive typing.

## Design Choices

This section is optional, but if you would like to explain to yourself of the future and others why you made some particular decisions this is where you do it.

## Other

Feel free to add sections as needed.
