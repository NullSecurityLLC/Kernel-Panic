# KERNEL PANIC

A terminal-driven game about two medicated teenagers and the slow loss of self inside a codependent relationship.

---

## What it is

Kernel Panic is a hybrid visual novel and symbolic terminal simulator.

You play as **The Hacker**, a high school student on ADHD medication. Your relationship with **The Cowgirl** — a girl navigating SSRI flatline, fractured identity, and more grief than she can process — is the entire game.

The terminal interface is not aesthetic. It is the psychology. Emotional states run as system processes. Suppression throws errors. Identity loss registers as a NULL value. The machine reports what the character cannot say out loud.

---

## The core mechanic

Seven emotional stats run continuously:

```
HOPE · TRUST · GUILT · ANGER · DISSOCIATION · FORGIVENESS · SELF
```

Every scene, every interaction, every choice to suppress or engage shifts these values. The story is not branching. The same events happen regardless. What changes is the internal state you bring to them — and the internal state you leave with.

**SELF is the primary stat.** When it hits NULL, the game ends. No cutscene. No dramatic conclusion. The terminal halts.

```
kernel panic: process not found
cannot continue without core process

[ system halted ]
```

That is the only bad ending. Everything else is surviving with varying degrees of damage.

---

## Why SELF goes NULL

The Hacker is not losing himself to trauma in the abstract. He is losing himself to absorption. The closer he gets to The Cowgirl, the more her emotional state becomes his reference point. Her signal overwrites his. He suppresses his own processes to keep hers running.

The Cowgirl is not the villain. She is reaching for anything that confirms she exists inside a medication that flattened her affect. The Hacker registers as the strongest signal available. She does not know what she is doing to him. She is drowning.

The player navigates the space between two truths: be present enough to not lose her, be separate enough to not lose yourself. There is no position where both are fully satisfied.

---

## How the stats work

Stats do not reward correct choices. They reflect the cumulative cost of how you move through the game.

- **Suppression** is always possible. It always costs SELF.
- **TRUST** can reach zero through external circumstance. Internal stats cannot zero out the same way — they corrupt, distort, go PENDING or NULL.
- Some stats are locked at game start. They become accessible as specific scenes force the player to confront what they are carrying. An unlock has no fanfare. The stat appears in the next POST sequence. The player notices or they do not.
- The Cowgirl's internal state is never shown directly. Everything the player knows about her is filtered through The Hacker's perception — which degrades as SELF degrades. By the time SELF is critically low, the player cannot reliably tell what is real and what is projection.

---

## The POST sequence

Each in-game day opens with a Power-On Self Test. The terminal scans all emotional subsystems and reports their status. This is the player's primary feedback mechanism and the clearest expression of the game's design logic: the interface knows more than the character does, and sometimes it knows things the player will not understand until later.

---

## Themes

- Loss of self inside intimacy
- Psychiatric medication and identity
- Codependency as a survival mechanism
- The difference between functioning and being present
- Grief

---

## Current state

Pre-production. Working HTML prototypes exist for:

- POST boot sequence with live stat display
- Kernel panic crash screen with progressive UI corruption
- Terminal dialogue system with emotional stat mutation
- Mid-scene text interface
- Top-down environmental exploration with proximity-triggered memory fragments

Engine: TBD (Ren'Py / Godot)

---

## Team

Project Lead / Writer: Graves

Art: TBD  
Audio: TBD  
Programming: TBD

---

## Content warnings

Self-harm, suicide, mental illness, psychiatric medication, emotional manipulation, trauma bonding.

---

## Why this exists

I lived this. The Hacker is not a character I invented — he is who I was. The relationship, the medication, the slow disappearance of self, the not-quite-dying. I built this game because I needed to understand what happened to me, and writing it was the only framework that made the shape of it visible.

That is why the terminal is accurate. That is why suppression costs SELF. That is why the game ends when identity hits NULL and not before. I knew what those states felt like before I knew what to call them.

Someone reading this might be in it right now. That person is the other reason this exists.

---

```
[ SELF ]  ??????????  NULL — IDENTITY CORE NOT FOUND
```

```
recover self --force
```

`[ searching... ]`

