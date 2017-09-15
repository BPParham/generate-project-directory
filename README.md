# generate-project-directory
generate-project-directory (gpd) creates a development directory structure for versioned projects.


## Prerequisites
- Ruby on Rails [download](http://installrails.com/ "Install Rails - A Step-by-Step Guide").


## Syntax
    gpd [ domain [entity [project [application]]]]


## Parameters
    domain        Top level domain name abbreviation.

    entity        Company or organization name.

    project       Project or concept name.

    application   The name of the application or program.


By default, gpd with all parameters will create a rails application in the directory provided.  Running the command with no parameters will prompt the user for the first three (3) parameters only.  The project directory will contain the "trunk", "tags", & "branches" directories with the application being installed to the trunk directory.  Normally, only the first three (3) parameters are passed to create the structure, then navigating to the directory and running "rails new ..." to create the application in any of the directories under branches.
