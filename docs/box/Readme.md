## To convert

```bash
convert '*.svg' -set filename:fn '%[basename]' '%[filename:fn].png'
```