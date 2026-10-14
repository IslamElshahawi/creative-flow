---
name: arabic-ad-copy
description: Use when writing Arabic advertising copy for Saudi audiences - hooks, on-frame lines, scripts, captions, or CTAs. Covers the four-rung register ladder from MSA to regional Saudi, the Najdi vs Hijazi contrast set with actual words, hook and CTA banks, locking one register across a whole campaign, and hook construction for the first 1.5 seconds. Do not use for translating finished English copy - Arabic ads are written in Arabic, not translated into it.
---

# Arabic Ad Copy

> **Written from research, not lived fluency.** This file wants a native Saudi copywriter's correction pass — flag anything below that reads wrong to a Saudi ear. Every dialect and register claim is tagged `[inferred]` unless sourced; treat that tag as an invitation to verify, not as a settled fact.

Copy translated from an English original reads imported — the single most common tell of foreign-made Saudi advertising. This file exists so copy is written in Arabic from the first draft, with its own structure and rhythm, not assembled by porting an English sentence's word order.

## Register ladder

Four points worth distinguishing, not three — research surfaced a real gap in the original three-rung version: it conflated two different things under "light Khaleeji."

| Register | Character | Signals |
|---|---|---|
| **Modern Standard Arabic (MSA)** | Formal, broadly understood across every Arab market, flatter emotionally. MSA can reach Arabic-speaking audiences beyond Saudi dialect groups, including some expats. | Institutional, government-adjacent, luxury heritage, anything where gravitas outweighs intimacy. |
| **Light Khaleeji** | Gulf-*wide* colloquial — inflected toward the whole Gulf region, not Saudi-specific. `[inferred]` | Broad Gulf reach without narrowing to Saudi nationals — a brand selling across the GCC, not Saudi-only. |
| **"White Saudi" / neutral Saudi colloquial** | A documented, named sociolinguistic register `[verified: Leiden University / LOT Publications dissertation, "The 'White Dialect' of young Arabic speakers from Qassim (Saudi Arabia)"]` — a leveled, blended variety young Saudis use that deliberately erases *sub-national* identity (Najdi vs. Hijazi), functioning as a neutral pan-Saudi register in both formal and informal public speech. This is a different axis from "light Khaleeji" above: Khaleeji trades regional specificity for Gulf-wide reach; White Saudi trades Najdi/Hijazi specificity for pan-Saudi reach while staying unmistakably Saudi. | Saudi-wide campaigns that want to read as Saudi without picking a side between Riyadh and Jeddah. |
| **Regional Saudi colloquial — Najdi or Hijazi** | Saudi-specific, and **not a single option** — the file previously named only Najdi. `[verified: Asharq Al-Awsat coverage of Saudi ad-industry practice]` Saudi campaigns are frequently produced in *two* dialect versions, Najdi (Riyadh/central) and Hijazi (Jeddah/western), because a Hijazi consumer may reject Najdi-dialect advertising and vice versa — the file's original "Najdi reads as foreign to non-Saudi Gulf viewers" framing is plausible but was never sourced to a study; treat it as a reasonable inference, not a citation. | Riyadh-specific creative → Najdi. Jeddah/western-region-specific creative → Hijazi. Don't default to Najdi as "the" Saudi option when the brief's audience is regional. |

Default heuristic, matching the copywriter's dialect-decision section exactly: **Saudi dialect (light Khaleeji through regional Saudi, by brief) for DTC and lifestyle categories; MSA for institutional, luxury, and government-adjacent brands.** The two files must not drift from this default independently — if one changes, update the other.

**The register ladder is not a fixed rung per category** — it's a dial, now with more positions than the original three-rung version had. A DTC skincare brand targeting a broad Gulf audience (not Saudi-only) sits at light Khaleeji; a Saudi-wide campaign that doesn't want to pick Riyadh over Jeddah sits at White Saudi; a Riyadh-specific or Jeddah-specific brief sits at Najdi or Hijazi respectively; a government National Day campaign sits at MSA regardless of how young the target audience skews. State the specific reasoning for the brief at hand — use the register decision in this skill — rather than mechanically applying the default.

## Lock one register, campaign-wide

**Pick a rung once, record it, and hold it across every shot.** The register goes in
supplied brand facts, is restated in the route bible, and is written to the delivered shot list as
`run.dialect_register`. Every downstream stage checks against it.

