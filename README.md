# OKD CLI

## Description

All binaries packed by UPX

----

## Versions

| Binary Name | Package Version                | Release                                      |
|-------------|--------------------------------|----------------------------------------------|
| oc4.11      | 4.11.0-0.okd-2023-01-14-152430 | https://github.com/okd-project/okd/releases  |
| oc4.10      | 4.10.0-0.okd-2022-07-09-073606 | https://github.com/okd-project/okd/releases  |
| oc3.11      | v3.11.0-0cbc58b                | https://github.com/openshift/origin/releases |

### Verify versions

```bash
for i in `ls -1` ; do echo -e "\n$i" && ./$i version 2>/dev/null ; done
```