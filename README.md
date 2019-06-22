# PidKeyBatch
密钥检测

#检测微软密钥是否有效

#返回批量密钥次数

#返回零售密钥错误代码

#自带各种证书，可以导入使用或者通过设置证书实现

#设置证书功能将会改变系统原有证书结构，会造成已激活证书丢失.导入证书不会.

#最新版本 V8.6f

![image](https://github.com/laomms/PidKeyBatch/blob/master/pidkey.png)

#Tool for check Microsoft Product Key for All Windows Version and All Office Version

#The activation test is best tested in the virtual machine environment with the key type relative to avoid affecting the local certificate environment.

#Example: For test Windows 10 Product Key, this tool must be started on a virtual machine (or PC) with Windows 10 this rule is valid for each product key

#Start the tool right click and on "english" to start it in English

#1.This software comes with a certificate, so no certificate file support is required.

#2.After the software is started, the system certificate environment will be modified, which will affect the original certificate of the system. If you want to restore, right-click on the main interface to select the recovery certificate environment. After the restart, it will return to normal.

#3.Support MAX query for all version keys.

#4.Support version key query of Office series 2010-2019 professional enhanced version.

#5.If you query Windows7 or Windows8.1 under Windws10, the version error will be displayed. The opposite is also true.

#6.Under Windows 10, the theory can query all Windows 10 versions of the key, the query process may automatically switch the system version, the special version of the key may not be able to feedback the error code.

#7.Support Win7 Pro and Win7 Ultimate key queries under Windows 7.

#8.Windows 8.1 key query is supported under Windows 8.1.

#9.Batch query automatic filtering key and automatically deduplicate key query.

#10.Support for error code queries.

#11.Support certificate management

#12.The rebuild tokens function is mainly used to repair the tokens file when the exception is activated. This function will invalidate the activated certificate. It will also cause the Office certificate to be lost.