This exists because **register whiplash is invisible to the writer and obvious to the reader**: a hook
in Najdi colloquial that drifts into MSA phrasing by shot 4 reads as two different brands talking. It is
the single most likely Arabic-side failure in a multi-shot ad, precisely because each line looks fine on
its own.

The check, at every stage: *is this line on the same rung as shot 1?* Not "is it good Arabic" — is it
**the same Arabic**.

**Dual-dialect production is a real option, not a hedge.**
`[verified: Asharq Al-Awsat on Saudi ad-industry practice]` Saudi campaigns are frequently produced in
two versions, Najdi and Hijazi. If the brief covers both Riyadh and Jeddah and the budget allows, produce
two copy sets against one set of frames rather than splitting the difference into something that belongs
to neither. Splitting the difference is what "White Saudi" is *for* — use it deliberately, not as an
accident of indecision.

## The dialect contrast set

The rungs above are useless without the words that distinguish them. What follows is the minimum
distinguishing set — enough to write a line that is actually Najdi rather than "Saudi-flavoured."

> **Status: built from sourced dialect features, not from observed ad copy.** These forms are attested;
> whether a given one belongs in a current ad for a given brand is a different question, and one a Saudi
> copywriter answers better than this file. Tag anything you use and record corrections in
> a recorded native-speaker review.

### The diagnostic words

The fastest way to tell which dialect a line is in.
`[verified: saudidialects.com — a quick guide to Saudi dialects]`

| Meaning | **Najdi** (Riyadh, central) | **Hijazi** (Jeddah, west) | **Southern / Jonoubi** (Asir, Jazan) |
|---|---|---|---|
| what? | وش (*wesh*) | إيش (*ēsh*) | إيش (*ēsh*) |
| what do you want? | وش تبي (*wesh tabi*) | إيش تبغى (*ēsh tabgha*) | إيش تبا (*ēsh tabā*) |
| now | الحين (*al-ḥīn*) | دحين (*daḥḥīn*) | هالحين (*hal-ḥīn*) |

**وش vs إيش is the single most diagnostic pair.** If a line contains one, it has picked a side. If the
brief hasn't picked a side, that line needs rewriting into something that avoids both — which is exactly
what the White Saudi rung does.

### Najdi structural features

`[verified: Wikipedia — Najdi Arabic, drawing on the descriptive literature]`

- **ق → /g/.** The standard reflex: قال → *gāl*. This is a pronunciation fact, so it matters for
  voiceover and for how written copy will be *read aloud*, not for orthography — you still write ق.
- **ض and ظ have merged**, both realised as [ðˤ]. Again a spoken fact, not a spelling one.
- **Affrication** of /k/ and /g/ to [t͡s] and [d͡z] before front vowels in northern and central varieties
  — but **levelling has made this increasingly uncommon**, and it reads as rural or old-fashioned. Not a
  feature to reach for in contemporary ad copy.
- **Negation**: **ما** (*ma*) before verbs in general; **لا** (*la*) with imperatives, i.e. for
  prohibition — لا تفوّت (*la tfawwit*, "don't miss").
- **Progressive aspect** marked with **قاعد** (*gāʿid*) plus an imperfective verb — قاعد أفكر
  ("I'm thinking"). A genuinely colloquial marker, useful for a conversational register.
- **Complementizers**: اللي (*illi*), إن (*in*), إذا (*itha*).
- **Discourse particles** that carry a lot of colloquial texture: عاد (*ʿād*), بعد (*baʿad*), جد (*d͡zid*).

### Hijazi

`[verified: saudidialects.com; saudidialect.com]` Softer phonology than Najdi, with Turkish and Urdu
loanwords from the Red Sea and Hajj trade history. Shorter vowels where Najdi runs long. Uses إيش and
دحين per the table above.

### Southern

`[verified: saudidialects.com]` Asir, Jazan, Najran, Al-Baha. Shares features with Yemeni Arabic, with a
distinct rhythm and intonation. **Absent from most Saudi advertising**, which is itself worth knowing —
it is an unclaimed register if a brief is genuinely southern.

### Registers that are always safe

Some Arabic is register-neutral and belongs in any rung. Imperatives from MSA — اكتشف (*iktashif*,
discover), جرّب (*jarrib*, try), اطلب (*uṭlub*, order) — sit comfortably in colloquial copy without
sounding formal, which is why they're the workhorse verbs of Gulf advertising. بس (*bass*, "enough /
that's it") is pan-Saudi colloquial. `[verified: saudidialects.com]`

