---
title: Taro.showTabBarRedDot(option)
sidebar_label: showTabBarRedDot
id: version-2.0.3-showTabBarRedDot
original_id: showTabBarRedDot
---

显示 tabBar 某一项的右上角的红点

> [参考文档](https://developers.weixin.qq.com/miniprogram/dev/api/ui/tab-bar/wx.showTabBarRedDot.html)

## 类型

```tsx
(option: Option) => Promise<CallbackResult>
```

## 参数

### Option

| 参数 | 类型 | 必填 | 说明 |
| --- | --- | :---: | --- |
| index | `number` | 是 | tabBar 的哪一项，从左边算起 |
| complete | `(res: CallbackResult) => void` | 否 | 接口调用结束的回调函数（调用成功、失败都会执行） |
| fail | `(res: CallbackResult) => void` | 否 | 接口调用失败的回调函数 |
| success | `(res: CallbackResult) => void` | 否 | 接口调用成功的回调函数 |

## API 支持度

| API | 微信小程序 | H5 | React Native |
| :---: | :---: | :---: | :---: |
| Taro.showTabBarRedDot | ✔️ | ✔️ |  |
