

## [1.1.0](https://github.com/xh-polaris/meowchat-app/compare/v1.0.0...v1.1.0) (2023-01-16)


### ✨ Features | 新功能

* 实现了喵世界/喵社区下拉刷新数据，添加了发布动态/帖子返回页面后立刻刷新显示最新的发布 ([#130](https://github.com/xh-polaris/meowchat-app/issues/130)) ([fdf678f](https://github.com/xh-polaris/meowchat-app/commit/fdf678f82ab1b71d93ac43628625143444e01a7e))
* 添加了动态详情页面的下拉刷新 ([#128](https://github.com/xh-polaris/meowchat-app/issues/128)) ([9367f94](https://github.com/xh-polaris/meowchat-app/commit/9367f94d2b220d0dd6ae423f3edf03d0abab2589))
* 添加了帖子详情页面的下拉刷新，调整了动态单张图片的显示效果 ([#137](https://github.com/xh-polaris/meowchat-app/issues/137)) ([835b420](https://github.com/xh-polaris/meowchat-app/commit/835b420dcb2e8c252b27bdfde0eb7e9577b2aa21))
* 在初次登录时自动更新用户头像和昵称 ([15356db](https://github.com/xh-polaris/meowchat-app/commit/15356db66346a4c114d099242868605d82611c64))
* 在网络异常时显示弹窗 ([3a132c2](https://github.com/xh-polaris/meowchat-app/commit/3a132c25da178f6461213c216158b66866c8e17a))


### 🐛 Bug Fixes | Bug 修复

* 解决了瀑布流长图显示过长问题 ([#138](https://github.com/xh-polaris/meowchat-app/issues/138)) ([5b93b1d](https://github.com/xh-polaris/meowchat-app/commit/5b93b1de32d4f3fc20503f6ba68b3e9533e4331f))
* 解决world界面头像挡住顶部导航栏的问题 ([#131](https://github.com/xh-polaris/meowchat-app/issues/131)) ([40b2e7e](https://github.com/xh-polaris/meowchat-app/commit/40b2e7e1e200a6335c84984a0fb5dc5ffb556606))
* 修复本地时间与服务器时间不一致时，显示的时间可能为“几秒后”的问题 ([810b906](https://github.com/xh-polaris/meowchat-app/commit/810b906ea514b8a28960cb6df636cd7ddba8f002))
* 修复编辑头像页面不显示原本头像的问题 ([750ec22](https://github.com/xh-polaris/meowchat-app/commit/750ec22f31a5c22dcd3636f35940b83d7fc34807))
* 修复图片上传时，content-type被设置为json的问题，以及上传动态或帖子过快导致图片url丢失的问题 ([2d8e88e](https://github.com/xh-polaris/meowchat-app/commit/2d8e88e7d50728f9812ea7b1ab6a94bf487c5652))


### ⚡ Performance Improvements | 优化

* 根据图片数量自适应显示方式，并调整动态图片上限为9张 ([#136](https://github.com/xh-polaris/meowchat-app/issues/136)) ([55eccc1](https://github.com/xh-polaris/meowchat-app/commit/55eccc1e47c77d519711e6ac5ec9df89adbd3f19))
* 在小图预览时使用缩略图代替原图 ([0187bd2](https://github.com/xh-polaris/meowchat-app/commit/0187bd206740a7a596f4aa821dde899276d95d70))