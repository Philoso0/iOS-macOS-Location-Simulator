# iOS-macOS-Location-Simulator
通过Mac上Xcode中的开发模式更改设备定位，！注意，只能通过Xcode实现！

# 原理
Xcode为开发者提供了定位模拟功能，以便在开发应用时测试各个地区是否都能正常运行

# 具体操作步骤
1. 打开Xcode新建一个应用项目iOS/macOS，根据需要修改定位的设备的系统选择。
2. 双击左侧文件栏，newfile -> resource -> GPX file
3. GPX file 就是保存项目地理信息的文件
4. <img width="641" alt="default GPX" src="https://github.com/Philoso0/iOS-macOS-Location-Simulator/main/GPX default.png">
5. "lat","lon"分别是纬度和经度，根据具体需要定位的地点选择。一般更改小数点后第3位第4位可以微调
6. time感觉可以不用写，如果是需要创建虚拟路径才会用到。
7. 最后先点击运行，接着在屏幕上方工具栏选择 debug -> Simulate Location -> 选择刚创建的gpx文件，此时设备定位就已经发生修改，可以打开地图软件验证

最后造福一下翔安校区的同窗：
- 西部片区：lat="24.6075" lon="118.2960"
- 学武楼：lat="24.6083" lon="118.3090"
- 文宣楼：lat="24.6080" lon="118.3052"

免责声明：
纯粹技术分享，技术没有好坏，取决于使用它的人。对于水课，请不要浪费自己的时间。鲁迅先生说过，无端地空耗他人时间无异于谋财害命，这还是写在小学课本上的。希望世界上少一些形式主义，这是我们用自己的方式抗议。
