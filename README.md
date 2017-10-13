# LMPrint

记录下第一个错误
➜  LMPrint git:(master) pod trunk push

[!] Found podspec `LMPrint.podspec`
Updating spec repo `master`
Validating podspec
 -> LMPrint (1.0.0)
    - ERROR | [OSX] unknown: Encountered an unknown error ([!] /usr/bin/git clone https://github.com/Amuxiaomu/LMPrint.git /var/folders/q4/4k7_cz3d5m95s2xl5114_xpw0000gn/T/d20171013-7926-1kdkdoh --template= --single-branch --depth 1 --branch 1.0.0

Cloning into '/var/folders/q4/4k7_cz3d5m95s2xl5114_xpw0000gn/T/d20171013-7926-1kdkdoh'...
warning: Could not find remote branch 1.0.0 to clone.
fatal: Remote branch 1.0.0 not found in upstream origin

解答:
http://tech.yunyingxbs.com/article/detail/id/280.html
添加 git tag v1.0.0 后 需要git push --tag

