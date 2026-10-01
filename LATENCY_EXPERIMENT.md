# FPS late-warp latency experiment

Use this demo as an archaeology/test workload for late-warp concepts, not as evidence that the 2021 implementation still represents current browser/GPU behavior.

Compare:

- warp disabled
- existing late warp
- equivalent camera motion with controlled synthetic input

Record:

- input event timestamp
- simulation timestamp
- warp timestamp
- frame submission timestamp
- frame interval distribution
- visible artifact/error notes

Run fixed seeds and repeat each variant. Report p50/p95/p99/max and raw traces.

The key question is whether late warp reduces motion-to-render delay without increasing visible spatial error or tail frametime.
