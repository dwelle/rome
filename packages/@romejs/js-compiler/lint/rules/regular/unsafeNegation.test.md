# `unsafeNegation.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-compiler/lint/rules/regular/unsafeNegation.test.ts --update-snapshots` to update.

## `unsafe negation`

### `0`

```

 unknown:1 lint/unsafeNegation FIXABLE ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unsafe usage of negation operator in left side of binary expression

    !1 in [1,2]
    ^^^^^^^^^^^

  ℹ Recommended fix

  + !(1 in [1,·2])

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
!(1 in [1, 2]);

```