## Building the observed corpus

**Sourced dialect features tell you what is *possible*. Only running ads tell you what is *current*.**
Before writing copy for a live brief, gather the actual language:

1. **Competitor ads that are actually running** — TikTok Creative Center filtered to KSA, Meta Ad Library
   filtered to Saudi Arabia, Google Ads Transparency Center. See current Saudi market research.
2. **The brand's own Arabic**, from supplied brand-voice samples. A brand with existing Arabic has already picked a rung; match it or
   deliberately change it, don't ignore it.
3. **Saudi brand accounts on X, TikTok and Instagram.** X has unusually high Saudi penetration and is
   where a lot of brand voice actually lives. `asset-extraction` covers the tooling.
4. **Saudi storefront copy** on Salla and Zid — product titles, button labels, delivery promises. This is
   where transactional Arabic lives, and CTAs should match it rather than invent their own conventions.

**What to reject as a source: unattributed Saudi-slang listicles.** They are full of rural, archaic and
regionally unmarked vocabulary presented without provenance, and they are the fastest way to produce copy
that reads as a foreigner performing Saudi-ness. **An unsourced Saudi word is worse than plain MSA**,
because MSA merely reads neutral while a misused colloquialism reads as a mistake.

Record what you find with provenance — where observed, in what kind of copy, what year.

## The 1.5-second hook

**Correction to this section's earlier claim.** `[verified: Cogent Arts & Humanities (Taylor & Francis, 2023), "Analyzing word order variation and agreement asymmetry in SVO and VSO structures of Standard Arabic"; SKASE Journal of Translation and Linguistics on Arabic headline word order]` This file previously claimed Arabic "naturally" reads topic-first (subject-first). That's backwards. Arabic's **default, unmarked word order is VSO — verb first** — headline-specific research found Arabic main headlines run close to 100% VSO. **Subject-first (SVO) is the marked, rhetorically emphatic order**, used specifically when the writer wants to spotlight the subject; the default VSO order is used when the action matters more than naming the actor first. This means:

- **Verb-first hooks aren't a special "urgency" device — they're the normal, unmarked rhythm of Arabic**, from news headlines to classical prose. "اكتشف..." (discover), "جرّب..." (try), placed first, read as native Arabic sentence rhythm, not as a stylistic urgency trick.
- **Subject-first hooks are the deliberate, marked choice** — reach for this specifically when the product noun itself is what you want the viewer's eye to land on first. "لبستك جديدة توصلك اليوم" (your new outfit reaches you today) is a legitimate hook, but it works *because* it's marked, not because SVO is Arabic's natural default — don't reach for subject-first as a habit, reach for it as a deliberate emphasis choice.
- **Don't open with a subordinate clause.** "بينما الجميع يبحث عن..." (while everyone searches for...) delays the payload exactly where the attention budget can't afford it — this part of the original guidance holds regardless of the VSO/SVO correction.
- **The attention-budget number itself**: `[verified: WARC / Lumen Research eye-tracking studies across thousands of video ad exposures]` — not Arabic-specific, but real: average video ads receive ~1.7 seconds of actual eye attention; as little as 1.4 seconds of attention drives a measurable lift in brand awareness; ~3.9 seconds is needed for prompted recall. "1.5 seconds" is in the right neighborhood and better-sourced now than when this file first used it, but it's global ad-attention research, not a Gulf/Arabic-specific study — hold it loosely.

Write three hook alternates per this guide's suggestion. Vary them on **two independent axes**, not one: grammatical structure (verb-first as the default choice, subject-first when the product noun itself deserves the spotlight) and hook mechanism — pattern interrupt, question, bold claim, POV, authority/stat, visual-only, social proof, or direct address are eight distinct mechanisms worth choosing between (`[verified: github.com/Creatify-AI/video-ad-reverse-engineer, 10-category hook taxonomy]`), not just three phrasings of the same grammatical move. One mechanism from that catalog needs a compliance gut-check before use here: **controversy/hot-take hooks** risk a current Saudi compliance review's rule against content that "challenges Saudi social norms" — don't reach for this mechanism without running it past that skill first.

### Hook bank

One realisation per mechanism, so the eight mechanisms above are something you can *write* rather than
just choose between. Each is a **pattern to fill**, not a line to lift.

