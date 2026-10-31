# eShop Fast Feedback on .NET

A minimal console app targeting .NET Core 3.1 for testing .NET tooling.
It prints `Hello World!` and exits.

**Unsupported legacy test baseline:** .NET Core 3.1 is out of support. This sample
is not a production recommendation.

## Run locally

Install the .NET Core SDK **3.1.426**, including the .NET Core **3.1.32** runtime.

From the repository root:

```powershell
dotnet run --project .\eshop-fastfeedback.csproj
```

Expected output:

```text
Hello World!
```

The app consists of one project file and `Program.cs`, with no additional packages.

## License

[MIT](LICENSE).
