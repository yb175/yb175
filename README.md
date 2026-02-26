# yug

```txt
things i enjoy:
race conditions
broken tests at 2am
and systems that finally behave after 37 logs
```

i'm a cs undergrad building backend systems and occasionally fighting distributed chaos.

most of my time goes into understanding **why systems fail** — and then making sure they don’t fail the same way twice.

---

## currently doing

* contributing to **Talawa API** (open source backend)
* learning how real production systems stay consistent under concurrency
* building tools around developer workflows and automation
* solving dsa problems when i want to feel humbled

---

## what i like working on

* backend architecture
* concurrency & idempotency
* performance debugging
* workers, queues, and async pipelines
* making APIs reliable 

i’m less interested in shiny tech, more interested in **correct systems**.

---

## tech i reach for

```ts
C++ | TypeScript | JavaScript | Java

Node.js · GraphQL · PostgreSQL · Redis
Docker · Linux · GitHub Actions

React (when backend people are forced to touch UI)
```

---

## open source

**Talawa API**

worked on problems that appear only when real users exist:

* prevented duplicate records during concurrent requests
* fixed authorization logic blocking users from their own data
* stabilized recurring job processing
* added tests so future bugs have fewer places to hide

---

## project

### pull shark

an automated pull request reviewer powered by llms.

built around one rule:

> the same event should never be processed twice.

* webhook-driven system
* background worker pipeline
* idempotent processing
* reduced llm payload size by ~70%

---

## stats (because engineers secretly care)

* 500+ dsa problems solved
* leetcode rating: 1636

---

## learning right now

system design
distributed systems thinking
ci/cd & infra basics
writing code future-me won’t complain about

---

```cpp
while(true){
    learn();
    build();
    break();
    rebuild_better();
}
```
