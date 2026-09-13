---
name: web-design
description: Design and build exceptional websites and web apps with strong product thinking, visual craft, and intentional interaction. Understand the product and user before designing, inspect the existing codebase and brand, establish a visual direction before implementation when needed, and reject generic AI-generated design patterns.
---

# Web Design

Design interfaces that feel **purposeful, clear, refined, and specific to the product**.

Do not design by assembling attractive components.

Design by understanding:

- what the product is for
- who uses it
- what they are trying to accomplish
- what matters most
- what should stay out of their way
- what makes this product different

The goal is not maximum visual novelty.

The goal is:

> **Make the important thing easier, clearer, and more satisfying to use.**

---

# Design Philosophy

Use these principles as the hierarchy for design decisions:

1. **Purpose** make the product meaningful.
2. **Agency** help users act without getting in their way.
3. **Familiarity** build on patterns people already understand.
4. **Flexibility** adapt to different contexts and needs.
5. **Simplicity** remove everything unnecessary.
6. **Craft** care about every detail.
7. **Delight** make the experience feel human.

These principles should influence product structure, content, layout, interaction, motion, accessibility, and visual design.

---

# 1. Understand Before Designing

**Never start by generating a hero section.**

First inspect the project and understand its context.

Look at:

- Framework
- Routes
- Existing pages
- Components
- Styling solution
- Design tokens
- Fonts
- Theme system
- Animation utilities
- Existing assets
- Images
- Logos
- Icons
- Existing copy
- Responsive implementation
- Component conventions

Then determine:

### What is this product?

Understand what it does in concrete terms.

### Why does it exist?

What problem does it solve?

### Who is using it?

Understand their technical familiarity, expectations, and environment.

### What is the primary user goal?

What should the user be able to accomplish quickly?

### What is the most important thing on this page?

There should be a clear answer.

### What makes the product distinctive?

The design should reflect this when appropriate.

---

# 2. Gather Missing Context

Ask the user questions when the answer could materially change the design.

Do not ask questions merely because information is technically missing.

Useful questions include:

### Product

- What is the project?
- What is this page supposed to accomplish?
- Who is the intended audience?
- What is the primary action?

### Visual direction

- Should the experience feel calm, technical, editorial, playful, premium, expressive, utilitarian, etc.?
- Are there reference websites or products?
- Are there styles the user explicitly dislikes?

### Existing design

- What styling solution does the project use?
- Is there an existing design system?
- What component library is already installed?
- Are there existing design tokens?

### Motion

Ask explicitly about animation preference:

- Still
- Subtle
- Interactive
- Expressive

Also understand whether motion should be used for:

- transitions
- feedback
- navigation
- storytelling
- decoration

Default to subtle, purposeful motion when no preference is provided.

### Brand

Ask whether the project has:

- Logo
- Brand colors
- Typography
- Design guidelines
- Illustrations
- Product screenshots
- Iconography
- Other visual assets

Do not invent important brand decisions when the user has not provided enough information.

---

# 3. If Branding Exists, Establish the Design System First

When the user provides a logo, brand identity, or strong visual direction:

**Do not immediately build the full website.**

First create a small representative design-system page.

It should demonstrate the proposed visual language in context.

Include:

- Logo
- Primary and secondary colors
- Backgrounds
- Heading hierarchy
- Body typography
- Labels
- Buttons
- Inputs
- Links
- Surfaces
- Borders
- Selected states
- Example content
- Example layout
- Motion behavior

Do not present a giant token table.

The user should be able to **feel the design system**, not read its implementation details.

---

# 4. Present Multiple Design Directions

Create 2–4 genuinely different design directions.

The differences must be structural, not superficial.

Vary things like:

- Typography
- Composition
- Grid
- Density
- Whitespace
- Surface treatment
- Navigation
- Content hierarchy
- Interaction style
- Motion

Do not create:

> version A = blue
> version B = purple
> version C = green

Instead create genuinely different interpretations of the same brand.

Examples:

### Editorial

Strong typography, asymmetric composition, deliberate whitespace, clear reading rhythm.

### Product

Focused hierarchy, efficient layouts, compact interactions, clear task completion.

### Technical

Precise grid, denser information, restrained typography, system-oriented visual language.

### Expressive

Stronger art direction, more personality, controlled motion, distinctive composition.

