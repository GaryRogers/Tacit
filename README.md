# Tacit - A Method for maintaining an AI Assisted Notebook

## Background

I _loved_ the productivity movement in the early 2000s. LifeHacker, 43 Folders, Getting Things Done, Bullet Journals, I ate it all up. I tried everything. I used to carry a Franklin Covey planner with me everywhere. I wrote tasks on index cards, and kept them in a huge paperclip, a hipster's PDA. I've been keeping professional notes for decades now. Other people's systems have morphed and merged, and eventually have become my own. Simple. Markdown. Easy to search, and easy to maintain. You can `grep` my notes. You can `find` them. When I'm particularly ambitious I'll try to write python to parse them.

LLMs, and especially GitHub Copilot when paired with Visual Studio Code, have changed everything. When I started using Copilot, I saw it as an assistant for writing code, but it quickly became clear that it was much more than that. It was a partner in thinking and brainstorming. The 'a ha' moment was asking GitHub Copilot to help with a writing project I was working on for fun. Agent mode, a few prompts, and I had a _lot_ of world building and plot ideas. From there it was a short leap to using Copilot to help me with my professional notes. At first I tried to get Copilot to summarize a week's worth of notes. It was okay, but not great. Then I discovered GitHub Copilot Instruction files and the world changed again.

GitHub Copilot Instructions are a way to tell Copilot how to behave in a given file, how to react, how to respond. I started providing _context_ to Copilot about my notes, my professional organization, the technologies we use, the challenges we face, the people who are important in my professional life and how the relate to me. With that context, Copilot is able to help me write better notes, and almost (but not quite) think ahead of me as I'm maintaining my notes.

## Tacit

Tacit is a method for maintaining an AI assisted notebook. It is a set of conventions, and a set of Copilot Instructions that help me maintain my notes. Tacit is not a product, or a piece of software. It is a way of thinking about how to use AI to help you maintain your notes. Yes, Copilot helped with the name.

### Setup

- Set up Visual Studio Code with GitHub Copilot. You will need a GitHub Copilot subscription. (These are free for limited interactions).
- Configure Visual Studio Code to suggest Copilot completions as you type. 
  - By default, GitHub Copilot doesn't make suggestions in markdown files. You need to enable it. In Visual Studio Code, go to the settings, search for "Copilot", and enable "GitHub Copilot: Enable in Markdown Files". This will allow Copilot to make suggestions in your notes.
- Create a directory structure that makes sense for you. I've included an example structure in the `/src` directory. You can adapt it to your needs.
- Create a `copilot-instructions.md` file in the root of your notes directory. This file will contain the instructions that tell Copilot how to behave in your notes. I've included an example in the [/src/.github/copilot-instructions.md](/src/.github/copilot-instructions.md) file.
- Configure your context.
  - When working in GitHub Copilot chat, be sure to add context via the "Add Context" button. This will help Copilot understand your notes better.
  - I like to keep 5 days of notes open, as well as my `copilot-instructions.md` file. This gives Copilot a good amount of context to work with.

### Maintenance

- As you work on notes, add to and refine your `copilot-instructions.md` file. The more context you provide, the better Copilot will be able to help you.

### Prompt ideas

- "Summarize the key points from the last 5 days of notes."
- "Create a new agile user story for adding an 'update' button to the customer dashboard on the 'account status' page that will link to the new '/update' route. The story should include acceptance criteria and story points. Add it to `/agile` before we push it to JIRA."
- "Write a Change Notification for the deployment we have for the updates to the account status page."
- "Create base documentation for the new payment processing API we are building. Include endpoints, request/response examples, and error codes. Add the swagger spec to `/scripts`."
- "Create a meeting agenda for the next sprint planning meeting. Include a review of the backlog, prioritization of tasks, and assignment of work."
