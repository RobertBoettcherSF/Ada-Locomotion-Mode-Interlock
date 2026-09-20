# Ada-Locomotion-Mode-Interlock

Hybrid wheeled/legged delivery platforms must not mix locomotion modes unsafely: legs while wheels are armed need an explicit hybrid transition, stairs need legs or hybrid, and each mode has its own speed cap. This tiny Ada interlock is a clean-room educational sketch of Rivr-like mode gating for last-meter doorstep robots — not Rivr proprietary code.

## Build & test

```bash
make test
```

Uses GNAT with `-gnatwa -gnat2022 -gnata`. No Alire.

## Optional SPARK

```bash
make prove   # SPARK L2 — proved clean on this package
```

## License

MIT. See `LLM_DISCLOSURE.md`.
