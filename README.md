# StableDiffusionQR
Examples of stable diffusion prompts and workflows applied to QR code images

Here is a collection of prompts and workflows sorted by category

General information
---

Stack: [Automous1111](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

Model selected: revAnimated v122

ControlNet: v1.1.219

The **Negative prompt** is being reused throughout the the project and is then not duplicated between the examples. 

All images produced have the following common img2img parameters:

**General settings**:

Stable diffusion:

| Setting | Value |
| ------- | ----- |
| `Image dimensions` | 768 x 768 |
| `CFG Scale` | 7 |
| `Iterations` | 20 |
| `Denoising strength` | 1 |

ControlNet:

| Setting | Value |
| ------- | ----- |
| `Preprocessor type` | Tile |
| `Model` | control_v11f1e_sd15_tile |
| `Pixel Perfect` | On |
| `Starting Control Step` | 0.23 |
| `Ending Control Step` | 1 |
| `Control Weigth` | [0.55..0.85] |
| `Control Mode` | Balanced |

Categories, Outputs and Prompts
---

## Architecture

### House on hill

Prompt
```
House on a hill, modern architecture, house concept, sunset, morning, stary sky, rtx lighting, cloudy sky
```

Negative Prompt
```
(worst quality:2), (low quality:2), (normal quality:2), lowres, normal quality, ((monochrome)), ((grayscale)), (worst quality, low quality:1.2), watermark, username,lowres, text, error, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, single color, (((duplicate))),(((blurry))), (((blur)))
```

Outputs

|Output 1             |
|-------------------------|
|![00159-1679541580](https://github.com/UnitagEngineering/StableDiffusionQR/assets/73647904/e707d9b2-a068-4559-8785-0f93f64d95b6)| |



### House with vegetation (Credits to redditor for prompt)

Prompt
```
A photo-realistic rendering of a 2 story house with greenery, pool, (Botanical:1.5), (Photorealistic:1.3), (Highly detailed:1.2), (Natural light:1.2), art inspired by Architectural Digest, Vogue Living, and Elle Decor
```

Outputs

|Output 1             | Output 2 | Output 3 |
|-------------------------|-------------------------|-------------------------|
| ![00121-2481559407](https://github.com/UnitagEngineering/StableDiffusionQR/assets/73647904/644c17e5-354b-4f4c-95db-a651722fd0b0)| ![00123-1829896796](https://github.com/UnitagEngineering/StableDiffusionQR/assets/73647904/51245c67-39e6-4d22-8944-dbc99cace46e) | ![00155-2345936299](https://github.com/UnitagEngineering/StableDiffusionQR/assets/73647904/beae0c59-9002-49b2-99c4-663856dea26b) |

---

## Entertainment

### Retro Gaming

Prompt
```
pacman, retro 80s, nintendo, color, console
```

### Super heroes

Prompt
```
super hero, gaming, monster, flying, above sky, in space
```

### Music

Prompt
```
guitar, drums, amp, piano, bass, brass
```

---

## Automobile

Prompt
```
cars, german cars, neon, at night, front shot, angled
```

---

## Marketing

### Cosmetics

Prompt
```
beauty products, shampoo bottle, make up, lotion, cream, bird view
```

### Holidays

Prompt
```
cruise, water, beach, sun, boat, sunny, bright sky, natural lightinhg
```

