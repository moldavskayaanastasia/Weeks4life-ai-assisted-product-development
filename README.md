# Weeks4life-ai-assisted-product-development

## Overview

This project explores AI-assisted product development using the concept of "Weeks4life", a visual representation of human life where each square represents one week.

The application was iteratively designed and refined through multiple interactions with the AI assistant Claude.

## Goal

Create a visually appealing interactive application that:

- Displays a grid representing weeks in a human life (up to 100 years)
- Allows users to add life events to specific weeks
- Supports event ranges and date-based entries
- Uses color-coded visualization for different types of life events
- Provides zoom and navigation features

## Tools

Claude (AI assistant)
Prompt-based interaction
Manual evaluation and testing

## Key Features Designed

- Weekly life grid visualization
- Event creation and editing
- Date-based event input
- Multi-week selection
- Color-coded event categories
- Event list and quick editing
- Grid zoom functionality
- Automatic birthday marking

## Development Process

The application was developed through iterative prompt engineering:

1. Initial concept and grid visualization
2. UI improvements and design refinement
3. Feature expansion (event ranges, event list)
4. Debugging and bug fixing
5. Navigation improvements
6. Testing of birthday date calculations

## Key Challenge

A persistent bug occurred when generating recurring birthday events. Because the application represents life using fixed 52-week years while real years contain ~52.14 weeks, birthday dates gradually shifted over time.

Multiple approaches were tested to solve the issue.

## Lessons Learned

- AI can rapidly generate functional UI prototypes
- Iterative prompting is required to refine complex behavior
- Some logical problems require deeper architectural solutions
- Clear problem statements improve AI output quality
