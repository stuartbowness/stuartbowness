# Stuart Bowness

Founder and builder based in Victoria, BC. My current work spans AI agents,
developer tools, and native applications.

I care about the details that make software useful: clear interfaces, observable
failures, reliable execution, and a product experience that respects the user.
These repositories show a few of those decisions in code.

## Selected work

### [Darkfactory](https://github.com/stuartbowness/darkfactory)

Coding-agent workflows backed by a Rust process supervisor. Darkfactory connects
planning, scoped implementation, and review while keeping process supervision
separate from agent instructions. The dispatcher handles worker events,
process-group timeouts, and structured results, with real subprocess tests on
Linux and macOS. A credential-free demo exercises success, failure, and timeout.

**Explore:** [Design](https://github.com/stuartbowness/darkfactory/blob/main/ARCH.md) · [Supervisor](https://github.com/stuartbowness/darkfactory/blob/main/tools/darkfactory-dispatch/src/supervisor.rs) · [Offline demo](https://github.com/stuartbowness/darkfactory/blob/main/examples/dispatch-demo.py)

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

### [Iron Zapper](https://github.com/stuartbowness/ironzapper)

A native macOS uninstaller built around explicit ownership evidence and recoverable
file operations. Its Swift core distinguishes exclusive, uncertain, and shared
data; the app revalidates selections before moving files to Trash. The source
includes an authenticated XPC helper, filesystem fixtures, and documented limits
on privileged cleanup, whose installed workflow still needs end-to-end verification.

**Explore:** [Design](https://github.com/stuartbowness/ironzapper/blob/main/docs/architecture.md) · [Ownership policy](https://github.com/stuartbowness/ironzapper/blob/main/Sources/IronZapperCore/Scanner.swift) · [Tests](https://github.com/stuartbowness/ironzapper/tree/main/Tests/IronZapperCoreTests)

These projects are MIT licensed. They are focused examples, with setup instructions
and documented limitations, rather than a complete account of my private work.

[Website](https://stuartbowness.com) · [LinkedIn](https://www.linkedin.com/in/stuartbowness/)
