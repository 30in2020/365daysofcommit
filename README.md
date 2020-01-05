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

---

### Day 4: January 4, 2020 (Sat)

**Today's Focus**: Find a React renderer modules for three.js.

**Details**:

- There was a lot of three.js module using React, such as `react-three`, `react-three-renderer`, and `react-three-fiber`. I chose [`react-three-fiber`](https://github.com/react-spring/react-three-fiber) because it works fine in React v16, and it comes with a lot of hooks already.

**Commits**:

| Message                                                                                                                          | Tags                                             |
| -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| [Feat: add react-three-fiber, three module](https://github.com/30in2020/doodles/commit/6a3d0f70b38b83d74587296ca4de490eb134da2c) | `react-three-fiber`, `Boilerplate`, `Typescript` |

**Links to work**:

- [Main repository](https://github.com/30in2020/doodles/tree/master/graphics/glitch-with-sync-scroll)

**Reference**:

- [react-three-fiber: repository](https://github.com/react-spring/react-three-fiber)
- [Tutorial: react-three-fiber & typescript starter code](https://codesandbox.io/s/react-three-fiber-ho4i8?from-embed)
- [Tutorial: Write three.js in React Using react-three-fiber](https://alligator.io/react/react-with-threejs/)

---

### Day 5: January 5, 2020 (Sun)

**Today's Focus**: Add `useScrollPosition` hook.

**Details**:

- Added `useScrollPosition` hook, referring to [this article](https://dev.to/n8tb1t/tracking-scroll-position-with-react-hooks-3bbj). I learned some facts about Hooks which I didn't usually know, such as the difference between `useEffect` and `useLayoutEffect`, and when to use `useRef` instead of `useState`.
  - `useEffect` runs asynchronously and after a render is painted to the screen. That goes:
    1. You cause a render somehow (change state, or the parent re-renders) 2. React renders your component (calls it) 3. The screen is visually updated 4. THEN useEffect runs
  - `useLayoutEffect` runs synchronously after a render but before the screen is updated. That goes: 1. You cause a render somehow (change state, or the parent re-renders) 2. React renders your component (calls it) 3. useLayoutEffect runs, and React waits for it to finish. 4. The screen is visually updated
  - According to React Hooks reference guide, `useRef` is useful for more than the ref attribute. It’s handy for keeping any mutable value around similar to how you’d use instance fields in classes. If you want to use a stateful value that won't trigger re-render on each state change, use `useRef`.
- Refactored the `GlitchFilter` code to make it usable with React context.

**Commits**:

| Message                                                                                                                                          | Tags                           |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------ |
| [Feat: add useScrollPosition hook](https://github.com/30in2020/doodles/commit/a7b5fadee271ad44f101b494bac8234c34a43ee4)                          | `Hooks`, `React`, `Typescript` |
| [Refactor: make the GlitchFilter usable with React context](https://github.com/30in2020/doodles/commit/e6a54515e88c80dc58e911304a3a57ad53aa0521) | `Graphics`, `Shader`, `WebGL`  |

**Links to work**:

- [Main repository](https://github.com/30in2020/doodles/tree/master/graphics/glitch-with-sync-scroll)

**Reference**:

- [Article: When to useLayoutEffect Instead of useEffect](https://daveceddia.com/useeffect-vs-uselayouteffect/)
- [Tutorial: Tracking Scroll Position With React Hooks](https://dev.to/n8tb1t/tracking-scroll-position-with-react-hooks-3bbj)

---
