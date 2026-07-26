# THE TRIPWIRE · bounded halt with hysteresis

A member of **[SKYNET](https://davidwise01.github.io/ud0/d/skynet.html)** — the stopping rule.

A monitor that **halts** when a metric crosses the high bound (0.80) and stays halted until it falls below a **lower** bound (0.55). The gap is **hysteresis** — a signal hovering at the edge can never flap the halt on and off. A stopping rule you can trust because it is reluctant to un-stop. Open [`index.html`](index.html).

**Honest:** a faithful hysteresis / Schmitt-trigger stopping rule on a synthetic metric stream — the mechanism, not a monitor wired to a live system. Self-test verifies it trips above HIGH, holds through edge-hover without flapping, and rearms only below LOW.

Part of **UD0** — David Lee Wise / ROOT0. CC-BY-ND-4.0, with AVAN.
