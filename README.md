# CS-350
CS-350

**Summarize the project and what problem it was solving.**

The final project in Module 7 involved solving the problem of making a working thermostat that regularly uploads data to a (in this situation simulated) server, for whatever purposes exist beyond that.

**What did you do particularly well?**

I believe that I did particularly well at the task scheduler.  I am slowly learning over time to become more "clever" when it comes to attacking problems in programming, and I suspect that this mostly comes with experience.  For instance, I originally just thought "Well, I have three things that need timing, so I'm going to just use three timers."  That actually worked just fine, my program ran smoothly.  It was not, however, the most efficient way of implementing task scheduling, so I fixed it.  Instead of having a 1 second timer, a 500ms timer, and a 200ms timer (which some other devkits may actually not even allow), I figured out after a little research that I can simply set an LCD timer (Lowest Common Denominator, not Liquid Crystal Display) for 100ms, and use incrementing variables to schedule tasks at 100ms increments.  This is one reason that I am going to love software engineering, I think, because there always seems to be a way to make something more efficient, or more organized, and that is one of my favorite things to do in general.

**Where could you improve?**

Oh, I can improve just about everywhere.  I have a lot to learn.  Given my current level of knowledge though, I submitted my absolute best work with this code.  If I continue with a career or classes in embedded systems, I'm sure that I'll find ways to improve, but for now, as they saying goes- "You don't know what you don't know."

**What tools and/or resources are you adding to your support network?**

Well for one, I have this devkit I've purchased that's going to sit around collecting dust unless I  find a practical use for it, so that's one tool I'm adding.  I've absolutely no idea what I might use it for, but I intend to find out.  Aside from that, this github repository and all of the rest like it are tools and resources I can add to my support network for my new career endeavors.

**What skills from this project will be particularly transferable to other projects and/or course work?**

Great question, as I actually typed the following to finish off the last one before I even read the current one: I suspect that I will most likely end up doing work in avionics, which is a form of embedded systems engineering.  I particularly liked working with the Lumin Cabin Management hardware/software by Heads Up Technologies on the Cessna business aircraft I worked on.

**How did you make this project maintainable, readable, and adaptable?**

I did so by commenting code thoroughly with change dates and initials throughout, and did my best to organize the code in a way in an intuitive manner.  There are often many ways that one could structure code that are not "incorrect", it seems to be a matter of preference sometimes, such as putting all of the global variables in one section at the top and then distributing them throughout the functions as necessary as opposed to instantiating the global variables for each function just prior to the function they're going to be used in.  I'm sure that maybe not this exact thing, but other things like this change depending on the employer that one works for, or the application, so I will tailor it per use case in the future.
