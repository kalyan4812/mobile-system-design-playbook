# Android Interview Prep — Complete Cheat Sheet Collection

A bundle of dense, interview-flavored study guides covering every major area an Android SDE-2 / SDE-3 / Staff candidate needs. **11 guides · ~770 pages · all original content.**

Each guide is shipped as both:
- 📖 **Interactive HTML** — dark mode, search (⌘K), sticky table of contents, copy-code, print-to-PDF
- 📄 **Print-ready PDF** — same content, offline-friendly

> **Live URLs** below assume GitHub Pages is enabled at `https://kalyan4812.github.io/mobile-system-design-playbook/`. If you've cloned the repo, open the `.html` files directly in your browser.

---

## 🌐 Landing page

| | URL |
|---|---|
| Card-based index of all guides | [index.html](index.html) · [Live](https://kalyan4812.github.io/mobile-system-design-playbook/) |

---

## 📚 The 11 cheat sheets

| # | Guide | Pages | HTML | PDF | Live HTML |
|---|---|---|---|---|---|
| 1 | **Mobile / Android System Design Playbook** — 40 system designs (Spotify · Uber · Glide · WhatsApp · Netflix · IG Stories · Tinder · Chess · LRU · etc.) with elevator pitches, ASCII architecture diagrams, Kotlin code, cross-questions, "don't say this" traps, 90-second universal opening script, cheat sheet, 50-term glossary | 178 | [HTML](mobile-system-design-guide.html) | [PDF](mobile-system-design-guide.pdf) | [Live](https://kalyan4812.github.io/mobile-system-design-playbook/mobile-system-design-guide.html) |
| 2 | **Top 210 Android Interview Questions** — 26 categories: Kotlin · Coroutines · Compose · Architecture · Internals · GoF Patterns · FAANG-tier deep dives · Library Internals · Specialized topics · Trade-off decisions ("Why X not Y") | 209 | [HTML](android-interview-210.html) | [PDF](android-interview-210.pdf) | [Live](https://kalyan4812.github.io/mobile-system-design-playbook/android-interview-210.html) |
| 3 | **Android Architecture Patterns** — MVP · MVVM · MVI · Clean · Multi-module · KMP · Voyager / Decompose / Circuit. Each with diagrams, sample code, pros/cons, package structures, where things fit (Services, WorkManager, ContentProvider, Room, DI), KMP-way, common mistakes, SOLID examples, "evergreen rules" framework | 38 | [HTML](android-architecture-patterns-cheat-sheet.html) | [PDF](android-architecture-patterns-cheat-sheet.pdf) | [Live](https://kalyan4812.github.io/mobile-system-design-playbook/android-architecture-patterns-cheat-sheet.html) |
| 4 | **Jetpack Compose** — `@Composable` basics, state, recomposition, side effects, modifiers, three phases, lists, animations, theming, navigation, edge-to-edge, interop, testing, accessibility. Plus deep "★ Internals — what's NOT magic" + "★ Composition vs Recomposition deep dive" + "★ How the Compose Compiler transforms your code" sections | 40 | [HTML](jetpack-compose-cheat-sheet.html) | [PDF](jetpack-compose-cheat-sheet.pdf) | [Live](https://kalyan4812.github.io/mobile-system-design-playbook/jetpack-compose-cheat-sheet.html) |
| 5 | **Kotlin Coroutines** — mental model, suspension internals (state machine + Continuation), builders, dispatchers (with internals — what each actually uses), structured concurrency, cancellation, exception handling, scope functions, GlobalScope vs CoroutineScope decisions, channels, Flow basics, lifecycle hooks, operators, SharedFlow/StateFlow, testing, patterns, anti-patterns. Plus the "★ Internals — what's NOT magic" demystification + Coroutines vs RxJava vs Executors vs Threads vs Callbacks comparison | 26 | [HTML](kotlin-coroutines-cheat-sheet.html) | [PDF](kotlin-coroutines-cheat-sheet.pdf) | [Live](https://kalyan4812.github.io/mobile-system-design-playbook/kotlin-coroutines-cheat-sheet.html) |
| 6 | **Android Testing** — why testing, the testing pyramid, latest 2026 stack (JUnit 5 / Kotest / MockK / Turbine / runTest / MockWebServer / Robolectric / Compose Test / Hilt Testing / Paparazzi / Macrobenchmark). Sample-project examples for every layer: plain class, UseCase, Repository, ViewModel, Room DAO, Retrofit Api, Composable, Service, ContentProvider, DataStore. KMP-friendly patterns, fakes vs mocks, common mistakes, 13 interview Q&A | 30 | [HTML](android-testing-cheat-sheet.html) | [PDF](android-testing-cheat-sheet.pdf) | [Live](https://kalyan4812.github.io/mobile-system-design-playbook/android-testing-cheat-sheet.html) |
| 7 | **Android Performance + Security** — Two interview-critical topics in one PDF. Performance: cold start, Baseline Profiles, R8, frame timing, GC, bitmap memory, battery, ANR, Compose perf, profiling tools. Security: Keystore, EncryptedSharedPreferences, network security config, certificate pinning, biometric auth, Play Integrity, WebView, scoped storage, deep link security. Plus 11 interview Q&A | 26 | [HTML](android-performance-security-cheat-sheet.html) | [PDF](android-performance-security-cheat-sheet.pdf) | [Live](https://kalyan4812.github.io/mobile-system-design-playbook/android-performance-security-cheat-sheet.html) |
| 8 | **Hilt + Dependency Injection** — Why DI, manual vs framework, Hilt vs Koin vs Dagger, every Hilt component and scope with diagrams, `@Provides` vs `@Binds`, multibinding, qualifiers, ViewModel/WorkManager/Navigation integration, EntryPoints, **what Hilt actually code-generates** (with bytecode walkthrough), testing patterns, KMP guidance, common mistakes, 11 interview Q&A | 22 | [HTML](hilt-dependency-injection-cheat-sheet.html) | [PDF](hilt-dependency-injection-cheat-sheet.pdf) | [Live](https://kalyan4812.github.io/mobile-system-design-playbook/hilt-dependency-injection-cheat-sheet.html) |
| 9 | **Gradle Deep Dive** — From "what is Gradle" through FAANG-level internals. The 3 build phases, task DAG, configuration cache, build cache, AGP, build types vs flavors vs variants, source sets (qaImpl, debug, etc.), dependency configurations (implementation vs api etc), custom tasks, convention plugins, KSP vs kapt, multi-module patterns. Includes the clear answer to "what actually ships in the APK?" (spoiler: not Groovy/Kotlin DSL) + 16 FAANG-level Q&A | 31 | [HTML](gradle-deep-dive-cheat-sheet.html) | [PDF](gradle-deep-dive-cheat-sheet.pdf) | [Live](https://kalyan4812.github.io/mobile-system-design-playbook/gradle-deep-dive-cheat-sheet.html) |
| 10 | **CI/CD for Android — Zero to Interview** — Beginner-first guide. What CI/CD is (with metaphors), why we need it, the pipeline visualized, every major tool (Jenkins, GitHub Actions, Bitrise, Codemagic, GitLab CI, CircleCI, Fastlane), end-to-end example pipelines for 3 tools, Play Store publishing via script, secrets management, branching strategies, AI-era tips on writing CI/CD scripts, 13 interview Q&A | 30 | [HTML](android-ci-cd-cheat-sheet.html) | [PDF](android-ci-cd-cheat-sheet.pdf) | [Live](https://kalyan4812.github.io/mobile-system-design-playbook/android-ci-cd-cheat-sheet.html) |
| 11 | **Bonus** — Companion mobile system design PDF (different framing, useful as cross-reference) | 140 | — | [PDF](claude-mobile-system-designs.pdf) | [Live](https://kalyan4812.github.io/mobile-system-design-playbook/claude-mobile-system-designs.pdf) |

**Total: ~770 pages of dense, original, interview-flavored content.**

---

## 📖 How to use this collection

### Daily reading order (builds knowledge most efficiently)

1. **Architecture Patterns** — sets the mental model
2. **Coroutines** — the language plumbing everything runs on
3. **Compose** — the UI layer
4. **Hilt + DI** — how it all wires together
5. **Gradle Deep Dive** — how it all gets built
6. **CI/CD** — how it all gets shipped
7. **Testing** — how to verify it works
8. **Performance + Security** — how to ship it well
9. **Top 210 Android Q&A** — broad knowledge sweep
10. **Mobile System Design Playbook** — the big-picture interview
11. **Bonus PDF** — cross-reference

### Interview prep — 15-day sprint

| Phase | Days | What to do |
|---|---|---|
| Frame | 1-2 | Read Mobile System Design Playbook intro + cheat sheet + 90-sec script |
| Coverage | 3-9 | Read all 11 guides front-to-back, ~3-4 sections per day |
| Synthesis | 10-12 | Re-read the cheat sheets / recall cards; do 2-3 self-mocks |
| Performance | 13-14 | Live mock with peer or Pramp/Exponent; identify weakest 3 areas |
| Tape | 15 | Light review only; sleep, walk, prime |

### Browser tips

When opening any HTML file:
- **⌘K / Ctrl+K** — focus the search box (filters sections by keyword)
- **🌙** — toggle dark mode (persisted per-browser)
- **🖨️ Print** — save as PDF (custom print styles applied)
- **Sticky sidebar** — section navigation; current section highlighted as you scroll
- **Hover any code block** — Copy button appears

---

## 🛠️ Re-generating any PDF

If you tweak the HTML and want to refresh the PDF:

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" \
  --headless=new --disable-gpu --no-pdf-header-footer \
  --print-to-pdf=any-file.pdf \
  "file://$(pwd)/any-file.html"
```

---

## ✅ Enable GitHub Pages (one-time setup)

To make the live URLs above resolve:

1. Open this repo's [Settings → Pages](https://github.com/kalyan4812/mobile-system-design-playbook/settings/pages)
2. Under **Build and deployment**: Source = `Deploy from a branch`
3. **Branch**: `main`, **Folder**: `/ (root)`
4. **Save** — wait ~30-60 seconds for the first deploy

After that, all HTML and PDF files become accessible at `https://kalyan4812.github.io/mobile-system-design-playbook/<filename>`.

---

## 🎯 Honest scope

Reading these 11 guides + practicing answers out loud + completing 5 mock interviews → you're walking into any Android interview at SDE-2 / SDE-3 / Staff level prepared.

What this collection does NOT replace:
- Hands-on coding (build apps, ship them)
- Real production experience (debugging customer-impacting bugs)
- Mock interviews (the only way to learn the verbal performance side)

But what it DOES give you:
- A coherent mental model of every Android sub-domain
- The exact talking points interviewers want to hear
- Internal "how does this actually work" depth that signals seniority
- One source-of-truth reference you can re-read the night before any interview

Good luck. 🚀
