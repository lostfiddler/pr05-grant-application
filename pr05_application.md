# 1. What is your motivation for contributing to Processing and p5.js projects?

I want to challenge myself. In the past I have done two coding tasks that I
have been compensated for, the first was to create a navigation component for a react app,
the second to style and animate the same component. Those tasks had a shorter
time frame and a far smaller scope.

I wish to accelerate the development of my career as a programmer, and for it
to be financialy sustainable.

I want to experience working alongside a community of creative programmers and
guidance from more senior programmers. If I am a recipient of this grant these
things will be new to me, and I believe the experience will ingrain habits and
grant wisdom that otherwise would be more difficult to acquire.

One of my favorite programming books I am currently reading is "The Nature of
Code" which makes heavy use of the processing/p5.js library. As a fan, the
prospect of being more involved is really exciting.

898/1500

# 2. Briefly describe your understanding of the technical challenges associated with this project and outline your approach to solving them.

Running the command 'npm build' after upgrading codemirror to version 6.0.1 and
also updating its peer dependency, codemirror-colorpicker, in package.json
generated 47 warnings and 29 errors.

https://github.com/lostfiddler/pr05-grant-application/blob/main/build_errors.txt

I was able to remove the 47 warnings by changing the import statement for the
codemirror component to the new component used in v6 and using an alias for it
to reduce the number of lines changed in the 3 files that uses the codemirror
component.

All 29 errors also deal with import statements, but for codemirror addons and
extensions in the same 3 files. Removing those lines caused the p5.js web
editor to build without errors, however the website no longer functions. My
naive assumption is that version 6 has a different system in place to extend
the codemirror component with these modules.

The documentation for codemirror v6 has a migration guide that looks
comprehensive. If I am selected as a grant recipient for this project, reading
that guide will be the first thing I do. Reading the source code for version 6
would benefit me as well, I took a peek and it is well commented.

During the 4 months of the project, when I come across a problem that is beyond
my understanding and not in the documentation, I will first try to
google/chat-gpt for help, then consult the prior work and recommended reading
linked in the project description. If I am still having trouble I will then
reach out to my mentor for advice and perhaps even reach out to the
author/maintainer of the codemirror source code.

I am unfamiliar with testing and accessibility, however I am eager to
learn and am confident I can become competent enough to finish this project
exceptionally well, especially with guidance.

It has been years since I have used react, but I have used both class based and
functional components before in the framework, and converted between the two.
Since that time I have used vanilla web-components to render html with
JavaScript, which I believe is the same api's react is built on top of.

2080/3000

# 3. Why are you the right person for this project?

I have been learning programming for just over 5 years. My focus has been
mainly on web-development and JavaScript has been the language I have used
almost exclusively this whole time. Although I have not had much professional
programming experience, I feel confident in saying I am a competent JavaScript
programmer. I have skimmed if not read all the JavaScript guides and the
reference from https://developer.mozilla.org. I have read "Structure and
Interpretations of Computer Programs JavaScript Edition", "Eloquent
JavaScript", and I am currently reading "The Secret Life of Programs" among
many other computer science and programming books, including and inspired by
https://teachyourselfcs.com.

From a raspberry pi, I self host an Apache web-server I use as a gateway for
node.js http applications. I am currently reading "Nature of Code" and am
making a website that hosts all of the code examples I have read and my
solutions to the challenges in the book,
https://github.com/lostfiddler/animations-wiki. I am attempting to use as
little frameworks as possible because the website has been for learning and fun
even if I end up "re-inventing the wheel" (or most likely finding it too hard
and end up still using frameworks). The stack is node.js for the server and
web-components with shadow dom for rendering html. I enjoy working on the
website along side reading the book, and I intend to add different versions of
the examples or maybe just animations/interactions inspired from them.

I am a Jamaican immigrant and my participation will align with the Processing
Foundations goal for DEIA.

1605/3000

# 4. What questions do I have about the project? (optional)

0/1000

# 5. What do you hope to gain from this program?

I would really like to get to know the concerns, requirements, and constraints
a programmer has to be aware of and deal with in a production environment and
work on legacy source code.

I would like to get to know a community of programmers. I have had brief
communications in online communities concerning programming before, however I
would like to experience more intentional discussions.

I would like to be a part of open source software and learn about the culture.

I would like to have a mentor and possibly other advisors, and receive feedback
and advice on my code and professional development.

I believe this experience would possibly open the door to a career as a
programmer, or at least give me the confidence to pursue my first full-time
programming job more vigorously.

787/1000

# 6. How will you seek and incorporate feedback during your project?

I believe requesting a code review from my mentor whenever I push a commit to
my fork of processing/p5.js-web-editor and the repository I will use to
document my work would be a good idea, and implement any suggestions.

I could prepare a monthly progress report which could serve as a draft of my
required bi-monthly progress report and, again, have my mentor look over it and
provide feedback on my progress, approach, and areas for improvement.

I can ask questions or start a thread to discuss my project and ask for
feedback from others in https://discourse.processing.org and other relevant
forums.

605/1000

# 7. How do you plan to document your project progress and outcomes?

On my github account I have created the repository,
https://github.com/lostfiddler/pr05-grant-application. I can use this to host
drafts of the required bi-monthly and final reports and any other helpful and
necessary documents.

In my progress reports I can include a description of what I have accomplished
since my last update, share any obstacles I came across and how I overcame
them, provide an overview of any changes I've made to the codebase, and outline
my objectives and priorities for the next month.

I have also forked the p5.js-web-editor where my commits will be available to
view.

598/1000

# 8. How do you plan to manage your time, particularly if you have other commitments during the program's duration?

I learn programming full time and my parents cover most of my expenses so
I will surely be able to commit the majority of my time to this project over
the next 4 months.

I usually program and study impromptu but if I notice that I am losing focus
easily or doing something tedious I do 25 minute pomodoros throughout the day
which help sustain my productivity.

I will dedicate at least 4 days a week where my focus is primarily on this project.

447/1000
