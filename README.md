# Awesome iOS Developer Handbook

A curated list of resources for iOS developers — covering Swift, SwiftUI, UIKit, architecture, testing, tooling, and building production-ready iOS apps.

## About

This is a living list of high-quality resources for learning and mastering iOS development, from getting started with Swift to shipping and scaling apps on the App Store. Contributions are welcome — see [Contributing](#contributing).

## Table of Contents

- [Getting Started](#getting-started)
- [Swift Language](#swift-language)
- [SwiftUI](#swiftui)
- [UIKit](#uikit)
- [Architecture Patterns](#architecture-patterns)
- [Concurrency](#concurrency)
- [Networking](#networking)
- [Persistence & Databases](#persistence--databases)
- [Dependency Management](#dependency-management)
- [Testing](#testing)
- [CI/CD & DevOps](#cicd--devops)
- [Design & UI/UX](#design--uiux)
- [Performance & Debugging](#performance--debugging)
- [App Store & Distribution](#app-store--distribution)
- [Tools](#tools)
- [Open Source Libraries](#open-source-libraries)
- [Blogs](#blogs)
- [Newsletters](#newsletters)
- [Podcasts](#podcasts)
- [YouTube Channels](#youtube-channels)
- [Books](#books)
- [Courses](#courses)
- [WWDC](#wwdc)
- [Communities](#communities)
- [Interview Preparation](#interview-preparation)
- [Job Boards](#job-boards)
- [Contributing](#contributing)

---

## Getting Started

- [Apple Developer Documentation](https://developer.apple.com/documentation/) — Official docs for all Apple frameworks and APIs.
- [Swift.org](https://www.swift.org/) — The official home of the Swift language, including the language guide.
- [100 Days of SwiftUI](https://www.hackingwithswift.com/100/swiftui) — Free structured course by Paul Hudson.
- [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/) — Apple's official design guidelines for building iOS apps.

## Swift Language

- [The Swift Programming Language (book)](https://docs.swift.org/swift-book/) — Official free language reference.
- [Swift Evolution](https://github.com/apple/swift-evolution) — Proposals and history of language changes.
- [Hacking with Swift](https://www.hackingwithswift.com/) — Tutorials, tips, and language deep dives.
- [Swift by Sundell](https://www.swiftbysundell.com/) — Articles, podcast, and videos on idiomatic Swift.
- [NSHipster](https://nshipster.com/) — In-depth articles on lesser-known Swift/Objective-C corners.
- [Point-Free](https://www.pointfree.co/) — Functional programming and Swift architecture (subscription, some free content).

## SwiftUI

- [Apple SwiftUI Tutorials](https://developer.apple.com/tutorials/swiftui) — Official step-by-step tutorials.
- [100 Days of SwiftUI](https://www.hackingwithswift.com/100/swiftui) — Free comprehensive course.
- [SwiftUI Lab](https://swiftui-lab.com/) — Advanced SwiftUI internals and techniques.
- [SwiftUI by Example](https://www.hackingwithswift.com/quick-start/swiftui) — Quick reference/snippets.

## UIKit

- [Apple UIKit Documentation](https://developer.apple.com/documentation/uikit)
- [raywenderlich/kodeco UIKit tutorials](https://www.kodeco.com/ios/paths) — Structured UIKit learning paths.
- [objc.io](https://www.objc.io/) — Deep technical books and articles on iOS internals.

## Architecture Patterns

- MVC, MVVM, VIPER, Clean Swift, TCA (The Composable Architecture) — common patterns for structuring iOS apps.
- [The Composable Architecture (TCA)](https://github.com/pointfreeco/swift-composable-architecture) — Popular state-management architecture from Point-Free.
- [RIBs](https://github.com/uber/RIBs) — Uber's cross-platform architecture framework.

## Concurrency

- [Swift Concurrency (async/await) documentation](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/concurrency/)
- [Swift Concurrency by Example](https://www.hackingwithswift.com/quick-start/concurrency) — Practical guide to async/await, actors, and tasks.
- [GCD (Grand Central Dispatch) docs](https://developer.apple.com/documentation/dispatch) — Still relevant for legacy codebases.

## Networking

- [URLSession documentation](https://developer.apple.com/documentation/foundation/urlsession)
- [Alamofire](https://github.com/Alamofire/Alamofire) — Elegant HTTP networking library.
- [Moya](https://github.com/Moya/Moya) — Network abstraction layer on top of Alamofire.

## Persistence & Databases

- [Core Data documentation](https://developer.apple.com/documentation/coredata)
- [SwiftData](https://developer.apple.com/documentation/swiftdata) — Apple's modern persistence framework.
- [Realm](https://github.com/realm/realm-swift) — Mobile database alternative to Core Data.
- [GRDB.swift](https://github.com/groue/GRDB.swift) — SQLite toolkit for Swift.

## Dependency Management

- [Swift Package Manager](https://www.swift.org/documentation/package-manager/) — Apple's official dependency manager.
- [CocoaPods](https://cocoapods.org/) — Long-standing dependency manager for Cocoa projects.
- [Carthage](https://github.com/Carthage/Carthage) — Decentralized dependency manager.

## Testing

- [XCTest documentation](https://developer.apple.com/documentation/xctest)
- [Swift Testing](https://developer.apple.com/documentation/testing) — Apple's modern testing framework (successor to XCTest for many use cases).
- [Quick & Nimble](https://github.com/Quick/Quick) — BDD-style testing framework for Swift.
- [XCUITest](https://developer.apple.com/documentation/xctest/user_interface_tests) — UI testing framework.

## CI/CD & DevOps

- [Fastlane](https://fastlane.tools/) — Automate building, testing, and releasing iOS apps.
- [Xcode Cloud](https://developer.apple.com/xcode-cloud/) — Apple's native CI/CD service.
- [Bitrise](https://bitrise.io/) — Mobile-focused CI/CD platform.
- [GitHub Actions for iOS](https://github.com/features/actions) — General-purpose CI usable for iOS pipelines.

## Design & UI/UX

- [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/)
- [SF Symbols](https://developer.apple.com/sf-symbols/) — Apple's icon library.
- [Figma iOS UI kits](https://www.figma.com/community) — Community design kits for iOS.

## Performance & Debugging

- [Instruments User Guide](https://developer.apple.com/library/archive/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/) — Apple's profiling tool.
- [LLDB documentation](https://lldb.llvm.org/) — Debugger used in Xcode.
- [MetricKit](https://developer.apple.com/documentation/metrickit) — Collect performance metrics from real devices.

## App Store & Distribution

- [App Store Connect](https://developer.apple.com/app-store-connect/)
- [App Store Review Guidelines](https://developer.apple.com/app-store/review/guidelines/)
- [TestFlight](https://developer.apple.com/testflight/) — Beta testing distribution.

## Tools

- [Xcode](https://developer.apple.com/xcode/) — Apple's official IDE.
- [SwiftLint](https://github.com/realm/SwiftLint) — Enforce Swift style and conventions.
- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) — Code formatter for Swift.
- [Swift Package Index](https://swiftpackageindex.com/) — Search engine for Swift packages.
- [Proxyman](https://proxyman.io/) / [Charles Proxy](https://www.charlesproxy.com/) — Network debugging tools.

## Open Source Libraries

- [Kingfisher](https://github.com/onevcat/Kingfisher) — Image downloading and caching.
- [SDWebImage](https://github.com/SDWebImage/SDWebImage) — Asynchronous image loading.
- [SnapKit](https://github.com/SnapKit/SnapKit) — Auto Layout DSL for Swift.
- [Lottie-iOS](https://github.com/airbnb/lottie-ios) — Render After Effects animations natively.

## Blogs

- [Swift by Sundell](https://www.swiftbysundell.com/)
- [Hacking with Swift](https://www.hackingwithswift.com/articles)
- [objc.io](https://www.objc.io/)
- [NSHipster](https://nshipster.com/)
- [Donny Wals](https://www.donnywals.com/)

## Newsletters

- [iOS Dev Weekly](https://iosdevweekly.com/) — Curated weekly iOS news by Dave Verwer.
- [Swift Weekly Brief](https://swiftweekly.github.io/) — Swift language and open-source ecosystem updates.
- [This Week in Swift](https://twis.dev/) — Community roundup.

## Podcasts

- [Swift by Sundell (podcast)](https://www.swiftbysundell.com/podcast/)
- [Under the Radar](https://www.relay.fm/radar) — Indie iOS development by Marco Arment and David Smith.
- [Fatal Error](https://www.fatalerror.fm/)
- [iPhreaks Show](https://devchat.tv/podcasts/iphreaks/)

## YouTube Channels

- [Sean Allen](https://www.youtube.com/@seanallen)
- [Paul Hudson (Hacking with Swift)](https://www.youtube.com/@twostraws)
- [Kavsoft](https://www.youtube.com/@Kavsoft) — SwiftUI-focused tutorials.
- [Stanford CS193p (developed for iOS)](https://cs193p.sites.stanford.edu/) — Free Stanford course with recorded lectures.

## Books

- *The Swift Programming Language* (free, Apple) — Official language reference.
- *iOS Apprentice* (Kodeco) — Beginner-to-intermediate project-based book.
- *Combine: Asynchronous Programming with Swift* (Kodeco).
- *Advanced Swift* (objc.io) — Deep dive for experienced developers.
- *Thinking in SwiftUI* (objc.io).

## Courses

- [Stanford CS193p](https://cs193p.sites.stanford.edu/) — Free university-level SwiftUI course.
- [100 Days of Swift / SwiftUI](https://www.hackingwithswift.com/100) — Free structured curricula.
- [Kodeco (raywenderlich) iOS Paths](https://www.kodeco.com/ios/paths) — Subscription-based structured courses.
- [Point-Free](https://www.pointfree.co/) — Advanced Swift/architecture videos (subscription).

## WWDC

- [WWDC Videos Archive](https://developer.apple.com/videos/) — All past sessions, searchable by topic and year.
- [WWDC Notes](https://www.wwdcnotes.com/) — Community-maintained notes and summaries of sessions.

## Communities

- [Swift Forums](https://forums.swift.org/) — Official Swift community forum.
- [r/iOSProgramming](https://www.reddit.com/r/iOSProgramming/) — Reddit community.
- [iOS Dev Slack / Discord communities](https://ios-developers.io/) — Directory of iOS developer chat communities.
- [Stack Overflow – swift tag](https://stackoverflow.com/questions/tagged/swift)

## Interview Preparation

- [Hacking with Swift – Interview Questions](https://www.hackingwithswift.com/interview-questions) — Common iOS/Swift interview questions with answers.
- [iOS Interview Guide (Kodeco)](https://www.kodeco.com/) — Search their library for interview-prep articles.
- LeetCode / algorithm practice — for the data structures & algorithms portion common in iOS interviews.

## Job Boards

- [Apple Jobs](https://jobs.apple.com/)
- [We Work Remotely – Programming](https://weworkremotely.com/categories/remote-programming-jobs)
- [iOS Dev Jobs (via iOS Dev Weekly)](https://iosdevweekly.com/)
- [LinkedIn Jobs – iOS Developer](https://www.linkedin.com/jobs/)

---

## Contributing

Contributions are welcome! To add a resource:

1. Fork this repository.
2. Add your entry to the relevant section, keeping the alphabetical/logical order.
3. Make sure the link works and the description is concise (one line).
4. Open a pull request.

Please avoid adding paywalled or low-quality resources, and prefer resources that are actively maintained.

## License

[MIT](LICENSE)
