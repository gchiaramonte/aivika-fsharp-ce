Aivika for .NET 

This is an F# port of the Haskell simulation [library] (http://hackage.haskell.org/package/aivika)
of the same name by the same author, David Sorokin, who developed
the original library. It supports discrete event simulation, system
dynamics and partially agent-based modeling. 

The main idea is that many simulation activities can actually be 
represented as abstract computations. Functional programming has 
a developed apparatus for creating such computations, combining them, 
reasoning about them and so on. This is monads, streams, arrows etc. 
It is important that F# and Haskell provide an easy-to-use syntactic 
sugar for working with such computations, which is a clue to practical 
usability of the method.

Aivika for .NET is available under a dual-license model: GNU GPL License v3 
(GPLv3) and Commercial.

A Commercial Aivika license keeps your code proprietary where only you can
control and monetize on your end product’s development, user experience 
and distribution. You also get additional modules that allow simplifying 
simulation experiments. These modules can plot charts and histograms, 
collect statistics and save the results in CSV files.

Aivika for .NET is also licensed under GPLv3. If you use Aivika under 
open-source license, you need to make sure that you comply with all 
the licenses of the components you use.

Please contact the author of this library for detail of licensing:
David Sorokin <mailto:david.sorokin@gmail.com>, Yoshkar-Ola, Russia.

Aivika for .NET can be installed via NuGet after accepting the license:

`PM> Install-Package Simulation.Aivika`

The PDF documentation is available by the following link:

[Aivika 3 User Guide: Version for .NET Framework and Mono] (https://github.com/dsorokin/aivika/wiki/pdf/aivika-user-guide.pdf)

This document describes the simulation API and contains examples for
the commercial version, although the simulation engine itself
is fully separated, self-contained and it is defined in this repository.

The simulation library can be actually used without what is called
in the document as simulation experiments. Only then you will have
to return and process the results manually.
