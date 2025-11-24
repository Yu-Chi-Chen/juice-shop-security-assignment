# Web Security Assignment - OWASP Juice Shop

## 環境說明

- 作業系統：Windows 11
- Docker version：v4.41.0

## 安裝與執行步驟

1. 安裝 Docker
2. 執行指令：`docker pull bkimminich/juice-shop`
3. 啟動容器：`docker run -p 3000:3000 bkimminich/juice-shop`
4. 瀏覽器開啟：http://localhost:3000

## 測試環境

- 完全在本機 Docker 容器中執行
- 未對任何公開或生產環境進行測試

## **Vulnerability Report Outline**

- 作業標題：Web Security Vulnerability Identification & Fixes
- 學生姓名/學號： 113598037 陳宥錡
- 使用平台：OWASP Juice Shop

#### 目錄

1. Executive Summary (摘要)
2. Environment Setup (環境設定)
3. Vulnerability Analysis (漏洞分析)
4. Proposed Fixes (修復建議)
5. Verification Results (驗證結果)
6. Reflection (心得反思)
7. References (參考資料)

---

#### Executive Summary

- Broken Access Control

#### Environment Setup

- Docker Pull
  ![Docker Pull](./screenshots/docker_pull.png)
- Juice Shop Activate
  ![activate](./screenshots/juice%20shop%20activate.png)
- 測試環境規格說明
- 安全聲明（僅在隔離環境測試）

#### Vulnerability Analysis

(點擊檢視詳細方式)  
[Broken Acess Control](./code-fixes/basket-access-control-fix.md)
