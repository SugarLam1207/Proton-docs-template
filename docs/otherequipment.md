# 前言
完成服務器的安裝及tentacle的配置後，此時POS系統已經能夠正常啟動並運作。
因此本章節，將講解其他周邊設備的配置

## 打印機
在开始之前，请确保您已经有打印機，店鋪環境已經搭建好網絡。

### 配置打印機（方式一） 
通過APP連接配置打印機：
| 序號 | 操作內容               | 操作示例                                                                                                                                                                                                       |
|----|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | 在手機端掃描二維碼，下載APP         | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F-1.png) |
| 2  | 待打印機連接電源后，長按打印機的重置按鈕4秒，直至聽到打印機綁定連接的提示音          | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F-2.jpg)  |
| 3  | 在手機端打開app，進入界面，點擊添加設備| ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F-3.png)  |
| 4  | 選擇設備類型中的打印機    | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F-4.png)  |
| 5  | 點擊開始掃描   | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F-5.png)  |
| 6  | 掃描打印機底部二維碼  | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F-6.png)  |
| 7  | 在手機端中選擇打印機    | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F-7.png)  |
| 8  | 選擇打印機WiFi，待WiFi連接后即可完成    | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F-8.png)  |

### 配置打印機（方式二） 
通過小程序連接配置打印機：

| 序號 | 操作內容               | 操作示例                                                                                                                                                                                                       |
|----|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | 在手機端掃描二維碼，進入小程序中         | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F2-1.png) |
| 2  | 待打印機連接電源后，長按打印機的重置按鈕4秒，直至聽到打印機綁定連接的提示音    | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F-2.jpg)  |
| 3  | 進入界面后，點擊開始設置     | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F2-3.png)  |
| 4  | 如果首次使用，會提示一些權限授權，點擊允許    | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F2-4.png)  |
| 5  | 在掃描結果中選擇打印機   | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F2-5.png)  |
| 6  | 選擇打印機WiFi    | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F2-6.png)  |
| 7  | 待WiFi連接后即可完成    | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F2-7.png)  |

### 配置打印機（方式三） 
通過網綫連接配置打印機：

| 序號 | 操作內容               | 操作示例                                                                                                                                                                                                       |
|----|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | 網綫連接到打印機的網絡接口，另一端連接路由器或連接了區域網的電腦         | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F-2.jpg) |
| 2  | 待打印機亮藍燈表示網絡連接成功    | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E6%89%93%E5%8D%B0%E6%A9%9F2-8.png)  |

## 錢箱
### 配置錢箱
連接配置錢箱：

| 序號 | 操作內容               | 操作示例                                                                                                                                                                                                       |
|----|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | 連接電源后，連接RJ12接口，另一端連接到終端臺式機或雲打印機中     | ![](https://github.com/VIDA101/Proton-docs-VIDA/blob/main/docs/source/images/%E9%8C%A2%E7%AE%B1-1%20(2).png?raw=true) |
| 2  | 在POS軟件中，點擊錢箱；若錢箱自動彈出，則説明連接成功；    | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E9%8C%A2%E7%AE%B1-1%20(1).png)  |

## 一體機
### 配置一體機
連接配置臺體機：

| 序號 | 操作內容               | 操作示例                                                                                                                                                                                                       |
|----|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | 在對應的接口中連接網綫、電源綫、錢箱RJ12     | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E4%B8%80%E9%AB%94%E6%A9%9F.png) |
| 2  | 長按電源鍵開機，進入臺式一體機界面；點擊設置    | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E4%B8%80%E9%AB%94%E6%A9%9F1%20(1).jpg)  |
| 3  | 在此界面中可以設置相關信息    | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E4%B8%80%E9%AB%94%E6%A9%9F1%20(2).jpg)  |

## 刷卡機
### 配置刷卡機
配置刷卡機：

| 序號 | 操作內容               | 操作示例                                                                                                                                                                                                       |
|----|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | 左滑界面，點擊setting     | ![](https://github.com/VIDA101/Proton-docs-VIDA/blob/main/docs/source/images/%E5%88%B7%E5%8D%A1%E6%A9%9F1%20(1).png) |
| 2  | 若要輸入管理員PIN碼，請填寫07139    | ![](https://github.com/VIDA101/Proton-docs-VIDA/blob/main/docs/source/images/%E5%88%B7%E5%8D%A1%E6%A9%9F1%20(2).png)  |
| 3  | 選擇Network並連接wifi    | ![](https://github.com/VIDA101/Proton-docs-VIDA/blob/main/docs/source/images/%E5%88%B7%E5%8D%A1%E6%A9%9F1%20(4).png)  |
| 4  | 點擊配對碼    | ![](https://github.com/VIDA101/Proton-docs-VIDA/blob/main/docs/source/images/%E5%88%B7%E5%8D%A1%E6%A9%9F1%20(3).png)  |
| 5  | 在Easy POS中綁定刷卡機時輸入配對碼即可完成連接    | ![](https://raw.githubusercontent.com/VIDA101/Proton-docs-VIDA/main/docs/source/images/%E5%88%B7%E5%8D%A1%E6%A9%9F1%20(1).jpg)  |


