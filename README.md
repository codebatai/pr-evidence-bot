# PR Evidence Bot (Public Skeleton)

This is a **safe, minimal** GitHub Action template. It **does not** perform real
verification. It only echoes a stub report so integrators can see the shape.

Use with:
```yaml
- uses: pharmflow/pr-evidence-bot@v0
  with:
    receipts: "./evidence/*.json"   # demo glob
