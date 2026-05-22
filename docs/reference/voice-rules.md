---
title: Voice rules
description: The writing constraints for every page in the Goshen wiki. Christofuturist baseline; hot opener and cooler operator body on chapters.
---

# Voice rules
*The writing constraints for every page in the Goshen wiki. Christofuturist baseline; hot opener and cooler operator body on chapters.*

---

## Hard rules

These are non-negotiable. The `goshen-field-notes` skill greps for violations before every commit.

- **No em dashes.** Use periods, commas, parens, or colons.
- **No "not X but Y" inversions.** Rephrase positively.
- **Capital-C Christofuturist** always.
- **No `Co-Authored-By` lines in commit messages.**

## Soft rules

- **Hot opener on every chapter, concept, and playbook page.** A few sentences at the top that frame why this matters in the flood era. Scripture allowed inline. Declarations encouraged.
- **Cooler operator body underneath.** Once the why is set, the how is prescriptive, specific, named (frameworks, models, playbooks), and actionable.
- **Cross-link to FaithWalk OS for upstream principles.** Never re-explain Ark Village, Formation Crisis, Elevation Centers, Kingdom Enterprises, Divine Principle First Design, etc. The Goshen wiki owns the applied layer; FaithWalk OS owns the principles.
- **Compression.** A clear sentence beats a clear paragraph. Three named tradeoffs beat ten generic ones.

## Page anatomy

Every content page should follow this shape:

```
---
title: <Title>
description: <One-sentence description>
---

# <Title>
*<Italic one-line definition>*

---

## <H2 section 1>
<prose>

## <H2 section 2>
<prose>

## Further Reading
- <cross-links>

## Sources
- <links to inspiration files that fed this page>
```

The `## Sources` section is required for any page born from a `goshen-field-notes` run, optional for deliberate authoring.
