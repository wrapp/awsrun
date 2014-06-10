awsrun
======

Run command with aws credentials exported to ENV

awsrun will search your ~/.boto file for AWS credentials associated with the
given profile. It will then run the specified command with the AWS credentials
available as environment variables.

Usage:
    awsrun <profile-name> <cmd> <args ...>

Example:
    awsrun my-profile env | grep AWS


Installing
----------

```bash
git clone git@github.com:wrapp/awsrun.git
cd awsrun
pip install .
```
