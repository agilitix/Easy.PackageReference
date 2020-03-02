
https://github.com/hvanbakel/CsprojToVs2017

Install the tools (in a VS console):
dotnet tool install --global Project2015To2017.Migrate2019.Tool
dotnet tool install --global Project2015To2017.Migrate2017.Tool

Migrate a project :
dotnet migrate-2019 wizard "D:\Path\To\My\TestProject.csproj"
dotnet migrate-2017 wizard "D:\Path\To\My\TestProject.csproj"

Update the project type guid in solution (or removed/add the project in the solution):
https://stackoverflow.com/questions/10802198/visual-studio-project-type-guids
