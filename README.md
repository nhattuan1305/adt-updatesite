# VNext ADT Tools — Eclipse Update Site

p2 update site cho 2 ADT plugin:

| Plugin | Bundle | Version |
|---|---|---|
| Generate ABAP Object | `generateObject` | 1.0.0.202405270000 |
| Execute ABAP Job Class | `executeJobClass` | 1.0.0.202404100358 |

## Cài đặt trong Eclipse / ADT

1. `Help > Install New Software...`
2. **Work with**: dán URL update site:
   ```
   https://nhattuan1305.github.io/adt-updatesite/
   ```
3. Tích **VNext ADT Tools** > Next > Finish > restart.

> Bỏ tick "Group items by category" nếu không thấy item.

## Build lại site

Update site được sinh bằng p2 publisher từ repo `JAR/`:
`pwsh -File JAR/build-site.ps1` → copy `JAR/updatesite/*` vào repo này.
