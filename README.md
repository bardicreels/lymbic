# lymbic

const brainAIAnalogy = `
Human Brain System as AI Learning System Analogy
|
|-- Central Nervous System
|   • Coordinates(AllProcesses) ∧ ¬Compute(DirectCalculations)
|
|-- Brain
|   • Manage(OverallFunction) ∧ ¬Store(Data)
|   |
|   |-- Cerebrum
|   |   • Process(HighLevelTasks) ∧ ¬Handle(LowLevelOperations)
|   |   |
|   |   |-- Frontal Lobe
|   |       • HUMAN(DecisionMaking) ∧ ¬Interface(InputOutput)
|   |       |
|   |       |-- AI Assistants (e.g., Cursor AI, Claude)
|   |           • Augment(HumanDecisionMaking) ∧ ¬Replace(HumanJudgment)
|   |           • Generate(CodeSuggestions) ∧ ¬WriteCompletePrograms
|   |           • Analyze(Context) ∧ ¬UnderstandFullHumanIntent
|   |
|   |-- Hippocampus
|   |   • Buffer(ShortTermMemory) ∧ ¬Store(LongTermData)
|   |   |
|   |   |-- Markdown Files
|   |       • Organize(TemporaryNotes) ∧ ¬Persist(PermanentKnowledge)
|   |       • Structure(QuickThoughts) ∧ ¬Formalize(CompleteDocumentation)
|   |
|   |-- Basal Ganglia
|       • Learn(Procedures) ∧ ¬Process(DeclarativeKnowledge)
`;


This folder contains AI-assisted development tools for improving code quality and consistency.

## How to use?

- Click on the "Use this template" button
- Create a `.ai` folder in your repository
- Move the content of this template into the `.ai` folder

## Codex

### Files

- [codex.md](codex/codex.md): AI Codex - A repository of learnings and errors.
- [learn.md](codex/learn.md): AI Learn - Protocol for updating the AI Codex.

### Usage

1. Review the Codex: [codex.md](codex/codex.md) (silent load, no output)
2. Update the Codex: [learn.md](codex/learn.md)

### Important Note

[codex.md](codex/codex.md) should be added to the context of every chat:

- For regular chats: Use the plus button at the top of the chat to add the file.
- For Composers: Add the file to a Project Composer so all Composers created in that project will automatically have the file.

### Structure

The [Codex](codex/codex.md) is divided into two main sections:

1. Errors: Mistakes made and how to prevent them.
2. Learnings: Insights gained and their applications.

Each entry includes context, description, correction/application, and related entries.

## Session

- [start-session.md](session/start-session.md): Initiates a new AI session
- [end-session.md](session/end-session.md): Concludes the current AI session

Session files create a "memory layer" for the AI across multiple interactions, enabling contextual awareness and adaptive assistance.

Key benefits:

- Maintains project context between sessions
- Reduces repetition of project details
- Provides consistent guidance aligned with project direction

Usage:

1. End a session: Use [@end-session](session/end-session.md) command
2. Start a new session: Use [@start-session](session/start-session.md) command

The AI will generate and read status files in [status](status) to maintain project continuity.

## Blueprints

Blueprints are comprehensive guides for implementing specific technical architectures or project setups. They provide step-by-step instructions for installing, configuring, and integrating various technologies to create a functional foundation for your project.

- [supabase-drizzle-actions.md](blueprints/supabase-drizzle-actions.md): Backend architecture with Supabase, Drizzle ORM, and Server Actions
- [flux-with-replicate.md](blueprints/flux-with-replicate.md): Image generation using Flux and Replicate

## Libraries

- [lib](lib): Contains documentation examples for library usage

## Contributing

This is an open-source template. Contributions are welcome! Please add a changelog entry with your contribution.

## Note

This system is designed for AI consumption. Entries should prioritize precision and relevance over human readability
