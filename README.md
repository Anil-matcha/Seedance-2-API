# Seedance 2.0 , Seedance 2.5 & Seedance 2 Mini API: Python Wrapper for ByteDance's AI Video Generator

[![Powered by MuAPI](https://img.shields.io/badge/Powered%20by-MuAPI-6366f1?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0tMSAxNHYtNGgtMnYtMmg0djZoLTJ6bTAtOFY2aDJ2MmgtMnoiLz48L3N2Zz4=)](https://muapi.ai?utm_source=github&utm_medium=badge&utm_campaign=seedance-2-api)


[![PyPI version](https://img.shields.io/pypi/v/seedance-2-api.svg)](https://pypi.org/project/seedance-2-api/)
[![GitHub stars](https://img.shields.io/github/stars/Anil-matcha/Seedance-2.0-API.svg)](https://github.com/Anil-matcha/Seedance-2.0-API/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/)

The most comprehensive Python wrapper for the **Seedance 2.0 API** , **Seedance 2.5 API** **Seedance 2 Mini API** (developed by ByteDance), delivered via [muapi.ai](https://muapi.ai?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api). Generate cinematic, high-fidelity AI videos from text prompts and static images — with industry-leading **realistic human face generation** — using the world's most advanced video generation model. Use Seedance 2.0 for maximum quality or **Seedance 2 Mini** for fast, affordable generation at a fraction of the cost.

Join the subreddit https://www.reddit.com/r/Seedance_2_API/ for discussions on using Seedance 2 api

Here is a comprehensive guide on using Seedance 2.0 API https://medium.com/@anilmatcha/seedance-2-0-api-complete-developer-guide-text-to-video-image-to-video-python-sdk-1479f5e5491f

> ✅ **Now Available: Seedance 2 Mini** — ByteDance's new lightweight model that outperforms Seedance 2.0 Fast at a fraction of the cost (pricing as low as ~$0.073/sec). Use `text_to_video_mini()` / `image_to_video_mini()` in the SDK, or hit the `/seedance-2-mini-t2v` and `/seedance-2-mini-i2v` endpoints directly. Discuss on [r/Seedance_2_API](https://www.reddit.com/r/Seedance_2_API/).
> - 🧪 Try **Seedance 2.0 Mini** now: [Image-to-Video Playground](https://muapi.ai/playground/seedance-2.0-mini-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api) · [Text-to-Video Playground](https://muapi.ai/playground/seedance-2.0-mini-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api)
> - 🚀 **Seedance 2.1** (~20% quality lift, 1080p, native audio) coming soon: [I2V Playground](https://muapi.ai/playground/seedance-2.1-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api) · [T2V Playground](https://muapi.ai/playground/seedance-2.1-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api)
> - 🌟 **Seedance 2.5** (native 4K, 30s clips, native audio, 30 images/10 videos/10 audio references) is **live now**: [I2V Playground](https://muapi.ai/playground/seedance-2.5-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api) · [T2V Playground](https://muapi.ai/playground/seedance-2.5-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api) · [📺 Video Tutorial](https://www.youtube.com/watch?v=Uszlw7H4VP4)

> 🌊 **Also explore these top AI video models:**
> - 🐎 [HappyHorse 1.0 API](https://github.com/Anil-matcha/HappyHorse-1.0-API) — Alibaba's #1 ranked model (1392 Elo I2V) with native 1080p & integrated audio
> - 🎬 [Veo 4 API](https://github.com/Anil-matcha/Veo-4-API) — Google DeepMind's native 4K model with audio, character consistency & camera controls

## 📺 Video Tutorial

[![How to Access Seedance 2.5 API (Step-by-Step Guide)](https://img.youtube.com/vi/Uszlw7H4VP4/maxresdefault.jpg)](https://www.youtube.com/watch?v=Uszlw7H4VP4)

**[How to Access Seedance 2.5 API (Step-by-Step Guide)](https://www.youtube.com/watch?v=Uszlw7H4VP4)** — a full walkthrough of getting an API key and making your first Seedance 2.5 call via [MuAPI](https://muapi.ai/seedance-2.5?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api).

## Related Projects

- [Seedance-2.5-API](https://github.com/SamurAIGPT/Seedance-2.5-API) — Python wrapper for the Seedance 2.5 API — text-to-video, image-to-video, character consistency

- [seedance-2.0-watermark-remover](https://github.com/SamurAIGPT/seedance-2.0-watermark-remover) — Remove watermarks from your Seedance 2 generated videos
- [seedance-2-generator](https://github.com/SamurAIGPT/seedance-2-generator) — Ready-made Next.js SaaS built on Seedance 2
- [seedance2-comfyui](https://github.com/Anil-matcha/seedance2-comfyui) — Run Seedance 2 inside ComfyUI
- [n8n-nodes-seedance2](https://github.com/Anil-matcha/n8n-nodes-seedance2) — Automate Seedance 2 in n8n workflows
- [awesome-seedance-2.5-api-prompts](https://github.com/Anil-matcha/awesome-seedance-2.5-api-prompts) — Curated Seedance 2.5 API guide, prompts, camera controls, and video generation examples

- [Awesome Claude Fable 5](https://github.com/Anil-matcha/awesome-claude-fable-5) — Curated real-world use cases, tutorials, and benchmarks for Claude Fable 5 — access exclusively via MuAPI
- [Flux-3-Dev-API](https://github.com/Anil-matcha/Flux-3-Dev-API) — Python wrapper for Black Forest Labs' FLUX 3 (Dev variant) — text-to-image, image-to-image, text-to-video, image-to-video
- [awesome-flux-3-api-prompts](https://github.com/Anil-matcha/awesome-flux-3-api-prompts) — FLUX 3 API guide, prompts, and parameters

## 🚀 Why Use Seedance 2.0 API?

Seedance 2.0 is the industry-leading **Sora alternative** developed by ByteDance, offering unparalleled video quality and motion consistency.

- **Cinematic Quality**: Generate 1080p AI videos with realistic physics and lighting.
- **Realistic Human Faces**: Best-in-class facial fidelity — natural expressions, skin detail, and identity consistency across frames.
- **Less Censorship**: More permissive content policy compared to other AI video models, enabling a wider range of creative use cases.
- **Superior Motion Control**: Advanced camera movement and character consistency for professional results.
- **Multimodal API**: Supports Text-to-Video (T2V), Image-to-Video (I2V), and Video Extension.
- **Seedance 2 Mini**: ByteDance's newest lightweight model — outperforms Seedance 2.0 Fast at ~$0.073/sec with dramatically lower cost. Ideal for prototyping, high-volume pipelines, and latency-sensitive apps.
- **Developer-First**: Fast processing via the MuAPI infrastructure with a simple Python SDK.

## 🌟 Key Features of Seedance 2.0 API

- ✅ **Realistic Human Face Generation**: Produces natural, high-fidelity human faces with accurate expressions, skin texture, and identity consistency — no uncanny valley.
- ✅ **Seedance 2.0 Text-to-Video (T2V)**: Transform complex descriptive prompts into stunning AI video clips.
- ✅ **Seedance 2.0 Image-to-Video (I2V)**: Animate any static image with precise motion control using `images_list`.
- ✅ **Seedance 2.0 Omni-Reference**: Condition a video on any combination of image, video, and audio references in one request.
- ✅ **Seedance 2.0 Character**: Generate a multi-panel character sheet (front, back, side, action pose, expressions) from 1–3 reference photos. Use `@character:<id>` inline in any prompt, or pass the sheet directly as an anchor image for tighter face fidelity via `consistent_video()`.
- ✅ **Seedance 2.0 Video-Edit**: Edit existing videos using text prompts and reference images for stylized results.
- ✅ **File Upload**: Directly upload local images and videos using the `upload_file` method, supporting seamless use in generation tasks.
- ✅ **Seedance 2 Mini Text-to-Video**: Fast, affordable T2V using `text_to_video_mini()` — outperforms Seedance 2.0 Fast at ~$0.073/sec.
- ✅ **Seedance 2 Mini Image-to-Video**: Animate images quickly and cheaply using `image_to_video_mini()` — great for high-volume workflows.
- ✅ **Seedance 2 VIP 1080p Text-to-Video**: Generate full 1080p videos from text with VIP priority queue and low censorship. *(Coming Soon)*
- ✅ **Seedance 2 VIP 1080p Image-to-Video**: Animate images to full 1080p with VIP priority queue and low censorship. *(Coming Soon)*
- ✅ **Video Extension**: Seamlessly extend existing clips while maintaining consistent style and characters.
- ✅ **High-Resolution Output**: Support for `basic` and `high` (1080p) quality settings.
- ✅ **Less Censorship**: More permissive content policy than competing models — broader creative freedom out of the box.
- ✅ **Flexible Aspect Ratios**: Optimized for `16:9`, `9:16` (TikTok/Reels), `4:3`, and `3:4`.

---

## 🛠 Installation

### Via Pip (Recommended)
```bash
pip install seedance-2-api
```

### From Source
```bash
# Clone the Seedance 2.0 API repository
git clone https://github.com/Anil-matcha/Seedance-2.0-API.git
cd Seedance-2.0-API

# Install required dependencies
pip install -r requirements.txt
```stall -r requirements.txt
```

### Configuration
Create a `.env` file in the root directory and add your [MuAPI](https://muapi.ai?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api) API key:
```env
MUAPI_API_KEY=your_muapi_api_key_here
```

---

## 🤖 Seedance 2.0 MCP Server (New!)

You can now use Seedance 2.0 as an **MCP (Model Context Protocol)** server. This allows AI models (like Claude Desktop or Cursor) to directly invoke Seedance tools.

### Running the MCP Server
1. Ensure `MUAPI_API_KEY` is set in your environment.
2. Run the server:
   ```bash
   python3 mcp_server.py
   ```
3. To test with the MCP Inspector:
   ```bash
   npx -y @modelcontextprotocol/inspector python3 mcp_server.py
   ```

---

## 💻 Quick Start with Seedance 2.0 API (Python)

```python
from seedance_api import SeedanceAPI

# Initialize the Seedance 2.0 client
api = SeedanceAPI()

# 1. Generate Video from Text (T2V) using Seedance 2.0 API
print("Generating AI Video using Seedance 2.0...")
submission = api.text_to_video(
    prompt="A cinematic slow-motion shot of a cyberpunk city in the rain, neon lights reflecting on puddles, 8k resolution",
    aspect_ratio="16:9",
    duration=5,
    quality="high"
)

# 2. Wait for completion
result = api.wait_for_completion(submission['request_id'])
print(f"Success! View your Seedance 2.0 video here: {result['url']}")
```

---

## 📡 API Endpoints & Reference

### 1. Seedance 2.0 Text-to-Video (T2V)
**Endpoint**: `POST https://api.muapi.ai/api/v1/seedance-v2.0-t2v`

Supports `@character:<id>` inline in the prompt — see [Character Workflow](#-character-workflow) below.

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-v2.0-t2v" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "prompt": "A majestic eagle soaring over the snow-capped Himalayas",
      "aspect_ratio": "16:9",
      "duration": 5,
      "quality": "high"
  }'
```

### 2. Seedance 2.0 Image-to-Video (I2V)
**Endpoint**: `POST https://api.muapi.ai/api/v1/seedance-v2.0-i2v`

Reference images with `@image1`, `@image2`, etc. in the prompt. Supports `@character:<id>` — characters are automatically appended to `images_list`.

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-v2.0-i2v" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "prompt": "Make the clouds move slowly across the sky",
      "images_list": ["https://example.com/mountain.jpg"],
      "aspect_ratio": "16:9",
      "duration": 5,
      "quality": "basic"
  }'
```

### 3. Seedance 2.0 Omni-Reference
**Endpoint**: `POST https://api.muapi.ai/api/v1/seedance-2.0-omni-reference`

Condition a single video generation on any combination of image, video, and audio references. Use `@character:<id>` inline in the prompt to inject a character (see section below).

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-2.0-omni-reference" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "prompt": "A dramatic chase scene through a neon city",
      "aspect_ratio": "16:9",
      "duration": 5,
      "images_list": ["https://example.com/scene_ref.jpg"],
      "video_files": ["https://example.com/style_ref.mp4"]
  }'
```

### 4. Seedance 2.0 Character (Consistent Character Sheets)
**Endpoint**: `POST https://api.muapi.ai/api/v1/seedance-2-character`

Create a multi-panel character sheet (front, back, side profile, action pose, facial expressions, accessories) at 4K / 21:9 from 1–3 reference photos of a real person.

Once the sheet is generated you can use it two ways:
- **`@character:<request_id>`** inline in any T2V, I2V, or Omni-Reference prompt
- Pass `outputs[0]` (the sheet image URL) directly as `@image1` in an I2V request for tighter face fidelity

| Field | Type | Required | Description |
|---|---|---|---|
| `images_list` | array of URLs | Yes | 1–3 photos of the reference person |
| `prompt` | string | Yes | Desired outfit/style for the character |

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-2-character" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "images_list": ["https://example.com/person.jpg"],
      "prompt": "cyberpunk jacket with neon accents"
  }'
```

**Cost:** $0.18 per character sheet

For a full guide including the direct sheet-anchored I2V workflow, see [CHARACTER_CONSISTENCY.md](CHARACTER_CONSISTENCY.md).

### 5. Seedance 2.0 Video-Edit
**Endpoint**: `POST https://api.muapi.ai/api/v1/seedance-v2.0-video-edit`
```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-v2.0-video-edit" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "prompt": "The cat walks through a garden",
      "video_urls": ["https://example.com/video.mp4"],
      "images_list": ["https://example.com/image.jpg"],
      "aspect_ratio": "16:9",
      "quality": "basic",
      "remove_watermark": false
  }'
```

### 6. Seedance 2 Mini Text-to-Video (T2V)
**Endpoint**: `POST https://api.muapi.ai/api/v1/seedance-2-mini-t2v`

ByteDance's lightweight Seedance 2 Mini model — outperforms Seedance 2.0 Fast at a fraction of the cost (~$0.073/sec). Supports the same prompt format as Seedance 2.0.

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-2-mini-t2v" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "prompt": "A golden retriever running on a sunny beach, slow motion",
      "aspect_ratio": "16:9",
      "duration": 5
  }'
```

**Python SDK:**
```python
submission = api.text_to_video_mini(
    prompt="A golden retriever running on a sunny beach, slow motion",
    aspect_ratio="16:9",
    duration=5,
)
result = api.wait_for_completion(submission["request_id"])
print(f"Seedance 2 Mini video: {result['outputs'][0]}")
```

### 7. Seedance 2 Mini Image-to-Video (I2V)
**Endpoint**: `POST https://api.muapi.ai/api/v1/seedance-2-mini-i2v`

Animate any image using Seedance 2 Mini — fast, affordable, and ideal for high-volume pipelines.

```bash
curl --location --request POST "https://api.muapi.ai/api/v1/seedance-2-mini-i2v" \
  --header "Content-Type: application/json" \
  --header "x-api-key: YOUR_API_KEY" \
  --data-raw '{
      "prompt": "The waves crash gently onto the shore",
      "images_list": ["https://example.com/beach.jpg"],
      "aspect_ratio": "16:9",
      "duration": 5
  }'
```

**Python SDK:**
```python
submission = api.image_to_video_mini(
    prompt="The waves crash gently onto the shore",
    images_list=["https://example.com/beach.jpg"],
    aspect_ratio="16:9",
    duration=5,
)
result = api.wait_for_completion(submission["request_id"])
print(f"Seedance 2 Mini video: {result['outputs'][0]}")
```

---

## 🎭 Character Consistency Workflow

Create a fictional character from reference photos and maintain their identity across multiple video scenes.

Two approaches are available — see [CHARACTER_CONSISTENCY.md](CHARACTER_CONSISTENCY.md) for a full guide.

### Option A — `@character:<id>` inline (simplest)

```python
from seedance_api import SeedanceAPI
api = SeedanceAPI()

# Step 1 — generate a character sheet (1–3 reference photos)
char = api.create_character(
    images_list=["https://example.com/person.jpg"],
    outfit_description="cyberpunk jacket with neon accents, glowing visor",
)
char_id = char["request_id"]
api.wait_for_completion(char_id)  # wait for sheet to render

# Step 2 — reference the character inline in any prompt
video = api.text_to_video(
    prompt=f"@character:{char_id} rides a motorcycle through a neon-lit city at night",
    aspect_ratio="16:9",
    duration=5,
)
result = api.wait_for_completion(video["request_id"])
print(f"Video: {result['outputs'][0]}")

# Multiple characters in one prompt
char2_id = "another-completed-character-request-id"
video2 = api.text_to_video(
    prompt=f"@character:{char_id} and @character:{char2_id} face off in a neon-lit arena",
    aspect_ratio="16:9",
    duration=5,
)
```

### Option B — `consistent_video()` (tighter face fidelity)

Pass the character sheet directly as the anchor image for Image-to-Video generation.

```python
# Get the sheet URL after character creation
sheet_result = api.wait_for_completion(char_id)
sheet_url = sheet_result["outputs"][0]

# Generate with the sheet as anchor
video = api.consistent_video(
    sheet_url=sheet_url,
    prompt="@image1 draws their weapon in slow motion, dramatic lighting",
    aspect_ratio="16:9",
    duration=5,
    quality="high",
)
result = api.wait_for_completion(video["request_id"])
print(f"Video: {result['outputs'][0]}")
```

> **Tip**: `@character:<id>` works in T2V, I2V, and Omni-Reference prompts. Use `consistent_video()` when face similarity is critical.

---

## 📖 Documentation & Guides

For a comprehensive walkthrough, check out the **[Seedance 2.0 API: Complete Developer Guide](https://medium.com/@anilmatcha/seedance-2-0-api-complete-developer-guide-text-to-video-image-to-video-python-sdk-1479f5e5491f)** on Medium. This guide covers advanced use cases, prompt engineering, and best practices for high-quality video generation.

| Method | Parameters | Description |
| :--- | :--- | :--- |
| `text_to_video` | `prompt`, `aspect_ratio`, `duration`, `quality`, `remove_watermark` | Generate video from text. Supports `@character:<id>` in prompt. |
| `image_to_video` | `prompt`, `images_list`, `aspect_ratio`, `duration`, `quality`, `remove_watermark` | Animate images. Supports `@image1`/`@character:<id>` in prompt. |
| `omni_reference` | `prompt`, `aspect_ratio`, `duration`, `quality`, `images_list`, `video_files`, `audio_files` | Multi-modal reference video generation. |
| `create_character` | `images_list` (1–3), `outfit_description`, `character_name` | Generate a 4K character sheet from reference photos. Returns `request_id`; `outputs[0]` is the sheet URL. |
| `consistent_video` | `sheet_url`, `prompt`, `aspect_ratio`, `duration`, `quality`, `extra_images` | I2V with the character sheet as anchor (`@image1`). Tighter face fidelity than `@character:<id>`. |
| `video_edit` | `prompt`, `video_urls`, `images_list`, `aspect_ratio`, `quality`, `remove_watermark` | Edit existing videos with prompts and images. |
| `watermark_remover`| `video_url` | Remove MuAPI watermark from a Seedance video. |
| `watermark_remover_pro`| `video_url` | Remove MuAPI watermark from a Seedance video (Pro version). |
| `text_to_video_mini` | `prompt`, `aspect_ratio`, `duration` | **Seedance 2 Mini** T2V — outperforms 2.0 Fast at ~$0.073/sec. |
| `image_to_video_mini` | `prompt`, `images_list`, `aspect_ratio`, `duration` | **Seedance 2 Mini** I2V — fast, affordable image animation. |
| `text_to_video_480p`| `prompt`, `aspect_ratio`, `duration`, `quality` | Generate a 480p video from text (faster/cheaper). |
| `image_to_video_480p`| `prompt`, `images_list`, `aspect_ratio`, `duration`, `quality` | Generate a 480p video from an image (faster/cheaper). |
| `extend_video` | `request_id`, `prompt`, `duration`, `quality` | Extend an existing Seedance video segment. |
| `upload_file` | `file_path` | Upload a local file (image or video) to MuAPI for use in generation tasks. |
| `vip_text_to_video_1080p` | `prompt`, `aspect_ratio`, `duration` | VIP 1080p text-to-video — priority queue, low censorship. *(Coming Soon)* |
| `vip_text_to_video_fast_1080p` | `prompt`, `aspect_ratio`, `duration` | VIP 1080p fast text-to-video — fastest 1080p T2V with priority queue. *(Coming Soon)* |
| `vip_image_to_video_1080p` | `prompt`, `images_list`, `aspect_ratio`, `duration` | VIP 1080p image-to-video — priority queue, low censorship. *(Coming Soon)* |
| `vip_image_to_video_fast_1080p` | `prompt`, `images_list`, `aspect_ratio`, `duration` | VIP 1080p fast image-to-video — fastest 1080p I2V with priority queue. *(Coming Soon)* |
| `get_result` | `request_id` | Check task status for the Seedance API. |
| `wait_for_completion` | `request_id`, `poll_interval`, `timeout` | Blocking helper for Seedance generation tasks. |

---

## 🔗 Official Resources
- **Developer Guide**: [Seedance 2.0 API: Complete Tutorial](https://medium.com/@anilmatcha/seedance-2-0-api-complete-developer-guide-text-to-video-image-to-video-python-sdk-1479f5e5491f)
- **Playground — Seedance 2.0**: [I2V](https://muapi.ai/playground/seedance-v2.0-i2v?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api) · [Extend](https://muapi.ai/playground/seedance-v2.0-extend?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api)
- **Playground — Seedance 2.0 Mini** *(coming soon)*: [I2V](https://muapi.ai/playground/seedance-2.0-mini-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api) · [T2V](https://muapi.ai/playground/seedance-2.0-mini-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api)
- **Playground — Seedance 2.1** *(coming soon)*: [I2V](https://muapi.ai/playground/seedance-2.1-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api) · [T2V](https://muapi.ai/playground/seedance-2.1-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api)
- **Playground — Seedance 2.5** *(coming soon)*: [I2V](https://muapi.ai/playground/seedance-2.5-image-to-video?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api) · [T2V](https://muapi.ai/playground/seedance-2.5-text-to-video?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api)
- **API Provider**: [MuAPI.ai](https://muapi.ai?utm_source=github&utm_medium=readme&utm_campaign=seedance-2-api)

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Keywords**: Seedance 2.0 API, Seedance 2 Mini API, Seedance 2 Mini, ByteDance Seedance, AI Video Generator, Text-to-Video AI, Image-to-Video API, Seedance Python SDK, Seedance V2 API, Seedance Mini, Seedance 2 Mini Python, Seedance 2 Mini Text-to-Video, Seedance 2 Mini Image-to-Video, Sora Alternative, MuAPI, Video Generation API, Cinematic AI Video, AI Video Creation, ByteDance Video AI, Seedance API Documentation, Seedance I2V, Seedance T2V, AI Movie Generator, AI Animation API, Python Video API, Seedance 2.0 Tutorial.
