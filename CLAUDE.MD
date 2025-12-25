# CLAUDE.MD - AI Assistant Guide for Adversarial Creativity

## Project Overview

**Adversarial Creativity** is a prompt engineering methodology framework for creative collaboration with AI systems through structured personas, wildcard techniques, and recursive refinement. The primary implementation is designed for Google NotebookLM but the principles can be adapted to other AI systems.

### Core Concept

This framework transforms generative AI from a simple information-retrieval tool into a creative partner by working WITH system constraints (like RAG grounding mechanisms) rather than against them. It enables AI to move beyond summarization into novel creative synthesis.

## Repository Structure

```
/
├── README.md                          # Primary methodology documentation
├── LICENSE                            # Project license
├── CLAUDE.MD                          # This file - AI assistant guide
├── personas/                          # Structured persona templates
│   └── recursive-chef/
│       └── MonFrierFranky_v1.md      # Example: Recursive Chef persona
├── methodology/                       # Detailed methodology components
│   └── wildcard-technique.md         # Wildcard technique documentation
└── examples/                          # Practical implementation examples
    ├── README.md                      # Examples overview
    ├── contextual-enhanccement/      # Enhancement mode examples
    │   └── template.md
    └── pure-generation/              # Pure generation mode examples
        ├── logo-design-abstract/
        └── RecursiveChef/
            └── Slides/               # Generated recipe presentations (PDFs)
```

## The Three Foundational Pillars

### 1. Persona Engineering
- Crafting structured prompts that enable AI to adopt specific creative roles
- Acts as both instruction set and quality control engine
- Contains clear identity, methodology, creative language, and output specifications
- **Key**: Use creative trigger words (synthesize, elevate, imagine, invent)
- **Avoid**: Grounding language (based on sources, according to documents)

### 2. The Wildcard Technique
- Strategic use of minimal source documents (often just `*wildcard`, `*TBD`, or `*placeholder`)
- Bypasses default retrieval-based behavior in RAG systems
- Signals permission for creative generation vs. summarization
- Acts as a "permission slip" for the AI to engage creative capabilities

### 3. Recursive Refinement Process
- Three-step internal process: Initial Synthesis → Recursive Analysis → Elegant Delivery
- Mimics how human experts iterate on creative work
- Built-in loop of self-evaluation and enhancement
- Transforms raw concepts into polished, professional-grade results

## Three Operational Modes

| Mode | Input | Persona Role | Use Case |
|------|-------|--------------|----------|
| **Pure Generation** | Wildcard only | Complete creative synthesis | Entirely novel content from scratch |
| **Contextual Enhancement** | Real documents + Persona | Creative elevation | Refining/transforming existing content |
| **Hybrid Synthesis** | Minimal sources + prompts + Persona | Guided creative expansion | Structured novel content with constraints |

## Implementation Workflow (5 Steps)

1. **Define Project & Prerequisites**
   - Identify use case (novel concepts, prototyping, rapid ideation)
   - Ensure access to NotebookLM or similar platform

2. **Engineer Creative Persona**
   - Define clear identity and expertise
   - Structure the recursive refinement methodology
   - Incorporate creative trigger words
   - Specify exact output format and quality standards

3. **Prepare Source Environment**
   - Create new notebook
   - Upload wildcard source file
   - Paste persona as custom instructions (NOT as source)
   - Critical: Persona should NOT be included as source document

4. **Execute Generation**
   - Use generation features (Audio/Video Overview, Infographic, Slide Deck)
   - AI interprets wildcard as permission for creativity
   - Observes three-step recursive refinement

5. **Evaluate & Iterate**
   - Measure: Novelty, Coherence, Utility, Creativity, Reproducibility
   - Refine persona if outputs are weak or inconsistent

## Key Success Criteria

When evaluating outputs from this framework, assess:
- **Novelty**: Content is new and not easily found in existing data
- **Coherence**: Output is logically consistent
- **Utility**: Has practical value for intended purpose
- **Creativity**: Demonstrates unexpected connections or approaches
- **Reproducibility**: Can achieve similar quality on subsequent attempts

## Troubleshooting Guide

**Generic/Wikipedia-like outputs**
→ Add more creative trigger words, remove grounding language

**Inconsistent output format**
→ Strengthen "Output Format" and "Elegant Delivery" sections in persona

**"Not enough source material" error**
→ Ensure persona prompt + wildcard are both uploaded as distinct sources

**Identical recursive refinement steps**
→ Make methodology step descriptions more distinct with unique active verbs

## Example Persona: Mon Frier Franky (Recursive Chef)

Located in `/personas/recursive-chef/MonFrierFranky_v1.md`, this persona demonstrates:
- Clear identity (trained at Cordon Blue, CIA, worked with renowned chefs)
- Recursive methodology (considers recipes through 3 recursive loops using Markov distributions)
- Creative language (synthesize, elevate, surpass expectations)
- Specific output format (visual descriptions, tone tags, full recipe with measurements)
- Meta-awareness (meta-cognitive, suggests persona improvements)

## Working with This Repository

### When Contributing
- Place new personas in `/personas/` organized by category
- Document examples in `/examples/` with mode type (pure-generation, contextual-enhancement, hybrid-synthesis)
- Update methodology documentation in `/methodology/`
- Maintain clear README files in subdirectories

### When Using This Framework
1. Start with README.md for full methodology understanding
2. Study example personas in `/personas/`
3. Review examples in `/examples/` for your desired mode
4. Adapt or create new persona based on your creative goals
5. Test and iterate following the 5-step workflow

### Advanced Techniques
- **Dual-Mode Personas**: Switch between generation and enhancement automatically
- **Constraint-Based Creativity**: Add specific limitations to focus generative energy
- **Nested Personas**: Primary persona with multiple sub-personas for varied tasks

## Ethical Considerations

1. **Transparency**: Disclose AI-generated content, document methodology
2. **Responsible Use**: Verify outputs before real-world application
3. **Attribution**: Credit AI system and methodologies used
4. **Limitations**: NOT appropriate for medical, legal, or safety-critical domains

## Primary Use Cases

Ideal for:
- Generating novel concepts (recipes, designs, products)
- Prototyping ideas with minimal input
- Rapid content ideation
- Creating diverse variations on a theme
- Creative enhancement of existing content

NOT suitable for:
- Factual information retrieval
- Safety-critical applications
- Legal or medical advice
- Situations requiring verified accuracy

## Notes for AI Assistants

When working with this repository:
- This is a METHODOLOGY framework, not a code project
- Primary artifacts are markdown documentation and PDF examples
- Focus is on prompt engineering and AI collaboration techniques
- Repository demonstrates meta-level AI usage (AI about AI)
- Maintain the theoretical and practical balance in documentation
- Examples should be concrete and reproducible
- Preserve the playful, creative tone while maintaining rigor

## Getting Started

New to this framework? Follow this path:
1. Read the full README.md
2. Study the Mon Frier Franky persona example
3. Review the PDF examples in `/examples/pure-generation/RecursiveChef/Slides/`
4. Choose your operational mode
5. Draft your first persona
6. Test in NotebookLM
7. Iterate and refine

## Support & Contribution

This is an open methodology for creative AI collaboration. Experiment, document findings, and contribute to evolving practices in creative AI partnership.

---

*Last Updated: 2025-12-25*
*Repository: LanguageAsCode/Adversarial-Creativity*
