# Tech Summit Ideas

* Stingray 101
* Spm + one button builds
* Extensibility: entity/component architecture & plugins
* Data-structures in the 21st century: what is fast on modern computers, both C++ and "data-oriented" JavaScript

## Speaker Biography

Niklas Frykholm has worked at leading technical positions in the games industry for a decade. A strong proponent of openness and information sharing he runs a popular technical blog, the Stingray Image of the Day project and is a frequent speaker at technical conferences such a GDC and the Lua Workshop. Together with Tobias Persson he created the Stingray game engine in 2009 and after Autodesk's acquisition in 2014, he now works as System Architect for the engine.

## Stingray 101

Autodesk has a game engine!

This talk will give a technical introduction to the Stingray game engine. We start by discussing what a game engine *is*, in technical terms and how that technology can be used outside the games domain (for architectural visualization or in the film industry). We a

* What is a game engine?
	* Gaming technology outside games
* How does Stingray work -- technical overview
	* Source data
	* Data compilation
	* The runtime loop
	* Lua scripting
* Stingray core values
	* Simplicity
	* Flexibility
	* Scalability
	* Quick iterations
* Stingray unique features
	* Mergable file formats
	* Collaborative editing
	* Reloadable game play
	* Extensibility
	* Flexible render pipe
	* Cross-platform drop/in-play

## Data Structures in the 21st Century

Processors are not what they used to be! Most programs are no longer CPU limited, instead they are limited by memory access patterns and lack of parallelization. But after years of indoctrination, we often write code as if the old rules still applied, making our programs unnecessarily sluggish.

This talk will show how to write high-performance software in a "data-oriented" way and get an order-of-magnitude (or more) of speed improvement. I will show how certain data structures, such as lists, lead to bad cache behavior and what you can use instead in order to get the same behavior but vastly improved performance. I will also show how to organize your code on a higher level to access the enormous computing power of modern multi-core CPU.

Most of my examples will be from C++, but since these are core CPU properties the lessons learned apply to all languages, including high level scripting languages such as Lua or JavaScript. I will demonstrate that the same programming techniques can lead to dramatic performance improvements in such langauges. 

* The development of modern CPUs
	* More cores
	* Memory speed does not increase with clock-speed
* Implications for performance
* Bad data structures that you should avoid, and what you should use instead
	* std::list
	* std::deque
	* std::map
* Data-structures for a modern application
	* Arrays
	* Hash tables
* SIMD processing and structure-of-arrays
* Multicore processing and data flow vs individual objects
* Data-oriented programming in JavaScript

## Spm + one button builds



## Extensible architecture
