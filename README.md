# TIPSSE 中華民國 行星科學系統工程學會 
# 0.25U CubeSat研究案

## Introdction
TIPSSE 是由學生團隊成立，創立於 2021 年 2 月 21 日

0.25U CubeSat 教育版是受***科技部 臺灣太空科學聯盟***委託研究，於 2021 年 1 月開始執行

0.25U CubeSat 太空版是受***拔不移衛星團隊***委託研究，於 2020 年 12 月開始執行


## 0.25U CubeSat Introduction
常見的CubeSat都以10x10x10cm 為一單位(Unit)，本研究案採用1/4 Unit為一顆衛星之大小。
正常衛星上的次系統，本顆衛星上皆有，舉凡，電力(EPS), 資料處理(CDH), 通訊(COMM), 姿態感測與控制(ADCS), 推進(Thrust), 結構(STR), 酬載(Payload)，

本計畫有相同大小，但根據用途不同而產生多種版本
- 教育版
- 工程版
- 太空版

### 教育版
#### Version 1
System Structure
- EPS
- CDH
  - CPU: STM32L
  - Development Enviroment: 文字編輯＋GCC  
- COMM
  - LoRa
- Payload
  -  Tri-Axis Gyroscope
  -  Tri-Axis Accelerometer
  -  Tri-Axis Magnetometer
  -  GPS
  -  Camera
  -  Barometer
  -  Temperature
- STR (TBD)
  - Parachute drop (TBD)
  - Antenna deployment (TBD)

### 工程版
#### Version 1
System Structure
- EPS (TBD)
- CDH (TBD)
  - CPU: smartfusion 2
  - Development Environment: Libreo 
      - need 45GB for the files, and pretty hard to install
        - Free license need to bind the "Mac Address". But the Libreo wouldn't detect all interface Mac address, while I use the iphone network shared to my computer.    It will detect the wrong interface. All I have to do is disconnect the network to pass the license verification...... Damn it...
        - And executes all the commands must need requires license verification. So I need to keep connecting and disconnecting from the Internet. This is the hardest development environment that I had ever install.
- COMM (TBD)
- Payload (TBD)
- STR (TBD)
- ADCS (TBD)
