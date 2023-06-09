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
| `Preprocessor type` | tile |
| `Model` | tile |
| `Pixel Perfect` | Off |
| `Weigth` | [0.55..0.85] |

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

### House with vegetation (Credits to redditor for prompt)

Prompt
```
A photo-realistic rendering of a 2 story house with greenery, pool, (Botanical:1.5), (Photorealistic:1.3), (Highly detailed:1.2), (Natural light:1.2), art inspired by Architectural Digest, Vogue Living, and Elle Decor
```

### Futuristic

Prompt
```
professional architectural photography of a city, futuristic cityscape, neon, sharp focus, post-production, surreal, neon, cyber punk
```

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

