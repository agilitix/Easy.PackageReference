
How to change your old csproj format to the new Sdk style project.

See :
https://github.com/hvanbakel/CsprojToVs2017

Install the tools (in a VS console):
dotnet tool install --global Project2015To2017.Migrate2019.Tool
dotnet tool install --global Project2015To2017.Migrate2017.Tool

Migrate your legacy project to the new Sdk style :
dotnet migrate-2019 wizard "D:\Path\To\My\TestProject.csproj"
dotnet migrate-2017 wizard "D:\Path\To\My\TestProject.csproj"

Do not foget to update the project-type guid in the solutions using it (you can also
remove then add the project in the solution to refresh the project type):
https://stackoverflow.com/questions/10802198/visual-studio-project-type-guids
