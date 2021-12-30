<style type="text/css" rel="stylesheet">
  h1 code {
    color: olivedrab;
    text-shadow: .5px 2px 2px;

  }
  h2 code {
    color: darkolivegreen;
    border-bottom: 2px solid darkolivegreen;
    text-shadow: .1px .5px 2px;
  }

  h5 code {
    color: olive;
    text-shadow: .1px .5px 2px;
  }

  p {
    color: ivory;
    width: 40%;
    font-family: "Lucida Console", "Courier New", monospace;
  }
</style>

# `dotnet cmds cheatsheet`

##### `by TenaciousDev`

<br />
<br />

## `Add a new project`

<br />

Basic:

```
dotnet new <TEMPLATE>
```

Specify output directory:

```ps
dotnet new <TEMPLATE> -o <OUTPUT_DIRECTORY>
```

Specify output directory & output name:

```ps
dotnet new <TEMPLATE> -o <OUTPUT_DIRECTORY> -n <OUTPUT_NAME>
```

Example:

```ps
# The following command will create a new dotnet console app
# It will be created in a directory called "MyConsoleApp"
# The .csproj file will be called "MyApp"

dotnet new console -o MyConsoleApp -n MyApp
```

<br />

## `Create a solution file`

<br />

```ps
dotnet new sln
```

<br />

## `Add project to solution`

<br />

```ps
dotnet sln add <PROJECT_PATH>
```
