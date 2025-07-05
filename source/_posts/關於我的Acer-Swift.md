---
title: Acer Swift Go 14 Touchpad is updating 充滿屏幕問題
date: 2025-04-25 18:05:54
tags: Acer筆電
categories: Acer筆電
cover: https://us.v-cdn.net/6029997/uploads/X43SVSMDODRO/screenshot-2024-12-19-225854.png
---

本文針對 Acer Swift Go 14 屏幕充滿 Touchpad is updating 的問題進行解決

<!-- more -->

## 前言
去年10月買的Swift Go 14 ，用了大概3、4個月左右，開始出現的問題，當時筆電更新完之後便有 `Touchpad is updating` 的視窗充滿屏幕問題
我的筆電畫面如同下圖
![image](https://us.v-cdn.net/6029997/uploads/X43SVSMDODRO/screenshot-2024-12-19-225854.png)

## 問題解決
在經過網路上的爬文之後，在reddit論壇上找到了解決方案

::: warning
論壇中有人用過此方法但出現觸控板無法使用的問題，請自行斟酌是否使用
:::

### 步驟
1. 按 `Windows 鍵 + R 鍵` 打開 MS 配置，然後輸入 Msconfig 按下確認
![image](https://i.imgur.com/J7l9NCV.png)

2. 在上面的列表中找到 `服務` ，然後請勾選 左下角的 `隱藏所有Micrsoft服務` (這樣就不會意外關閉所需的內容)
![image](https://i.imgur.com/NzA9ecZ.png)

3. 服務清單中找到 `PxiTpService`，並取消左側的框裡勾勾，點擊確定並重新開機

## 參考資料
- [Reddit論壇-Touchpad is updating filling screen](https://www.reddit.com/r/laptops/comments/1fvtk67/touchpad_is_updating_filling_screen)

