[← 回 EEG 管理目錄 / Back to EEG index](README.md)

# R605 EEG 考核說明<br>R605 EEG Assessment Guide

本文件說明 R605 EEG 儀器使用考核的事項、考核表與 EEG 注意事項。
This document explains the R605 EEG usage assessment — items, the assessment form, and EEG notes.

> **無論是否已有 EEG 實驗經驗，所有使用者皆須通過考核。**
> **All users — regardless of prior EEG experience — must pass the assessment.**

## 目錄 / Contents

1. [考核事項 / Assessment Items](#1-考核事項--assessment-items)
2. [考核表 / Assessment Form](#2-考核表--assessment-form)
3. [EEG 注意事項 / EEG Notes](#3-eeg-注意事項--eeg-notes)

---

## 1. 考核事項 / Assessment Items

<!-- 原「Room 605 EEG 獨立執行認證」，依要求更名為「考核事項」。 -->

### 流程 / Procedure

| # | 中文 | English |
|---|------|---------|
| 1 | **報名考核**：填寫下方「考核時段登記表」預約考核時段。 | **Register**: use the assessment registration form below to book a session. |
| 2 | **面談 / 訓練**：由負責教師安排，確認申請人有足夠能力與知識可**獨立操作**。 | **Interview / training**: arranged by the responsible faculty to confirm you can **operate independently**. |
| 3 | **開通設備權限**：通過考核後，管理人員開通「R605 腦波儀 Google Calendar」預約權限。 | **Equipment access**: once you pass, the manager grants access to the "R605 EEG Google Calendar". |
| 4 | **空間權限**：另須向**認知所辦公室**申請 R605 實驗室行事曆權限（見[借用規則 → 時段預約](R605-EEG-usage-rules.md#1-時段預約--reservation)）。 | **Space access**: also request R605 lab calendar access from the **ICN office** (see [Usage Rules → Reservation](R605-EEG-usage-rules.md#1-時段預約--reservation)). |

<!-- 註: 上方連結指向「R605 EEG 儀器借用規則」檔。若該檔實際檔名不同，請更新路徑。 -->

### 報名表單 / Registration Form

- 📝 [R605 EEG 考核時段登記表 / Assessment Registration Form](請填入連結 / add link)

<!-- 註: 來源文件提及此表單但未附網址，請管理團隊補上連結。 -->

### 已通過考核名單 / Users Who Passed

<!-- 可於此維護已通過考核的成員清單，或連結至另一份文件。 -->
（填寫或連結 / fill in or link）

---

## 2. 考核表 / Assessment Form

考核所使用的考核表（PDF）**之後會上傳**，屆時連結將放於此處。
The assessment form (PDF) **will be uploaded later**; the link will appear here.

- 📄 考核表 PDF / Assessment Form PDF：（待上傳 / to be uploaded）

<!-- 註: 上傳方式 — 將 PDF 放入 repo（例如 eeg-management/assets/），再把上方連結改為
     [考核表 PDF](assets/你的檔名.pdf) 即可。 -->

---

## 3. EEG 注意事項 / EEG Notes

本節整理 EEG 實驗前中後的檢查重點與常見問題排除。
This section covers pre-, during-, and post-experiment checks plus troubleshooting.

### 3.1 空間與環境 / Room & Environmental Setup

| 中文 | English |
|------|---------|
| 降低電氣雜訊：關閉非必要電子設備。 | Electrical noise minimization: turn off unnecessary electronic devices. |
| 照明：避免日光燈（50/60 Hz 雜訊）。 | Lighting: avoid fluorescent lights (50/60 Hz noise). |
| 溫度：維持舒適室溫。 | Temperature: maintain a comfortable room temperature. |
| 座椅：使用舒適、最好可後躺的椅子。 | Chair: use a comfortable, preferably reclining chair. |
| 緊急應變：確保安全程序與急救用品可取用。 | Emergency protocols: ensure safety procedures and first-aid supplies are accessible. |

### 3.2 系統與硬體檢查 / System & Hardware Check

| 中文 | English |
|------|---------|
| 放大器：正確連接並**卡扣鎖定於底座**、連上電腦、韌體／軟體最新。 | Amplifier: properly connected and **clicked/locked on the base**, connected to the computer, firmware/software up to date. |
| 電極帽：尺寸正確、清潔完整、無斷線或鬆脫。 | Electrode cap: correct size, clean and intact, no broken wires or loose connectors. |
| 電極：以清水清潔；阻抗一般 **< 5–10 kΩ**。 | Electrodes: cleaned with water; impedance generally **< 5–10 kΩ**. |
| 纜線與接頭：輕插並**確認卡扣**；避免纏繞。 | Cables/connectors: gently plug in and **confirm it clicks locked**; avoid tangling. |
| 導電膠與針筒：確認未過期；勿過量以免搭接（bridging）。 | Gel & syringe: check expiry; avoid over-application to prevent bridging. |
| 電極定位（10–20）：標記 nasion / inion / 耳前點；**Cz 置於頭頂正中**。 | Placement (10–20): mark nasion, inion, preauricular points; **Cz at the center/vertex**. |
| 阻抗量測裝置：已校正且功能正常。 | Impedance device: calibrated and functioning. |

### 3.3 電腦與軟體 / Computer & Software

| 中文 | English |
|------|---------|
| 採集軟體（Curry）：載入正確 protocol；通道設定與帽相符。 | Acquisition software (Curry): correct protocol loaded; channel config matches the cap. |
| 事件標記／同步：刺激軟體（PsychoPy / E-Prime / Psychtoolbox）已同步；**parallel port trigger 已設定測試**。 | Markers/sync: stimulus software synchronized; **parallel-port triggers configured and tested**. |
| 備份：確認資料儲存位置；必要時備妥備份硬碟。 | Backup: confirm data save location; backup drive ready if needed. |

### 3.4 受試者準備 / Participant Preparation

| 中文 | English |
|------|---------|
| 頭髮：以酒精棉片或去角質膏清潔頭皮；長髮於低處束起（勿用金屬髮夾）。 | Hair: clean scalp with alcohol swabs or abrasive gel; tie long hair low (non-metallic clips). |
| 皮膚：於眼動通道電極與乳突下方輕擦去角質膏以降阻抗。 | Skin: lightly apply scrub gel under eye-movement channels and mastoids to reduce impedance. |
| 舒適度：帽子貼合但不過緊；清楚說明並答問。 | Comfort: cap snug but not too tight; give clear instructions and answer questions. |
| 禁忌篩檢：頭皮傷口、皮膚過敏、可能干擾的植入物。 | Contraindications: screen for scalp injuries, skin allergies, interfering implants. |
| 受試者狀況：留意怕針、頭暈、噁心；可中途如廁；**請移除手機與（智慧）手錶**。 | Participant: watch for needle fear, dizziness, nausea; allow toilet breaks; **remove phone & (smart)watch**. |

### 3.5 最終組裝與記錄前檢查 / Final Assembly & Pre-recording

| 中文 | English |
|------|---------|
| 帽子固定對齊（Cz 於頂點）；所有電極正確連接。 | Cap secured and aligned (Cz at vertex); all electrodes connected correctly. |
| 接地與參考電極放置穩固、接觸穩定。 | Ground and reference electrodes secure with stable contact. |
| 檢查阻抗（最好 < 5–10 kΩ）。 | Check impedance (< 5–10 kΩ at best). |
| 試記錄：確認低雜訊；眨眼／動作假影出現在預期通道。 | Test recording: confirm low noise; blink/movement artifacts in expected channels. |
| 檢查電極搭接（bridging）。 | Check for electrode bridging. |
| 檢查刺激與 EEG 的同步訊號。 | Check sync signal between stimulus and EEG. |
| 通道故障時，必要時借用替代電極。 | Borrow alternative electrodes if channels malfunction. |

### 3.6 記錄文件 / Documentation

| 中文 | English |
|------|---------|
| 記錄帽子尺寸、使用導電膠、各通道阻抗值。 | Record cap size, gel used, impedance values. |
| 記錄組裝與開始記錄時間、遇到的問題。 | Record setup/recording start times and any issues. |
| 記錄受試者編號與知情同意。 | Record participant ID and informed consent. |

### 3.7 空間復原與 EEG 清潔 / Restoration & Cleaning

| 中文 | English |
|------|---------|
| 電極帽與電極：使用後**立即以冷水沖洗**；棉棒輕刷去殘膠；檢查裂痕／斷線／彎針；晾乾後存放陰涼乾燥處。 | Cap/electrodes: **rinse with cold water immediately**; brush gel off with swabs; inspect for cracks/broken wires/bent pins; dry and store cool & dry. |
| 耗材：妥善丟棄棉棒、紙巾、3M 膠帶。 | Consumables: properly dispose of swabs, tissues, 3M tapes. |
| 工作區：擦拭椅子、桌面與重複使用表面；整理纜線、歸還材料。 | Workstation: wipe chair, table, reused surfaces; reorganize cables, return materials. |
| 電子設備：**先關軟體**再拔放大器與電腦。 | Electronics: **turn off software first**, then unplug amplifier and computer. |
| 房間：恢復至下一位的基準設定。 | Room: restore to baseline for the next user. |
| 事件回報：記錄設備問題、維護需求或流程偏差。 | Incident reporting: note equipment issues, maintenance needs, protocol deviations. |

### 3.8 常見問題排除 / Troubleshooting

| 中文 | English |
|------|---------|
| 環境／網路：需手動 key in IP 連線放大器；注意 PsychoPy 版本。 | Env/network: key in the IP to connect the amplifier; mind the PsychoPy version. |
| 放大器斷線：重新連線（可能需數次）。 | Amplifier disconnection: reconnect (may take a few attempts). |
| Trigger tags：僅支援 **1–55**。 | Trigger tags: **1–55 only**. |
| 雜訊來源：纜線拉扯晃動、電極接頭接觸不良、電源與接地不穩。 | Noise sources: cable movement/pulling, poor connector contact, unstable power/grounding. |
| 導電膠比例／阻抗／帽子貼合：注意尺寸與形狀。 | Gel ratio / impedance / cap fitting: mind size and shape. |

<!-- 來源: R605 EEG Details to Notice.pdf 與 20250502 R605 EEG Workshop Slides.pptx -->
