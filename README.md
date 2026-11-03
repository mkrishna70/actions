triggers:

- event-based
- Manual
- Scheduled
- Workflow


Variables:
 Settings -> Secrets and variables -> Actions -> varibles ->New repository variables -> create one varaible and commit -> Go To .yaml file and use this created variable

 To access the created variable:  ${{<vars.variable_name>}}

 Secrets: 
  Settings -> Secrets and variables -> Actions -> Secrets ->New repository Secret -> add data ->Click edit and check

  To access the created variable:  ${{<secrets.variable_name>}}
