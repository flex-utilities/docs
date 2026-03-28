# How do test results work?

Flex is known for its strict tests. Just like sUNC, ever since it was made, it was built to expose falsified environments by actually testing for functionality - not merely checking for their presence.

---

## Using the dedicated game & prorgam

All tests **must** be conducted in the official Flex testing game, and must be accompanied by the Flex  - an external application used to verify functionality that cannot be reliable tested from the Luau environment.

The official game may be found in our [Discord server](https://discord.gg/7AcZs3VmFx).

!!! danger "Distribution of the Flex Helper"

	The Flex Helper is **ONLY** distributed via [flex.gd/helper](https://flex.gd/helper), and **NOWHERE ELSE**.
	
	If you encounter *any* impersonation or unofficial distribution, report it immediately to [legal@numelon.com](mailto:legal@numelon.com).

A dedicated testing environment allows Flex to provide **online, verifiable test results via [Rubiš](https://rubis.app)**, ensuring results are reproducible and trustworthy, instead of people sending meaningless screenshots of their console output.

The Flex Helper exists to extend testability beyond the limitations identified in sUNC.

Certain functionality is inherently ambiguous or "untestable" within Luau alone. For example, the [Drawing library](https://docs.sunc.su/Drawing/) can be partially vaidated by sUNC to see if the correct object structure is returned, but it cannot determine whether rendering has actually occurred on-screen.

The Flex Helper resolves this limitation by enabling external verification of such behaviour.

<!-- ---

## Viewing your test results

Once your test is complete, sUNC will generate a short redirect link via `r.sunc.su` like this:

![An `r.sunc.su` redirect link generated](./assets/test-results/r.sunc.su.png)

This generated link redirects to **Numelon Rubiš**:

![An sUNC Test Result being displayed with Numelon Rubiš](./assets/test-results/RubisTestResult.png)

The results page offers a clean, visually appealing UI that lays out which functions passed and which failed, why they failed, and cryptographic guarantees of authenticity.

---

## Verified integrity

Rubiš doesn't just store your sUNC test results, it also **verifies** them.

- Every result is **cryptographically signed** by the sUNC test game servers.
- Any tampered or faked data is **flagged as unverified**.

Even if someone tries to replicate the link or manually upload fake data and use it with the results viewer (since [Rubiš is also a public paste service](https://rubis.app) which is usable by anyone), it will not work. -->
