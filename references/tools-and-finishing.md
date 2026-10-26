# Recommended tools and finishing practice

Read before choosing providers, generating media, or preparing an export. These recommendations do not install software, grant account access, or authorize spending by themselves.

## Use the tools appropriate to the agreed treatment

| Tool | Starting role | Verify before use |
| --- | --- | --- |
| fal.ai | Generated video/images and suitable media-analysis models | Account, exact model/version, supported input/output, price, included credits, terms for intended use, and request status/billing |
| MiniMax H3 Max through fal.ai | Preferred presenter lip sync | Exact endpoint/version, reference identity, input audio, duration/resolution support, price and output quality |
| ElevenLabs v4 | Preferred narration when the treatment needs it | Exact voice identifier/model/settings, pronunciation, available allowance, usage conditions and intended delivery |
| Gemini Lyria 3.5 | Preferred music creation | Exact model/endpoint availability, supported duration/output, price, usage conditions and intended delivery |
| Remotion | Programmable visual edit, synchronized graphics/captions, and rendering | Existing project and dependencies, suitable installed version, relevant Remotion skills/docs, assets, fonts, timing and render settings |
| FFmpeg/ffprobe or equivalent installed media tools | Assembly, audio mixing/encoding, media identity and technical diagnostics | Tool availability, exact inputs, reproducible parameters and measured outputs |

Remotion was used in the source production that informed this workflow. MiniMax H3 Max through fal.ai is the preferred option for presenter lip sync; choose other footage methods to fit the treatment. Honor an explicitly requested model. Verify current documentation and rates when selecting providers; do not copy a past production's price into a new budget.

Treat Hyperframes as a potential alternative only after verifying actual tool availability, project structure, timing/export behavior, and a representative output. Do not describe it as tested or used merely because it was named in a conversation. An existing user editor/project may be preferable; preserve its editable authority unless a migration is requested or justified and authorized.

Use available purpose-built connectors, skills, APIs, or authorized browser sessions. Follow their instructions. Do not solicit passwords or secrets in chat. Keep private files and credentials in the appropriate local/private production storage.

## Generation discipline

First identify the visual purpose and source suitability. Use real/recorded material when it serves the treatment; generate when a new visual is useful and authorized. Do not substitute generated footage for factual evidence of an event.

A useful generation request specifies subject and action, camera/composition, surroundings and period, physical/spatial relationships, lighting/materials, continuity anchors, duration/output needs, and exclusions that matter. Prefer a manageable continuous action over a prompt requiring many unrelated actions. Use references/consistent assets when appropriate and permitted. Evaluate the result in motion before accepting it.

For failures, state the observed fault and change the prompt, reference, model, or method for a reason. Do not keep submitting near-identical requests without diagnosing the failure. Track every attempt and its disposition, including billed rejects. Poll an existing request before submitting a replacement; request uncertainty is not proof of failure or non-billing.

## Voice and audio assembly

Voice choice is an episode/channel decision. Save the exact provider voice ID, model, settings, pronunciation choices, and an accepted reference recording. A display name or global account default is insufficient. Verify the binding before generation. Never borrow another channel's voice by accident.

Write numbers for listening. When exact precision is unnecessary to the explanation or viewer's decision, speak an accurate approximation and show the exact sourced figure on screen: $1.505 billion can be “around one and a half billion”; $1.946 billion can be “just under two billion.” Keep units, dates and metric labels clear. Record both spoken and displayed wording, check the arithmetic and rounding, and read the line aloud before generation. Retain necessary precision in technical instructions or other passages where rounding would mislead.

Produce coherent takes long enough to preserve natural phrasing within provider limits. Join at genuine pauses and listen to joins. Keep the narration continuous through picture changes; avoid many artificial scene-boundary audio splices. Work from preserved originals, use lossless intermediate audio where practical, and inspect the final encoded soundtrack after mixing/rendering.

Choose a loudness/peak preset suitable for the treatment, document it, and measure the delivered mix. Keep dialogue intelligible, maintain headroom, and assess music/effects perceptually. A numeric loudness result does not establish complete words, good pronunciation, or a pleasant balance. Intentional quiet sections are valid; an accidental silent ending is not.

