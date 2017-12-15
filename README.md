# CQDevice
## 收集手机信息
以下为上传设备信息的接口，url为上传地址，item为可选参数，以字符串形式组成可选参数列表，可选参数格式在下面讲明
```
[UIDevice postDeviceInfoWithUrl:@"" success:^(id obj) {

} failure:^(NSError *error) {

} item:@"IDFA",@"DeviceModel",@"AppVersion",nil];
```
可选参数列表
* IDFA：广告标识符
* IDFV：应用唯一标识符
* DeviceModel：设备型号
* AppVersion：设备型号
* SystemVersion：系统版本号
* SystemName:系统名称
* BundleID：应用bundleID
* IpAddress：设备IP地址

