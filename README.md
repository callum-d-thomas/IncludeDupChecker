# DuplicateLineChecker

DuplicateLineChecker is a console application designed to find and confirm duplicate `<Include>` statements in a `.csproj` file. It prompts the user for confirmation before considering any duplicates and writes the confirmed duplicates to a file.

## Usage

To run the application, use the following command:

```bash
dotnet run --project DuplicateLineChecker.csproj <path_to_csproj_file_to_check>
```