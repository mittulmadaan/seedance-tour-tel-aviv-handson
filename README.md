# Seedance Tour Tel Aviv — hands-on

In this session you make a short luxury fragrance film with BytePlus models in
**Lumen Hub**: three pictures with **Seedream 5.0**, then a 24-second video
with **Seedance 2.5** that uses those pictures as its cast, product and set.

It takes about 20 minutes. You need a laptop with Chrome, Edge or Safari.

Want to see what Seedance 2.5 can make first? [▶ Watch the example films](https://mittul-demo-4.tos-ap-southeast-1.bytepluses.com/telaviv_deck/Seedance_TelAviv_Loop/index.html)
(the LAMANO "Blessed" teaser and the Seedance 2.5 launch film; turn the sound on).

| | |
|---|---|
| **Lumen Hub** | <https://lumen-hub.up.railway.app> |
| **Example films** | [Watch what Seedance 2.5 can make](https://mittul-demo-4.tos-ap-southeast-1.bytepluses.com/telaviv_deck/Seedance_TelAviv_Loop/index.html) |
| **This guide** | <https://github.com/mittulmadaan/seedance-tour-tel-aviv-handson> |

---

## 1. Get your BytePlus account and API key

1. **Register.** If you have not already, open the
   [registration form](https://www.larkoffice.com/share/base/form/shrmyvnj5EiZm2AlPtJSDYX51gd),
   and submit your details.
2. **Check your email.** We create a BytePlus account for you and send a
   registration link. Complete the registration; **$50 of credit** is loaded
   on the account for you to test with.
3. **Create an API key.** Sign in at
   [console.byteplus.com/ark](https://console.byteplus.com/ark), open
   **API Keys**, choose **Create API Key**, and copy it. Keep it to yourself:
   anything made with it is billed to your account.

## 2. Add your key to Lumen Hub

1. Open <https://lumen-hub.up.railway.app>.
2. Click **Add API key** at the top right (or the gear icon). You land on
   **Settings**.
3. Paste your key into **BytePlus API key** and click **Save & continue**.

**Skip everything under "Optional keys".** The one key is all this session
needs. Your key is kept only in your browser, never on the server.

<img src="assets/screens/1-settings.png" width="720" alt="Settings: paste the BytePlus API key, then Save & continue">

## 3. Make three pictures (Seedream 5.0)

Open **Generator → Image**. The model is already **Seedream 5.0 Pro**, square,
2K. Leave those as they are.

Generate the three pictures below, **in this order**, one at a time: paste the
prompt, click **Generate**. Each takes about 20–50 seconds and appears under
**Creations** on the right, and in your **Library**.

**Image 1 — the bottle**

```text
Luxury perfume bottle, square clear heavy glass with pale champagne liquid, tall brushed-gold cylindrical cap, no label or text. Standing on a weathered stone ledge in a misty rose garden at dawn, soft backlight, dew on the leaves, shallow depth of field, photoreal premium fragrance advertising still.
```

**Image 2 — the woman**

```text
Portrait of a woman in her late 20s with long dark wavy hair, natural bare skin with visible texture, calm half-smile, wearing a loose cream linen robe. Standing beside sheer linen curtains in soft morning light, Mediterranean villa interior, photoreal fragrance campaign portrait, 85mm lens.
```

**Image 3 — the location**

```text
Sunlit stone colonnade of an old Mediterranean villa at dawn, climbing roses and ivy on arches, lavender beds along a gravel path, light haze, warm golden side light, no people, cinematic establishing shot.
```

What we got with these prompts (yours will differ):

<img src="assets/examples/image-1.jpg" width="250" alt="Image 1: perfume bottle"> <img src="assets/examples/image-2.jpg" width="250" alt="Image 2: woman in linen robe"> <img src="assets/examples/image-3.jpg" width="250" alt="Image 3: villa colonnade">

Not happy with one? Click **↻ Reuse prompt** on it to put its prompt back, then **Generate** again for another take. Use the one you like.

## 4. Make the film (Seedance 2.5)

Open **Generator → Video**. The model is already **Seedance 2.5** in **Draft**
(a fast 480p preview).

1. **Add the three pictures as references, in order.** Under **References**,
   click the **folder icon** next to **Add media** (From Library) and pick the
   **bottle**. Do it again for the **woman**, then the **colonnade**. They are
   now tagged **@Image 1**, **@Image 2** and **@Image 3**, the names the prompt
   uses. If the order is wrong, remove them (✕) and add them again.
   Leave **Start image** and **End image** empty.
2. **Set Duration to Auto** (the clock menu below the prompt, which starts at
   5 s). The prompt plans 24 seconds; Auto lets the model take the time it needs.
3. **Keep 16:9 and sound On.**
4. **Paste the prompt** and click **Generate draft**:

```text
Luxury fragrance brand film. The woman is always @Image 2, the bottle is always @Image 1,  the location is @Image 3 .
0-4s: wide establishing shot of the colonnade from @Image 3 at dawn, she walks slowly through the arches in her cream linen robe.
4-8s: close-up, her hand brushes through sheer linen curtains, soft light flickering through the fabric.
8-11s: macro, a single dewdrop rolls off a white rose petal and splashes on the stone in slow motion.
11-14s: low tracking shot of her robe and bare feet on the gravel path between lavender beds.
14-21s: medium close-up in side profile, backlit by the low morning sun, one slow unbroken shot. 14-16s: she tilts her head and sweeps her hair over one shoulder to bare the side of her neck. 16-18s: with the cap already removed to reveal the gold atomizer, she raises the bottle from @Image 1 to a hand's length from her neck and presses the nozzle once. 18-21s: a fine, glittering mist sprays onto her neck and drifts in slow motion through the sunbeam as she closes her eyes with a soft, contented breath. Her fingers wrap naturally around the glass, and the bottle shape and gold atomizer match @Image 1 exactly.
21-24s: hero shot, the bottle from @Image 1 rests on the stone ledge in the foreground, the last of the mist still hanging in the light, her out-of-focus silhouette behind; the camera settles on the bottle.
Natural skin, consistent lighting, slow elegant camera moves. Sound: soft piano and strings, birdsong, linen rustle, a single water-drop chime at 8s, a delicate perfume-spray hiss at 17s. No dialogue.
```

<img src="assets/screens/3-video-ready.png" width="720" alt="Video tab: Seedance 2.5, Draft, three references, Auto, 16:9, sound on">

The draft takes **about 3 minutes**. It plays in **Creations** when it is ready.
Happy with it? Click **Make final · 1080p** on the clip for the full-quality
version (a few more minutes).

What we got (a 24 s draft, frames left to right):

<img src="assets/examples/film-frames.jpg" width="760" alt="Frames from the draft film: colonnade, curtain, dewdrop, gravel path, perfume spray, bottle hero shot">

[▶ Watch the example draft](assets/examples/fragrance-film-draft.mp4)

<img src="assets/screens/4-video-result.png" width="720" alt="The finished draft in Creations, with Make final · 1080p">

## 5. Make it yours

- **Your product.** Upload a photo of your own product in the Video tab
  (**Add media**) as @Image 1, and change the prompt's story.
- **Edit a picture.** Hover a picture in Creations → **Open in Image editor**.
- **Canvas.** Open **Canvas → Sample boards** for ready-made multi-step
  boards (product ads, storyboards), and click **Run all**.
- **Download.** Every creation has a **Download** button. Links from the
  models expire after about a day, so keep what you want.

---

## If something goes wrong

| What you see | What to do |
|---|---|
| "No BytePlus API key" / **Add API key** | Settings → paste the key → Save & continue. Keys are per browser: on another browser or device, add it again. |
| "BytePlus rejected this key" / 401 | Copy the key again from console.byteplus.com/ark → API Keys (no spaces). |
| A message saying the model is not activated / not open | In the ModelArk console, open the model's page (Seedream 5.0 Pro or Seedance 2.5) and activate it, then try again. |
| "Too many requests" / 429 / busy | Everyone is generating at once. Wait a minute and try again. |
| The video is still running after 5 minutes | It is queued behind other people's videos. Leave the tab open; it appears when done. |
| A reference is rejected | Make another take of that picture (↻ Reuse prompt → Generate) and use it instead. |
| You run out of credit | Tell the presenter. |

---

## For the presenter

<details>
<summary>Audio demo (Seed Audio): presenter only, needs a Seed Audio key</summary>

Audio is shown on the presenter's screen; attendee accounts in this session
have image and video access only. In Lumen Hub: **Generator → Audio**, paste
the prompt, **Generate**. The prompt is also in
[`prompts/presenter-audio-battlefield.txt`](prompts/presenter-audio-battlefield.txt).

```text
A vast battlefield before a black mountain, thunder rolling overhead, thousands of armored footsteps shaking the earth. Background music: deep war drums, low brass, and a mournful choir rising beneath the clash of steel.
Aric (young prince, breathless but brave, fantasy war film style) says, “There are too many. The valley is full of them.” Mara (warrior woman, clear fierce voice, steady despite fear) answers, “Then we hold the ridge. If they pass us, the last city burns before dawn.” Tobin (young archer, shaky voice, trying to sound strong) whispers, “I can’t even see the end of their army.” Aric, low and tense, “Look at our men. They know it too.”
A horn sounds in the distance, harsh and terrible. The enemy roars like a storm breaking. Mara, gripping her sword, “Fear is not shame. Running is.” Tobin swallows hard. “And if the king does not come?” Aric looks toward the dark horizon. “Then we become the wall he hoped to find.”
Background music swells: drums quicken, choir grows brighter but sorrowful. An old captain (rough voice, weary and noble) shouts, “Shields forward! Spears down! Hold until your arms fail, then hold with your bones!” The soldiers brace. Arrows hiss through the rain. Monsters crash against the shield line.
Tobin cries out, “They’re breaking through on the left!” Mara, fierce, “With me! Push them back!” Steel rings, horses scream, fire erupts across the field. Aric is knocked to one knee, blood on his face. Aric, gasping, “We cannot fall here.” Mara pulls him up. “Then stand.” A sudden clear horn echoes from the eastern hills. The clouds part with pale dawn light. Tobin, stunned, “The king…” Across the ridge, banners appear. Cavalry charges down the hill like a river of silver. Aric, voice breaking with hope, “Sound the horns! Forward!” Background music: full orchestra, thunderous drums, heroic brass, and soaring choir. Mara raises her sword. “For the living! For the fallen! For the light that still remains!” The army roars and charges. Steel meets darkness as dawn spills across the battlefield.
```

</details>

<details>
<summary>Files in this repo</summary>

- `prompts/`: each prompt as a plain text file.
- `assets/examples/`: the results from our own run of this guide.
- `assets/screens/`: screenshots of each step.

</details>

All four steps were run end to end on the live site with a single BytePlus
API key before the session: three Seedream 5.0 Pro images (2K) and a
24-second Seedance 2.5 draft with sound, using them as references.
