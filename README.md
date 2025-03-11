# iOS-macOS-Location-Simulator
通过Mac上Xcode中的开发模式更改设备定位！注意，只能通过Xcode实现！

# 原理
Xcode为开发者提供了定位模拟功能，以便在开发应用时测试各个地区是否都能正常运行

# 具体操作步骤
1. 打开Xcode新建一个应用项目iOS/macOS，根据需要修改定位的设备的系统选择。
2. 双击左侧文件栏，newfile -> resource -> GPX file
3. GPX file 就是保存项目地理信息的文件
4. <img src="https://github.com/Philoso0/iOS-macOS-Location-Simulator/blob/main/default%20GPX.png"/>
5. "lat","lon"分别是纬度和经度，根据具体需要定位的地点选择。一般更改小数点后第3位第4位可以微调
6. time感觉可以不用写，如果是需要创建虚拟路径才会用到。
7. 最后先点击运行，接着在屏幕上方工具栏选择 debug -> Simulate Location -> 选择刚创建的gpx文件，此时设备定位就已经发生修改，可以打开地图软件验证

免责声明：
纯粹技术分享，技术没有好坏，取决于使用它的人。
