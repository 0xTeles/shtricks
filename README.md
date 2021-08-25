# shtricks


### Search by extension:
```bash
find . -type f -name "*.extension"
```
### Grep in all files of a specific extension:
```bash
find . -type f -name "*.extension" | xargs -n 1 -I {} strings {} | grep TEXT  
```
### Setup proxy on Iphone device (jailbreak):
```bash
iproxy 2222 44&
ssh -p 2222 -R 8080:localhost:8080 root@localhost
```
