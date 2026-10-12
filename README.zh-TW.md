# 陳沛安 | Pei An Chen

> 嵌入式生醫感測、研究儀器與 FPGA 系統

[English](README.md) · [繁體中文](README.zh-TW.md) · [個人網站／中文](https://chen861019.github.io/peian-chen/) · [個人網站／英文](https://chen861019.github.io/peian-chen/en/) · [Email](mailto:chen861019@gmail.com)

我是陳沛安，目前就讀國立陽明交通大學電機工程博士班，主要投入感測系統與研究設備開發。我的工作從實驗中的量測與控制需求出發，包含裝置韌體、通訊介面、操作軟體與資料處理，讓研究構想具備實際執行與驗證的條件。

在開發過程中，我關注各個部分接在一起後能否可靠運作：資料如何取得與保存、裝置如何控制，以及出現異常時如何追查。目前持續投入低功耗感測、BLE 裝置整合與 FPGA 邏輯設計，並透過實測、模擬與技術文件記錄設計選擇及其限制。

## 工程領域

| 領域 | 實作內容 | 核心技術 |
| --- | --- | --- |
| 穿戴式生醫感測 | 多部位溫度與汗液壓力感測、生理資料同步、裝置歷史紀錄 | Nordic nRF、BLE、MLX90614、Android、Wear OS |
| 裝置到雲端 | 手機資料擷取、離線儲存、裝置識別、身分驗證與研究儀表板 | Kotlin、Jetpack Compose、Room、Firebase、Flask |
| 電化學量測 | 可攜式計時安培量測、單鍵流程、TFT 回饋與 SD 紀錄 | EmStat Pico、C/C++、SPI、MethodSCRIPT |
| 微流體系統 | 幫浦與閥控制、stop-flow 觀測、手機取像與系統整合 | ESP32、PlatformIO、PDMS、微幫浦、Android |
| 太空與生物實驗 | 定時高解析取像與閉迴路微重力模擬運動平台 | ESP32-S3、OV5640、運動控制、PID |
| FPGA 與數位系統 | RTL、FSM、記憶體、處理器、HPS-FPGA 介面與自動檢查 | Verilog、Quartus、Qsys、Questa、DE1-SoC |

## 系統設計重點

- **跨層整合：** 韌體、通訊、應用狀態、資料儲存與分析共同設計。
- **考慮硬體限制：** 納入時序、功耗、記憶體保留、校正、無線行為與實體介面。
- **以證據驗證：** 分別記錄模擬、編譯、實測與實驗驗證，讓讀者了解各階段的成果與限制。
- **研究可用性：** 重視可重現擷取、可解讀資料、操作流程與持續維護。

## 精選公開專案

| 專案 | 說明 | 技術 |
| --- | --- | --- |
| [ThermoPatch](https://github.com/chen861019/ThermoPatch) | 多節點 BLE 體表溫度平台，整合 Android 視覺化、Firebase 同步與 OTA 韌體更新 | Kotlin、Compose、BLE、Firebase、nRF52840 |
| [SpaceCellCam](https://github.com/chen861019/SpaceCellCam) | ESP32-S3／OV5640 定時高解析生物取像，包含 LED 輔助照明與 microSD 紀錄 | C++、Python、ESP32-S3、OV5640 |
| [Space BMC Core RTL](https://github.com/chen861019/Space-BMC-Core-SEMC) | 參數化 Verilog-2001 心跳逾時監測核心，附週期邊界、清除與重新計時檢查 | Verilog、Questa、FPGA |
| [nRF54L15 MLX90614](https://github.com/chen861019/nRF54L15_MLX90614) | XIAO nRF54L15 紅外線溫度感測韌體與低功耗分析 | C、Zephyr、I2C、BLE |
| [Galaxy Watch Sensor Monitor](https://github.com/chen861019/GalaxyWatchSensorMonitor) | Samsung 手錶皮膚溫度擷取與研究型感測應用 | Kotlin、Wear OS、Samsung Health Sensor SDK |
| [資料結構與圖論演算法](https://github.com/chen861019/NYCU-Data-Structures-Graph-Algorithms) | 九份 C 作業：排序、BFS、稀疏矩陣、運算式、Segment Tree、Huffman、MST 與最短路徑，附結果與限制說明 | C、GCC、Python、Graphviz |
| [台北公車 Live](https://github.com/chen861019/taipei-bus-live) | 開發中的公車即時地圖，包含路線／車牌搜尋、標記聚合、路線匹配與官方快照的短時間位置推估 | JavaScript、Node.js、MapLibre GL JS |

**課程實作典藏：** [NYCU-AFPGA](https://github.com/chen861019/NYCU-AFPGA-Labs) 整理八組 Verilog／DE1-SoC 實驗，涵蓋組合邏輯、FSM、RAM、簡易處理器與 HPS/Qsys 整合。目前 repository 為 **private**，須具存取權限才能查看。

## 研究經驗

| 平台 | 工程貢獻 |
| --- | --- |
| 微重力模擬系統 | 雙軸 Random Positioning Machine、多軸嵌入式運動控制、感測與影像整合、即時資料擷取 |
| 穿戴式 IoT 裝置 | nRF52840 感測節點、BLE 通訊、手機與雲端資料管理、LVGL 裝置介面 |
| 仿生微流體生醫工程 | 趨溫性／流變性分選、溫度梯度控制、影像式運動分析、自動化資料擷取 |

- **2025：** Texas A&M University 研究發表；北海道大學 RIES-CEFMS Joint Symposium 海報發表。
- **2024：** CES TTA 臺灣科技新創館參展；DMS (NAIST)-CEFMS (NYCU) Joint Symposium 口頭發表；ICSS 海報發表。
- **2023：** 未來科技獎；FITI 創新創業激勵計畫入圍。
- **2021：** 生醫創意構想競賽佳作。
- **2017-2019：** 機器人與 AIoT 競賽經驗，包括 AIoT 智慧機器人、愚公移山與物聯網智慧控制社群成果發表第一名。

[完整網站](https://chen861019.github.io/peian-chen/#research) 保留各項競賽明細與 *Biosensors & Bioelectronics*、*Sensors and Actuators A* 期刊紀錄。

## 教育背景

| 期間 | 學歷 |
| --- | --- |
| 2022-2026 | 國立陽明交通大學電機工程博士班（就讀中） |
| 2020-2022 | 國立陽明交通大學生醫工程碩士 |
| 2016-2020 | 國立宜蘭大學生物機電工程學士 |

語言：中文、英文、基礎日文。

## 技術能力

### 硬體與數位設計

- **FPGA／RTL：** Verilog／Verilog-2001、Intel/Altera Quartus、Qsys／Platform Designer、DE1-SoC、HPS-FPGA 整合
- **數位邏輯與驗證：** 組合與循序邏輯、FSM、RAM／ROM、簡易處理器、Questa／ModelSim、波形分析、自動檢查式 testbench
- **PCB 設計：** KiCad 電路圖繪製與 PCB 佈線
- **硬體整合：** 感測器、攝影模組、幫浦、閥、馬達回授及機構／CAD 整合

### 嵌入式韌體與感測

- **開發平台：** Nordic nRF52840／nRF54L15、ESP32／ESP32-S3、Arduino 相容開發板、Raspberry Pi
- **韌體開發：** C/C++、Zephyr RTOS／nRF Connect SDK、Arduino framework、PlatformIO、LVGL 裝置介面
- **通訊與介面：** BLE 廣播與 GATT、裝置識別、OTA／DFU 整合、I2C、SPI、UART、microSD 紀錄
- **低功耗感測：** 週期量測、裝置歷史資料保存、電源狀態控制、溫度校正與功耗量測

### 軟體開發與資料整合

- **程式語言：** C/C++、Python、Kotlin、JavaScript、HTML、CSS
- **Android／Wear OS：** Jetpack Compose、ViewModel、Kotlin coroutines／Flow、BLE 用戶端開發、Samsung Health Sensor SDK 整合
- **資料儲存與同步：** Room／SQLite、WorkManager、Firebase Authentication／Realtime Database、離線儲存、雲端同步
- **網頁與桌面應用：** Flask 研究儀表板、Node.js、MapLibre GL JS、GitHub Pages、PyQt5 分析介面

### 資料分析與生物影像

- **科學運算：** NumPy、pandas、SciPy、Matplotlib、OpenCV、scikit-image
- **影像分析：** 前處理、分割、運動追蹤、影像配準、時間序列分析、特徵萃取
- **研究資料流程：** LabVIEW、感測資料擷取、實驗視覺化、人工標註、分析結果比對

### 研究系統整合與開發流程

- **量測與儀器：** 穿戴式生醫感測、EmStat Pico／MethodSCRIPT 電化學擷取、微流體幫浦與閥控制、生物取像
- **運動控制：** PID 回授控制、多軸運動、Random Positioning Machine 系統整合
- **開發與除錯：** Git／GitHub、Gradle、GCC、序列埠紀錄、Android Logcat、韌體與應用整合測試
- **文件與驗證：** 可重現測試流程、技術 Markdown、GitHub Actions 靜態網站發布，分別記錄模擬、建置與實機量測結果

## 目前方向

- 建立可靠、低功耗的多裝置穿戴式感測流程。
- 整合生理訊號、電化學、微流體與影像資料，支援研究應用。
- 開發附可重現驗證流程的 FPGA 控制與可靠度模組。
- 改進微重力模擬實驗的閉迴路運動平台。

聯絡：**[chen861019@gmail.com](mailto:chen861019@gmail.com)**。完整作品集：[中文版](https://chen861019.github.io/peian-chen/) · [English](https://chen861019.github.io/peian-chen/en/)。
