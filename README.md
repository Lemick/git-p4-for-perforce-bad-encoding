# git-p4-for-perforce-bad-encoding

I wanted to clone a Perforce depot with the nice tool git-p4, but our depot was not utf-8 encoded (cp1252), resulting in having some weirds characters in the changelists descriptions, authors names and filepaths when git tried to interpret it..
You can set your own charset by replacing 'cp1252' by yours :)
