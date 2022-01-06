---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/api-extractor](./api-extractor.md) &gt; [IConfigCompiler](./api-extractor.iconfigcompiler.md) &gt; [skipLibCheck](./api-extractor.iconfigcompiler.skiplibcheck.md)

## IConfigCompiler.skipLibCheck property

This option causes the compiler to be invoked with the `--skipLibCheck` option.

<b>Signature:</b>

```typescript
skipLibCheck?: boolean;
```

## Remarks

This option is not recommended and may cause API Extractor to produce incomplete or incorrect declarations, but it may be required when dependencies contain declarations that are incompatible with the TypeScript engine that API Extractor uses for its analysis. Where possible, the underlying issue should be fixed rather than relying on skipLibCheck.
