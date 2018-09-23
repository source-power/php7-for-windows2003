PHP 7 and PHP 5.6 for Windows XP/2003
=====================================

**最新版本**：7.0.9 / 5.6.24

**更新日期**：2016-7-28

**系统要求**：Windows XP/2003

**修改说明**：因从头编译PHP太麻烦，故将部分Vista以上的API函数手动实现，然后为可执行文件的导入表打补丁。

## 目前实现的函数列表：

| DLL名称       | 函数名称                     | nonxp.dll版本   |
| ------------- | --------------------------- | -------------- |
| iphlpapi.dll	| if_nametoindex	            | 0.0.1.11
| ------------- | --------------------------- | -------------- |
|               |	GetFinalPathNameByHandleA	  | 0.0.2.20
|               | GetFinalPathNameByHandleW	  | 0.0.2.20
|               | GetTickCount64             	| 0.0.1.11
|               | InitializeConditionVariable	| 0.0.4.40
| kernel32.dll  | InitializeCriticalSectionEx	| 0.0.3.30
|               | SleepConditionVariableCS	  | 0.0.4.40
|               | WakeAllConditionVariable  	| 0.0.4.40
|               | WakeConditionVariable	      | 0.0.4.40
| ------------- | --------------------------- | -------------- |
| shell32.dll	  | SHGetKnownFolderPath	      | 0.0.3.30
| ------------- | --------------------------- | -------------- |
| 	            | WSASendMsg	                | 0.0.1.11
| ws2_32.dll    | inet_ntop	                  | 0.0.1.11
|               | inet_pton	                  | 0.0.1.11
 
## 使用说明：

PHP 7：系统必须装有 IE8 和 [VC14 运行时库](http://www.microsoft.com/zh-cn/download/details.aspx?id=48145)。

PHP 5.6：系统必须装有 IE8 和 [VC11 运行时库](http://www.microsoft.com/zh-cn/download/details.aspx?id=30679)。

## 下载地址：

**程序包**

[PHP 7.0.9 for Windows XP/2003 完整版 (non thread safe, for IIS)](http://www.lindasc.com/php/php-7.0.9-nts-WinXP32-VC14-x86.7z)

[PHP 7.0.9 for Windows XP/2003 完整版 (thread safe, for Apache httpd)](http://www.lindasc.com/php/php-7.0.9-WinXP32-VC14-x86.7z)

[PHP 5.6.24 for Windows XP/2003 完整版 (non thread safe, for IIS)](http://www.lindasc.com/php/php-5.6.24-nts-WinXP32-VC11-x86.7z)

[PHP 5.6.24 for Windows XP/2003 完整版 (thread safe, for Apache httpd)](http://www.lindasc.com/php/php-5.6.24-WinXP32-VC11-x86.7z)

**源代码**

[nonxp.dll 源代码](http://www.lindasc.com/php/nonxp-0.0.4.40-src.7z)


## 出处

http://www.lindasc.com/php/
