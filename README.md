# shtricks


### Search by extension
```bash
find . -type f -name "*.extension"
```
### Grep in all files of a specific extension

```bash
find . -type f -name "*.extension" | xargs -n 1 -I {} strings {} | grep TEXT  
```
