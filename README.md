# Wax on, Wax Off

> A **koan** is a riddle or puzzle that Zen Buddhists use during meditation to help them unravel greater truths about the world and about themselves. Zen masters have been testing their students with these stories, questions, or phrases for centuries.

As we learn a new language, we need to practice the new ideas, syntax and paradigms that come what that language. The idea of language Koans helps both beginners and veterans learn the ins and outs of language.

## Objectives

- Complete your language Koans

## Requirements

### .NET Students

- Head here: [https://github.com/suncoast-devs/DotNetCoreKoans](https://github.com/suncoast-devs/DotNetCoreKoans) and follow the directions in the README.md. This will have you fork this repository, clone it and practice the

### Ruby Students

- Head here: [http://rubykoans.com/](http://rubykoans.com/) and follow the directions

### Explorer Mode

- [ ] Complete the Koans

### Adventure Mode

- [ ] (.NET) There are a few Koans that were commented out, comment these in and complete them.

## Reading Material

### .NET Students

- Here are some videos about inheritance and interfaces to help gain some more exposure.
  - Interfaces: https://www.youtube.com/watch?v=neTerkT7LhE
  - Inheritance: https://www.youtube.com/watch?v=m0DJIhmUtP8
  - Getters & Setters: https://www.youtube.com/watch?v=M0IY3712QCE

---

# .Net Core Koans [![Build status](https://ci.appveyor.com/api/projects/status/j0ykx336513hmnep/branch/master?svg=true)](https://ci.appveyor.com/project/NotMyself/dotnetcorekoans/branch/master) [![Join the chat at https://gitter.im/dotnetcorekoans/Lobby](https://badges.gitter.im/dotnetcorekoans/Lobby.svg)](https://gitter.im/dotnetcorekoans/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

The .NET Core Koans walk you along the path to enlightenment in order to learn C# on .NET Core. The goal is to learn C# syntax, structure and some common functions and libraries available on the .NET Core platform. .NET Core is a cross platform environment that runs happily on Windows, OS X and Linux. It is super simple to get started learning.

### The Structure

The koans are broken out into areas by file, arrays are covered in AboutArrays.cs, lambdas are introduced in AboutLambdas.cs, etc. They are presented in order in the PathToEnlightenment.cs file.

Each koan builds up your knowledge of C# and builds upon itself. It will stop at the first place you need to correct.

Some koans simply need to have the correct answer substituted for an incorrect one. Some, however, require you to supply your own answer. If you see the object FILL_ME_IN listed, it is a hint to you to supply your own code in order to make it work correctly.

### Getting Started

1. Install [.NET Core SDK 2.0](https://www.microsoft.com/net/core).
2. Install [Visual Studio Code](https://code.visualstudio.com/), the [Insiders Edition](https://code.visualstudio.com/insiders) is highly recommended.
3. Fork this repository, the clone the fork: `git clone https://github.com/<<Your github name>>/DotNetCoreKoans.git`.
4. Change directory into the cloned repository `cd DotNetCoreKoans`.
5. Restore packages: `dotnet restore`.
6. Open the project in VSCode `code-insiders .` or `code .` depending on what version you chose to install.
7. Run the koans in watch mode: `dotnet watch --quiet run`.
   - **Note:** The `--quiet` flag is used here to suppress messages from the watch framework.
8. Follow along with the instructions printed to your console. Each time you save a \*.cs file, the project will be built and run again for you automatically.

### About Koans

This project is based on the work of [Cory Foy](https://github.com/CoryFoy) and his original multi-language project [DotNetKoans](https://github.com/CoryFoy/DotNetKoans). If you are interested in learning VB.NET or the Full .NET Framework (windows only), please look at his fine work.

Programming Koans came about because of the most enlightened [Ruby Koans](https://github.com/edgecase/ruby_koans) by [Jim Weirich](https://github.com/jimweirich). Jim was a great teacher & programmer whom I had the pleasure of meeting, learning from and playing games with. Rest in peace, sir. We will continue your effort to bring a love of the craft to anyone willing to learn.

For a fuller explanation of what is going here, see the blog post [Learn C# on Windows, OSX or Linux with the .NET Core Koans](http://iamnotmyself.com/2016/07/22/learn-c-on-windows-osx-or-linux-with-the-net-core-koans-2/)
