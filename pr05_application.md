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
editor to build without errors, however, the website no longer functions. My
naive assumption is that version 6 has a different system in place to extend
the codemirror component with these modules.

The documentation for codemirror v.6 has a migration guide that looks
comprehensive. I imagine if I am selected as a grant recepiant for this project
reading that guide will be the first thing I do and see where that leads me.

During the 4 months of the project, when I come across a problem that is beyond
my understanding and not in the documentation, I will first try to
google/chat-gpt for help. If I am still having trouble I will then reach out to
my mentor for advice and perhaps even reach out to the author/maintainer of the
codemirror source code.

1245/3000

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
0/1000

# 6. How do you plan to document your project progress and outcomes?
---
0/1000

# 7. How do you plan to manage your time, particularly if you have other commitments during the      program's duration?
---
0/1000
