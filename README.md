# Kyrgyz Audio Annotation — Work Sample


A work sample produced for an application, not prior professional annotation work.
Transcription, tagging, and the judgments below are my own.

**Contents**
- `transcript.md` — 59 seconds of annotated Kyrgyz speech
- `source.md` — source attribution and timestamps (no audio redistributed)
- `audio/` — my own voice recordings

---

**Related work:** [kyrgyz-occupational-eval](https://github.com/merimastarlit/kyrgyz-occupational-eval) — a pre-registered study measuring model performance degradation on Kyrgyz versus English across 20 occupational tasks.

## 1. Source and scope

**Platform:** YouTube
**Publisher / channel:** ERNIS KYIAZ PODCAST (ЭРНИС КЫЯЗОВ)
**Video title:** 
Бала чакта кезүүгө чыгып, кой кайтарат элем | Саламат Садыкова | Ernis Kyiaz Podcast
**URL:** https://www.youtube.com/watch?v=2bSt53h3M74
**Published:** 11/2025
**Segment annotated:** 02:15 – 03:39
**Speakers:** 

S1 — Ernis Kyiazov; 

---
S2 — Salamat Sadykova
---

## 2. Transcription conventions

| Marker | Meaning |
|---|---|
| `S1`, `S2` | speaker labels |
| `(.)` | micro-pause, not timed |
| `(0.2)` | estimated pause length in seconds |
| `{B}` | integrated borrowing |
| `{CS}` | live code-switch |
| `{B?}` `{CS?}` | uncertain |

Pause durations are estimated by ear, not measured in software.
I did not choose to mark intonation, stress, and vowel length, because I want text to be readable as well.


**On speaker labels.** Both speakers are publicly identifiable here, so the
labels are glossed with names. 

---



## 3. The borrowing / code-switch rule
 
**My rule:** I tagged a token as a borrowing when it carries Kyrgyz morphology and
no native equivalent is in active use in that register. I tagged it as a
code-switch when a native equivalent appears elsewhere in the same passage —
that is, when the speaker demonstrably had the Kyrgyz word available and used
the Russian one anyway.
 
**Where the rule holds.** The awards vocabulary is unambiguous: республика,
артист, орден, кавалер, медаль, грамота. These are institutional terms that
entered Kyrgyz during the Soviet period and have no competing native word in
active use. Every one of them takes full Kyrgyz morphology in this clip —
Республикасынын, ордеринин, медалынын. A Kyrgyz speaker introducing an artist
would not reach for an alternative, because there isn't one.
 
**Where the rule breaks — искусство.** This is the hardest judgment in the clip,
and I did not resolve it.
 
The speaker lists ырчылардын, өнөр адамдарынын, искусстванын — singers, people of
өнөр, and искусство. He uses the native word өнөр two words before he uses
искусство, for overlapping territory. So a native equivalent is not merely
available; it is active in the same breath. My rule says code-switch.
 
But искусство takes the Kyrgyz genitive -нын, which is what integrated borrowings
do. And its phonology is not nativized at all — the -ств- cluster does not occur
in native Kyrgyz words.
 
So the three signals disagree. Morphology says borrowing. Lexical competition
says code-switch. Phonology says the word never assimilated. I tagged it {CS?}
rather than force the rule, because the honest answer is that this token sits
between the two categories and my rule was not built to handle a case where a
speaker uses both words for the same domain in one sentence.
 
**сентябрь — a different problem.** сентябрь carries no Kyrgyz morphology at all.
It sits bare before айында, doing no grammatical work of its own. Kyrgyz has
native month names, but Russian ones dominate ordinary speech to the point where
the native forms sound archaic in this register.
 
That makes it the opposite shape from искусство. There, the question was whether
integration outweighs lexical competition. Here, there is no integration to
weigh — but there is also no real competition, because no one says the native
month name in casual speech. I tagged it {B?}: a borrowing so complete it has
become the default, which is not quite the same thing as a borrowing that
assimilated.
 


---

## 4. Speakers and regional variation

S2 is from Batken — deep southern Kyrgyzstan. I am a northern speaker from
Issyk-Kul. The interview makes the regional framing explicit: the host
contrasts Talas and Toktogul as the expected homelands of artists before asking
how a star came from Batken instead.

**What I heard.** 
I heard specific southern dialect features. Rich descriptive Kyrgyz language, where I had trouble with some Russian words that are fully integrated to Kyrgyz language. I had to transribe the original speech despite it was Russian words. 

**Where my own dialect interfered.** 
My northern dialect conflicted with one word тага журтунда as it doesn't exist in out dialect, rather we say it ата журтунда, but the host said both of these words, included both dialects next to each other. 

**Regionally marked vocabulary.** 
өрүк-зарлуу — Batken is apricot country, it is a southern dialect based word, because apricots grow only there on the South of Kyrgyzstan



---

## 5. Genuinely ambiguous segments
 
**искусстванын {CS?}** — covered in section 3. Competing readings: integrated
borrowing on morphological evidence, live code-switch on lexical-competition
evidence. What would resolve it: hearing how this speaker uses искусство versus
өнөр across a longer stretch of the interview, or comparing against other
speakers in the same register. A single instance is not enough to tell whether
he treats them as synonyms or as distinct concepts.
 
**сентябрь {B?}** — covered in section 3. What would resolve it: whether the
speaker ever produces a native Kyrgyz month name elsewhere. If she never does,
the case for "default" strengthens.
 
**тага журтунда (.) ата журтунда** — this one looks ambiguous and is not, which
is why I am including it.
 
Heard cold, this sounds like a disfluency: a speaker starting a word, breaking
off, and self-correcting to a similar-sounding one. An annotator without the kin
vocabulary would mark a repair here.
 
It is not a repair. тага журт and ата журт are two distinct terms — maternal-side
kin and paternal-side kin. The host is asking about both lineages in sequence,
which is the natural way to ask where someone's talent comes from. The micro-pause
between them is a list boundary, not a correction.
 
I note this because it is the clearest example in the clip of annotation error
that would come from lexical gaps rather than from audio quality. The audio is
perfectly clear. The ambiguity is entirely in the annotator's knowledge.
 
 
**мына бул, негизи ушул** — a false start. The host begins a framing, abandons it,
and restarts with негизи. I transcribed it as produced rather than smoothing it,
but I want to flag that the boundary between "false start" and "list of hedges"
is a judgment call here, and a second annotator could reasonably read it as
ordinary spoken hedging rather than an abandoned construction.
 
**What I would do in production.** Tag the uncertain token, record the competing
readings, and escalate rather than guess. On a real annotation task I would want
these flagged for a second pass, and I would want the guidelines to state
explicitly which way to resolve the borrowing/code-switch boundary — because the
consistency of the dataset matters more than which convention is chosen.
 
---

## 6. Where I would expect ASR to fail on this clip

These are predictions, not test results. I have not run a system against this
audio.
 
**The awards list.** Түрк Союзу, Токтогул, Манас ордени, Казакстан arrive in rapid
sequence with little pause. Proper nouns are where recognition is weakest,
because they are rare tokens and the model has less context to fall back on.
Organization names are worse still — I would expect Түрк Союзу in particular to
be garbled or partially substituted.
 
**The backchannel "йе".** A brief non-lexical response token. Systems trained to
produce fluent text tend either to drop these entirely or to force them into the
nearest real word. Either failure destroys the turn structure: the transcript
loses the fact that S2 responded at all.
 
**Sentence-final да.** This appears three times — турат да, деген да, эсептелинет
да. It is a discourse particle carrying stance and tone, not the Russian word да
meaning "yes." A model with substantial Russian in its training data has an
obvious wrong answer available, and it is the kind of error that produces
plausible-looking output, which makes it harder to catch than garbled text.
 
**Code-switched tokens.** искусство and сентябрь require a language decision
mid-sentence. A model that commits to Kyrgyz may distort them toward Kyrgyz
phonotactics; one that switches may drop the Kyrgyz case ending. The -нын on
искусстванын is exactly the kind of morphology that gets lost at a language
boundary.
 
**The evidential -экенмин.** төрөлгөн экенмин carries an evidential nuance — the
speaker relating her own birth as reported rather than witnessed fact. This is
low-frequency morphology, and low-frequency morphology in a low-resource language
is the least-supported case there is. I would expect it flattened to a plain past
tense, which loses the nuance without producing an obvious error.
 
**The southern speaker.** S2 is from Batken. If Kyrgyz training data skews toward
Bishkek and northern speech — which is likely, given where broadcast and web
Kyrgyz is produced — her pronunciation is comparatively out of distribution, and
I would expect higher error rates on her turns than on the host's.
 
**The false start.** мына бул, негизи ушул. Systems tend to either smooth
disfluency into fluent text or garble it. Both are wrong for annotation purposes,
where the disfluency is data.
 
**One I can report from experience rather than predict.** On my first pass I
transcribed ким экен- экендигин as a single clean word, smoothing a truncation
into fluent text without noticing. I only caught it on re-listening. That is the
same failure mode I am predicting for ASR, and I made it myself — which is part
of why I think disfluency handling needs explicit annotation guidelines rather
than annotator instinct.

---

## 7. Limitations

59 seconds is a sample, not a corpus. One annotator, no
inter-annotator agreement. Pauses estimated by ear. Standard orthography imposed
on speech that does not always match it. No prior professional annotation
experience — this is a first work sample

---

## 8. Note on input tooling

Typing Kyrgyz required hunting for a keyboard layout that handles ө, ү, and ң;
typing English required nothing. Input friction is part of why Kyrgyz text data
is scarce, which is part of why models underperform on it. 

---

**Related work:** a pre-registered study measuring model performance degradation
on Kyrgyz versus English across occupational tasks —
github.com/merimastarlit/kyrgyz-occupational-eval
