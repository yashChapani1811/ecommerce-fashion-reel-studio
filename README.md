# E-Commerce Fashion Reel Studio

![E-Commerce Fashion Reel Studio icon](assets/reel-studio.svg)

**Reference-accurate fashion Reel planning for e-commerce sellers.**

**Publisher:** Yash Chapani  
**Category:** Creativity  
**Current specialization:** Indian sarees  
**Status:** Private ChatGPT plugin; preparing public directory submission.

[Open the ChatGPT plugin](https://chatgpt.com/plugins/plugins_6afc362302088191863fd7aa8500c903) · [Support](SUPPORT.md) · [Privacy policy draft](PRIVACY_POLICY.md) · [Terms draft](TERMS_OF_SERVICE.md)

## What it does

E-Commerce Fashion Reel Studio helps fashion sellers plan cinematic, photorealistic Instagram Reels from photographs of the *actual product*. The current workflow specializes in Indian sarees.

Upload **four or five photographs of the same saree** to receive:

1. A **reference ledger** mapping observed colors, motifs, fabric appearance, border, pallu and blouse details to source photographs.
2. One selected Reel concept with a product-accurate storyboard.
3. A fixed **adult fashion-model identity** and five model-reference image prompts.
4. Standalone **Google Flow prompts** for each planned 10-second video phase, with 9:16 framing by default.
5. Phase-to-phase **continuity handoffs** for pose, camera, lighting, location, drape and movement.
6. Editing instructions and a quality-control checklist.

The reference notation keeps source evidence and planned assets separate: **SR** (saree reference photo), **MR** (model reference), **SC** (scene), **PH** (video phase), and **HF** (handoff).

## Example prompt

> Here are five product photos of the same saree. Create a reference-locked 30-second Instagram Reel plan with one best-fit concept, consistent adult model, five model-reference prompts, three 10-second Google Flow prompts, phase handoff notes, and a final editing checklist. Do not invent any unverified saree details.

Explore [example prompts and expected outputs](examples/EXAMPLE_PROMPTS.md).

## Important limitations

- **Planning and prompts only:** The plugin does **not** render images or videos, call Google Flow, edit clips, upload videos, or post to Instagram.
- It cannot guarantee pixel-perfect model consistency or exact garment details from generative video systems. Check all generated footage against the original product references before use.
- If an image does not show a detail, the plugin should mark that detail **unverified**, rather than inventing it.
- Use only product/model photographs you have permission to use.

## Help and publishing information

- [Support and common questions](SUPPORT.md)
- [Privacy policy — draft awaiting publisher approval](PRIVACY_POLICY.md)
- [Terms of service — draft awaiting publisher approval](TERMS_OF_SERVICE.md)
- For questions about the plugin's behavior, [open a GitHub support issue](https://github.com/yashChapani1811/ecommerce-fashion-reel-studio/issues/new/choose). **Do not post private photos, personal information or credentials in public issues.**

**Publisher:** Yash Chapani. This repository provides public documentation and help pages for the ChatGPT plugin; it is not a separate video-generation service.
