<!-- BEGIN:nextjs-agent-rules -->
# devapp

A developer knowlegde hub for snippets, commands, prompts, notes, files, images, links and custom types.

## Context Files

Read the following to get the full context of the project:

- @memory-bank/project-overview.md
- @memory-bank/coding-standards.md
- @memory-bank/ai-interaction.md
- @memory-bank/current-feature.md

## Commands

- **Dev server**: `npm run dev` (runs on <http://localhost:3000>)
- **Build**: `npm run build`
- **Production server**: `npm run start`
- **Lint**: `npm run lint`

## Architecture

This is a Next.js application using:

- **App Router**: with files in the `src/app/`
- **React**: with the React compiler enabled (`reactCompiler: true` in the next.config.ts)
- **TailWind CSS**: via PostCSS
- **TypeScript**: with strict mode and `@/*` path alias mapping to `./src/*`

<!-- END:nextjs-agent-rules -->
