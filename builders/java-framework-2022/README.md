```bash
pack builder create cnbs/sample-builder:java-framework-2022 --config builder.toml
```

#### Build app with builder

```bash
pack build sample-app --builder cnbs/sample-builder:java-framework-2022 --trust-builder --path ../../apps/aspnet
```
