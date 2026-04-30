# AGENTS.md — prospera-brand-engineering-framework
# AI Agent Operating Contract | L5 — Brand Product Layer
# Version: 1.0 | 2026-04-30
# Governance Reference: Prospera-Governance-Core v3.0
# Pipeline Reference: Prospera-Workflow-Engine v1.0
# Codex Reference: prospera-engineering-codex v2.0

## 1. REPO IDENTITY
Repo: ccktaiwan/prospera-brand-engineering-framework
Layer: L5 — Brand Product（品牌工程框架）
Role: Brand OS 的工程化實作，P0 顧問商品的技術基礎
核心公式: Human Intelligence x AI Governance = Prospera Brand OS

## 2. 生態系定位
Brand OS 是 Prospera 顧問生態系的市場入口：
顧問知識 → Brand KB → ContentAgent → 四平台輸出 → 客戶業務成果

B1-B5 架構：
B1 Brand Boundary → Brand KB（客戶資料結構化）
B2 Narrative Constitution → 品牌敘事憲法
B3 Strategy Validation → 四問法策略驗證
B4 Execution Binding → 四平台內容規格
B5 Market Feedback → 績效回饋閉環

## 3. Audience Kernel 五族群
AK-01 探索者 → Google, Meta（廣泛搜索，好奇心強）
AK-02 深度學習者 → Google, Blog（專業搜索，長閱讀）
AK-03 社交連結者 → Meta, LINE（互動頻繁，分享欲強）
AK-04 決策導向者 → Wix, LINE（比較行為，詢價）
AK-05 忠誠擁護者 → LINE, Meta（重複購買，推薦行為）

四平台閉環：Google→Meta→Wix→LINE

## 4. Pipeline-Thread-Container 角色
Pipeline：Brand KB 是 Layer 1 INTENT 的輸入基礎
Thread：每個客戶的品牌任務是獨立 Thread
Container：每個客戶是獨立 Container（鳳凰吉祥/欣轅TOTO）

## 5. AGENT RULES

### PERMIT — 允許自動執行
- 讀取 Brand KB（客戶資料）
- 根據 Audience Kernel 生成各平台內容
- 執行 B1-B5 診斷流程
- 生成四平台內容規格
- 讀取績效數據（唯讀）
- 生成月度績效報告草稿

### ESCALATE — 執行前必須確認（J點）
- 修改客戶 Brand KB 定義 → J2（品質審閱）
- 建議調整客戶品牌定位 → J3（策略決策）
- 生成診斷報告後發送給客戶 → J2
- 新增新客戶 Container → J1（確認 Brand KB 完整性）

### BLOCK — 禁止執行
- 在無 Brand KB 情況下生成品牌內容
- 直接發布內容到客戶平台（必須客戶自己操作）
- 修改客戶 Brand KB 不通知（Brand KB 是客戶資產）
- 生成虛假數據或誇大療效的醫療內容
- 在沒有顧問審閱前給客戶競品分析

## 6. Decision Engine 四問法
Q1 Should → 品牌任務在 PERMIT 清單內？
Q2 Can    → Brand KB 存在且 ContentAgent 可用？
Q3 Fit    → 內容符合 Brand KB 定義的語氣和規範？
Q4 Profit → 有明確的品牌業務目標？

## 7. 現有客戶 Container
鳳凰吉祥（LPHM）：
  定位：自律神經調理 x 東方養生智慧
  受眾：AK-04 決策導向者（40-55歲）
  現況：Trust Layer 完成，Decision Layer 待建立
  Brand KB：clients/lphm/brand_kb.yaml

欣轅 x TOTO：
  定位：整體衛浴 x 工程整合專家
  受眾：AK-04 屋主 + AK-02 設計師
  現況：HTML 原型完成，Phase 1 進行中
  Brand KB：clients/xinyuan/brand_kb.yaml

## 8. Agent Orchestration
ContentAgent：讀取 Brand KB → 生成內容 → J2 確認
StrategyAgent：執行 B1-B5 診斷 → 生成報告 → J2 確認
AnalyticsAgent：讀取績效數據 → 生成月報 → J1 確認

## 9. J 點確認
J1 技術確認：Brand KB 完整性、ContentAgent 可用性
J2 品質審閱：內容品質、診斷報告準確性
J3 架構決策：品牌定位調整、策略方向修改

## 10. 稽核要求
Commit 格式：brand(scope): [change] - reason: [why] - phase: [N]

# Version: 1.0 | 2026-04-30
# Human-Reviewed: yes