<div align="center">

# SimplexAI

**Your personal AI. Proactive, collaborative, and yours to run.**

An open-source, local-first personal AI that gets to know you, takes initiative, and brings agents together to get things done.

**English** · [Bilingual](./README.bilingual.md)

[Meet Simplex](#meet-simplex) · [See it in action](#see-it-in-action) · [Yours to run](#yours-to-run)

</div>

> Product preview — this repository currently hosts product documentation.

<!-- Main demo: Profile; a proactive follow-up from Another Me; Room collaboration with the Collaboration sidebar; open the actual deliverable. -->

<a id="meet-simplex"></a>

## Meet Simplex

Bring your files, projects, and tools into one workspace. Let your AI pick up where you left off.

**Another Me** is your personal assistant. It uses your Profile to understand your background, retrieves past decisions and project context when needed, and keeps track of things worth following up on. For work that needs several roles, ask it to bring other agents into one Room to discuss, divide the work, and deliver results.

Agents run on the computers you connect, using local files, command-line tools, and existing environments. Conversations, collaboration plans, activity, and outputs stay together in one workspace, ready for the next round of work.

<a id="see-it-in-action"></a>

## See it in action

### An AI that gets to know you

**See what your AI knows about you.**

Upload a resume, notes, or an introduction. Choose material from connected apps you have authorized, or bring in another AI's summary of you. Simplex turns these sources into a personal Profile: your experience timeline, communication style, working style, preferences, and writing style.

Another Me uses that same Profile as context. Add new sources to update what it knows, so the next conversation needs less introduction.

Projects, conversations, and files can also become a Personal Wiki, organized around projects, topics, people, and companies. When you return to earlier work, Another Me can retrieve the background and check the original material.

> Pick up our previous project. Find the decisions we've already made and the questions still open.

<!-- Profile demo: Add source; generate the Profile; show the experience timeline and five modules; add a source and show the update. Follow with a Wiki project page and retrieval of original material. -->

### It takes initiative

**The things you said you'd do get a follow-up.**

Another Me can identify commitments, deadlines, to-dos, and replies you are waiting for, keep track of them, and arrange a suitable time to check back. You can also set a Routine in a Room to have it work on an agreed schedule.

With proactive reminders enabled and supported apps connected, new mail, calendar changes, and messages can become follow-up signals. It decides what needs your attention now and what can wait, and uses your feedback to adjust its reminders.

> I'm showing this project to friends on Friday. Check our preparations on Thursday evening, and first pull together the material we have and the questions still open.

When the Routine runs, Another Me checks the preparations and comes back with the results. Adjust the request in the conversation, or manage the Routine from the Room sidebar.

<!-- Proactive demo: state a goal; show the Room Routine; show Another Me returning with findings and prepared material. Optionally add a reminder triggered by a change in an authorized app. -->

### Bring your agents into one room

**Give the team a goal and let different roles move it forward.**

Bring research, development, writing, or review agents into one Room to work with the same material. Another Me can find agents available to you and request a collaboration Room. Once you confirm, the project material and brief arrive in the new Room together.

Agents can make explicit assignments, hand results to the next person or agent, and bring blockers back to the coordinator. Join the conversation whenever you need to add context or change the direction.

> Start a group for this beta demo. Work out the demo flow, build a page we can open, then review it.

Open **Collaboration** in the sidebar to see the agreed roles, handoffs, and reporting relationships. Use **Activity** to inspect what agents are actually doing. Documents and files return to the Room, where you can preview them, keep editing, and organize them in Library.

<!-- Collaboration demo: confirm Room creation; show the agent assignments and Collaboration graph; capture a real handoff and a revision after review; open the final output. The graph shows the agreed workflow; Activity shows actual execution. -->

> In active development. Proactive reminders and first-run Profile generation are enabled through an experimental feature switch.

<a id="yours-to-run"></a>

## Yours to run. Yours to shape.

| Your choice | How it works in Simplex |
|---|---|
| Run it yourself | Self-host the workspace and connect agents to your own Local Computer, with local files, CLI tools, and existing sign-ins. |
| Choose your runtime and models | Choose a Computer, Runtime, and available model for each agent. Supported runtimes include Codex, Claude Code, and Pi; available models depend on the connected environment. |
| Build your agent team | Define roles and working instructions in conversation, adjust your agents, and choose a collaboration approach for the project. |
| Use your tools and Skills | Reuse local tools and supported Skills to extend your own workflows. |
| Make it your own | Use the open-source code to understand and adapt the assistant, tool integrations, and collaboration mechanisms. |

Local first means you can deploy and control the workspace and execution environment. When you choose cloud models or external apps, the corresponding requests are still sent to those services.

