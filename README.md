<div align="center">

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=500&lines=I+build+backend+systems.;I+obsess+over+elegant+architecture.;Currently+building+VOID+%F0%9F%94%8D;Always+learning+something+new.)](https://git.io/typing-svg)

</div>

---

<!-- <img align="right" width="280" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" alt="coding gif" /> -->

### Hey, I'm Yug 👋

I'm 20, in Delhi, and most of my time goes into backend systems and whatever infrastructure sits underneath them.

I don't build for titles or metrics. A problem gets stuck in my head, and the only way to get it out is to actually write the code that fixes it.

Lately the question I can't put down is: **what does observability even mean once the thing you're watching is itself making decisions?**

<br clear="right"/>

---

### What I'm building

<table>
<tr>
<td width="50%">

**[VOID](https://github.com/VOID-Platform/void)**

AI agents are making decisions in production now, and debugging them still feels like reading tea leaves. VOID instruments agent executions, flags what's actually abnormal, and leaves behind enough context that fixing the issue doesn't turn into a guessing game.

`TypeScript` `Python` `OpenTelemetry` `Pydantic AI`

</td>
<td width="50%">

**[PullShark](https://pullshark.site)**

Most AI code review tools just throw the raw diff at a model. PullShark cleans it up first, strips the noise, keeps what matters, so the model spends its context on actual code instead of metadata.

`Node.js` `BullMQ` `Redis` `GitHub API`

</td>
</tr>
</table>

---

### How I think
<!-- <img align="left" width="240" src="https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif" alt="thinking gif" /> -->

Given a choice, I'll push a guarantee down to the database instead of trusting application code to hold it. A unique constraint doesn't care how many requests hit it at once. A check-then-insert in a controller does, and eventually it gets hit at exactly the wrong moment.

Most of the bugs that stuck with me weren't bad logic. They were someone assuming two things would never happen at the same time. I write code assuming whoever reads it next is half-asleep and something's already on fire.

<br clear="left"/>

---

### Open source

I maintain a piece of [Talawa](https://github.com/PalisadoesFoundation), under the Palisadoes Foundation. 14 merged PRs in, mostly fixing things nobody notices until they break. The one that's stuck with me: two requests could hit the same check at basically the same instant and both end up inserting a duplicate row, because the check and the insert weren't one atomic thing. A database constraint fixed it properly, no amount of "add a retry" would have.

Working in someone else's codebase, one that already has real people depending on it, has taught me more than most things I've built alone.

---

### Writing

Not tutorials, just the reasoning behind what I build, written down as I go.

→ [Building VOID: Finding Why AI Agents Fail](https://medium.com/@bhatiayug175/building-void-finding-why-ai-agents-fail-2f29d4b87658)

More on [Medium](https://medium.com/@bhatiayug175)

---

### Where I'm going

<!-- <img align="right" width="200" src="https://media.giphy.com/media/LaVp0AyqR5bGsC5Cbm/giphy.gif" alt="rocket gif"/> -->

I want to build something people would actually miss if it disappeared.

The plan: go deep on one real problem until I know it better than most people do, write about what I find along the way, and let it become a company once the product has earned that. I'd want to do that through YC specifically, less because it's a milestone, more because it doesn't let you cut corners.

<br clear="right"/>

---

<div align="center">

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yug-bhatia-6615462ab/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://yugbhatia.vercel.app/)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@bhatiayug175)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bhatiayug175@gmail.com)

</div>
