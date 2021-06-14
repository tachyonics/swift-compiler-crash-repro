Reproduce with command-

```
docker run --rm -v "$(pwd)":/workspace -w /workspace swift:5.4.1-amazonlinux2 bash -cl "cd /workspace && swift build"  
```
