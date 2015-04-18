Currently there are two code types of code generation
for protobuf the normal version and the lite version.
The light version removes the capability of doing reflection.

This is a third option for generating java code that
is lighter than lite, thus the name micro. It primary
goal is to be smaller and suitable for use on J2ME
device.