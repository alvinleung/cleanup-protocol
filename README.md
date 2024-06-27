To make sure classes are being cleaned up, this package provide a `CleanupProtocol` interface. This package work with [eslint-plugin-enforce-cleanup](https://www.npmjs.com/package/eslint-plugin-enforce-cleanup)

Usage:

```typescript
class MyClass implemenets CleanupProtocol {
  // ...
  cleanup():void {
    // implement cleanup code here
  }
}
```
