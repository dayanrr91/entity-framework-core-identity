"# entity-framework-core-identity" 

Install-Package Microsoft.EntityFrameworkCore.Tools
Install-Package Microsoft.AspNetCore.Identity.EntityFrameworkCore
Install-Package Microsoft.EntityFrameworkCore.SqlServer


en Startup.cs incluir:
using Microsoft.AspNetCore.Identity;
incluirlo en todos los lugares que se use identity
