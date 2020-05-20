---
id: fast-foundation.forcedcolorsstylesheetbehavior
title: forcedColorsStylesheetBehavior variable
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[@microsoft/fast-foundation](./fast-foundation.md) &gt; [forcedColorsStylesheetBehavior](./fast-foundation.forcedcolorsstylesheetbehavior.md)

## forcedColorsStylesheetBehavior variable

Applies ElementStyles to a FASTElement when the forced-colors media query is matched, removes the ElementStyles when the query is no-longer matched

<b>Signature:</b>

```typescript
forcedColorsStylesheetBehavior: (sheet: ElementStyles) => Readonly<{
    query: MediaQueryList;
    cache: WeakMap<(new () => HTMLElement & FASTElement) & {
        from<TBase extends {
            new (): HTMLElement;
            prototype: HTMLElement;
        }>(BaseType: TBase): new () => InstanceType<TBase> & FASTElement;
        define<TType extends Function>(Type: TType, nameOrDef?: string | import("@microsoft/fast-element").PartialFASTElementDefinition | undefined): TType;
        getDefinition: <T extends Function>(Type: T) => import("@microsoft/fast-element").FASTElementDefinition | undefined;
    }, ((this: MediaQueryList) => void)[] | ((this: MediaQueryList) => void)>;
    sheet: ElementStyles;
    constructListener(this: MatchMediaStyleSheetBehavior, source: (new () => HTMLElement & FASTElement) & {
        from<TBase extends {
            new (): HTMLElement;
            prototype: HTMLElement;
        }>(BaseType: TBase): new () => InstanceType<TBase> & FASTElement;
        define<TType extends Function>(Type: TType, nameOrDef?: string | import("@microsoft/fast-element").PartialFASTElementDefinition | undefined): TType;
        getDefinition: <T extends Function>(Type: T) => import("@microsoft/fast-element").FASTElementDefinition | undefined;
    }, sheet: ElementStyles): MediaQueryListListener;
    bind(this: MatchMediaStyleSheetBehavior, source: (new () => HTMLElement & FASTElement) & {
        from<TBase extends {
            new (): HTMLElement;
            prototype: HTMLElement;
        }>(BaseType: TBase): new () => InstanceType<TBase> & FASTElement;
        define<TType extends Function>(Type: TType, nameOrDef?: string | import("@microsoft/fast-element").PartialFASTElementDefinition | undefined): TType;
        getDefinition: <T extends Function>(Type: T) => import("@microsoft/fast-element").FASTElementDefinition | undefined;
    }): void;
    unbind(this: MatchMediaStyleSheetBehavior, source: (new () => HTMLElement & FASTElement) & {
        from<TBase extends {
            new (): HTMLElement;
            prototype: HTMLElement;
        }>(BaseType: TBase): new () => InstanceType<TBase> & FASTElement;
        define<TType extends Function>(Type: TType, nameOrDef?: string | import("@microsoft/fast-element").PartialFASTElementDefinition | undefined): TType;
        getDefinition: <T extends Function>(Type: T) => import("@microsoft/fast-element").FASTElementDefinition | undefined;
    }): void;
}>
```