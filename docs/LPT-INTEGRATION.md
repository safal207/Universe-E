# LPT Integration

Universe-E integrates with LPT by treating LPT-reported transitions as the sole input for energy activation decisions.

## How LPT triggers energy activation

1. LPT detects and publishes a transition event.
2. Universe-E evaluates the transition against a Significance Trigger.
3. If meaningful, Universe-E applies the Energy Policy to activate energy.
4. If not meaningful, systems remain in Sleep (Dormant State).

## How Universe-E reacts to meaningful transitions

- A meaningful transition is the only trigger for energy activation.
- Energy activation is bounded by the Energy Policy, not by continuous availability.
- The response is deterministic within the policy scope (no inference or prediction).

## Principle: No Transition → No Energy

Universe-E enforces a strict rule: without a meaningful transition, energy remains dormant. The absence of LPT transitions implies no activation.
