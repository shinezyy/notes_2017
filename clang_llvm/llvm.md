### build llvm

链接llvm是永恒的梦魇：
https://stackoverflow.com/questions/40536508/is-it-possible-to-compile-link-clang-llvm-using-the-gold-linker
```
cmake -G "Unix Makefiles" -DLLVM_USE_LINKER=gold /media/hdd_ext4/compiler/llvm-4.0.0.src
```
