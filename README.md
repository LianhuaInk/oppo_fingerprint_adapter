# OPPO R11/R11s通用指纹修复
## 使用方法
将本仓库中的文件添加到```/system```中的对应路径（README.md除外）。

## 注意事项
有些内容需要您自行添加到```/system```中的原始文件中，这些内容在本仓库的
```etc/vintf/manifest.xml.diff```和```etc/selinux/plat_file_contexts.diff```中，
请将它们添加到```/system/etc/vintf/manifest.xml```和```/system/etc/selinux/plat_file_contexts```中。
另外，manifest.xml部分请参照原厂```/vendor```对应路径中的相同文件中vendor.oppo.hardware.biometrics.fingerprintpay@1.0的格式进行添加。

## 采用Apache协议 使用请标注来源和作者
