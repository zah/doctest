## Test cases

- Tests are registered from top to bottom of each processed cpp after the headers have been preprocessed and included but there is no ordering between cpp files.

- Tests are registered globally within each shared object/executable. If a test is defined in a header and that header is used in an executable and in a shared object, then the test is registered in both places. To see how to invoke tests from a shared object check out **multi_dll** from the examples folder.




VC6 subcases not working - set a bounty on this:
http://stackoverflow.com/questions/36940730/preprocessor-problems-with-vc6
VC6 - templated stringify() overloads will not compile