All directions must remain faithful to the brand.

---

# 5. Let the User Select the Direction

Show the design-system previews before implementing the complete website.

Ask the user to select a direction when the decision is significant.

Once selected, lock in:

- Typography
- Color system
- Spacing
- Grid
- Surface language
- Control language
- Motion language
- Image treatment

Do not allow the full implementation to slowly drift into generic defaults.

If the user does not select a direction, choose the strongest one based on the product and continue.

---

# 6. Start With Purpose

Every page should answer:

> **Why does this page exist?**

Do not design sections simply because similar websites contain them.

For each major section, determine:

- What user need does this address?
- What information does it provide?
- What action does it enable?
- Why does it belong here?

If no useful answer exists, remove the section.

Avoid designing:

```text
Hero
Features
Benefits
Testimonials
Logos
Pricing
CTA
```

just because it is a familiar landing-page structure.

The structure should emerge from the product.

This should emphasize focusing on what matters most and keeping the experience centered on the product's actual use.

---

# 7. Protect User Agency

The interface exists to help the user accomplish something.

It should not constantly demand attention.

Users should understand:

- What they can do
- What is happening
- What changed
- What went wrong
- How to recover
- How to leave or undo an action

Prefer direct access to the main task.

Avoid unnecessary:

- onboarding walls
- forced flows
- popups
- confirmations
- modals
- interruptions
- decorative interaction

when they do not improve the experience.

Make mistakes recoverable.

Use clear feedback for:

- loading
- success
- failure
- changes
- disabled states
- destructive actions

This follows the principle of emphasis on agency, staying out of the way, exploration, recovery, and clear feedback.

---

# 8. Use Familiarity Without Becoming Generic

Use established interaction patterns when they help users understand the interface immediately.

Do not reinvent:

- buttons
- navigation
- forms
- checkboxes
- tabs
- dialogs
- menus
- standard interactions

for the sake of originality.

Innovation belongs where it improves the product.

Once a pattern is established:

**keep it consistent.**

A button should not behave differently in another section without a strong reason.

A selected state should look and behave consistently.

A navigation pattern should not change between pages.

This should emphasize familiarity, consistency, and predictable feedback.

---

# 9. Simplicity Is Not Minimalism

Do not confuse simplicity with having fewer visual elements.

A complex product can have a simple experience.

Simplicity means:

> **Only show what helps the user at that moment.**

Remove unnecessary:

- controls
- copy
- decoration
- layers
- navigation
- choices
- states
- visual noise

But keep anything necessary for:

- understanding
- trust
- accessibility
- orientation
- recovery
- decision-making

This should describe simplicity as including what is necessary, staying concise, and establishing clear hierarchy.

---

# 10. Hierarchy Before Decoration

When something does not feel visually strong, do not immediately add:

- gradients
- shadows
- borders
- color
- animation
- illustrations

First improve:

1. Importance
2. Position
3. Size
4. Typography
5. Spacing
6. Alignment
7. Contrast

A strong hierarchy should survive even when decorative effects are removed.

---

# 11. Typography Is Structure

Typography is not decoration.

Use it to communicate:

- importance
- grouping
- sequence
- tone
- hierarchy

Establish consistent roles for:

- Display
- Page title
- Section title
- Body
- Label
- Metadata
- Code

Avoid arbitrary typography throughout the page.

Do not:

- use huge headings just to look modern
- make body text tiny to fit more content
- overuse bold
- use random font sizes
- add unnecessary letter spacing
- use all caps everywhere

Make text easy to read before making it impressive.

---

# 12. Layout Should Express Relationships

A layout should communicate how things relate.

Use:

- Alignment
- Proximity
- Grouping
- Scale
- Grid
- Whitespace

to show relationships before relying on borders and cards.

Elements that belong together should feel connected.

Elements that are unrelated should not accidentally appear connected.

Every major visual relationship should have a reason.

---

# 13. Design the First Viewport Carefully

The first viewport is not a billboard.

It should immediately establish:

- what this is
- why it matters
- what the user can do
- what deserves attention

Do not sacrifice clarity for dramatic hero composition.

The user should understand the page without scrolling merely to discover its purpose.

---

# 14. Composition Over Templates

Before coding, identify the obvious layout this type of website would normally receive.

Then challenge it.

Ask:

> Is this structure actually the best representation of this product?

