## 0.6.1
  * Adds benchmark feature
## 0.6.0
  * Adds ability to list puppet types
  * Adds ability to list puppet datatypes
## 0.5.1
  * accidently bump 
## 0.5.0
  * Fixes #gh-49 - puppet 4 functions don't seem to work
  * Disables trying to set trusted_node_data for puppet versions that do not support it
## 0.4.4
  * Refactor to upcoming puppet 5.0  (minor fix, requires a few more changes)
  * Fixes issue with frozen string literal under ruby 2.3.x
## 0.4.3
  * Fixes issue with older facterdb filter not working
## 0.4.2
  * Fixes #44 - error when running under puppet apply
## 0.4.1
  * Adds a puppet application face
  * Fixes #41 - add file reference when showing code during code break
## 0.4.0
  * Rename to puppet-debugger
## 0.3.4
  * Fixes issue with temporary file not being unique
## 0.3.3
  * Adds ability to call breakpoints from within repl
  * Adds newline for each multiline input
## 0.3.2
  * Fixes #31 - adds ability to show surrounding code
## 0.3.1
  * Fixes #28 - puppet 4.6 support
  * Fixes #27 - repl should throw puppet error message instead of stacktrace
  * adds support for customizing facterdb filter
  * adds support for puppet 4.6
  * Fixes #26 - allow configuration of facter version and facterdb filter

## 0.3.0
  * Fixes #23 - add quiet flag to suppress banner
  * Fixes #11 - cannot declare and use a class or define
## 0.2.3
  * fixes #21 - type display causes error
## 0.2.2
  * adds better support for playing back puppet code
    * this now allows playback of any manifest
    * allows mixed puppet code and repl commands
## 0.2.1
  * Fixes #2 - adds support for multiline input

## 0.2.0
  * Fixes #19 - lock down dependency versions
  * fixes #18 - add ability to filter out functions based on namespace
  * fixes #15 - node classes return error
  * fixes #16 - use auto complete on functions and variables
  * Fixes #14 - add functionality to set node object from remote source
  * adds support for server_facts
  * fixes other minor bugs found along the way
  * adds ability to list classification parameters from ENC

## 0.1.1
  * adds ability to load files or urls

## 0.1.0
  * ensure the title of classes contains quotes
  * adds support to import a file or import from stdin
  * added additional ap support for puppet::pops::types
  * adds ability to print resources and classes
  * adds the ability to pass in a scope

## 0.0.8
  * adds ability to list currently loaded classes
  * adds formatted output using awesome print
  * adds verbose type output when creating resources

## 0.0.7
  * Added ability to list scope variables

## 0.0.6
  * Bug fix for puppet 3.8   

## 0.0.5
  * Added ability to set puppet log level  
