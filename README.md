![Logo](https://github.com/fluttify-project/fluttify-core-example/blob/develop/other/Logo-Landscape.png?raw=true)

# 百度 人脸识别 Flutter插件
[![pub package](https://img.shields.io/pub/v/baidu_face_flutter.svg)](https://pub.Flutter-io.cn/packages/baidu_face_flutter)

**专业版为付费插件, 如有需要请联系qq 382146139**

**专业版为付费插件, 如有需要请联系qq 382146139**

**专业版为付费插件, 如有需要请联系qq 382146139**

## 依赖
```yaml
dependencies:
  flutter:
    sdk: flutter
  baidu_face_flutter: any
```

## 配置
### Android
1. 百度人脸识别的licenseId和licenseFile和打包时的签名key是绑定在一起的, 所以要做到licenseId, licenseFile, applicationId, jks一致.
2. 把licenseFile放在`android/app/src/main/assets/`下, 插件会从这个位置读取licenseFile, 注意不要改动licenseFile名称, 默认名称为`idl-license.face-android`;

### iOS
1. **(注意!)在XCode中**添加授权文件到`Runner/`下, 默认名称为`idl-license.face-ios`, 插件会从此位置读取授权文件.
2. 调起摄像头需要配置权限信息, 在Info.plist中添加
```xml
<key>NSCameraUsageDescription</key>
<string>需要相机</string>
```

## 导入
```dart
import 'package:baidu_face_flutter/baidu_face_flutter.dart';
```

## 使用
参考[wiki](https://github.com/fluttify-project/baidu_face_flutter/wiki).

## 社区
| QQ2群 | QQ1群(已满) |
| :----------: | :----------: |
| 加入QQ群讨论 <br/> <img src="https://github.com/fluttify-project/fluttify-project/blob/master/resources/qrcode_1593774649831.jpg?raw=true" height="300"> |加入QQ群讨论 <br/> <img src="https://github.com/fluttify-project/fluttify-project/blob/master/resources/1593774713224_temp_qrcode_share_9993.png?raw=true" height="300"> | 

## 社区版与专业版
|  推流  | 社区版 | 专业版 |
|:-----:|:-----:|:-----:|
|  活体检测(默认配置)  |  ✅ |  ✅   |
|  活体动作配置  |  ☑️ |  ✅   |
|  动作是否随机  |  ☑️ |  ✅   |
|  模糊度范围  |  ☑️ |  ✅   |
|  光照范围  |  ☑️ |  ✅   |
|  剪裁人脸大小  |  ☑️ |  ✅   |
|  人脸角度范围  |  ☑️ |  ✅   |
|  最小检测人脸  |  ☑️ |  ✅   |
|  是否进行质量检测  |  ☑️ |  ✅   |
|  人脸遮挡范围  |  ☑️ |  ✅   |
|  是否开启提示音  |  ☑️ |  ✅   |

## LICENSE
> Copyright (C) 2020 yohom
> 
> This program is free software: you can redistribute it and/or modify
> it under the terms of the GNU General Public License as published by
> the Free Software Foundation, either version 3 of the License, or
> (at your option) any later version.
> 
> This program is distributed in the hope that it will be useful,
> but WITHOUT ANY WARRANTY; without even the implied warranty of
> MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
> GNU General Public License for more details.
> 
> You should have received a copy of the GNU General Public License
> along with this program.  If not, see <https://www.gnu.org/licenses/>.
