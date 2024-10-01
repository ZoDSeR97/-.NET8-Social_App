# -.NET8-Social_App
Making Social App in .NET8

## :interrobang: Why use this mixture of technology?
Main reason is to learn Next.js, Typescript, and practice ASP.Net.

## :white_check_mark: Requirements
We are using MySQL in this journey
```bash
$ node --version
v22.9.0
$ dotnet --version
8.0.400
$ dotnet tool install --global dotnet-ef # This install entity framework globally
```

## :checkered_flag: How to run ##
Go to appsetting.json edit connection to your MySQL DB
```json
{  
    "Logging": {    
        "LogLevel": {      
            "Default": "Information",      
            "Microsoft.AspNetCore": "Warning"    
        }  
    },
    "AllowedHosts": "*",    
    "ConnectionStrings":    
    {        
        "DefaultConnection": "Server=localhost;port=3306;userid={yourID};password={yourPass};database={DBName};"    
    }
}
```
Now use these commands in terminal
```bash
$ cd Social_App.Server # cd into folder directory where .cs files are
$ dotnet restore # Restore the dependencies and tools of a project
$ dotnet ef database update
$ dotnet run
```

## 🤡 Frontend
- NextJS
- Tailwindcss

## 👾 Backend
- ASP.Net
- Entity Framework
- MySQL