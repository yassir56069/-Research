# Golang

Golang is a "better C++". To keep it short. it's claimed to be :


- Robust,
- Stable,
- And rather flexible in it's implementations
---
you can use it for all sorts of things, from personal projects to complex backend-services. it's pretty neato in that front.

## The Why

### Generally - 
It has industry validation for a very reasonable amount of time. about as much as Java, with the added quirks of being "better" (simpler, that is)

To be more technical -- golang is essentially c++ with garbage collection. gc's add a necessary overhead, and it's easily a couple of magnitudes slower than C. The appeal of go might be that despite these shortcomings, it's a very solid implementation of a gc, and it's ahead in terms of speed.

In a sense a form of GC is a good idea for go, because forgo-ing it does add a level of complexity and fundamental changes to the language you're working in and how you manipulate memory - This isn't rust. and it's not trying to be. To my eyes, go seems to be an implementation of C++ that makes it memory safe without slowing it down or ruining stability in the process.

### But why C++?
The current tech stack that I'm familliar with would be .NET and C#, and the advantages moving towards C++-like golang would be questionable without looking into it. if it isn't broke why fix it? 3 things come to mind personally.

- .NET loves OOP, and OOP loves needless abstraction and complication. At the end of the day if I can write 3 lines of code that do what 10 do or even just 10 lines of code that don't require an extra dependency, that is quite a charming prospect.

- More flexibility with the IDE I'm using. Visual studio loves to hold your hand and do everything for you. as a developer, this feels like racing through your development stack mounting a pig with a carrot stick. it's definitely nice ot have best practices in place and not to have to do all the foot-work of making things "correctly", but when it headaches and ruins some sort of implementation that could've been done in 3 terminal commands with a couple of extra lines to add some imports? it's not nearly as attractive. Despite all the legwork that visual studio does to set up c# and ASP.NET Core, it's still a bit of a jank having to have those things working in order to get to the "good" stuff. AKA, the actual work at hand. go tends to be much more of a breeze to setup, and it'd be fine to use VSC I'm sure.

- Statically linked libraries are rather pleasant.

- Possibly better to setup with Docker.

## Cons (vs .NET)
- Less libraries, less mature than Microsoft.

- Likely has a learning curve in terms of learning the language. this isn't java, and it certainly isn't C#.