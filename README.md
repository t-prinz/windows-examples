# windows-examples
Samples to use with Windows systems

Notes about specifying the username and password
  - Using include_vars to include credentials does not work
  - Specifying credentials using vars_files works
  - Specifying credentials in a vars block works (but leaves the password in plain text)

In any case, the connection options need to be specified as part of the group_vars file
