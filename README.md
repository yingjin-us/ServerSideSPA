﻿# Blazor code
https://medium.freecodecamp.org/how-to-build-a-single-page-application-using-server-side-blazor-1e37875e8ed

Note:
1) For some reasons cannot find Blazor template from VS, has to create the project by cmdline -- dotnet new blazorserverside -n ServerSideSPA
2) dotnetcore 2.2 won't work, will throw "An item with the same key has already been added. Key: .wasm", has to use dotnet core 2.1
3) Correspondingly, EF Core has to stay with 2.1.* version, 2.2.* version will not work
