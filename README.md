# melihercan.github.io


To avoid [Integrity attribute invalid](https://github.com/dotnet/aspnetcore/issues/21560) error:
1. In the wwwroot folder, add a .gitattributes file with "* binary" content.
2. Run "git add --renormalize ." if you've just added or changed the .gitattributes file.
