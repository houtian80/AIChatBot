### Flutter GetX 实现 AIChat

**Flutter 是一款跨平台的移动应用开发框架，而 GetX 是 Flutter 中一种简单易用的状态管理和路由管理工具**

我们需要在 Flutter 项目中引入 GetX 库。在`pubspec.yaml`文件中添加以下依赖：

```
dependencies:
  flutter:
    sdk: flutter
  get:

```


在`main`函数中添加以下代码：

```
void main() {
  //在main函数第一行添加这句话
  WidgetsFlutterBinding.ensureInitialized();
  runApp(GetMaterialApp(
    home: ChatPage(),
  ));
}
```
