---
title: Wee 簡約任務看板
emoji: ✅
colorFrom: indigo
colorTo: blue
sdk: static
pinned: false
---

# Wee 簡約任務看板

簡潔的任務管理看板，協助你安排工作、追蹤進度、記錄改善原因並回顧成果。

## 功能

- **新增任務：** 記錄任務名稱、月份和分類。
- **設定預計進度：** 為任務設定預計完成百分比。
- **更新實際進度：** 透過進度控制項更新完成百分比。
- **自動更新狀態：** 進度達 100% 時標示為已完成，未達 100% 時標示為進行中。
- **篩選任務：** 依任務狀態查看全部、進行中或已完成的項目。
- **記錄改善原因：** 留下執行過程中遇到的問題或可改善之處。
- **撰寫回顧心得：** 記錄完成任務後的心得。
- **依月份查看：** 選擇月份查看或管理對應任務。
- **保存資料：** 任務資料儲存在目前瀏覽器的本機儲存空間。

## 系統流程：三步任務管理循環

```mermaid
flowchart LR
    A["① 建立任務<br/>輸入名稱、月份與分類"] -->|設定目標| B["② 執行與追蹤<br/>更新實際進度"]
    B -->|記錄執行情況| C["③ 改善與回顧<br/>填寫原因與心得"]
    C -->|作為下次安排參考| A
## Features

- **Task Management:** Add tasks and organize them by month and category.
- **Progress Tracking:** Set planned progress and update actual completion.
- **Status Filters:** View all tasks, tasks in progress, or completed tasks.
- **Improvement Notes:** Record reasons when a task needs improvement.
- **Task Reviews:** Write a review after completing a task.
- **Monthly View:** Select a month to view its tasks.
- **Local Storage:** Task data is saved in the current browser.

## Browser Requirements

- Use a modern browser with JavaScript enabled.
- Task data is stored separately in each browser.
- The board does not automatically sync data across browsers or devices.

## Quick Start

1. Open the [Wee Task Board Space](https://huggingface.co/spaces/sony3021919/test).
2. Select a month and enter the task details.
3. Add the task, then update its actual progress as you work.
4. Use the status filters to find tasks.
5. Add improvement notes or a review when needed.

## Workflow

```mermaid
flowchart LR
    A["Create a task<br/>Name, month, category"] --> B["Track progress<br/>Planned and actual"]
    B --> C["Improve and review<br/>Record notes"]
    C --> A
