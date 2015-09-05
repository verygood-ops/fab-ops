# Infrastructure Operations

Some useful utilities that are helpful in managing infrastructure

## AWS Utilities

The `aws_credentials` parameter that's used in some tasks expects a JSON string
representing a dictionary with these fields:

     AWS_DEFAULT_REGION
     AWS_ACCESS_KEY_ID
     AWS_SECRET_ACCESS_KEY

## GUI

When evaluating an operations GUI, it is important to have options that can auto-populate a GUI.  [Rundeck](http://rundeck.org), combined with
[rundeck-fabric](https://github.com/balanced-cookbooks/rundeck-fabric), can generate a GUI for you.


# TODO:

Explore, using execnet and ansible
- http://codespeak.net/execnet/
- http://www.ansible.com/home
