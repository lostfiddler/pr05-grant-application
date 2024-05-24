# 1. What is your motivation for contributing to Processing and p5.js projects?
---

I want to challenge myself. I want to experience working alongside a community.
I want guidance from a more senior programmer. I want for my career to lean
more towards creative areas, working alongside creative people.

280/1500

# 2. Briefly describe your understanding of the technical challenges associated with this project and outline your approach to solving them.
---

Running the command 'npm build' after upgrading codemirror to version 6.0.1 in
package.json generated 47 warnings and 29 errors. I was able to remove the 47
warnings by changing the line 'import CodeMirror from "codemirror"' to 'import
{EditorView as CodeMirror} from "codemirror"' in the 3 files that uses the
codemirror component.

All 29 errors also deal with import statements, but for codemirror addons and
extensions in the same 3 files. Removing those lines caused the p5.js web
editor to build without errors, however the website no longer functions. My
naive assumption is that version 6 has a different system in place to extend
the codemirror component with these modules. Upgrading codemirror also caused
npm to warn that the dependency codemirror-colorpicker should also be upgraded.

The documentation for codemirror v6 has a migration guide that looks
comprehensive. If I am selected as a grant recepiant for this project, reading
that guide will be the first thing I do and see where it leads me. Reading the
source code for version 6 would benefit me as well, I took a peek and it is
well commented.

During the 4 months of the project, when I come across a problem that is beyond
my understanding and not in the documentation, I will first try to
google/chat-gpt for help, then consult the prior work and recommended reading
linked in the project description. If I am still having trouble I will then
reach out to my mentor for advice and perhaps even reach out to the
author/maintainer of the codemirror source code.

I am unfamiliar with testing and also accessibility, however I am eager to
learn and am confident I can become competent enough to finish this project
execptionlly well, especially with guidance.

It has been years since I have used react, but I have used both class based and
functional components before in the library and converted between the two.
Since that time I have used vanilla web-components to render html with
javascript.

1972/3000

# 3. Why are you the right person for this project?
---

I have been learning programming for just over 5 years. My focus has been
mainly on web-development and JavaScript has been the language I have used
almost exclusively this whole time. Although I have not had any professional
programming experience, I feel confident in saying I am a competent JavaScript
programmer.

I self host an Apache web-server I use as a gateway for a few node.js http
applications. I am currently reading "Nature of Code" (which uses
processing/p5.js extensively) and am making a website that hosts all of the
code examples I have read and my solutions to the challenges in the book. I
enjoy working on the website along side the book a lot, and I intend to add
different versions of the examples or maybe just animations/interactions
inspired from them. I imagine this will be a long-term project which means I
will be using p5.js for a long time.

874/3000

# 4. What questions do I have about the project? (optional)
---
0/1000

# 5. How will you seek and incorporate feedback during your project?
---

I believe requesting a code review, from my mentor or a member of the
community, whenever I push a commit to my fork of the github repository would
be a good idea. I could also prepare a draft of my required bi-monthly progress
report and, again, have my mentor or another member of the community look over
it and provide feedback.

332/1000

# 6. How do you plan to document your project progress and outcomes?
---
0/1000

# 7. How do you plan to manage your time, particularly if you have other commitments during the program's duration?
---

I self learn programming full time and my parents cover most of my expenses so
I will surely be able to commit the majority of my time to this project over
the next 4 months.

I usually program and study impromptu but if I notice that I am losing focus
easily or doing something tedious I start 25 minute pomodoros which help
sustain my productivity.

I will dedicate at least 4 days a week where my focus is primarly on this project.

435/1000
