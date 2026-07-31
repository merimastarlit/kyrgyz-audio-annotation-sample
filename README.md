# Kyrgyz Audio Annotation — Work Sample

> Everything in square brackets is a prompt for you to answer and delete.
> Write in English. Every claim here should be something you can defend out loud.

A work sample produced for an application, not prior professional annotation work.
Transcription, tagging, and the judgments below are my own.

**Contents**
- `transcript.md` — 59 seconds of annotated Kyrgyz speech
- `source.md` — source attribution and timestamps (no audio redistributed)
- `audio/` — my own voice recordings

---

## 1. Source and scope

[Outlet, programme, speakers, timestamps, why you chose this clip.
One sentence on why an interview beats a solo news read for this purpose:
two speakers, natural speech, real code-switching, regional contrast.]

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

[State plainly: pause durations are estimated by ear, not measured in software.
Say what you chose NOT to mark and why — intonation, stress, vowel length.
Scope decisions are decisions.]

**On speaker labels.** [Both speakers are publicly identifiable here, so the
labels are glossed with names. Say that in ordinary annotation work you would
assign labels by voice alone and not attribute identity — and why that
distinction matters.]

---

## 3. The borrowing / code-switch rule

**My rule:** [State it in two or three sentences. Roughly: tagged as borrowing
when the token carries Kyrgyz morphology and no native equivalent is in active
use in this register; tagged as code-switch when a native equivalent appears
elsewhere in the same passage.]

**Where the rule holds.** [The awards vocabulary — республика, артист, орден,
кавалер, медаль, грамота. Say why these are unambiguous: institutional register,
full Kyrgyz morphology, no competing native term in active use.]

**Where the rule breaks — искусство.** [This is the centrepiece. Work through it:
the speaker says өнөр two words earlier, so a native equivalent is not merely
available but in active use in the same breath. Yet искусство takes the Kyrgyz
genitive -нын. And its phonology is un-nativized — the -ств- cluster does not
occur in native Kyrgyz. Morphology says borrowing, lexical competition says
code-switch, phonology says foreign. Say which way you called it, why, and that
you marked it uncertain rather than forcing the rule.]

**сентябрь — a different shape of problem.** [No Kyrgyz morphology at all; it sits
bare. Kyrgyz has native month names, but Russian ones dominate ordinary speech.
Is that a borrowing so complete it has become default, or a switch so habitual
it goes unnoticed? Say what you think and why it is not the same question as
искусство.]

---

## 4. Speakers and regional variation

[S2 is from Batken — deep southern Kyrgyzstan. You are a northern speaker from
Issyk-Kul. Note that the interview makes the regional framing explicit: the host
contrasts Talas and Toktogul as the expected homelands of artists before asking
how a star came from Batken instead.]

**What I heard.** [Specific southern features, if any. Vowel realizations,
lexical choices, intonation. If жэргеси reflects something you actually heard,
this is where it goes. If it does not, correct the transcript instead.]

**Where my own dialect interfered.** [The honest one. Did your northern
intuitions ever pull you toward a form the speaker did not produce? Did anything
slow you down or make you re-listen? A reviewer can tell the difference between
someone reporting this and someone asserting "familiar with all dialects."]

**Regionally marked vocabulary.** [өрүк-зарлуу — Batken is apricot country.
Anything else.]

---

## 5. Genuinely ambiguous segments

[Three or four. For each: what you heard, the competing readings, what you would
need to resolve it — better audio, a second annotator, asking the speaker.
Say what you would do in production when you cannot resolve it.]

[Candidates: искусство. сентябрь. The тага журтунда / ата журтунда pair. The
false start "мына бул, негизи ушул". Anything you re-listened to.]

---

## 6. Where I would expect ASR to fail on this clip

[Concrete predictions, tied to segments. Think about: rapid-fire proper nouns in
the awards list, Türksoy and other organization names, the southern speaker,
backchannels like "йе" that may be dropped or mistranscribed, sentence-final да
as a discourse particle, the evidential -экенмин, code-switched tokens where the
model may guess the wrong language.]

[This section is the one most likely to be read closely. It is where you stop
describing what you did and start showing what you understand.]

---

## 7. Limitations

[Short and honest. 59 seconds is a sample, not a corpus. One annotator, no
inter-annotator agreement. Pauses estimated by ear. Standard orthography imposed
on speech that does not always match it. No prior professional annotation
experience — this is a first work sample.]

---

## 8. Note on input tooling

[Typing Kyrgyz required hunting for a keyboard layout that handles ө, ү, and ң;
typing English required nothing. Input friction is part of why Kyrgyz text data
is scarce, which is part of why models underperform on it. Two or three
sentences — you observed this by living it.]

---

**Related work:** a pre-registered study measuring model performance degradation
on Kyrgyz versus English across occupational tasks —
github.com/merimastarlit/kyrgyz-occupational-eval
