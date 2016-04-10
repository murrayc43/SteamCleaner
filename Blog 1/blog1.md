Blog 1:

When I was looking for an open sourced project to work on, I was a little stumped on what to look for and where to find it. Despite being given a website that allowed a user to browse for projects relatively easily, there were a ton of projects that simply didn't interest me, projects that I didn't understand what they did, or projects that didn't were dead (haven't been worked on for over a month).

Finally I found SteamCleaner. It was a relieve to have found something that not only interested me but also was a product that I myself could use as a consumer. This is how I decided to choose to work on this project.

At first, I had some slight difficulty loading everything up on my machine whereby the program would run without errors. My biggest problem was the authentication issues I experienced with Visual Studio. At first I thought it was some authentication issue with the program itself, as I had experience a very similar issue with a previous program a few months ago which did relate to invalid certificates of the project. Luckily, I foudn the quick fix and I was up and running from that point on!

Next up was going through the root directory and figuring out how the project was laid out and how each of the files worked to produce the program. This, at first, was a bit daunting. In some aspects it still is as there are a lot of function calls that are seemingly built into the IDE which I have never encountered before. Additionally, I am still working on getting use to the programming practices of the individuals who have programmed SteamCleaner up to this point.

After figuring out the basic structure of the project, I started diving into the code a bit, more specifically, I started working my way through what I thought was the most interesting part of the program: the C-Sharp files which actually locate the junk files! I found it quite amusing to realize that SteamCleaner not only cleans out junk data from Steam but as well as other services such as Battlenet, Gamestop, Nexon, Origin, UPlay, etc. These can all be located in the Analyzer --> Analyzers folder. Thinking about it further, it occurred to me that this layout was likely a smart move as it allows for easy additions to the program for other services in the future.

I worked my way through the remainder of the project, going file by file to try and understand what each file did. Again, there were a lot of function calls which seemed to be built directly into the IDE which I never knew about (and still am confused about a lot), but overall I feel I was able to walk through the majority of the code to understand the fundamentals of the project.