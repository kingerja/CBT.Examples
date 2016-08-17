# CBT.Examples

This repo contains various project types using CBT.

## [CSharp/Windows](src/CSharp/Windows)
### [ClassLibrary](src/CSharp/Windows/ClassLibrary)
A simple class library project which builds a .dll.

### [ClassLibrary.Package](src/CSharp/Windows/ClassLibrary.Package)
A NuProj project which builds a NuGet package containing the referenced [ClassLibrary](src/CSharp/Windows/ClassLibrary) project.  This project utilizes a standard NuGet package as a CBT module by including it in the [module packages.config](.build/local/CBTModules/packages.config#L9) and enabling the functionality in the [local build extensions build.props](.build/local/Extensions/build.props#L27-L29).
