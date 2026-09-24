# Awesome AI Image Prompts

A practical, no-hype guide to writing AI image prompts that actually work — tested across GPT Image, Midjourney, and other modern image models.

Most people prompt AI image tools with vague adjectives ("make it look cool") and get generic, obviously-AI results. This repo breaks down the actual structure that produces consistent, professional-looking output.

## The 5-Part Framework

Every strong prompt follows the same order:

**Subject → Setting → Lighting → Style → Exclusions**

### 1. Subject
Be specific about what the subject actually is — not "a candle" but "a matte black soy candle."

### 2. Setting
Where is it? What surface, background, or environment?

> "on a marble countertop" vs. no setting at all

### 3. Lighting
This is the single highest-impact addition. Name a light source and direction.

> "soft window light from the left" — real photos almost never have perfectly even, shadowless lighting, so naming a direction avoids the flat "AI look."

### 4. Style
Depth of field, composition, photographic or illustrative style.

> "shallow depth of field, minimal styling"

### 5. Exclusions
Tell the model what *not* to include. This one fixes more "why does this look off" problems than any other step.

> "no text, no watermark, no extra objects"

## Example

**Weak prompt:**
```
product photo of a candle
```

**Structured prompt:**
```
Photorealistic product shot of a matte black soy candle on a marble
countertop, soft window light from the left, shallow depth of field,
minimal styling, no text
```

Same subject, same model — the difference is entirely in the structure.

## Works Across Models

This framework isn't tied to one tool. The syntax varies slightly, but the underlying structure holds:

| Model | Notes |
|---|---|
| GPT Image | Takes the full structure in plain English |
| Midjourney | Same structure, plus `--ar` for aspect ratio and `--style` flags |
| Stable Diffusion / Flux | Same structure; negative prompts handle the "exclusions" step separately |
| DALL-E | Plain English, similar to GPT Image |

## More Prompt Categories

This repo covers the core framework. The full guide extends it across more categories:

- Product photography
- Social media / lifestyle content
- Branding and book covers
- **Character consistency across multiple images** (the hardest problem to solve without this structure)

**Free 15-prompt starter guide:** [kiyanibooks.gumroad.com/l/starterprompts](https://kiyanibooks.gumroad.com/l/starterprompts)

## Contributing

Found a prompt structure that works well? Open a pull request or an issue with your example — before/after comparisons are especially welcome.

## License

Free to use, adapt, and share. Attribution appreciated but not required.
