# MSVC 使用笔记

- 发行版运行时查找路径：`C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\VC\Redist`以及`C:\Program Files (x86)\Windows Kits\10\Redist`。此为常见路径，请根据自己的环境自行修改。
- 根据宏定义判断编译器版本

  | MSVC版本 | `_MSC_VER`的值 | 对应的VS版本 |
  | -------- | -------------- | ----------- |
  | 14.2 | 1920 | 2019 |
  | 14.1 | 1910 | 2017 |
  | 14.0 | 1900 | 2015 |
  | 13.0 | - | - |
  | 12.0 | 1800 | 2013 |
  | 11.0 | 1700 | 2012 |
  | 10.0 | 1600 | 2010 |
  | 9.0 | 1500 | 2008 |
  | 8.0 | 1400 | 2005 |
  | 7.1 | 1310 | 2003 |
  | 7.0 | 1300 | - |
  | 6.0 | 1200 | - |
  | 5.0 | 1100 | - |
