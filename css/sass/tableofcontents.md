# Table of Contents for the CSS/SASS Directory #
## Siren Listening Page Boilerplate v1.0 ##
This Table of Contents goes through top level files first and then the files, .scss snippets, in the different subdirectories grouped by subdirectory.

### FILES ###
Collection files

1. basic.scss
	- Contains the Safe CSS styles served to all browsers inline in the <head>
	- Collects snippet files
2. enhanced.scss
	- Contains the enhanced styles that are applied following a test.
	- Developed responsively and mobile-first
	- Collects snippet files
3. enhanced-ie.scss
	- Served to IE8 browsers
	- Same as enhanced.css but without the media queries as that code is generated by respond.js for these browsers
	- Can contain IE specific rules if necessary
	- Collects snippet files


### DIRECTORIES ###
The directories in the CSS/SCSS folder and notes.

1. BASE-ENHANCED
	- Contains SCSS snippets referring to universal selectors in the enhanced experience for the project
2. BASIC
	- Contains SCSS snippets for the basic experience including a variant on the Normalize reset
3. LAYOUT
	- Contains all snippets pertaining to layout rules
4. MISC
	- Contains snippets that don't fit elsewhere the _print.scss snippet
5. MIXINS
	- Contains snippets for mixins
6. OBJECTS
	- Contains highlevel CSS objects seperated into snippets based on purpose
7. RESPONSIVE
	- Contains snippets related to the responsive design of the site
	- Everything is mobile first
8. VARIABLES
	- Contains snippets relating to Global variables for the project


### FILES BY SUBDIRECTORIES ###
This list, more than others, should be updated often throughout the project.

#### VARIABLES ####
1. _variables.scss
	- Contains Variables for colors used throughout the project
	- Contains extendable classes for fonts used throughout the project
	- Contains configuration for Modular Scale mixins
	- Contains configuration for Vertical Rhythm mixins
	- Intended for use in enhanced.scss

#### MIXINS ####
1. _mixins.scss
	- Contains mixins that represent common CSS patterns

#### BASIC ####
1. _core.scss
	- Contains a variant on the Normalize reset and the basic styles for the project
	- Contains SAFE styles only

#### BASE-ENHANCED ####
1. _core-enhanced.scss
	- Extends the style rules for _core.scss for the enhanced experience

#### LAYOUT ####
1. _container.scss
	- Contains the style rules for content containers

2. _grid.scss
	- Contains the basic horrizontal grid rules for the project and related classes

#### OBJECTS ####
1. _headerfooter.scss
	- Contain the style rules for the Header and Footer sections of the project
	- Shouldn't be extensive for Listing Page sites
2. _password.scss
	- Styles for the Password form on the homepage
3. _playlist.scss
	- Styles for the playlist and associated elements on the listening page
4. _mgmt.scss
	- Styles for Management container elments on listening page
5. _nope.scss
	- Styles for the "Password is Wrong" page

#### RESPONSIVE ####
1. _responsive.scss
	- The home for all media-queries

#### MISC ####
1. _print.scss
	- Contains the print style rules
