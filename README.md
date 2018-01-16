# Kata: TDD Prime Numbers with C#

Command for project creation

```dos
mkdir _tddPN
cd _tddPN
md PrimeNumbers PrimeNumbers.Tests

cd PrimeNumbers
dotnet new classlib
cd ..

cd PrimeNumbers.Tests
dotnet new xunit
dotnet add reference ..\PrimeNumbers\PrimeNumbers.csproj
cd ..

dotnet new sln --name PrimeNumbers
dotnet sln add .\PrimeNumbers\PrimeNumbers.csproj
dotnet sln add .\PrimeNumbers.Tests\PrimeNumbers.Tests.csproj
```
