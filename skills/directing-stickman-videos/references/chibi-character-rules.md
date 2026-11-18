# Chibi-Cartoon Art Style, Clear Voiceover & Hook Rules

This contract supersedes basic stick-figure defaults when generating topic-accurate videos inside Antigravity.

## 1. Art Style & Topic-Accurate Character Lock (No Stick Figures)
- **Canonical Reference Image**: [`../assets/chibi-style-reference.jpg`](../assets/chibi-style-reference.jpg)
- **Do NOT use stick figures** (no hollow circle heads, single-line torsos, wire limbs, or cartoon mittens).
- **Character Proportions & Rendering**:
  - **2D Stylized Chibi-Cartoon**: Bold dark ink outlines (`#1d1c24`), smooth cel-shaded color fills with soft rim highlights and subtle radial/linear gradients.
  - **Head & Face**: Large expressive rounded-square head with warm skin tones (`#f5cba7` / `#e5b58d`), soft cheek shading/freckles, thick expressive eyebrows, rounded nose, and large expressive eyes with rich irises and crisp white specular catchlights.
  - **Topic-Accurate Identity & Wardrobe**: Characters must accurately reflect the real people or roles in the topic (for example, **Jensen Huang** with swept-back silver-gray hair, signature rectangular glasses, black leather moto jacket with silver zippers/lapels, dark trousers, and sneakers; **Alice Huang** with sleek dark bob hair and tailored burgundy executive blazer).
  - **Body & Limbs**: Full chibi torso, clothed sleeves/trousers, shaded arms/hands, and detailed footwear.
- **Generation Engine**: Use the **currently selected Antigravity model** to author/generate the required scene illustrations (or high-detail layered vector/canvas artwork rendered to `720×1280` / `1280×720` PNGs) matched to `assets/chibi-style-reference.jpg`.

## 2. Crystal-Clear, Easy-to-Understand Voiceover
- **Natural Speech Clarity**: Use clean neural speech synthesis (e.g., `edge-tts` `en-US-ChristopherNeural` or `en-US-AndrewNeural` at `48 kHz` mono PCM WAV) at **natural speaking rate (`+0%` to `+5%`)**.
- **No Time-Stretch Distortion**: Never apply aggressive `atempo` speed-ups (`> 1.05x`) or aggressive `silenceremove` thresholds that clip initial/final consonants or introduce metallic phase artifacts.
- **Voice-First Audio Mix**:
  - Keep narration normalized cleanly at the front of the mix (`volume=1.15`).
  - Keep background ambience ultra-subtle (`gain <= 0.04`) and place transition SFX only between phrases or at low non-masking levels (`gain <= 0.22`) so the voiceover is never muddy or obscured.

## 3. High-Retention Start Hook & End Hook
- **Start Hook (`0.0s–3.0s`)**:
  - Must open with an immediate high-stakes paradox or visual shock—both in the poster headline and the first spoken sentence (e.g., *"A $3 TRILLION EMPIRE / SHATTERED OVERNIGHT"* — *"He built a three-trillion-dollar AI empire—then one secret affair brought him down overnight."*).
  - Never open with slow background definitions or generic questions.
- **End Hook (Final Shot)**:
  - Must close with a sharp synthesis punchline and a polarizing viewer-verdict prompt that drives comments (e.g., *"Was Jensen a national security risk—or did NVIDIA just lose its greatest leader? Drop your verdict below."*).
