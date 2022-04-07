# DotNetTest

A minimal C# application that deliberately references NuGet packages with known vulnerabilities.

While the following components are included as references in the project file `DotNetTest.csproj`, the only file containing code, `Program.cs`, does not reference any of these vulnerable components.

### Components referenced

| Component ID | Version | Highest CVSS Score | CVE ID(s) |
| ------------ | :-----: | :-------: | :----: |
| log4net | 2.0.8 | 9.8 | [CVE-2018-1285](https://nvd.nist.gov/vuln/detail/CVE-2018-1285) |
| Microsoft.AspNetCore.HttpOverrides | 2.0.1 | 8.8 | [CVE-2018-0787](https://nvd.nist.gov/vuln/detail/CVE-2018-0787) |
| System.Net.Security | 4.3.1 | 7.5 | [CVE-2017-0248](https://nvd.nist.gov/vuln/detail/CVE-2017-0248) </br> [CVE-2017-0249](https://nvd.nist.gov/vuln/detail/CVE-2017-0249) </br> [CVE-2017-0256](https://nvd.nist.gov/vuln/detail/CVE-2017-0256)  |
| NUnit | 3.12.0 | N/A | N/A |


