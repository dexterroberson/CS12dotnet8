**Errata** (25 items)

If you find any mistakes, then please [raise an issue in this repository](https://github.com/markjprice/cs12dotnet8/issues) or email me at markjprice (at) gmail.com.

- [Page 10 - Installing other extensions](#page-10---installing-other-extensions)
- [Page 15 - Understanding .NET runtime and .NET SDK versions](#page-15---understanding-net-runtime-and-net-sdk-versions)
- [Page 43 - Configuring inline aka inlay hints](#page-43---configuring-inline-aka-inlay-hints)
- [Page 50 - Exercise 1.2 – Practice C# anywhere with a browser](#page-50---exercise-12--practice-c-anywhere-with-a-browser)
- [Page 51 - Exercise 1.5 – Explore themes of modern .NET](#page-51---exercise-15--explore-themes-of-modern-net)
- [Page 54 - Understanding C# standards](#page-54---understanding-c-standards)
- [Page 58 - Showing the compiler version](#page-58---showing-the-compiler-version)
- [Page 65 - Comparing programming languages to human languages](#page-65---comparing-programming-languages-to-human-languages)
- [Page 87 - Comparing double and decimal types](#page-87---comparing-double-and-decimal-types)
- [Page 95 - Displaying output to the user](#page-95---displaying-output-to-the-user)
- [Page 124 - Exploring bitwise and binary shift operators](#page-124---exploring-bitwise-and-binary-shift-operators)
- [Page 261 - Passing optional parameters](#page-261---passing-optional-parameters)
- [Page 316 - Comparing objects when sorting](#page-316---comparing-objects-when-sorting)
- [Page 361 - Comparing inheritance and implementation](#page-361---comparing-inheritance-and-implementation)
- [Page 383 - Creating a console app to publish](#page-383---creating-a-console-app-to-publish)
- [Page 386 - Publishing a self-contained app](#page-386---publishing-a-self-contained-app)
- [Page 421 - Generating GUIDs](#page-421---generating-guids)
- [Page 522 - Using the lightweight ADO.NET database providers](#page-522---using-the-lightweight-adonet-database-providers)
- [Page 548 - Getting the generated SQL](#page-548---getting-the-generated-sql)
- [Page 553 - Getting a single entity](#page-553---getting-a-single-entity)
- [Page 616 - Be careful with Count!](#page-616---be-careful-with-count)
- [Page 641 - Customizing the model and defining an extension method](#page-641---customizing-the-model-and-defining-an-extension-method)
- [Page 694 - Exercise 13.3 – Enabling HTTP/3 and request decompression support](#page-694---exercise-133--enabling-http3-and-request-decompression-support)
- [Page 714 - Route constraints](#page-714---route-constraints)
- [Appendix - Page 1 - Exercise 1.1 – Test your knowledge](#appendix---page-1---exercise-11--test-your-knowledge)

# Page 10 - Installing other extensions

> Thanks to [Muhammad Faisal Siddiqui](https://github.com/devcloud-ops) for raising [this issue on November 20, 2023](https://github.com/markjprice/cs12dotnet8/issues/3).

At the time of publishing, the Polyglot Notebooks extension has a dependency on .NET 7. The extension will soon be updated to use .NET 8 but for now you must install .NET 7 SDK. Hopefully the team will also update the extension to use the **.NET Install Tool** that ensures a correct version of a required .NET SDK is installed so users do not have to manually install it.

> Note: The .NET Interactive team targetted .NET 8 two days after this issue was raised: https://github.com/dotnet/interactive/pull/3336.

> Support for LTS only: When .NET 9 is released in November 2024, Interactive .NET and Polyglot Notebooks will upgrade to it. If you are limited to only LTS releases, "As a workaround, you can install older versions of Polyglot Notebooks that use previous .NET versions and turn off automatic updates in VS Code.": https://github.com/dotnet/interactive/issues/3355.

# Page 15 - Understanding .NET runtime and .NET SDK versions

> Thanks to a reader who contacted my publisher Packt on November 16, 2023 about this issue.

I wrote, ".NET SDK versioning does not follow semantic versioning. The major and minor version numbers are tied to the runtime version it is matched with. The patch number follows a convention that indicates 
the major and minor versions of the SDK."

But the patch number is not created from the major and minor versions of the SDK. It is created from the minor and patch versions of the SDK.

I should have written, ".NET SDK versioning does not follow semantic versioning. The major and minor version numbers are tied to the runtime version it is matched with. The third number follows a convention that indicates the minor and patch versions of the SDK. The third number starts at `100` for the initial version (equivalent to `0.0` for minor and patch number). The first digit increments with minor increments, and the other two digits increment with patch increments."

# Page 43 - Configuring inline aka inlay hints

> Thanks to [TheFumblebee](https://github.com/TheFumblebee) for raising [this issue on November 30, 2023](https://github.com/markjprice/cs12dotnet8/issues/5).

In the bullet for Visual Studio 2022, I wrote the label for the check box was **Display inline parameter hint names**. I should have written **Display inline parameter name hints**.

# Page 50 - Exercise 1.2 – Practice C# anywhere with a browser

> Thanks to MrBiteyFace in the book's Discord channel for raising this issue.

In this exercise, I wrote "You can start coding online at any of the following links: **Visual Studio Code for Web**: https://vscode.dev/".

Although **Visual Studio Code for Web** does support some extensions, it does not support the C# extension. If you edit a `.cs` file then you will not have IntelliSense to help you. It also does not support running and debugging C# code. 

In the next edition, I will remove this bullet or change it to **GitHub Codespaces** (i.e. Visual Studio Code hosted in a cloud-based virtual machine) instead.

# Page 51 - Exercise 1.5 – Explore themes of modern .NET

> Thanks to [Emre Duman](https://github.com/Emopusta) who raised this [issue on March 11, 2024](https://github.com/markjprice/cs12dotnet8/issues/25).

Microsoft appears to have stopped paying for the domain used by the following link: https://themesof.net/. In the next edition, I will remove this exercise. 

# Page 54 - Understanding C# standards

> Thanks to [mark23344](https://github.com/mark23344) who raised this [issue on May 10, 2024](https://github.com/markjprice/cs12dotnet8/issues/36).

In the note box, I put a link to the C# specifications: https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/specifications. But Microsoft changed the link without an automatic redirect so that link now returns a 404. 

The new link is: https://learn.microsoft.com/en-us/dotnet/csharp/specification/.

# Page 58 - Showing the compiler version

In Step 3, the code should have been styled as `Code` (monospace black-on-light-gray text) instead of `Command Line` (monospace white-on-black).

# Page 65 - Comparing programming languages to human languages

> Thanks to [zaynchoudry](https://github.com/zaynchoudry) who raised this [issue on April 14, 2024](https://github.com/markjprice/cs12dotnet8/issues/34).

I wrote, "this YouTube video shows a demonstration of an Arabic programming language: https://youtu.be/dkO8cdwf6v8."

That video has been removed. An alternative is available at the following link: https://www.youtube.com/watch?v=EwYIZBL4sAU.

# Page 87 - Comparing double and decimal types

> Thanks to Yousef Imran who raised this issue via email on December 15, 2023.

At the top of page 87, I end the section describing a few special values associated with real numbers that are available as constants in the `float` and `double` types. I wrote, "`NaN` represents not-a-number (for example, the result of dividing by zero)," but that sentence is missing a "zero". It should be, "`NaN` represents not-a-number (for example, the result of dividing zero by zero),". In the next edition I will fix this mistake. 

> Please also note a [related improvement](https://github.com/markjprice/cs12dotnet8/blob/main/docs/errata/improvements.md#page-87---comparing-double-and-decimal-types).

# Page 95 - Displaying output to the user

> Thanks to SilentSolace in the book's Discord channel for raising this issue on December 18, 2023.

I wrote, "If you want to write three letters to the console without carriage returns after them, then call the `Write` method, as shown in the following code:"
```cs
Write("A");
Write("B");
Write("C");
```

But I neglected to prefix the method calls with `Console.` so how does this work?

On page 102, in the section titled "Simplifying the usage of the console", I show how to avoid needing to prefix those method calls with `Console.` by adding a statement to statically import the `System.Console` class, as shown in the following code:
```cs
using static System.Console;
```

But seven pages earlier I show code without the prefix without an explanation why that works! 

In the next edition, I will show the full code, as shown in the following code:
```cs
Console.Write("A");
Console.Write("B");
Console.Write("C");
```

And the same for the second code block:
```cs
Console.WriteLine("A");
Console.WriteLine("B");
Console.WriteLine("C");
```

# Page 124 - Exploring bitwise and binary shift operators

> Thanks to [Vlad Alexandru Meici](https://github.com/vladmeici) for raising [this issue on January 19, 2024](https://github.com/markjprice/cs12dotnet8/issues/13).

In Step 3, I refer to variables `a` and `b`, "In `Program.cs`, add statements to output the results of applying the left-shift operator to move
the bits of the variable `a` by three columns, multiplying `a` by 8, and right-shifting the bits of the variable `b` by one column, ...". 

I should have written `x` and `y`.

In the last paragraph, I wrote, "The `3` result is because the 1 bits in `b` were shifted one column into the 2-and 1-bit columns."

I should have written, "The `3` result is because the 1 bits in `y` were shifted one column into the 2-and 1-bit columns."

# Page 261 - Passing optional parameters

> Thanks to [Vlad Alexandru Meici](https://github.com/vladmeici) for raising [this issue on March 18, 2024](https://github.com/markjprice/cs12dotnet8/issues/28).

In Step 1, the method signature has an extra space between `command` and `=`, as shown in the following code:
```cs
public string OptionalParameters(string command  = "Run!",
```

Although extra whitespace has no effect on the compiler, in the next edition, I will remove the extra space, as shown in the following code:
```cs
public string OptionalParameters(string command = "Run!",
```

# Page 316 - Comparing objects when sorting

> Thanks to **Ashish** in the Discord channel for this book for raising this issue.

In Step 9, the final `else` statement will never execute because the logic of the `if` and `else if` clauses mean it will only execute when `this` (the current object instance) is `null`. In that scenario, the method could not execute anyway since the object wouldn't exist! When I wrote the `if` statement, I exhaustively covered all combinations of `null` and `not null` for `other` and `this`, but one of those combinations could never in practice happen. 

In the next edition, I will delete the following code from the `CompareTo` method:
```cs
else
{
  position = 0; // this and other are at same position.
}
```

And I will add a comment in the code explaining why it is not needed. I have already done this in the code solution here:
https://github.com/markjprice/cs12dotnet8/blob/main/code/Chapter06/PacktLibrary/Person.cs#L196

# Page 361 - Comparing inheritance and implementation

> Thanks to Blix in this book's Discord channel for pointing out this typo.

For the first sentence, I wrote, "For me, the terms inherit and implement are different, and in the early days of C# and .NET you could
strictly apply them to classes and interfaces respectfully."

In the next edition, I will correct the word "respectfully" to "respectively", as explained at the following link: https://www.merriam-webster.com/grammar/respectively-vs-respectfully.

# Page 383 - Creating a console app to publish

> Thanks to `mdj._` in the book's Discord channel for raising this issue on December 18, 2023.

In Step 5, I tell the reader to "add the runtime identifiers (RIDs) to target five operating systems" including Windows 10 or later. The legacy RID was `win10-x64` but in .NET 8 RC1 this changed to `win-x64`. The RID for MacOS/OS X also changed. From the documentation, "Starting with .NET 8, the default behavior of the .NET SDK and runtime is to only consider non-version-specific and non-distro-specific RIDs."

The book lists the RIDs as shown in the following markup:
```xml
<RuntimeIdentifiers>
  win10-x64;osx-x64;osx.11.0-arm64;linux-x64;linux-arm64
</RuntimeIdentifiers>
```

The RIDs should be as shown in the following markup:
```xml
<RuntimeIdentifiers>
  win-x64;osx-x64;osx-arm64;linux-x64;linux-arm64
</RuntimeIdentifiers>
```

In the next edition, as well as fixing the RID values, I will link to the official documentation so that readers can confirm the current valid values. For example, for known RIDs: https://learn.microsoft.com/en-us/dotnet/core/rid-catalog#known-rids.

# Page 386 - Publishing a self-contained app

> Thanks to `mdj._` in the book's Discord channel for raising this issue on December 18, 2023.

Related to the [previous issue](#page-383---creating-a-console-app-to-publish), in Step 2, I tell the reader to "Enter a command to build and publish the self-contained release version of the console application for Windows 10". But the command uses the legacy RID value `win10-x64`, as shown in the following command:
```
dotnet publish -c Release -r win10-x64 --self-contained
```

The command should be:
```
dotnet publish -c Release -r win-x64 --self-contained
```

Any other references to `win10-x64`, like the folder name, should also be changed to `win-x64`.

Similarly, in Step 4, the command `dotnet publish -c Release -r osx.11.0-arm64 --self-contained` should be:
```
dotnet publish -c Release -r osx-arm64 --self-contained
```

I have updated the **Command Lines** summary file to use the new valid RIDs: https://github.com/markjprice/cs12dotnet8/blob/main/docs/command-lines.md#page-386---publishing-a-self-contained-app

# Page 421 - Generating GUIDs

> Thanks to [Cem Kaya](https://github.com/cmkaya) for raising this issue on [March 20, 2024](https://github.com/markjprice/cs12dotnet8/issues/31).

In Step 1, I wrote, "In `Program.cs`, add statements to access the shared `Random` instance, and then call its methods
to generate random numbers, as shown in the following code:" 

This should have been, "In `Program.cs`, add statements to output the value of an empty `Guid`, generate a new random `Guid` and then output its value, and finally output each individual byte of the random `Guid` value, as shown in the following code:".

# Page 522 - Using the lightweight ADO.NET database providers

> Thanks to `blix11` in the book's Discord channel for raising this issue.

In the fourth paragraph I wrote, "The EF Core database providers for SQLite and SQL Server are built on top of the ADO.NET libraries, so EF Core is always inherently slower than ADO.NET. Furthermore, ADO.NET can be used independently
for better performance because the EF Core database providers are “closer to the metal.”"

The second sentence is confusing or just wrong, and I probably meant to write, "Furthermore, ADO.NET can be used independently which will give better performance because the ADO.NET database providers are “closer to the metal.”". But even then the sentence doesn't add much so in the next edition I will remove that sentence.

# Page 548 - Getting the generated SQL

> Thanks to `Ashish` in the book's Discord channel for raising this issue.

In Step 1, I wrote, "In the `FilteredIncludes` method" and in the GitHub solution code I do the same thing. Originally this was so that later you could see what happens when you run that method. But I'm not sure if this is necessary now because in the next section I get the reader to enable logging of SQL queries globally. It's also confusing because it happens to use a variable named `categories` so a reader might think I meant to add the statement to the `QueryCategories` method but this is not necessary. For the next edition, I might just remove this step. 

In Step 3, I wrote, "Run the code, enter a minimum value for units in stock, like `99`, and view the result," but the output shows I entered `95`. In the next edition I will change the text to also say `95`.

# Page 553 - Getting a single entity

> Thanks to `Ashish` in the book's Discord channel for raising this issue.

In Step 3, I show output of the logged SQL which includes `WHERE NOT ("p"."Discontinued") AND "p"."ProductId" > @__id_0`. But I do not tell the reader to add a global filter that would add the `NOT ("p"."Discontinued")` clause to the `WHERE` until the **Defining global filters** section on page 557.

In the next edition, I will edit the output to remove this SQL clause, as shown in the following output:
```
Enter a product ID: 1
Connection: Data Source=C:\cs12dotnet8\Chapter10\WorkingWithEFCore\bin\
Debug\net8.0\Northwind.db
dbug: 9/17/2023 18:04:14.210 RelationalEventId.CommandExecuting[20100]
(Microsoft.EntityFrameworkCore.Database.Command)
    Executing DbCommand [Parameters=[@__id_0='1'], CommandType='Text',
CommandTimeout='30']
    SELECT "p"."ProductId", "p"."CategoryId", "p"."UnitPrice",
"p"."Discontinued", "p"."ProductName", "p"."UnitsInStock"
    FROM "Products" AS "p"
    WHERE "p"."ProductId" > @__id_0
    LIMIT 1
Info > First: Chang
dbug: 9/17/2023 18:04:14.286 RelationalEventId.CommandExecuting[20100]
(Microsoft.EntityFrameworkCore.Database.Command)
    Executing DbCommand [Parameters=[@__id_0='1'], CommandType='Text',
CommandTimeout='30']
    SELECT "p"."ProductId", "p"."CategoryId", "p"."UnitPrice",
"p"."Discontinued", "p"."ProductName", "p"."UnitsInStock"
    FROM "Products" AS "p"
    WHERE "p"."ProductId" > @__id_0
    LIMIT 2
Info > Single: Chang
```

# Page 616 - Be careful with Count!

> Thanks to Clint Mayers who submitted this issue via email.

I showed a code teaser by Amichai Mantinband, a software engineer at Microsoft, as shown in the following code:
```cs
IEnumerable<Task> tasks = Enumerable.Range(0, 2)
  .Select(_ => Task.Run(() => Console.WriteLine("*")));

await Task.WhenAll(tasks);
Console.WriteLine($"{tasks.Count()} stars!");
```

But I mistakenly used `WriteLine` methods when they should have been `Write` methods, as shown in the following code:
```cs
IEnumerable<Task> tasks = Enumerable.Range(0, 2)
  .Select(_ => Task.Run(() => Console.Write("*")));

await Task.WhenAll(tasks);
Console.Write($"{tasks.Count()} stars!");
```

# Page 641 - Customizing the model and defining an extension method

> Thanks to swissbobo in the book's Discord channel for raising this issue.

In Step 4, in the `AddNorthwindContext` method, Word's autocorrect changed an `o` into an `O` in `Options.UseSqlite`, as shown in the following code:
```cs
services.AddDbContext<NorthwindContext>(options =>
{
  // Data Source is the modern equivalent of Filename.
  Options.UseSqlite($"Data Source={path}");

  options.LogTo(NorthwindContextLogger.WriteLine,
    new[] { Microsoft.EntityFrameworkCore
      .Diagnostics.RelationalEventId.CommandExecuting });
}
```

The correct code is shown here:
```cs
services.AddDbContext<NorthwindContext>(options =>
{
  // Data Source is the modern equivalent of Filename.
  options.UseSqlite($"Data Source={path}");

  options.LogTo(NorthwindContextLogger.WriteLine,
    new[] { Microsoft.EntityFrameworkCore
      .Diagnostics.RelationalEventId.CommandExecuting });
}
```

This is only a problem in the source code in the print book and PDF, not in the GitHub repository, as shown in the following statement: https://github.com/markjprice/cs12dotnet8/blob/de8310d8aaf82510a759e196566d111c4c839c57/code/PracticalApps/Northwind.DataContext.Sqlite/NorthwindContextExtensions.cs#L33

# Page 694 - Exercise 13.3 – Enabling HTTP/3 and request decompression support

> Thanks to [Phil Edmunds](https://github.com/Pip1987) for raising this [issue on January 20, 2024](https://github.com/markjprice/cs12dotnet8/issues/15) and to [RTD](https://github.com/RTDMakler) for discovering why Kestrel adds the HTTP/3 header but Chrome does not show it using HTTP/3 and a link to a work around on March 10, 2024. 

This exercise is about enabling HTTP/3 and testing it. The following online page has step-by-step instructions with a localhost-hosted website: 
https://github.com/markjprice/cs12dotnet8/blob/main/docs/ch13-enabling-http3.md

Unfortunately, "Browsers don't allow self-signed certificates on HTTP/3, such as the Kestrel development certificate", as described here: https://learn.microsoft.com/en-us/aspnet/core/fundamentals/servers/kestrel/http3#localhost-testing

The official documentation does not show a work around because Microsoft decided the steps are too difficult. You can read about the issue here if you want to try the complex workaround: https://github.com/dotnet/AspNetCore.Docs/issues/23700. RTD wrote more detailed instructions that you can read here: https://github.com/markjprice/cs12dotnet8/issues/15#issuecomment-1987353759.

In the next edition, I will add a note about this and remove the step-by-step instructions to try to test it. 

# Page 714 - Route constraints

At the top of the page, I wrote, "Use colons to separate multiple constraints, as shown in the following example:"
```cs
[Route("employees/{years:int:minlength(3)}")]
public Employees[] GetLoyalEmployees(int years)
```

But `minlength` is for checking the minimum length of a `string`, not the size of an `int`. The example should be as shown in the following code:
```cs
[Route("employees/{years:int:min(3)}")]
public Employees[] GetLoyalEmployees(int years)
```
# Appendix - Page 1 - Exercise 1.1 – Test your knowledge

> Thanks to Ikarmus in the book's Discord channel for raising this issue.

In question 1, I wrote "Interactive Development Environment (IDE)". This should be "Integrated Development Environment (IDE)".
