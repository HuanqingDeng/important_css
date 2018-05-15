# weui 微信的统一web页面

## 表单 cells
> 在小程序中，使用weui做快速开发，让小程序更快
- MVVM
  用户登陆模块
  username password
  Model？ user object
  value="{{user.username}}"
  value="{{user.passwrod}}"
  V? wxml weui 写form
  VM? 两者的结合体 ，view 是一个模板，等待被编译，改变之后会自动编译，跟随model
  model数据绑定，bindinput bindtap 值改变，状态改变
  VM代表那一刻的状态
  