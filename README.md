# Legacy Modernization Framework

> A multi-agent AI workflow for reverse-engineering and rewriting legacy enterprise
> systems — with a built-in, self-auditing quality gate.
>
> 一套以**多 Agent AI 工序鏈**為核心的遺留系統現代化方法論：把 4GL、VBA 等老舊企業程式，
> 逆向工程並改寫成現代 SQL / Python，過程內建 **14+1 維度自證審查**品質閘門。

> 🚧 **Work in progress** — 方法論文件建構中，內容陸續補上。

---

## The Problem | 問題

Legacy 4GL / VBA 系統是許多企業 IT 的黑洞：原始開發者離職、缺乏文件、邏輯散落在
數千行程序裡，沒人敢動也沒人能改寫。本框架要解的，是**如何用 AI 把這類系統安全、可驗證地
現代化**。

> （完整問題定義待 `1A-5` 補。）

## Methodology Overview | 方法論概覽

兩大支柱：

1. **9-Phase Multi-Agent Workflow** — 規劃 → 設計 → 撰寫 → 審查 → 驗證的角色分工工序鏈。
   詳見 [`docs/9-phase-workflow.md`](docs/9-phase-workflow.md)
2. **14+1 Dimension Self-Audit** — 讓 AI 自我審查改寫品質的領域檢核框架。
   詳見 [`docs/sp-audit-framework.md`](docs/sp-audit-framework.md)

## Proof | 實證數據

| 指標 | 數據 |
|------|------|
| 改寫規模 | 4,594 行 4GL → 5,410 行 SQL Server Stored Procedure |
| 學習曲線 | 第 1 案 17 輪修補 → 第 2 案 0 輪撞牆（約 16× 效率提升） |
| 品質閘門 | 14+1 維度自證 audit |

> （數據脈絡與圖表待 `1A-5` 補。）

## How to Use | 如何使用

> （待補。）

## Case Studies | 案例

- **Case #1** — 一支 4,594 行的 legacy 4GL ERP 成本計算引擎 → 5,410 行 SQL Server SP
  （去敏化版本建構中）。

---

## License

[MIT](LICENSE)
