# dotnet-template

## Development

### Environment setup

* Copy and rename the file `.env.example` to `.env`:

    ```bash
    cp .env.example .env
    ```

    > Customize the values if you see fit

### Useful commands

* Create a solution

    ```bash
    dotnet new sln --name <name of the solution>
    ```

* Create a project

    ```bash
    dotnet new <type of projects>
    ```

    > To see a full list of possible types, use the following command:
    >
    > `dotnet new list`

* Add a new project to a existing solution

    ```bash
    dotnet sln add ./<path to the>/<projects target>.csproj
    ```

    > Considering the same directory of the `.sln` file

* Link projects with refereces

    ```bash
    dotnet add ./<path to the>/<receiver project>.csproj \
        reference ./<path to the>/<referenced project>.csproj
    ```

## References

* [DevContainer](https://code.visualstudio.com/docs/devcontainers/create-dev-container)
* [DevContainer specification](https://containers.dev/)
* [.dotnet DevContainer](https://github.com/devcontainers/images/tree/main/src/dotnet)
* [dotnet command](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet)
