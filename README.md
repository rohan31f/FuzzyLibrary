# README #

I created some basic tools/data types written completely in C++ to replicate some of the functionality used in a 
language that has automatic memory management like C#. I wrote my own data types that would use garbage collection
similar to that found in C# data types like a List, String, Delegates and allow for use in C++. Initially created
as a practice project to better understand the under-the-hood workings of C# data types and its memory management,
I hope to use this library in my own work and would be happy to see someone use it for their projects.

FuzzyDelegates::
FuzzyDelegates is a component of the project which is based upon the idea of delegates from Sergey Alexandrovich Kryukov's fantastic
article 'The Impossibly Fast C++ Delegates'

https://www.codeproject.com/Articles/1170503/The-Impossibly-Fast-Cplusplus-Delegates-Fixed
It is only fair I mention his article as much of my learning curve to understand a generic C++ function pointer was understood from it.

FuzzyEvent::
This component has an 'Event Manager' that could potentially include several 'Event Handlers'. 
The reason for this is that you would for example want to keep a handler specifically for you 'Animations'
and a separate handler for your 'Input' etc.
An event fired will be fired into the 'Event Manager' thus calling the corresponding 'event listener' if stored
in any of the 'Event handler's' created.
Each new type of event you create needs to be derived from FuzzyEvent and event listener from FuzzyEventListener.

Utilities::
The file titled 'Utilities' is a practise/dump file. I intend to write several global functions in that file over the course of this project.

If you wish to contact me regarding the project in any way send me an email at rohan31f@gmail.com