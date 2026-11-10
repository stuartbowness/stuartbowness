# Stuart Bowness

Founder and builder based in Victoria, BC. My current work spans AI agents,
developer tools, and native applications.

I care about the details that make software useful: clear interfaces, observable
failures, reliable execution, and a product experience that respects the user.
These repositories show a few of those decisions in code.

## Selected work

### [TestKitchen](https://github.com/stuartbowness/testkitchen)

A conversational-agent testing toolkit adapted from internal QA work on Toyo.
The standalone public edition includes a Python runner, synthetic scenarios, and
an offline demo that distinguishes an agent's completion claim from execution
evidence. Start with the demo, then read the architecture and provenance notes.

**Explore:** [Design](https://github.com/stuartbowness/testkitchen/blob/main/docs/architecture.md) · [Implementation](https://github.com/stuartbowness/testkitchen/blob/main/testkitchen.py) · [Tests](https://github.com/stuartbowness/testkitchen/blob/main/tests/test_runner.py)

### [Iron Search](https://github.com/stuartbowness/ironsearch)

A native macOS application and contact launcher built with Swift, AppKit, and
SwiftUI. It pairs a small ranking engine with explicit permission handling and
an optional terminal handoff. The repository explains the concurrency, windowing,
and command-boundary decisions, along with what the tests do and do not cover.

**Explore:** [Design](https://github.com/stuartbowness/ironsearch/blob/main/docs/architecture.md) · [Search core](https://github.com/stuartbowness/ironsearch/blob/main/Sources/SearchCore/SearchEngine.swift) · [Tests](https://github.com/stuartbowness/ironsearch/blob/main/Tests/SearchCoreTests/SearchEngineTests.swift)

Both projects are MIT licensed. They are focused examples, with setup instructions
and documented limitations, rather than a complete account of my private work.

[Website](https://stuartbowness.com) · [LinkedIn](https://www.linkedin.com/in/stuartbowness/)
