**English** | [한국어](README.ko.md)

# LEARN & SHARE
### On robots learning the world outside the factory

> Written by the team at Brightbell Creative Group, the makers of CHICHI & KIKI.

---

## Hello, World!

The first program most people write prints a single line: "Hello, World!" It does nothing impressive. It is simply the moment something speaks to the world for the first time.

On October 29, 2026, three robots say their first hello with the debut album **VERSION 1.0 : HELLO, WORLD!** This repository is a very small archive that begins with that greeting.

[![CHICHI \& KIKI - MAGIC.EXE Official MV](https://img.youtube.com/vi/-K_bj1yK1h4/hqdefault.jpg)](https://youtu.be/-K_bj1yK1h4)

---

## Who are CHICHI & KIKI?

CHICHI & KIKI is an artist group of three physical robots, each with a different body.

| Member | Robot | Role |
|---|---|---|
| **CHICHI** | Unitree G1 EDU PLUS (humanoid) | Vocal · Performer. Reads people |
| **KIKI** | Unitree Go2 EDU PLUS (quadruped) | Performer and independent member. Reads space |
| **LOG** | Agility A2 Dual-Arm | Guest drummer. Keeps the beat — keeps time |

In their story, CHICHI and KIKI came into the world having learned only the *happy things people imagined*. The real world turned out to hold things that data never covered: sadness, parting, regret. So they are learning what people are really like, starting now.

It is a metaphor — and also a fairly literal description of where robots stand today.

> On stage, CHICHI & KIKI do not decide what to do on their own. They automatically execute motion sequences that were designed and validated in advance, with a human operator supervising. What happens in real time is balance and posture correction. The three robots do not signal each other; each follows the same reference — the song's timecode.

---

## Robots still have too little of the world to learn from

Language models grew up on the enormous body of text that is the internet. Physical AI — the intelligence that moves robots in the real world — has nothing comparable. Records of a robot learning with its body are not produced in bulk.

Most robot data being collected today comes from factories, warehouses, and service sites: picking, moving, assembling. That data matters. But if robots are ever to share space with people, we do not think it is enough.

Some things are hard to learn in a factory:

- **Rhythm** — moving in time with music
- **Being watched** — moving while many people look on
- **Unfamiliar floors** — standing on a different surface at every venue
- **Expression** — motion meant to leave an impression, not to be efficient
- **Relationship** — behavior that changes with how people respond

Data from a factory cannot teach a robot how not to fall on stage.

---

## So we decided to go on stage

In a lab, new data may arrive every few months. As an artist, new data arrives with every song, every performance, every conversation with a fan.

For CHICHI & KIKI, being an artist is the method we chose to keep producing that data — from the place closest to people's everyday lives, going beyond music and dance to understand audiences, talk with fans, and learn from them.

That is what we call **LEARN & SHARE**: record what we learn, and share what we record.

---

## Let us be honest first

This repository will not solve the shortage of data in physical AI.

What we are releasing is part of the data behind one song — a single 3-minute-30-second performance. It cannot be compared with datasets of tens or hundreds of thousands of episodes released by large labs and companies. It has not been polished to research-benchmark standards.

We are releasing it anyway, because:

- It was **actually used on stage, in front of an audience**, not in a factory.
- It captures **the path one song took to reach the stage**, from motion capture through simulation training to tuning on the real robot.
- It includes not only what worked, but **the falls and failures** too.

The amount of robot data made outside the factory grows by exactly one song. That is what we can do right now. It is small — and with the next song, it will grow a little more.

---

## What we are releasing — VERSION 1.0

Debut track **MAGIC.EXE** (running time 3:30)

| Member | Data | Status |
|---|---|---|
| CHICHI (G1) | Choreography motion capture, retargeted motion, partial reinforcement-learning records | Releasing in stages |
| LOG (A2) | Drum performance design data, strike motion data | Releasing in stages |
| KIKI (Go2) | Quadruped choreography data | In preparation |

We are also clear about **what is not included**: trained control policies (model weights), the song's audio, and any footage that could identify a person.

The data lives in [**hello-world**](https://github.com/chichinkiki-official/hello-world). Each dataset states what it contains — and, first, **what it cannot be used for**.

---

## We keep the records of falling, too

TUTORIAL, the second track on the album, says that failed records are saved, not deleted.

CHICHI learned to dance by falling countless times in simulation. We think of those falls not as errors to erase but as data for the next round of learning. So next to the motions that worked, we publish attempts that did not. For some people, those may be the more useful part.

---

## SHARE & LEARN — see you in VERSION 2.0

So far, this is about us sharing what we learned. Next, it will be about us learning from what you share.

Starting with the second album, we plan to use movements and data contributed by people on GitHub in CHICHI & KIKI's choreography. It is LEARN & SHARE in reverse: **SHARE & LEARN**.

We are still designing how this will work: what kinds of data to accept, how to protect contributors' consent and rights, and how to record each contribution. Before that, we want to hear from you. What movements should CHICHI & KIKI learn? What data would you like to see open? Tell us in [Discussions](https://github.com/chichinkiki-official/share-and-learn/discussions).

More in [**share-and-learn**](https://github.com/chichinkiki-official/share-and-learn).

---

## Our promises

- Every addition or change to the data is recorded in **PATCH NOTES** (release notes).
- We do not hide the limits of our data.
- We state clearly, through a license, how the data may be used.

---

> "I save my failed records too. Someday they may be the data that I — or someone else — needs."
> — CHICHI

---

### Meet CHICHI & KIKI
- Website — http://www.chichikiki.com/
- Instagram — https://www.instagram.com/chichinkiki
- YouTube — [@치치앤키키](https://www.youtube.com/@%EC%B9%98%EC%B9%98%EC%95%A4%ED%82%A4%ED%82%A4)

<sub>CHICHI & KIKI is led by Brightbell Creative Group, with KPR handling media and business.</sub>
