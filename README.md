# iOS-JIT-Enablers
A list of JIT Enablers for iOS and iPadOS.

**arm64 = A7-A11 | arm64e = A12+/M1+**

 | Supported OS Versions | JIT Enabler | OS for JIT Enabler | Supported SoC architecture | Recommended |
 |---------|---------|--------|-------|-------|
 | 18.4b1 (22E5200s) | [JankJIT](https://gist.github.com/JJTech0130/142aee0f7bda9c61a421140d17afbdeb) | Likely MacOS-only | arm64🤷‍♂️,arm64e✅ | 🤷‍♂
 | 17.4 - 18.3.2 / 18.4b2 - 18.5 | [StikDebug/StikJIT](https://github.com/StephenDev0/StikJIT) | iOS/iPadOS | arm64✅,arm64e✅ |  ✅ (recommended to use with SideStore)
 | 17.4 - 18.3.2 / 18.4b2 - 18.5 | [Guide](https://sidestore.io) + [SideStore "Nightly" build (required!)](https://github.com/SideStore/SideStore/releases/tag/nightly) | iOS/iPadOS | arm64✅,arm64e✅ | ✅ (Recommended to use with StikDebug)
 | 17.4 - 18.3.2 / 18.4b2 - 18.5 | [JITStreamer-EB](https://github.com/jkcoxson/JitStreamer-EB) | iOS/iPadOS | arm64🤷‍♂️,arm64e✅ | ❌
 | 14.2 - 18.3.2 / 18.4b2 - 18.5 | [Xcode](https://apps.apple.com/de/app/xcode/id497799835?l=en-GB&mt=12) | MacOS | arm64✅,arm64e✅ | ❌ (Requires an active Xcode Project but doesn't need to be the same one as the app)
 | ??? - 18.3.2 / 18.4b2 - 18.5 | [Guide](https://youtu.be/1LHTr3QZVwQ?si=esiE19BqI-aV7G49) + [UTM SE](https://apps.apple.com/de/app/utm-se-retro-pc-emulator/id1564628856?l=en-GB) | iOS/iPadOS | arm64🤷‍♂️,arm64e✅ | ❌
 | 17.4 - 18.3.2 / 18.4b2 - 18.5 | [app** JIT](https://www.youtube.com/watch?v=xvFZjo5PgG0) | MacOS | amr64🤷‍♂️,arm64e✅ | ❌
 | 17.0 - 17.3.1 - ??? | [SideJITServer](https://github.com/stossy11/SideJITServer) | Windows/MacOS | arm64🤷‍♂️,arm64e✅ | ✅ (if on 17.0.1 - 17.3.1, otherwise no)
 | 17.0 - ??? | [iOS17-JIT-WIN](https://github.com/fritzlb/iOS17-JIT-WIN) | Windows | arm64🤷‍♂️,arm64e✅ | ❌
 | 17.0b1 - 17.0 | [TrollStore](https://ios.cfw.guide/installing-trollstore/) | iOS/iPadOS | arm64✅,arm64e✅ | ✅
 | 14.0 - 16.7.x | [SideStore](https://sidestore.io) | iOS/iPadOS | arm64✅,arm64e✅ | ✅ (if on 16.7.x, otherwise no)
 | ??? - 16.7.x | [Jitterbug](https://github.com/osy/Jitterbug) | iOS/iPadOS (requires a 2nd iDevice) | arm64🤷‍♂️,arm64e✅ | ❌ 
 | ??? - 16.7.x | [JITStreamer](https://github.com/jkcoxson/JitStreamer) | iOS/iPadOS | arm64🤷‍♂️,arm64e✅ | ❌ 
 | 14.0 - 16.7.x | [AltServer](https://altstore.io) | Windows/MacOS | arm64✅,arm64e✅ | ❌
 | 14.0b2 - 16.7RC (20H18) | [TrollStore](https://ios.cfw.guide/installing-trollstore/) | iOS/iPadOS | arm64✅,arm64e✅ | ✅
 | 14.0 - 15.7.1 / 16.0 - 16.1.2 | [DirtyJIT](https://github.com/haxi0/DirtyJIT) | iOS/iPadOS | arm64🤷‍♂️,arm64e✅ | ❌
 | 12.0 - 16.5(.1)/16.6b1-b4 | [Jailbreak (Not all Jailbreaks support JIT enabling)](https://ios.cfw.guide/get-started/) | iOS/iPadOS | arm64✅,arm64e✅ | ✅
 |↪️ 16.6 - 18.3.2 | [Jailbreak](https://ios.cfw.guide/get-started/) + [TrollStore Lite (search for it in Sileo/Zebra once jailbroken)](https://havoc.app/package/trollstorelite?srsltid=AfmBOorVtTrW_VvOq42bb8zsG4CeTtGi3VmoEmaAnFgiTEnWqeqfdLZs) | iOS/iPadOS | arm64✅,arm64e❌ |✅ (you can use normal TrollStore instead if you are on 14.0b2 - 16.7RC/17.0b1 - 17.0 if you dont want to jailbreak for some reason)
| 17.4 - 18.3.2 / 18.4b2 - 18.5 | [pymobiledevice3](https://github.com/doronz88/pymobiledevice3) (SideJITServer is just a pymd3 wrapper) | MacOS/Windows/Linux | arm64✅,arm64e✅ | ❌ (kinda old now and has been shown to be unstable on a lot of networks (same as SideJITServer) and is a pain to use)

# What is "JIT" ?
JIT means "Just-In-Time Compilation", it makes emulators (which support JIT) run better/run at all or has other use cases in tools such as [LiveContainer](https://github.com/LiveContainer/LiveContainer) to launch iOS apps faster (by not having to sign them first with SideStore) which are installed into it. 

Read more [here](https://en.wikipedia.org/wiki/Just-in-time_compilation)
