# FloraFauna-ai to floranodus

This repository contains the integration project combining FloraFauna-ai and floranodus-monorepo.

## Structure

This repository uses git submodules to include two separate projects:

- **FloraFauna-ai/**: The original FloraFauna-ai application for plant and animal identification
- **floranodus-monorepo/**: The floranodus monorepo containing the AI-native creative canvas application

## Getting Started

After cloning this repository, you'll need to initialize and update the submodules:

```bash
git submodule update --init --recursive
```

## Projects

### FloraFauna-ai
A React-based web application for identifying plants and animals using AI.

### floranodus-monorepo
A comprehensive monorepo containing:
- Figma plugin for design integration
- AI-native creative canvas application
- Backend services and infrastructure

## Development

Each submodule can be developed independently. Navigate to the respective directory and follow the development instructions in each project's README.

## Integration

This parent repository serves as the coordination point for integrating features between FloraFauna-ai and the floranodus ecosystem.
