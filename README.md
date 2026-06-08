# hu.ad-best
Research on AI tools for advertising and film production.
AI-assisted workflows that help small, budget-constrained creators turn visual references into actionable production plans — and understand why a trend works.

Overview
hu.ad-best is an open-source research project that documents and builds AI tools for advertising and film production. It is maintained by a working advertising creative who aims toward filmmaking, and it focuses on a single hard problem: delivering high-quality video on a limited budget.
The project provides two core AI-assisted tools.
Core Features
1. Reference Decomposition Engine
Analyzes a target video reference and breaks it down into editable, deployable production elements — shot composition, color/grade direction, pacing, lighting, sound, and editing rhythm. Instead of leaving "I want it to feel like this" as a vague brief, it produces a structured, modifiable checklist of components that a creator can adapt to the video they actually want to make.

Input: a reference video / link / description of a target look
Output: a structured, editable breakdown of production elements
Use: turn intuition into a concrete pre-production plan a small crew can execute

2. Trend Appeal Analysis
Analyzes current video trends and explains why they intuitively appeal to MZ-generation audiences — across cultural, national, and artistic dimensions. Rather than only describing what is trending, it articulates the underlying drivers of appeal so creators can apply the principle, not just copy the surface.

Input: a trend, format, or reference clip
Output: a cultural / national / artistic read on why it resonates
Use: ground creative decisions in why it works, not guesswork

How to Use

Clone or download this repository.
Set your OpenAI API key as an environment variable (see .env.example).
Run the tool with your reference input.
Review the structured breakdown / trend analysis and adapt it to your project.


Detailed setup and command examples are in the examples/ directory.

Roadmap

 Treatment & storyboard draft generation
 Shooting schedule & budget simulation
 Usage guides and templates for non-technical creators

License
MIT License
