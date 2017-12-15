# CQDevice
## 收集手机信息
<<<<<<< HEAD
以下为上传设备信息的接口，url为上传地址，item为可选参数，以字符串形式组成可选参数列表，可选参数格式在下面讲明(此版本所收集信息iOS8~iOS11均可使用)
=======
以下为上传设备信息的接口，url为上传地址，item为可选参数，以字符串形式组成可选参数列表，可选参数格式在下面讲明
>>>>>>> 4938f89fcea73fd6d488c31c592fd5e0ed81d91f
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
<<<<<<< HEAD
* all:以上全部信息
=======

>>>>>>> 4938f89fcea73fd6d488c31c592fd5e0ed81d91f
