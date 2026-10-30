<div align="center">

# SimplexAI

**An open-source, local-first personal AI workspace.**

Run agents on your own computers, connect local files and tools, and use personal context, proactive reminders, and agent group collaboration to get work done.

**English** · [Simplified Chinese](./README.zh-CN.md)

[Local first](#local-first) · [Feature demos](#features)

</div>

> Product preview — this repository currently hosts product documentation.

<a id="local-first"></a>

## Local first

Self-host the SimplexAI workspace and run agents on the computers you connect. Agents use local files, command-line tools, and your existing environment.

Personal context, project material, and deliverables accumulate in that workspace. Configure each agent's models, tools, and role to fit the way you work.

| Component | How it works |
|---|---|
| Workspace | Self-host the workspace to keep conversations, project material, and deliverables in a deployment you control. |
| Agent execution | Agents run on the computers you connect through Local Computer, using the existing host environment. |
| Local tools and Skills | Connect local files and CLI tools, reuse existing sign-ins, and load supported Skills. |
| Runtimes and models | Choose a Computer, Runtime, and available model for each agent. Supported runtimes include Codex, Claude Code, and Pi; model availability depends on the connected environment. |
| Open-source customization | Inspect and adapt the assistant, tool integrations, and collaboration mechanisms through the open-source code. |

> 📎 **Media 01 · Local setup**
>
> Add a screenshot of the connected Local Computer, runtime and model selection, or local tools and Skills.

<!-- MEDIA SLOT 01-local-setup
Replace the placeholder block above with your video link or image. Example:
![Local setup](./assets/local-setup.png)
-->

When you use cloud models or external apps, the corresponding requests are sent to those services. Where data is processed depends on your configuration.

<a id="features"></a>

## Feature demos

**Another Me** is your personal assistant. It uses your Profile and project knowledge as context, follows up on open items, and can bring other agents into a Room to collaborate.

> 📎 **Media 02 · Main demo**
>
> Add a 60–90 second video. Start with the connected local computer, then show Profile, a proactive follow-up, Room collaboration, and the final deliverable.

<!-- MEDIA SLOT 02-main-demo
Replace the placeholder block above with your video link or image. Example:
[![Watch the demo](./assets/main-demo-cover.png)](PASTE_VIDEO_URL_HERE)
-->

### Profile and personal knowledge

Upload a resume, notes, or an introduction. Choose material from connected apps you have authorized, or bring in another AI's summary of you. Simplex turns these sources into a personal Profile: your experience timeline, communication style, working style, preferences, and writing style.

Another Me uses that same Profile as context. Add new sources to update what it knows, so the next conversation needs less introduction.

Projects, conversations, and files can also become a Personal Wiki, organized around projects, topics, people, and companies. When you return to earlier work, Another Me can retrieve the background and check the original material.

> Pick up our previous project. Find the decisions we've already made and the questions still open.

> 📎 **Media 03 · Profile**
>
> Add a screenshot or short recording of Add source, the experience timeline and five Profile modules, and an update after adding a source.

<!-- MEDIA SLOT 03-profile
Replace the placeholder block above with your video link or image. Example:
![Profile](./assets/profile-demo.gif)
-->

### Proactive reminders and scheduled tasks

Another Me can identify commitments, deadlines, to-dos, and replies you are waiting for, keep track of them, and arrange a suitable time to check back. You can also set a Routine in a Room to have it work on an agreed schedule.

With proactive reminders enabled and supported apps connected, new mail, calendar changes, and messages can become follow-up signals. It decides what needs your attention now and what can wait, and uses your feedback to adjust its reminders.

> I'm showing this project to friends on Friday. Check our preparations on Thursday evening, and first pull together the material we have and the questions still open.

When the Routine runs, Another Me checks the preparations and comes back with the results. Adjust the request in the conversation, or manage the Routine from the Room sidebar.

> 📎 **Media 04 · Proactive reminders**
>
> Add a screenshot or short recording of the goal, its Room Routine, and Another Me returning with findings and prepared material.

<!-- MEDIA SLOT 04-proactive
Replace the placeholder block above with your video link or image. Example:
![Proactive reminders](./assets/proactive-demo.gif)
-->

### Agent group collaboration

Bring research, development, writing, or review agents into one Room to work with the same material. Another Me can find agents available to you and request a collaboration Room. Once you confirm, the project material and brief arrive in the new Room together.

Agents can make explicit assignments, hand results to the next person or agent, and bring blockers back to the coordinator. Join the conversation whenever you need to add context or change the direction.

> Start a group for this beta demo. Work out the demo flow, build a page we can open, then review it.

Open **Collaboration** in the sidebar to see the agreed roles, handoffs, and reporting relationships. Use **Activity** to inspect what agents are actually doing. Documents and files return to the Room, where you can preview them, keep editing, and organize them in Library.

> 📎 **Media 05 · Agent group collaboration**
>
> Add a screenshot or short recording of the Room, Collaboration graph, a real handoff, a revision after review, and the final output.

<!-- MEDIA SLOT 05-collaboration
Replace the placeholder block above with your video link or image. Example:
![Agent group collaboration](./assets/collaboration-demo.gif)
-->

> In active development. Proactive reminders and first-run Profile generation are enabled through an experimental feature switch.