> **Constructed from the sourced dialect features above, not observed in running campaigns.** Treat
> every line as a starting shape needing a native ear. Register is marked so you don't mix rungs by
> accident.

| Mechanism | Arabic | Register | Note |
|---|---|---|---|
| Direct address (imperative) | جرّب \<المنتج> مرة وحدة | neutral / light colloquial | Verb-first, unmarked rhythm. The workhorse |
| Question | وش يفرق \<المنتج> عن غيره؟ | **Najdi** (وش) | Swap وش → إيش for Hijazi |
| Question, register-neutral | ليش الكل يتكلم عن \<المنتج>؟ | neutral | Avoids the وش/إيش fork entirely |
| Pattern interrupt | لا تشتري \<الفئة> قبل لا تشوف هذا | colloquial | لا + imperative = prohibition, per Najdi negation |
| Bold claim (substantiable only) | \<المنتج> يوصلك خلال ٢٤ ساعة | neutral | A number survives compliance; a superlative doesn't |
| Authority / stat | ٥ فوائد مثبتة في \<المنتج> | neutral | Must trace to supplied brand facts |
| Social proof | أكثر من \<العدد> عميل في السعودية | neutral | Needs a real figure |
| POV / direct-experience | أول مرة تجرّب \<المنتج>… بس | colloquial | بس as the colloquial closer |
| Subject-first (marked emphasis) | \<المنتج> الجديد وصل اليوم | neutral | Marked order — use when the noun is the payload |

**Reading the table.** The neutral rows are usable at any rung and are where a pan-Saudi campaign should
start. The Najdi row is marked as such precisely because وش commits you — if the brief hasn't picked a
region, use the register-neutral question form instead.

### CTA bank

The most-reused copy in any ad and, until now, entirely absent from this repo. Verb-first, one line.

| Intent | Arabic | Note |
|---|---|---|
| Order / buy | اطلب الحين | الحين is **Najdi**; use دحين for Hijazi, or drop the time word to stay neutral |
| Order, neutral | اطلبه اليوم | Avoids the الحين/دحين fork |
| Shop | تسوّق الحين | Same fork applies |
| Discover / explore | اكتشف المزيد | Register-neutral, safe everywhere |
| Try | جرّبه الحين | |
| Learn more | اعرف أكثر | |
| Link in bio | الرابط في البايو | *bio* as a loanword is standard in Saudi social copy `[inferred]` |
| Limited offer | العرض لفترة محدودة | Must be true — see Claim language |
| Free delivery | توصيل مجاني | A category-standard proposition in KSA e-commerce |
| BNPL | قسّمها على ٤ دفعات | The framing that changes perceived accessibility more than a discount does — see current Saudi market research |

**Note the الحين / دحين trap.** The most natural-sounding CTAs are the ones that commit to a region. If
the campaign is pan-Saudi, prefer the neutral variants — this is exactly the kind of place a register
leak happens without anyone noticing.

**Check every CTA against the transactional Arabic the brand's own storefront already uses.** Salla and
Zid checkout copy has established conventions, and a CTA that fights the button the user is about to
press is friction, not creativity.

## Length discipline

Arabic is more compact than English in word count but wider in set width — connected letterforms and long horizontal joins mean a short Arabic sentence can still run wide on screen. Arabic typography review deliberately does not give a numeric character-per-line budget ("test at final size; do not estimate from the English") — this skill doesn't invent one either, and that's a checked position, not an oversight: `[verified — absence checked]` neither TikTok's, Instagram's, nor Snapchat's official creative specs give language-specific text budgets; the UAE Government Design System (a real, live official design system) applies the same line-height rule to Arabic and Latin without differentiating; the W3C's Arabic & Persian Layout Requirements covers justification and line-breaking but not a caption character count. No platform or standards body publishes the number this section could cite — what does exist is generic content-marketing-blog numbers with no disclosed methodology, not reliable enough to repeat here even with attribution. What this skill specifies instead:

- Write to the **line-count** discipline that does exist: maximum two lines for a hook, three for supporting copy (Arabic typography review).
- Draft short, then test the actual set width at final frame size before locking a line — a count-based estimate from the English draft will be wrong in both directions depending on how many long-descender or wide-join letters land in the Arabic phrasing.
- When a line is too wide, cut words before abbreviating — Arabic abbreviation conventions are inconsistent and read as a mistake more often than a stylistic choice.

