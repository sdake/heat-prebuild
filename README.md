heat-prebuild
=============

`heat-prebuild` takes a Heat (or CloudFormation) JSON template, builds image for every specified instance, installs software packages that the instance needs and then returns a new template that uses these images when launched.
