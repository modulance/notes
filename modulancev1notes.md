## My Custom Windsurf global rules

```
# Completion of Commands
- Use npm run dev to run the development server.
- Use npm run lint to lint the code.
- Fix errors after commands
- After fixing an error, check again for errors.
```

Aside from that I'm using the Windsurf: Front-End-> Typescript rules found here - https://windsurf.com/editor/directory

## My Initial Prompt for Brainstorming with Claude 3.7 Sonnet (Thinking)
##### In the IDE itself in Chat Mode via Cascade

You are an expert frontend webapp developer with expert knowledge in developing websites using React, Typescript, Tailwind CSS, and Tanstack Query. Today I want to build a single page application that will serve as my homepage to all my software projects. For now, all the tools will be standalone webapp tools self contained onto this website. Help me brainstorm the details of what you need to know to help me build this application. Ask one or a few questions at a time and once you're ready, lets track the system specifications down in a new markdown file. I want the codebase to be well organized so each tool specific component and page should live in a folder with that tool name. There should be a homepage with an about section and navigation that allows you to switch between the tools. I want the UI to look modern and simple and allow it to scale to mobile screens as well. 

## New Chat Prompt to build the Calculator app 
##### (after the homepage and initial application setup was complete)

You are an expert frontend developer with a depth of knowledge in tool development using React, Typescript, Tailwind CSS, and React Query. In this project, lets go ahead and build the Scientific Calculator tool as described in the SPECIFICATIONS.md file. Make sure the code is grouped together and organized in the appropriate folder. 

##### Note: This did crash along the way a few times so I had to restart it figuring out where it left off. If it didn't hang, it would have been a pretty good one shot. 