## Numerals

Two systems — Arabic typography review covers the mechanics (numerals read left-to-right even inside RTL text; SAR symbol placement after the figure). **The commerce-default claim needs softening, not reversing** — real usage is more contextual and more in-flux than a clean binary:

- **Western Arabic numerals (0123)** trend as the default in Saudi digital/commerce contexts — technology, computing, business, e-commerce. `[inferred]`
- **Eastern Arabic numerals (٠١٢٣)** are the technically "correct" formal default under the `ar-SA` locale, and historically dominate currency, street signage, newspapers, and official documents.
- **A genuine complication worth knowing**: `[inferred — single secondary source, worth a copywriter double-checking before treating as settled]` Saudi Arabia's 2023 Highway Code reportedly mandates new road signage use only Western numerals — official/state contexts moving *toward* Western, not away from it, which cuts against a simple "Eastern = formal, Western = commerce" split. The direction of travel may be toward Western becoming dominant everywhere, not staying confined to commerce.
- **What to actually do**: there's no single settled "correct" default to cite with confidence. Pick one system per campaign based on the brand's existing convention (check supplied brand facts) or the route's formality, and hold it consistent across every frame — mixing systems within one ad reads as an error regardless of which system you picked.

## Claim language

Persuasive copy still has to survive a current Saudi compliance review's substantiation rules — cite that section rather than restating it here. In practice for copywriting specifically:

- Prefer specific, verifiable phrasing over superlatives. "٥ فوائد مثبتة" (5 proven benefits) survives a compliance pass that "الأفضل في المملكة" (the best in the Kingdom) does not, unless that claim traces to a source in supplied brand facts.
- Every claim in a draft must be checkable against supplied brand facts before it ships — if a fact is not stated in the supplied evidence, copy cannot assert it.

## Never translate

Writing the hook (or any line) in English first and translating it into Arabic produces copy that reads imported. Part of this is structural — English and Arabic order a sentence differently by default (see The 1.5-second hook's VSO/SVO correction above), so a faithful translation carries over English word order at the cost of Arabic's own unmarked rhythm. Part of it is documented separately in the translation-studies literature as cultural/idiomatic loss, not just word-order loss: `[verified, medium confidence: academic sources on English-to-Arabic ad-slogan translation document specific cases where literal translation loses intended rhetorical effect through cultural mismatch, independent of the word-order question]`. Either way, the fix isn't a better translator — it's drafting in Arabic from the first word, testing the hook's rhythm independently of what the English-language brief says, and treating the brief as the *idea* to express, not a sentence to carry over.

## Related

`hooks-and-ctas` (why a hook or CTA is emotionally activating, which mechanism it uses, and which named
viral format it takes — decide that first, then render it here in correct dialect/register; this file
doesn't diagnose flat vs. activating or pick a TikTok format on its own) · `saudi-culture` (who is
speaking and to whom) · a current Saudi compliance review (what a claim has to survive) · Arabic typography review (how the
line is set) · current Saudi market research (platforms, seasons, competitor copy) ·
a recorded native-speaker review (where corrections to this file get recorded)

## Sources consulted

`[verified]` claims above trace to: Cogent Arts & Humanities (Taylor & Francis, 2023) on SVO/VSO word order in Standard Arabic; SKASE Journal of Translation and Linguistics on Arabic headline word order; the Leiden University/LOT Publications dissertation on the "White Dialect" of Qassim, Saudi Arabia; saudidialects.com's guide to Hijazi/Najdi/Jonoubi for the diagnostic contrast set; Wikipedia's Najdi Arabic article (drawing on the descriptive literature) for phonology, negation particles, the قاعد progressive and the complementizers; ArabAd's "The Handbook of Arabic Copywriting: On The Myth of 'White Arabic'" (Gulf ad-industry trade press — full text unreachable at research time, cited via search summary, worth a manual read before leaning on it further); Asharq Al-Awsat coverage of Najdi/Hijazi dual-dialect production practice in Saudi advertising; WARC and Lumen Research eye-tracking studies on video-ad attention windows; Creatify's open-sourced hook-type taxonomy (`github.com/Creatify-AI/video-ad-reverse-engineer`). Everything else marked `[inferred]` is exactly that — a reasoned but unsourced claim, flagged so a native Saudi copywriter's review pass (this file's own stated ask) knows where to look first.
