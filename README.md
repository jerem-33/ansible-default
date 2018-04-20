Default config for ansible

folder defaults :
    main.yml contains default values for role variables
    Values can be overwritten when role is used
    
folder files :
    Contains static files referenced by role tasks
    
Filder handlers :
    main.yml contains role handler definitions

meta :
    main.yml defines role information
    includes author, license, platforms, optional dependencies
    
tasks :
    main.yml contains role task definitions
    
templates : 
    contain Jinja2 templates referenced by role tasks

tests :
    can contain inventory and test.yml playbook
    used to test role

vars :
    main.yml defines role variable values