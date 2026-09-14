# Ihar Leshchanka

**Frontend Developer with 5+ years of Android engineering background**

Warsaw, Poland

![Portrait photo of Ihar Leshchanka, frontend developer](profile.jpg)

## Contact Information

- **Location:** Warsaw, Poland
- **Email:** [ihar.leshchanka@gmail.com](mailto:ihar.leshchanka@gmail.com)
- **Phone:** [+48&nbsp;515&nbsp;008&nbsp;301](tel:+48515008301)
- **LinkedIn:** [linkedin.com/in/ileshchanka](https://www.linkedin.com/in/ileshchanka)
- **GitHub:** [github.com/ileshchanka](https://github.com/ileshchanka)
- **Discord:** ileshchanka

## Self-Introduction

I am a developer moving into frontend after 5+ years of building production mobile
applications. My Android background taught me what really matters in a user interface:
predictable state, reusable components, accessible layouts and measurable performance.
I am now applying the same habits to the web, writing TypeScript, semantic HTML and
modern CSS, and building Angular applications in my study projects.

I enjoy work where design and engineering meet — turning a mockup into a responsive,
maintainable interface, then refining it until it feels fast. I learn quickly, review
code carefully and communicate in English on a daily basis.

## Skills

### Frontend

- JavaScript (ES2015+), TypeScript
- Semantic HTML5, CSS3
- Responsive layout: Flexbox, Grid, media queries
- Angular, RxJS
- Vite, npm

### Android

- Kotlin, Java
- Jetpack Compose, Coroutines and Flow
- Hilt, Dagger 2, Koin, Retrofit, Room
- MVVM, Clean Architecture, modularization
- JUnit, Espresso, MockK, Robolectric

### General

- Git: GitHub, GitLab, Bitbucket
- CI/CD with GitHub Actions
- REST API, GraphQL
- Figma, Zeplin, Material Design
- Agile, Scrum, Jira, Confluence

## Code Example

My solution to the [Valid Parentheses](https://www.codewars.com/kata/52774a314c2333f0a7000688)
kata (5 kyu) on Codewars. A single pass over the string with a counter is enough: the
balance may never go negative, and it has to end at zero.

```js
function validParentheses(string) {
  let balance = 0;

  for (const char of string) {
    if (char === '(') {
      balance += 1;
    } else if (char === ')') {
      balance -= 1;
    }

    if (balance < 0) {
      return false;
    }
  }

  return balance === 0;
}
```

## Educational Projects

### Interview Trainer — Angular, TypeScript

A single-page application for practising technical interview questions: topic selection,
question flow and progress tracking, all kept in client-side state.

- [Source code](https://github.com/ileshchanka/interview-trainer)
- [Live demo](https://ileshchanka.github.io/interview-trainer/)

### Online Zoo — HTML, CSS, TypeScript, Vite

A multi-page marketing site built pixel by pixel from a Figma mockup, with a responsive
layout, an animated slider and a donation form.

- [Source code](https://github.com/ileshchanka/rsschool-online-zoo)
- [Live demo](https://ileshchanka.github.io/rsschool-online-zoo/)

### Film Collection — Angular, TypeScript

A catalogue of films with search, filtering and a details view, used to practise Angular
routing, services and reactive forms.

- [Source code](https://github.com/ileshchanka/angular-film-collection)

## Work Experience

### Android Developer — Appyfurious

*Mar 2024 – Aug 2025 · Remote*

- Developed and published a mobile application using Jetpack Compose, improving UI
  rendering performance by 30%.
- Designed reusable UI components and extended the internal UI Kit to keep several
  projects visually consistent.
- Worked closely with the product team on user flows, which doubled app engagement metrics.
- Contributed to an app that scaled from 1,000 to 100,000+ downloads within months.
- Refactored legacy UI logic and decreased the crash rate by 40%.

### Android Developer — Andersen

*Mar 2023 – Mar 2024 · Hybrid*

**Tele Doc — healthcare**

- Built features that let elderly patients monitor vitals and reach doctors over video calls.
- Integrated health data APIs and video call modules with Kotlin and Jetpack Compose.
- Worked with QA to find and fix key defects before the production launch.

**RMT Mobile — banking**

- Implemented payments, transfers and currency exchange in a secure mobile application.
- Wrote unit and integration tests, raising coverage to 85%.
- Took part in architectural decisions and planning sessions.
- Reduced feature delivery time by 25% through better component reuse.

### Android Developer — Solbeg_

*Feb 2020 – Mar 2023 · Hybrid*

**Flow Automotive**

- Created modules for booking services and tracking vehicle history.
- Integrated the Directions API and Google Maps for in-app navigation.
- Reviewed code and collaborated with QA and business analysts.

**MODD — medical IoT**

- Integrated insulin pump data into an Android app over BLE.
- Diagnosed and resolved connectivity issues during the rollout.

## Education

### Brest State A.S. Pushkin University

*2007 – 2012*

Bachelor of Physical Education.

## Professional Development

| Period | Course | Organization |
| --- | --- | --- |
| Jan 2026 – Aug 2026 | JS/FE Short Track 2026 Q1 | The Rolling Scopes School |
| Jul 2021 – Dec 2021 | Android Developer, Professional | OTUS |
| Jan 2021 – Jun 2021 | Android Developer, Basic | OTUS |
| Feb 2020 – Jul 2020 | Android Development | IT Academy |

## Languages

- **English** — B1+, daily working communication
- **Russian** — Native
- **Polish** — B1
