To build toolchains, we follow the steps.

1.linux headers install
```
./linux_header_install.sh
```
2.build musl
```
./build_musl_clang.sh
```
3.copy usr directory
```
cp -rf usr/lib usr/include ../../usr/
```
