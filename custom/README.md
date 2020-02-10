# 麒麟申威cpu兼容
custom\kirin\rocksdbjni-6.4.0-linux64.jar
custom\kirin\librocksdbjni-linux64.so

# deepin申威cpu兼容
custom\deepin\rocksdbjni-6.4.0-linux64.jar
custom\deepin\librocksdbjni-linux64.so

## 修改Makefile
移除 -march=native编译选项
DEBUG_LEVEL默认0
有些包下载不下来，需要提前下载

# 修改部分测试代码
gtest.h路径不对

# 编译打包，最后一步可能很久
make jclean clean rocksdbjava
