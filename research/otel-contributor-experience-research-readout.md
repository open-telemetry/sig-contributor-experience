# Improving the New Contributor Experience

**OpenTelemetry Contributor Experience Research Readout — February 2026**
Amy Super, Maintainer, Contributor Experience SIG ([@amy-super](https://github.com/amy-super))

Identifying opportunities to improve the experience for new contributors to the OpenTelemetry project.

## Contents

- [Study overview](#study-overview)
- [High-level takeaways](#high-level-takeaways)
- [Participant overview](#participant-overview)
- [Detailed findings](#detailed-findings)
- [Suggestions summary](#suggestions-summary)

---

## Study overview

### Why are we here?

In a community survey, we heard that people were excited to contribute but got stuck taking those first steps. Contributing to open source can feel daunting, and we want to change that.

The survey results uncovered some challenges, and we're grateful that the data helped us understand that. Now, we'd like to learn more about why those things are challenging.

We wanted to understand what's working well, where people are having issues, and how we can better support community members who want to get involved.

### What were we trying to learn?

- Where do people go when they want to get started contributing to OpenTelemetry?
- What worked for them?
- What didn't work for them?
- Did they reach out to others for help?
- What suggestions do they have for improving the getting started experience?

### A quick note!

This research was qualitative, and gives us:

- In-depth understanding and emergent patterns
- A shared reality to work from
- The "what" and "why" with regard to contribution and friction points

This research was not quantitative, and does not give us:

- A prediction about "how many…" or "how often…"

---

## High-level takeaways

### New contributor opportunities summary

1. **Knowing where to begin** — I'm excited to get started, but I get overwhelmed and don't know how exactly to dive in.
2. **Open source etiquette** — I'm new to open source. Can I just join a SIG meeting? Raise a PR? Pick up an issue?
3. **Understanding the ecosystem** — Once I figure out the first steps, it's intimidating to understand where my work will be helpful.
4. **Account for diverse learning styles** — There's a ton of great information out there, but it requires a lot of reading. Are there other ways I can learn?

---

## Participant overview

*In the sections that follow, participants are identified by a participant number (e.g., P7, P19).*

### Recruiting and participation

In our blog post calling for research participants, we emphasized that we wanted to talk to new contributors. This was misconstrued by some as "we're going to help new contributors" rather than "we want to ask questions of new contributors."

The blog post went out in mid-December, but most interviews were scheduled for the first two weeks of January. This may have contributed to a high rate of people who signed up but did not attend the scheduled call (only 12 of 35 people attended).

That said, we were aiming to talk with 10 people total, so we had plenty of data from which to draw findings.

### Motivation

We asked participants why they are interested in contributing to OpenTelemetry:

- 7 said they are motivated by personal interest in observability and OpenTelemetry
- 4 said they are motivated by wanting to learn and improve their own skill sets
- 2 said they are participating as part of their job
- 2 said their contributions are to help them solve a problem or get unstuck with OpenTelemetry tooling

### Experience level

We asked participants how long they've been working with or on technology or observability. There was an almost even split between:

- Beginners or students (ranging from technology students to people who had never used GitHub)
- 2-3 years of experience, comfortable with opening PRs and using GitHub
- Very experienced, working with technology every day

### Open source participation

When asked if they were contributing to other open source projects:

- Half are participating with OTel only
- Half either have or are currently contributing to other projects

### What resources did people try?

| # of participants | Resource | Positives | Challenges |
|---|---|---|---|
| 4 | opentelemetry.io | Documentation is helpful | Hard to know where to begin, lots of reading |
| 4 | GitHub | "Good first issue" is a nice entry point, documentation is good | Good first issues don't help people get deeper into the domain, ecosystem is overwhelming, hard to know where to start, etiquette unclear |
| 4 | Slack | Community is helpful and responsive | So many Slack channels that it's hard to know where to start |
| 2 | Mentors | Personalized attention and encouragement | Dependent on availability of more experienced contributors |
| 1 | YouTube | Easy to find | Content is focused on end users rather than contributors |
| 1 | LinkedIn | Content is served up — people don't need to go looking for it | Content is focused on end users rather than contributors |
| 1 | Local meetups | Very personal and hands-on | Dependent on being in a location that has meetups |

---

## Detailed findings

### Knowing where to begin

Three participants joined the call expecting it to be a how-to walkthrough for getting started (P7, P11, P34). Three participants answered our questions but also requested help (P12, P19, P29). Two participants canceled the call once they realized we were going to ask questions of them, rather than the other way around.

Some illustrative moments from the interviews:

> Okay, and when you got stuck on that first issue, did you reach out to anybody in Slack or with some other method?
> **P7:** No.
> Okay. If you wanted to, do you know how to reach out to anyone?
> **P7:** No. Can you guide me? How can I reach out on the Slack?

> Have you gone to look for information about how to contribute?
> **P11:** No. So I thought this kind of call would help me there.

> **P12:** Where should I start with if I want to do open source contribution here?

> **P34:** Now I wanted to see how which areas I can contribute — I haven't started anything… So I just wanted to kick off and get an idea how to get started, or which areas I might be able to do something where it makes more value. So that's why I looked at the calendar, that's how I was able to schedule and we are meeting now.

**What people are asking for:**

- Some extremely basic information on how to get started (P8, P19, P29)
- Guidance for how to be helpful — each SIG sharing clear information about their priorities

> **P19:** So maybe if there's a better way of bringing in more people to get into committing real changes, not just documentation or some readmes or stuff like that — because I know it gives you a GitHub activity on my profile, but if I contribute actively, it will be more promising and accomplishing, is what I thought.

### Understanding the ecosystem

Multiple participants described the ecosystem as "vast," "large," or "complex." This made it difficult for newcomers to know where their contributions would be welcome or helpful.

> Okay, and so you found the tag that says good first issue. And did you choose an issue then to work on?
> **P7:** I opened the contributing MD file, but it assumed that I already had a very high level of understanding of the OpenTelemetry specifications.

> **P10:** For me, just knowing how to navigate Slack, how to navigate the committee and the hierarchy and how things work… for someone very new in tech, it might be different. It's not a problem for me to fork a project, create a branch, create a PR — that's easy — but maybe for some people that can be daunting. Like, how do I contribute a new page here?

> **P19:** Due to the vastness there are many components involved. So sometimes getting the right understanding of the project is more important in this case, rather than plugging in something and contributing.

> **P29:** The ecosystem is a large one and I'm not clear on which repository is best for beginners. And some assumptions in the documentation could be clarified.

**What people are asking for:**

- An ecosystem overview
- Links to content that helps with working in GitHub

> **P19:** I think sometimes I felt the OTel, or maybe other larger CNCF applications, are pretty vast. And even though I am experienced in general, I still feel the process of getting into starting PRs could be a little more handheld. Given that there's very good documentation of OTel since it's vast, I think maybe breaking it down from a new contributor perspective would be helpful.

### Open source etiquette

Participants who are newer to working in open source were unclear on the etiquette (P19, P11). Even seasoned contributors could see where people might feel unsure (P10).

> **P19:** How much of a commitment can I expect if I dig into being a contributor? I also wanted to understand what a typical day looks like — should I get involved daily? Or, let's say if it's my side gig and I just want to use my spare time. And from the point of view of attending or being part of SIGs, is there any minimum level of expectation for contribution?

> **P11:** I just wanted to understand — can I pick any issue randomly, go through the list of issues, and identify one I can fix and pick up? Is that how it works?

> **P10:** I already had this concept, so for me it wasn't that difficult to see that you need to join this meeting and that channel. But I suspect for people who've never worked with CNCF, it might be more difficult to navigate where you have to go. What's the etiquette — should I say something in the Slack channel? Should I join the meeting or not? For me, I guess I didn't care that much, and I know I can join the meetings now, but I don't know if other people will feel the same way.

**What people are asking for:**

- Basic "getting started" information that explains how to work in open source overall, or a link to such information
- Encouragement for SIG members to include and interact with newcomers in meetings

> **P10:** I tried to go to a SIG meeting and it was a little bit weird… They didn't even say hi. They didn't ask why I was there. I felt like I was joining a call where they were already talking between themselves, and they never stopped talking about the things [they were discussing].

### Diverse learning styles

#### Video content

People found the OTel end-user videos, but contribution information is very text-heavy. There's an opportunity to provide different formats, perhaps by learning from how the End User SIG works (P8, P27, P29).

> **P27:** Documentation is there, and for some people it's easy to read and follow, but most of them need some video content that can guide them — like, this is the thing, or you need to go through these steps, and that's how your first contribution is done.

> **P29:** For me I would prefer videos. Because once I watch and do that step by step from what the video is all about, and then do it myself, this increases my understanding and I grasp the concept faster and more easily.

#### Mentoring

Users who worked with a mentor had very positive feedback and experience (P8, P10; also suggested by P27).

> **P10:** [An OTel member] was so welcoming. When I said I'd like to contribute, she immediately reached out to me personally and asked if we could do a call and chat. She shared a page she'd created explaining how to actually contribute, and it was so easy to start. It's so welcoming and friendly that you really feel like you're part of the team immediately.

> **P8:** I was looking for a place where I could contribute. One of my former colleagues was our great mentor and was very helpful to the entire group of us who were interested in OpenTelemetry — he helped us a lot to get started.

> **P27:** Maybe if we could have some of the more experienced people help new beginners while they're trying to contribute — like a 101 program. In the same way Kubernetes has their LFX mentorship program, we could have mentors set up in a similar way.

---

## Suggestions summary

- Create extremely basic getting-started information that includes:
  - Guidance for how to be helpful
  - Etiquette for contributing to open source
  - An ecosystem overview
- Encourage SIG meetings to include and interact with newcomers
- Provide content in more formats, like video
- Encourage more LFX mentorships, and encourage more informal mentoring

---

## Thank you

To everyone who contributed to scheduling and conducting interviews:

Adrienne Caputo ([@ancaputo](https://github.com/ancaputo)), Ana Muenz ([@vampirarte](https://github.com/vampirarte)), Andrej Kiripolsky ([@AndrejKiri](https://github.com/AndrejKiri)), Brie Mignano ([@bmignano](https://github.com/bmignano)), Dmitry Nekrasovski ([@uxdmitryn](https://github.com/uxdmitryn)), Eric Lee ([@ericlee1111](https://github.com/ericlee1111)), Gianni Baiardi ([@giannicolab](https://github.com/giannicolab)), Husain Zaidi ([@hizaidii](https://github.com/hizaidii)), Julia Furst Morgado ([@juliafmorgado](https://github.com/juliafmorgado)), Kayla Reopelle ([@kaylareopelle](https://github.com/kaylareopelle)), Nat De Jesus Castillo ([@natydej](https://github.com/natydej)), Niat Hadgu ([@niat22](https://github.com/niat22)), Teddy Bartha ([@teddyba](https://github.com/teddyba)), Victoria Nduka ([@nwanduka](https://github.com/nwanduka))
