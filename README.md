# iOS-JIT-Enablers
A list of JIT Enablers for iOS and iPadOS.

**arm64 = A7-A11 | arm64e = A12+/M1+**

 | Supported OS Versions | JIT Enabler | OS for JIT Enabler | Supported SoC architecture | TestFlight available | Recommended | Shortcuts to make JIT enabling faster | Dylibs to make JIT enabling faster | More |
 |---------|---------|--------|-------|-------|-------|------|------|------|
 | 18.4b1 (22E5200s) | [JankJIT](https://gist.github.com/JJTech0130/142aee0f7bda9c61a421140d17afbdeb) | Likely MacOS-only | arm64🤷‍♂️,arm64e✅ |No| 🤷‍♂ |No|No|
 | 17.4 - 18.3.2 / 18.4b2 - 18.5 | [StikDebug](https://stikdebug.xyz) | iOS/iPadOS | arm64✅,arm64e✅ |[Yes](https://testflight.apple.com/join/8rHFcgzC)|  ✅ (recommended to use with SideStore) |[Yes](https://github.com/C4ndyF1sh/iOS-JIT-Enablers/releases/tag/StikJIT-Shortcuts)|No|
 | 17.4 - 18.3.2 / 18.4b2 - 18.5 | [StikJIT](https://github.com/StephenDev0/StikJIT) | iOS/iPadOS | arm64✅,arm64e✅ |No| ❌ |[Yes](https://github.com/C4ndyF1sh/iOS-JIT-Enablers/releases/tag/StikJIT-Shortcuts)|No|
 | 17.4 - 18.3.2 / 18.4b2 - 18.5 | [Guide](https://sidestore.io) + [SideStore "Nightly" build (required!)](https://github.com/SideStore/SideStore/releases/tag/nightly) | iOS/iPadOS | arm64✅,arm64e✅ |No| ✅ (Recommended to use with StikDebug) |No|No|
| 17.4 - 18.3.2 / 18.4b2 - 18.5 | [pymobiledevice3](https://github.com/doronz88/pymobiledevice3) (SideJITServer is just a pymd3 wrapper) | MacOS/Windows/Linux | arm64✅,arm64e✅ |No| ❌ (kinda old now and has been shown to be unstable on a lot of networks (same as SideJITServer) and is a pain to use) |No|No| 
| 17.4 - 18.3.2 / 18.4b2 - 18.5 | [JITStreamer-EB](https://github.com/jkcoxson/JitStreamer-EB) | iOS/iPadOS | arm64🤷‍♂️,arm64e✅ |No| ❌ |No|No|
 | 17.4 - 18.3.2 / 18.4b2 - 18.5 | [JITStreamer-2.0](https://github.com/jawshoeadan/JITStreamer-2.0) | Windows/MacOS | arm64🤷‍♂️,arm64e✅ |No| ❌ |No|No|
 | 14.2 - 18.3.2 / 18.4b2 - 18.5 | [Xcode](https://apps.apple.com/de/app/xcode/id497799835?l=en-GB&mt=12) | MacOS | arm64✅,arm64e✅ |No| ❌ (Requires an active Xcode Project but doesn't need to be the same one as the app) |No|No| if you want to do it via CLI [xcjit](https://github.com/wxwern/xcjit) |
 | ??? - 18.3.2 / 18.4b2 - 18.5 | [Guide](https://youtu.be/1LHTr3QZVwQ?si=esiE19BqI-aV7G49) + [UTM SE](https://apps.apple.com/de/app/utm-se-retro-pc-emulator/id1564628856?l=en-GB) | iOS/iPadOS | arm64🤷‍♂️,arm64e✅ |No| ❌ |No|No|
 | 17.4 - 18.3.2 / 18.4b2 - 18.5 | [app** JIT](https://www.youtube.com/watch?v=xvFZjo5PgG0) | MacOS | amr64🤷‍♂️,arm64e✅ |No| ❌ |No|No|
 | 17.0 - 18.3.2 / 18.4b2 - 18.5 | [SideJITServer](https://github.com/stossy11/SideJITServer) | Windows/MacOS | arm64🤷‍♂️,arm64e✅ |No| ✅ (if on 17.0.1 - 17.3.1, otherwise no)
 | 17.0 - ??? | [iOS17-JIT-WIN](https://github.com/fritzlb/iOS17-JIT-WIN) | Windows | arm64🤷‍♂️,arm64e✅ |No| ❌ |No|No|
 | 14.0b2 - 16.7RC (20H18) / 17.0b1 - 17.0 | [TrollStore](https://ios.cfw.guide/installing-trollstore/) | iOS/iPadOS | arm64✅,arm64e✅ |No| ✅ |No|[Yes](https://github.com/C4ndyF1sh/iOS-JIT-Enablers/releases/tag/TrollStoreJITEnabler.dylib)|
 | 14.0 - 16.7.x | [SideStore](https://sidestore.io) | iOS/iPadOS | arm64✅,arm64e✅ |No| ✅ (if on 16.7.x, otherwise no) |No|No|
 | ??? - 16.7.x | [Jitterbug](https://github.com/osy/Jitterbug) | iOS/iPadOS (requires a 2nd iDevice) | arm64🤷‍♂️,arm64e✅ |No| ❌ |No|No|
 | ??? - 16.7.x | [JITStreamer](https://github.com/jkcoxson/JitStreamer) | iOS/iPadOS | arm64🤷‍♂️,arm64e✅ |No| ❌ |No|No|
 | 14.0 - 16.7.x | [AltServer](https://altstore.io) | Windows/MacOS | arm64✅,arm64e✅ |No| ❌ |No|No|
 | 14.0 - 15.7.1 / 16.0 - 16.1.2 | [DirtyJIT](https://github.com/haxi0/DirtyJIT) | iOS/iPadOS | arm64🤷‍♂️,arm64e✅ |No| ❌ |No|No|
 | 16.5(.1)/16.6b1-b4 and lower for arm64e but for arm64 even 16.6 - 18.3.2 | for arm64e: [Jailbreak](https://ios.cfw.guide/get-started/) and for arm64 (if on 16.6-16.7RC/17.0b1-17.0 use normal TrollStore, otherwise use the following): [Jailbreak](https://ios.cfw.guide/get-started/)+[TrollStore Lite (search for it in Sileo/Zebra once jailbroken)](https://havoc.app/package/trollstorelite?srsltid=AfmBOorVtTrW_VvOq42bb8zsG4CeTtGi3VmoEmaAnFgiTEnWqeqfdLZs) | iOS/iPadOS | arm64✅,arm64e✅ |No| ✅ |No|No|

# What is "JIT" ?
JIT means "Just-In-Time Compilation", it makes emulators (which support JIT) run better/run at all or has other use cases in tools such as [LiveContainer](https://github.com/LiveContainer/LiveContainer) to launch iOS apps faster (by not having to sign them first with SideStore) which are installed into it. 

Read more [here](https://en.wikipedia.org/wiki/Just-in-time_compilation)
