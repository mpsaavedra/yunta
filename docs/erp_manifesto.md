# Yunta ERP Manifesto

``Written by Michel Pérez Saavedra``

## Preface

**``Yunta``** is a modular **microservices** based [ERP][erp], 
and this is his manifesto. 

> ``i made it sound like this on porpouse **:D``

It has been written in a way that we all know about how it was consive and how it **MUST** evolve throught time, even when am working - today, January, 01, 2020- this project has been create with the idea to provide and create an ERP system that could be used by most of [SOHO](https://wikipedia.org/wiki/soho) and many other type of enterprises with the aim of make the systems as distributable as possible allowing to share information with other services, in a single enterprise or to share information with enterprises.

## What's Bimbo, Inc and Yunta

Codename (**BIMBO**) has to be keep because is one of those word my son **Samuel** has pronnounse the best, when he whose ony 1 and a half years old and it describes the **rombe** figure. I **Michel** have no intentions to change it for nothing, even more now that his mother does not understand what means to be a son that take cares of my ``alzeheimer's`` sick mother (**worst sickness ever**). So this is my simple way to give to my son the importance it deserves now that am not as close to him as i which.

The name of **Yunta** cames because here in ``Cuba`` we call this way to a pair of bulls used to work in farms, and because all services work together i decide to call it that way. Also because it sounds funny **:D**.

## Coding and language style

We are **ALWAYS** going to use ``english`` as developing, commenting and documentation languages and C# coding style any other, style using in code will be revoked, because it could interfear with the clarity am persuing in the code of the entire system. If you want more details about how to organize your code and how to make it clearer to read please read the [Coding Style](./coding_style.md) document for a more detailed information.

Sorry boys, even when am an ``spanish speaker`` i could not deny that an english written code is more clear than an spanish one. for example in english you could name a variable:

```csharp
var year_of_birth = 1979;
```
But in spanish

```csharp
var ano_de_nacimiento = 1979;
```

I think that if your spanish speakers like me you could find this a little offensive, and if you are not spanish speakers you may notice that you have to type a little more, so english is the rule.

>But for your own services you could use what ever you want, english is only for the main stream services, sou you are free to choose.


## Contributing

Well am not entirely certain about how the system is going to be distributed or if it will but the idea is that it's going to be so is better to explain my personnal idea about is going to be.

Any contribution most be notice to the main system mantainer, this will allow to avoid double works or service that could confuse to the final user. This will allow to the system to growth horizontally in amount of services and not to repeat work. It does not means that you could work in the same thing that other user, of course not, this means that the name of the work could not be the same.

And finally included contributions **MUST** have all data about authors, name, descriptions and other information very well detailed and documented.

All work must be done in a separate branch **never** in the master branch only the main system mantainer could administrate this branch, because all clone request of the project could contain only we'll debugged code.

A full battery of test must be included on every contribution to allow to test everything and then decide what to include in the master branch.

## Authors and rights

People think that we developers work dark places with huge glasses and all that but is not real so the people should know how we are. In order to do that every single service has to had an authors file in the root of the service code folder. This file will be included in the main authors file.

Because this file is going to be included as an embedded resource in the Core of the application so every version of the service will had a full list of every developer that had work in a given service, to honor all.

For every author it must be included in the list:

> * name: ``or a codename if you like``
> * email: ``this is optional``
> * service: ``the service you have work on``
> * task: ``what you work on``

## Logo

There's a main logo the official bimbo logo designed by that me could or not be  used, you could choose to develop your own frontend and not to use the official frontend with include the logo, well your are free to use it not not, but please make us public to growth and to be known.

A simple thing to add about the official logo is that displays the idea of the official form of bimbo and well is my son's idea, you know what i mean. **;)**

## Developing IDE


You could use what ever you want, the project is mostly developed in C# with .NET Core 2.2 so a compatible IDE could be found any where. Am personally using [MonoDevelop][mono] because am a **Linux** user and most of the other IDE's i try they really suck and i don't like Windows (sorry Redmond guys), but i like [.NetCore][netcore] and many otheropensource fun things. 

You could use what ever you want but please edit your personnal .gitignore file to avoid the inclussion of undesire files in the code you submit. Avoid to submit your personnal IDE settings, and all that.

I also use [Visual Studio Code][code] to write this documentation because if light and the markdown editor is very cool. I also use it for the NodeJS parts of the application the idea is the same that for the markdown.

## Code of conduct

Is very important that you never do things that ofend other developers and if you report every an error that you could find on any service or core, developers will preciate alooooot, trust me we will. 

Is very important to notice you should never talk about:

* Politics
* Religion
* Ofenses to other developers

And any other mis behavior know by all of us..


[Back to Readme](../README.md)

[soho]: https://www.wikipedia.org/wiki/erp
[coding_style]: ./coding_style
[vscode]: https://vscode.microsoft.com
[monodev]: https://monodevelop.com
[erp]: http://wikipedia.org/wiki/erp
[mono]: https://monodevelop.xamarin.com
[netcore]: https://microsoft.com/aspnetcore
[code]: https://vscode.microsoft.co