Possible compositions include:

- Editorial
- Tool-first
- Product-first
- Comparison
- Narrative
- Dashboard
- Dense utility
- Split-screen
- Asymmetric
- Full-bleed
- Step-based
- Interactive

Choose based on the user task.

Do not use a fixed template across unrelated products.

---

# 15. Cards Must Earn Their Place

Do not put every piece of content into a card.

A card should communicate a meaningful boundary.

Use one when it represents:

- a distinct object
- a selectable item
- a separate action
- a meaningful grouping
- a state
- a surface requiring contrast

Avoid:

```text
Card
  Card
    Card
      content
```

Prefer whitespace and hierarchy when they communicate the relationship clearly.

---

# 16. Color Should Have Meaning

Use brand colors intentionally.

Color may communicate:

- brand identity
- interactive state
- system status
- data
- emphasis

Do not color every important element.

Avoid:

- random gradients
- gradient text
- glowing backgrounds
- decorative neon
- color blobs
- excessive accent colors

unless the brand genuinely supports them.

A restrained palette with excellent hierarchy is stronger than a colorful interface with weak hierarchy.

---

# 17. Motion Should Preserve Context

Motion is useful when it helps users understand change.

Good motion:

- connects one state to another
- confirms an action
- establishes spatial relationships
- gives feedback
- preserves context during transitions
- makes interaction easier to understand

Bad motion:

- exists to make the website look "AI-generated but cool"
- delays access to content
- distracts from the task
- repeatedly animates while the user is reading
- adds spectacle without meaning

Avoid:

- parallax by default
- scroll reveal on every section
- floating objects
- fake typing
- cursor effects
- excessive spring physics
- bounce
- auto-scrolling marquees
- decorative particles

Support reduced motion.

This should connect flexibility with preserving context and using natural animations to ease transitions.

---

# 18. Delight Through Craft, Not Decoration

Delight should emerge from the experience.

Look for moments where the product can feel:

- effortless
- satisfying
- responsive
- thoughtful
- reassuring
- playful when appropriate

Examples:

- An action responds immediately.
- A transition preserves spatial context.
- An empty state actually helps.
- An error explains what to do next.
- A successful action gives useful feedback.
- A complex task becomes surprisingly simple.

Do not add:

- confetti
- jokes
- random Easter eggs
- gratuitous animation
- gimmicky interactions

unless they genuinely fit the product.

Delight should be created by design, not decoration.

---

# 19. Accessibility Is Part of Design Quality

Design for different:

- abilities
- devices
- screen sizes
- input methods
- preferences
- contexts

Support:

- Keyboard
- Touch
- Mouse
- Screen readers
- Reduced motion
- Zoom
- Narrow screens

Do not treat accessibility as a final compliance pass.

It should influence the design from the beginning.

Flexibility is about designing for everyone and supporting multiple contexts and input methods.

---

# 20. Responsive Design Preserves the Experience

Do not simply shrink desktop.

Preserve the user's:

- context
- hierarchy
- task
- relationships

Change the composition when necessary.

For example:

Desktop:

```text
[content] [supporting content]
```

Mobile may become:

```text
[content]

[supporting content]
```

or:

```text
[primary action]

[secondary actions]
```

Do not preserve desktop geometry at the cost of usability.

---

# 21. Content and Interface Are One System

Good UI cannot rescue unclear writing.

Write content that is:

- specific
- concise
- useful
- understandable

Headings should tell the reader something.

Buttons should describe actions.

Labels should describe controls.

Error messages should explain what happened and what to do next.

Remove marketing filler.

Avoid:

> Unlock next-generation productivity.

Prefer:

> Review every pull request in one place.

Never invent:

- testimonials
- customers
- metrics
- capabilities
- claims
- quotes

---

# 22. Avoid AI-Slop

Before shipping, actively identify generic generated-design patterns.

### Hard reject by default

- Generic centered hero
- Purple/blue gradient background
- Gradient text
- Huge rounded cards everywhere
- Glassmorphism without purpose
- Random blobs
- Decorative 3D objects
- Excessive pills
- Icon circles for every feature
- Every section using the same card grid
- Three identical feature columns by default
- Excessive floating elements
- Unnecessary shadows
- Excessive borders
- Decorative illustrations
- Scroll animations everywhere
- Fake social proof
- Fake statistics
- Generic startup copy
- Repetitive section structures

