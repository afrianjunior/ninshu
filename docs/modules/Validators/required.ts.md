---
title: Validators/required.ts
nav_order: 34
parent: Modules
---

## required overview

Added in v0.0.2

---

<h2 class="text-delta">Table of contents</h2>

- [Validators](#validators)
  - [validateRequired](#validaterequired)

---

# Validators

## validateRequired

validate nil

**Signature**

```ts
export declare const validateRequired: <E>(b: E) => <A>(a: A) => Either<E, unknown extends A ? any : A>
```

Added in v0.0.2
