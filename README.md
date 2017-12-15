# CQDevice
## 收集手机信息
以下为上传设备信息的接口，url为上传地址，item为可选参数，以字符串形式组成可选参数列表，可选参数格式在下面讲明(此版本所收集信息iOS8~iOS11均可使用)
```
[UIDevice postDeviceInfoWithUrl:@"" success:^(id obj) {

} failure:^(NSError *error) {

} item:@"IDFA",@"DeviceModel",@"AppVersion",nil];
```
可选参数列表
* IDFA：广告标识符
* AppVersion：应用版本
* SystemVersion：系统版本号
* SystemName：系统名称
* BundleID：应用bundleID
* AppName：应用名称
* AppBuild：应用build号
* IDFV：应用唯一标识符
* DeviceName：设备名称
* DeviceModel：设备类型（e.g. iPhone Or iPod touch..）
* DeviceModelID：设备型号（e.g. iPhone6,2）
* IpAddress：设备IP地址
* ScreenBrightness：屏幕亮度
* TotalDiskCapacity：磁盘总容量
* FreeDiskCapacity：磁盘未使用容量
* WifiSSID：WIFI名称
* WifiBSSID：WiFi的BSSID，即mac地址
* SIMCarrierName：SIM运营商
* all:以上全部信息

# CQDevice(private)
可选参数列表
* IDFA：广告标识符
* AppVersion：应用版本
* SystemVersion：系统版本号
* SystemName：系统名称
* BundleID：应用bundleID
* AppName：应用名称
* AppBuild：应用build号
* IDFV：应用唯一标识符
* DeviceName：设备名称
* DeviceModel：设备类型（e.g. iPhone Or iPod touch..）
* DeviceModelID：设备型号（e.g. iPhone6,2）
* IpAddress：设备IP地址
* UDID：设备标识符（调用私有api,iOS10.2之后禁用）
* ScreenBrightness：屏幕亮度
* TotalDiskCapacity：磁盘总容量
* FreeDiskCapacity：磁盘未使用容量
* WifiSSID：WIFI名称
* WifiBSSID：WiFi的BSSID，即mac地址
* SIMCarrierName：SIM运营商
* AllInstalledAppBundleID：获取设备所有安装应用的bundleID(调用私有api,iOS11以后不可用)
* all:以上全部信息

