# 365 Days of Commit

> Code anywhere, Commit everyday. My personal coding challenge for 2020.

**Day 0: December 31, 2019**

2020 is just starting tomorrow. I'm having mixed feelings about it. This is the year I will be in my 30s and at the same time my salary will be frozen due to company circumstances. Well...so I decided to make some slight changes in my life. I will **commit** and **push** code to my github repository, and **write** what I did at here **every single day** in this year. The code will be mainly related to my interests or my personal projects, and I will try not to bring the code at work here. All kinds of feedback like comments and PR are always welcome, and please point out if there is a grammar error, since English is not my native language. This project is highly inspired by the daily coding project called **[100-days-of-code](https://github.com/kallaway/100-days-of-code)**.

---

### Day 1: January 1, 2020 (Wed)

**Today's Focus**: Learn and code [SWR](https://swr.now.sh/).

**Details**:

- Recently I heard a lot about a stack called [SWR](https://swr.now.sh/), a React Hooks library for remote data fetching. It has a lot of feature that I want, such as caching, revalidation, and local mutation for optimistic UI. (looks similar to Apollo...) So I decided to learn it.
- Today, I tried to read the document and write basic data fetching and global configuration code.
- I made a repo called [doodles](https://github.com/30in2020/doodles). All the code from my personal study will be uploaded here.

**Commits**:

| Message                                                                                                                                   | Tags                         |
| ----------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------- |
| [Feat: create swr-experiment directory](https://github.com/30in2020/doodles/commit/e6bd9624509fcfdfab2ec55d0785be78d6352c64)              | `Boilerplate`                |
| [Feat: try global config and data-fetch code of SWR](https://github.com/30in2020/doodles/commit/afe76513f98dd8f07027e68efb2444acba91013b) | `SWR`, `React`, `Typescript` |
| Chore: Add README.md                                                                                                                      | `Documentation`              |

**Links to work**:

- [Main repository](https://github.com/30in2020/doodles/tree/master/react/swr-experiment)

**Reference**:

- [SWR - Github Repository](https://github.com/zeit/swr)

---

### Day 2: January 2, 2020 (Thu)

**Today's Focus**: Continue learning [SWR](https://swr.now.sh/) library.

**Details**:

- Tried to use React.Suspense mode with [SWR](https://swr.now.sh/). By just passing `suspense: true` to useSWR's option parameter, it enabled me to use the mode.
- Also tried data fetching using GraphQL. Used [GraphQLZero](https://graphqlzero.almansi.me/) for implementing fake APIs.

**Commits**:

| Message                                                                                                                                    | Tags                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------- |
| [Feat: use graphql fetching and suspense mode of swr](https://github.com/30in2020/doodles/commit/6f3a776a0b6f2e6fbd55bab48bf6055fdab945b3) | `SWR`, `React`, `GraphQL`, `React.Suspense`, `Typescript` |

**Links to work**:

- [Main repository](https://github.com/30in2020/doodles/tree/master/react/swr-experiment)

**Reference**:

- [SWR - Github Repository](https://github.com/zeit/swr)

---

### Day 3: January 3, 2020 (Fri)

**Today's Focus**: Learn how to make WebGL glitch effect with scroll interaction. Search a shader sample to use.

**Details**:

[![monokai_tokyo](./assets/Jan-03-2020_monokai_tokyo.gif "Monokai: a trip through Japan")](https://monokai.nl/2019/japan/)

> [Monokai: A trip through Japan](https://monokai.nl/2019/japan/)

- I found a cool project called 'A trip through Japan'. I love the way it uses shader effects for the character animation on background. I don't know the specific name of shaders, but it seems like using glitch and noise shader...just my assumption.
- Checked with the inspector and realized that the letters in front ('Tokyo' and caption) and behind (kanji) are separated into different layers. The former is DOM, and the latter is canvas using WebGL.
- With reference to this artwork, I'm going to make a similar one. (Instead, I wanted to make it using React as a precondition.) I searched the shader samples and found a good one I was looking for: [GlitchFilter](https://github.com/pixijs/pixi-filters/tree/master/filters/glitch) of [Pixi.js](https://www.pixijs.com/). I need to modify the original code to use it on react environment. I will do it tomorrow...
- By the way, today there was a first pull request from this account. 🎉

**Commits**:

| Message                                                                                                                               | Tags                             |
| ------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------- |
| [Feat: create glitch-with-sync-scroll directory](https://github.com/30in2020/doodles/commit/83e19350868533ec41307183dd2acb6f3ee516d3) | `Boilerplate`                    |
| [Feat: add PixiJS's GlitchFilter module](https://github.com/30in2020/doodles/commit/c4e8bdd162bf6a6b9a3ecc038c2333f7d43ce87a)         | `Graphics`, `Shader`, `WebGL`    |
| [Update unused method name in docs](https://github.com/30in2020/website/commit/e88a51fa08ac71d89a796a8498852ba5ca625ff4)              | `Documentation`, `PR`, `Flutter` |

**Links to work**:

- [Main repository](https://github.com/30in2020/doodles/tree/master/graphics/glitch-with-sync-scroll)

**Reference**:

- [Monokai: A trip through Japan](https://monokai.nl/2019/japan/)
- [Pixi filter Demo](https://pixijs.io/pixi-filters/tools/demo/)