## Music progression and mix

Use Gemini Lyria 3.5 as the preferred music generator, with availability and pricing verified before generation. Choose the genre, tempo, instrumentation, and energy from the episode's agreed direction. Ask the user about genre/style, BPM, song key, drums, and instruments, preserving answers already given and any explicitly delegated choices.

Build a coherent musical progression across the edit. Use related passages or arrangements that develop through changes in texture, percussion, instrumentation, and intensity. Match those changes to meaningful story beats. Repetition can establish a theme, but an obvious short loop should not carry the entire film without development.

Choose music behavior according to each passage:

- **Narration and explanation:** Keep a supportive bed at a level and density that leave speech clear.
- **Visual demonstrations, website footage, or montages:** Continue the music when it supports attention and no important source audio needs space.
- **Examples with meaningful dialogue, sound, or music:** Lower, fade, or temporarily mute the background track so the viewer can assess the original audio. Plan its return to bring music back in, fade in, louder. Keep the return consistent with narration clarity and the intended energy.
- **Emphasis, reflection, and transitions:** Use changes in intensity or intentional silence when they serve the moment. Coordinate fades and returns with both the picture and musical phrasing.

Check the complete exported soundtrack for repetitive passages, accidental gaps, abrupt joins, distracting changes, and missing returns after a fade. Confirm that the music supports the intended energy without competing with the presenter.

## Editable visual/caption presets

Reuse components and data contracts rather than baking one channel's style into this skill. An episode preset should record canvas dimensions, frame rate, palette, typography, caption enablement/grouping/size/outline/background/safe area, graphic treatment, and ending behavior. Choose those values from the brief or delegated creative judgment. Do not impose yellow captions, metallic colors, or a particular font on every video.

Timing must follow actual narration/action. Preserve necessary archive context and source framing. Generated text is not a reliable way to render essential labels; use verified editorial text where needed. Keep essential explanations readable through their spoken beat. Captions should not obscure the key mechanism, speaker, or demonstration.

For website and interface evidence, capture enough native pixels for its final displayed size: a full-frame 1080p view needs at least 1920×1080 source pixels, with extra resolution for a planned push-in. Upscaling a small capture does not restore detail. Prefer a clean full-frame view with recognizable branding and only necessary overlays; crop or zoom for a specific point while preserving the context needed to understand it. Recapture soft or obstructed views and inspect their text in the final export, not only the browser preview.

Check infographic composition in the finished frame at both full size and phone size. Treat the heading, diagram and labels as one visual group with a clear hierarchy; center that group when it is the sole focal point. Balance any presenter overlay deliberately. Reveal and highlight the item being explained, then hold it long enough to understand; motion should clarify rather than compete with the information.

Default to a 16:9, 1920×1080 deliverable when suitable and unspecified after briefing; choose frame rate to fit the source material and treatment. Do not repeatedly retime or interpolate footage merely to enforce a preset. Honor requested formats and keep editable project/assets alongside the exported master in the production workspace.

Plan the next-video invitation as part of the ending, with one clear reason to continue and a smooth picture/sound handoff. Use a specific next video's topic only when that destination is known; otherwise keep the invitation truthful and general. When an end-screen target is planned, leave unobstructed space and enough time for it. Review the complete final words and the transition into the ending layout. A rendered placeholder is separate from configuring a clickable platform element.

## Delivery and accounts

For the authorized destination, verify that the expected revision uploaded/imported successfully and actually plays, including its ending. Keep a local master and a clear version identity. Do not confuse a queue acknowledgement, configured OAuth, or successful encode with a completed upload or watched video.

If publication preparation is requested, prepare the title, description, thumbnail, subtitles, chapters where useful, credits, and accurate platform disclosures. Configure real end-screen functionality only when supported and authorized. Creating a channel, buying credits/subscriptions, changing visibility, scheduling, and public publishing remain distinct actions governed by the user's authorization and applicable tool rules.