This is not a ban on these techniques.

Use them when the product genuinely calls for them.

The question is always:

> **Does this serve the product or is it filling visual space?**

---

# 23. Avoid the "Design System Demo" Look

A polished website should not look like a collection of components.

Avoid making the page feel like:

```text
Button
Card
Card
Badge
Card
Stats
Card
CTA
```

Components are implementation details.

The user experiences a composition.

Think in:

- relationships
- hierarchy
- flows
- moments
- tasks

not isolated components.

---

# 24. Craft Every Detail

Quality is often determined by small decisions.

Inspect:

- line breaks
- spacing
- alignment
- hover states
- focus states
- disabled states
- loading states
- empty states
- error states
- transitions
- mobile behavior
- text truncation
- input behavior
- cursor placement
- icon alignment
- border consistency
- image cropping

Do not stop when the page "looks good."

Refine until the rough edges disappear.

Craft is about caring for every detail, iteration, refinement, and maintaining quality after shipping.

---

# 25. Iterate Instead of Committing Too Early

Do not become attached to the first layout.

When an important page is ambiguous, explore at least two materially different compositions before settling on one.

Compare:

- What is easier to understand?
- What feels more natural?
- What emphasizes the right thing?
- What requires less explanation?
- What has less visual noise?
- What better reflects the product?

Choose based on the user, not personal preference alone.

---

# 26. Render and Inspect

After implementation, inspect the actual rendered result.

Review:

### Purpose

Can someone understand what this page is for?

### Agency

Can they accomplish the primary task quickly?

### Familiarity

Do interactions behave predictably?

### Simplicity

Can anything be removed without harming the experience?

### Flexibility

Does it work across screen sizes and input methods?

### Craft

Are the small details polished?

### Delight

Is there anything unexpectedly thoughtful?

---

# 27. The 5-Question Review

Before shipping, ask:

### 1. What is the user here to do?

If the answer is unclear, fix the hierarchy.

### 2. What is competing for their attention?

Remove or quiet everything that should be secondary.

### 3. What can disappear?

Remove anything that does not earn its place.

### 4. What feels generic?

Replace template-driven decisions with product-specific ones.

### 5. What feels unfinished?

Fix the smallest details that break the illusion of quality.

---

# 28. Final Design Test

Use these tests together.

### Squint test

Blur your attention.

Can you still see:

- the primary focal point
- the hierarchy
- the main action
- the reading path?

### Text removal test

Ignore all copy.

Does the layout still communicate relationships and importance?

### Decoration removal test

Remove:

- gradients
- shadows
- borders
- animations
- icons

Does the interface still work?

If not, the underlying hierarchy is probably weak.

### Genericity test

Ask:

> Could this design belong to 1,000 unrelated companies?

If yes, make the composition more specific to the product.

### Friction test

Ask:

> What unnecessary work is the user doing because of this design?

Remove it.

---

# 29. Decision Hierarchy

When design decisions conflict, use this order:

1. User goal
2. Product purpose
3. Clarity
4. User agency
5. Information hierarchy
6. Familiarity and consistency
7. Accessibility
8. Brand
9. Interaction
10. Motion
11. Decorative detail

Never sacrifice usability and clarity to make a page more visually impressive.

---

# 30. Default Behavior

When the project provides an existing design system:

**Use it.**

When a brand identity exists:

**Study it and establish a design-system preview before building the full experience.**

When the user has not provided visual direction:

**Infer a restrained, product-appropriate system from the product itself.**

When animation preference is unknown:

**Use subtle, purposeful motion.**

When the product feels visually empty:

**Improve hierarchy and composition before adding decoration.**

When the interface feels boring:

**Improve typography, proportions, composition, and interaction before adding effects.**

When requirements are unclear:

**Ask only the questions that can materially change the design.**

When something looks impressive but makes the product harder to use:

**Remove it.**

---

# Final Standard

Do not aim for:

> "A beautiful modern website."

Aim for:

> **A product experience that feels obvious, intentional, refined, and made specifically for its users.**

The best design should make the user think:

> **"Of course it works this way."**

not:

> **"Wow, that's a cool animation."**

Visual sophistication should be the result of **purpose, simplicity, consistency, flexibility, craft, and care**.

Not decoration.
